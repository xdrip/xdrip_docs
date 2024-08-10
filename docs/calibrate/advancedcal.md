This menu provides some important settings and mechanisms for calibration.

!!!xdrip "`Advanced Calibration`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Less Common Settings  
    &emsp;&ensp;Advanced Calibration

##### Use Treatment BG values

!!!xdripitem "Use Treatment BG values&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Choose whether to calibrate with the BG value in a Treatments entry  

You can decide to use BG [treatments](../../use/mainUI/#treatments) (blood tests) as calibrations.

!!!warning  
    Always use treatments as calibrations is **not recommended**.

Automatic mode will only suggest you to use the treatment as a calibration if xDrip+ detects that current conditions are good to calibrate (like BG stable for 20 minutes, low noise).

It might also suggest to you enable automatic calibration.  

<img src="../images/M-S-LCS-AC1a.png" style="zoom:75%;" />

**It is not recommended to use this feature with G6/G7/1/1+ sensors.**

<img src="../images/M-S-LCS-AC3b.png" style="zoom:75%;" />

Ask me every time will do exactly this every time you enter a BG treatment.

<img src="../images/M-S-LCS-AC3c.png" style="zoom:75%;" />

Never use treatments will never use them to calibrate (and will prevent you from transforming a [treatment](../../use/mainUI/#treatments) into a calibration).

##### Automatic Calibration

!!!xdripitem "Automatic Calibrations&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Calibrate using new blood glucose reading if the conditions appear right to do so without asking confirmation (experimental)  


It is recommended to **disable this for G6/G7/1/1+ sensors**.

Automatic calibration will accept a treatment as a calibration if it satisfies the conditions of a flat trend for 20 minutes.

### Plugins

!!!xdripitem "Calibration Plugin"  
    &ensp;Experimental calibration secondary plugin  

Calibration plugins are available in xDrip+, most are not used anymore.  If enabled, a plugin acts instead of the standard xDrip+ calibration. The idea was to have a customizable calibration algorithm selection but was never fully implemented.

!!!warning "Wear extension"  
    Plugins are not fully implemented in Wear. You might see different vaues on your watch.

<img src="../images/M-S-LCS-AC3a.png" style="zoom:75%;" />

**`None`** by default the xDrip+ algorithm is used. **Recommended**

**`Datricsae`** was popular with those in trouble with default xDrip+ algorithm. It requires 8 calibration points (if less than 4 the original xDrip+ algorithm will be used) and has slope limits between 0.5 and 1.7. Its main strength is to remove outliers (bad calibration points) that fall too far out of the calibration line. Once filtered, if the number of calibration points fall below 4 or slope is out of limits, the classic xDrip+ algorithm is used.  
Be careful as noisy calibrations might lead to inconsistent results.

<img src="../images/M-S-LCS-AC3d.png" style="zoom:75%;" />

**`Fixed slope`** is an empty plugin returning slope 1.08 and intercept -5. **Do not use it for real BG.**

**`xDrip Original`** was the plugin equivalent of the xDrip+ algorithm. It doesn't do anything else than the xDrip+ algorithm. **There is no added value in using it.**

**`Last 7 unweighted`** was an early attempt to improve the original algorithm. It requires at least 7 calibrations (if non-existing, current xDrip+ algorithm is used). **Not recommended.**

!!!xdripitem "Plugin plot on graph&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Show glucose results from the plugin on the main graph  

Enable if you want xDrip+ to plot results using the plugin.

<img src="../../use/images/M-S-DS2l2.png" style="zoom:75%;" />

!!!xdripitem "Use Plugin Glucose&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Main glucose display number comes from plugin!  

Enable if you want the main BG number to be from plugin results. A circled P will show.

<img src="../images/M-S-LCS-AC5a.png" style="zoom:75%;" />

!!!xdripitem "Plugin Override ALL&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Main glucose display number comes from plugin!  

Not implemented.

### Calibrations

!!!xdripitem "Double Calibrations&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Ask for a second optional initial calibration blood test  

If you're not actually performing two different blood tests for initial calibration: disable this.

!!!xdripitem "Infrequent Calibration&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;If needed, use calibrations from longer ago, e.g. if calibrations are supplies infrequently  

Calibrations get ignored when too old, if you calibrate rarely and want older calibrations measurements to weight on the current calibration curve: enable this. 

### Libre specific

##### Non-fixed Libre Slopes

!!!xdripitem "Non-fixed Libre Slopes&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Enable to allow variable slopes with Libre collection methods  

Libre sensors might be difficult to calibrate. If you cannot manage to get full range accuracy or never calibrate in the higher range, disable this and make the slope equal to 1. This is recommended for beginners.

**Always calibrate at stable glucose when in the lower normal range for safety.**

!!!xdripitem "Check Libre Serial&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Automatically stop if Libre Serial changes unexpectedly  

Carrying forward calibrations from the old sensor to a new one is dangerous. **Leave this enabled.**

### Bypass quality check

!!!xdripitem "Bypass quality check&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Allow initial calibration even if we don't have good enough data. Beware could result in inaccurate calibration.  

During preliminary measurements for first calibration, 3 valid measurements are required. If they are missing or fail safety values, xDrip+ will wait. Enabling this will allow calibration without checking. **Not recommended.**

<img src="../../install/images/M-SS-InitialR2.png" style="zoom:65%;" />

</br>

[*Last modified 3/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
