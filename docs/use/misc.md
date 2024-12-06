More options are available in this menu.  
If they are hidden here it's probably because you won't need to change them every day, or you should leave them as they are unless instructed differently.

!!!xdrip "`Other miscellaneous options`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;&ensp;Less Common settings  
    &emsp;&emsp;&emsp;Other Misc. options

##### Run collector in foreground

Mandatory to keep xDrip+ from being put to sleep by Android.  
This will force displaying a graph in the notifications area, **you shouldn't disable it**.

!!!xdripitem "Run collector in foreground&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ✔"  
    &ensp;Shows a persistent notification graph, visible on lock screen and prevents Android killing the service.

<img src="../images/M-S-LCS15a2.png" style="zoom:75%;" />

##### Engineering mode

Enables feature that are potentially dangerous or untested. You do not need it to be enabled for restarting a G5 or an old G6 transmitter (new ones called Firefly can't be restarted).

!!!xdripitem "Engineering mode&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Allows changing the most unsafe settings which could break everything!

To enable engineering mode enter or speak the following treatment.

<img src="../images/M-S-LCS15b2.png" style="zoom:75%;" />

You will be reminded monthly engineering mode is on. Make sure you really need it, else keep it disabled.

<img src="../images/M-S-LCS15b3.png" style="zoom:52%;" />

##### Battery Optimization Prompt 

Should be left **disabled**. xDrip+ needs [whitelisting](../../install/install/#authorize-background-activity) and shouldn't be subject to optimization. 

!!!xdripitem "Battery Optimization prompt&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;On Android 6+ ensure battery optimization is switched off (recommended)

##### Samsung Workarounds

Renamed to Wake Workarounds as other devices are not compliant.

##### Wake Workarounds

Fixed a non compliance in respect to some Android of devices, now default for Samsung, Xiaomi, OnePlus, Oppo and Huawei.   
Should be kept **enabled**.

!!!xdripitem "Wake workarounds&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Use workarounds to avoid non-standard Android behavior of some handsets. Without this, collectors usually fail to get data.

Use Excessive Wakelocks is not required. They are additional "wake-up" messages sent by xDrip+ to your Android device to prevent it to go in sleep mode. 

!!!xdripitem "Use Excessive Wakelocks"

Display Predictive Values (old method) is deprecated. Use [Predictive Simulation](../predictions/).

!!!xdripitem "Display Predictive Values (old method)"

Proper Ongoing is mandatory for devices with Android 8 and above.

!!!xdripitem "Proper Ongoing"

##### Out of Process Algorithm

[Out Of Process Algorithm](../OOP) enables the integration of an external plugin to give vendor like BG values for Libre sensors or provide decoding of the Libre 2 EU sensor information.  
If the external app doesn't exist on your phone or doesn't provide the information, xDrip+ will not display BG.

!!!warning  
    This option should only be enabled if using an Out Of Process algorithm version 1 (OOP1).  
    It must be disabled for OOP2.

!!!xdripitem "Out of process Libre algorithm"  
    &ensp;Use an out of process (OOP) Libre algorithm. (Bridge/NFC/LibreAlarm)

##### OOP2

!!!xdripitem "OOP2 algorithm calibration"  
    &ensp;Apply xDrip calibration method on OOP2 data

You can use OOP2 in different ways:

- No calibration generates vendor like values (native mode) without the need of calibrating. It doesn't mean that results are not calibrated (raw) but a vendor-like algorithm is applied (like the Libre 1 reader). **Recommended** to start with.
- Calibrate based on raw uses the sensor raw data (no temperature correction) like Libre 1. You will use the xDrip+ calibration algorithm.
- Calibrate based on glucose allows you to apply xDrip+ calibration to native values. Raw data are transformed using the vendor-like algorithm, then fed to the xDrip+ calibration algorithm.

!!!xdripitem "OOP2 algorithm calibration"  
    &emsp;No calibration&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;●  
    &emsp;Calibrate based on raw&emsp;&emsp;&emsp;○  
    &emsp;Calibrate based on glucose&nbsp;&emsp;○

Smooth Libre data averages on 5 measurement. This will also delay readings.  
If this option doesn't bring the improvement expected, also try [Smooth Sensor Noise](../display/#smooth-sensor-noise).

!!!xdripitem "Smooth Libre data"  
    &ensp;Use average of 5 points to get smoother Libre data

Retrieve Libre History is required for BluCon bridges. Other bridges perform backfilling automatically.

!!!xdripitem "Retrieve Libre History"

This option is not available at all.

!!!xdripitem "NOT FOR PRODUCTION USE"

</br>

[*Last modified 6/26/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.06.24)