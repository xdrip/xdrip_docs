This menu provides some important settings and mechanisms of calibrations.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-LCS.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-LCS3.png" style="zoom:75%;" />

You can decide to use [treatments](../../use/mainUI/#treatments) as calibrations.

<img src="../images/M-S-LCS-AC1.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-AC1a.png" style="zoom:75%;" />

Automatic mode will only suggest you to use the treatment as a calibration if xDrip+ detects that current conditions are good to calibrate (like BG stable for 20 minutes, low noise).

It might also suggest to you enable automatic calibration.

<img src="../images/M-S-LCS-AC3b.png" style="zoom:75%;" />

Ask me every time will do exactly this every time you enter a BG treatment.

<img src="../images/M-S-LCS-AC3c.png" style="zoom:75%;" />

Never use treatments will never use them to calibrate (and will prevent you from transforming a [treatment](../../use/mainUI/#treatments) into a calibration).

Always use treatments as calibrations is not recommended. 

Automatic calibration will accept a treatment as a calibration if it satisfies the conditions of a flat trend for 20 minutes.

<img src="../images/M-S-LCS-AC2.png" style="zoom:75%;" />

### Plugins

<img src="../images/M-S-LCS-AC3.png" style="zoom:75%;" />

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

Enable if you want xDrip+ to plot results using the plugin.

<img src="../images/M-S-LCS-AC4.png" style="zoom:75%;" />

<img src="../../use/images/M-S-DS2l2.png" style="zoom:75%;" />

Enable if you want the main BG number to be from plugin results. A circled P will show.

<img src="../images/M-S-LCS-AC5.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-AC5a.png" style="zoom:75%;" />

Not implemented.

<img src="../images/M-S-LCS-AC6.png" style="zoom:75%;" />

### Calibrations

If you're not actually performing two different blood tests for initial calibration you might as well disable this.

<img src="../images/M-S-LCS-AC7.png" style="zoom:75%;" />

Calibrations get ignored when too old, if you calibrate rarely and want older calibrations measurements to weight on the current calibration curve, enable this. 

<img src="../images/M-S-LCS-AC8.png" style="zoom:75%;" />

### Libre specific

Libre sensors might be difficult to calibrate. If you cannot manage to get full range accuracy or never calibrate in the higher range, disable this and make the slope equal to 1. This is recommended for beginners.

<img src="../images/M-S-LCS-AC9.png" style="zoom:75%;" />

Carrying forward calibrations from the old sensor to a new one is dangerous. Leave this enabled.

<img src="../images/M-S-LCS-AC10.png" style="zoom:75%;" />

### Bypass quality check

<img src="../images/M-S-LCS-AC11.png" style="zoom:75%;" />

During preliminary measurements for first calibration, 3 valid measurements are required. If they are missing or fail safety values, xDrip+ will wait. Enabling this will allow calibration without checking. **Not recommended.**

<img src="../../install/images/M-SS-InitialR2.png" style="zoom:55%;" />

</br>

[*Last modified 28/3/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)
