<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistC.png" style="zoom:75%;" />

# Libre and bridge

Many NFC to Bluetooth bridges are available on the market for Libre sensors.

The original project was developed by Joern: [LimiTTer](https://github.com/JoernL/LimiTTer). You need to remember this name as it will appear as the default bridge name when the actual device is not identified. Unless you actually have a LimiTTer (or connect directly a Libre 2), seeing this name means your bridge is not connected to xDrip+.

xDrip+ supports some of them for some sensors.  
**Libre H, Libre 2 US/CA/AUS are not supported.**  
You can use Diabox in [Nightscout follower](../nightscoutfollower/#diabox) mode.

Here below a compatibility table for supported bridge devices, for compatible sensors **minimum** firmware version is indicated.

|   Bridge    | - Libre 1 / Pro - | - 14 days US - | - Libre 2 EU - |
| :---------: | :---------------: | :------------: | :------------: |
|   BluCon    |       `Yes`       |     `4.2*`     |     `4.2*`     |
|  MiaoMiao   |       `Yes`       |     `39*`      |     `39*`      |
| MiaoMiao 2  |       `Yes`       |      `7*`      |      `7*`      |
| MiaoMiao 3  |       `Yes`       |     `3A*`      |     `3A*`      |
|   Bubble    |       `Yes`       |     `2.6*`     |     `2.6*`     |
| Bubble mini |       `Yes`       |     `2.6*`     |     `2.6*`     |
|   Droplet   |       `Yes`       |      `No`      |     `2.2*`     |
|    Atom     |       `Yes`       |                |                |

*Note:*  
*`*` [external add-on required](../../use/OOP)*

</br>

## Bridge settings

If you haven't yet, [check xDrip+ will not be put to sleep](../install/#make-sure-xdrip-will-not-be-put-to-sleep).

Before trying to connect your bridge verify your settings are correct to avoid frequent disconnections.

`Menu` / `Settings` / `Less Common Settings` / `Bluetooth Settings`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-S.png" style="zoom:75%;" />

<img src="../../images/M-S-LCS.png" style="zoom:75%;" />

<img src="../../images/M-S-LCS-BT.png" style="zoom:75%;" />

Use settings as shown below to start with.

!!!info  
    Mind the Bluetooth watchdog ang G5 Bluetooth watchdog with turn off then on your phone Bluetooth, this will lead to a temporary Bluetooth disconnection on all connected devices. You might want to disable this feature if you use AAPS and your bridge/pump doesn't recover automatically Bluetooth connection.

<img src="../images/M-S-LCS-BT-L1.png" style="zoom:75%;" />

If your bridge loses connection and scanning Bluetooth allows you to recover, you can try to enable `Use scanning`.

<img src="../images/M-S-LCS-BT-L2.png" style="zoom:75%;" />

For Samsung phones you must disable `Trust Auto-Connect`! If your phone is not a Samsung but loses connection you can try to disable it too.

<img src="../../images/M-S-LCS-BT-TAC.png" style="zoom:75%;" />

For Android version 8 and above you can enable `Use Background Scans`. If you lose connection, leave it disabled.

<img src="../images/M-S-LCS-BT-L3.png" style="zoom:75%;" />

If your bridge is a Transmitter_T or a Droplet enable this else keep it disabled.

<img src="../images/M-S-LCS-BT-MK.png" style="zoom:75%;" />

If you have connection losses you can enable polling mode. It will not do anything useful but keep the phone Bluetooth awake.

<img src="../images/M-S-LCS-BT-L4.png" style="zoom:75%;" />

If your bridge is a BluCon you can enable this.  
*Note: only BluCon bonds to Android, other bridges don't.*

<img src="../images/M-S-LCS-BT-L5.png" style="zoom:75%;" />

</br>

Restart your phone to make sure all parameters are being taken into account.

</br>

## Connect Bluetooth bridge

Make sure your bridge is not connected to anything else: any other device and any other app.  
Scan Bluetooth.

`Menu` / `Bluetooth Scan` 

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-BTS.png" style="zoom:75%;" />

<img src="../../images/M-BTscan.png" style="zoom:75%;" />

If your bridge doesn't show up make sure it's fully charged (or has a new battery) and reset it.

Once visible select it.

If your bridge is a Blucon enter the code written on the side. 

<img src="../images/M-BT-BK.png" style="zoom:75%;" />

Position it correctly on your sensor. Some bridges have very little tolerance in respect with angle and distances to the sensor.

!!!info "External Add-on"  
    If your sensor requires an [out of process algorithm](../../use/OOP), make sure it is installed now.

</br>

Continue to [Start Sensor](../../use/startsensor/#libre)

## Stop Libre sensor

xDrip+ cannot physically stop a Libre sensor, it will stop running by itself after 14 days and 12 hours and keep showing the last value.

Still, when changing sensor it is strongly recommended to inform xDrip+ of the change by stopping the sensor.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-StoS.png" style="zoom:75%;" />

Confirm you really want to stop the sensor.

<img src="../images/M-StoSC.png" style="zoom:75%;" />

This will reset all calibrations and allow xDrip+ to start a new sensor.

</br>

[*Last modified 27/4/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.04.27)