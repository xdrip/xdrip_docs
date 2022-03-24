More options are available in this menu.  
If they are hidden here it's probably because you won't need to change them every day, or you should leave them as they are unless instructed differently.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-LCS.png" style="zoom:75%;" />  
<img src="../images/M-S-LCS15.png" style="zoom:75%;" />

Run collector in foreground is mandatory to keep xDrip+ from being put to sleep by Android.  
This will force displaying a graph in the notifications area, **you shouldn't disable it**.

<img src="../images/M-S-LCS15a.png" style="zoom:75%;" />

<img src="../images/M-S-LCS15a2.png" style="zoom:75%;" />

Engineering mode enables feature that are potentially dangerous or untested. You do not need it to be enabled for restarting a G5 or an old G6 transmitter (newer ones will be permanently damaged). It will automatically disable when restarting xDrip+ (rebooting your phone for example).

<img src="../images/M-S-LCS15b.png" style="zoom:75%;" />

To enable engineering mode enter the following treatment.

<img src="../images/M-S-LCS15b2.png" style="zoom:75%;" />

Battery Optimization Prompt should be left **disabled**. xDrip+ needs [whitelisting](../../install/install/#authorize-background-activity) and shouldn't be subject to optimization. 

<img src="../images/M-S-LCS15c.png" style="zoom:75%;" />

Samsung Workarounds fixes a non compliance in respect to Android of devices of this brand. It can be useful to enable it on other devices too. If you have connection issues you should try to **enable** it.

<img src="../images/M-S-LCS15j.png" style="zoom:75%;" />

Use Excessive Wakelocks is not required. They are additional "wake-up" messages sent by xDrip+ to your Android device to prevent it to go in sleep mode. 

<img src="../images/M-S-LCS15e.png" style="zoom:75%;" />

Display Predictive Values (old method) is deprecated. Use [Predictive Simulation](../predictions/).

<img src="../images/M-S-LCS15e.png" style="zoom:75%;" />

Proper Ongoing is mandatory for devices with Android 8 and above.

<img src="../images/M-S-LCS15g.png" style="zoom:75%;" />

##### Out of Process Algorithm

[Out Of Process Algorithm](../OOP) enables the integration of an external plugin to give vendor like BG values for Libre sensors.  
If the external app doesn't exist on your phone or doesn't provide the information, xDrip+ will not display BG.

!!!warning  
    This option should only be enabled if using an Out Of Process algorithm version 1 (OOP1).  
    It must be disabled for OOP2.

<img src="../images/M-S-LCS15h.png" style="zoom:75%;" />

For safety reasons you cannot calibrate OOP plugin values.

<img src="../images/M-S-LCS15i.png" style="zoom:75%;" />

Smooth Libre data averages on 5 measurement. This will also delay readings.  
If this option doesn't bring the improvement expected, also try [Smooth Sensor Noise](../display/#smooth-sensor-noise).

<img src="../images/M-S-LCS15j.png" style="zoom:75%;" />

Retrieve Libre History is required for BluCon bridges. Other bridges perform backfilling automatically.

<img src="../images/M-S-LCS15k.png" style="zoom:75%;" />

This option is not available at all.

<img src="../images/M-S-LCS15l.png" style="zoom:75%;" />