!!!xdrip "`Hardware data source`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Hardware Data Source  
    &ensp;&emsp;Libre Bluetooth

# Libre and bridge

Many NFC to Bluetooth bridges are available on the market for Libre sensors.

The original project was developed by Joern: [LimiTTer](https://github.com/JoernL/LimiTTer). You need to remember this name as it will appear as the default bridge name when the actual device is not identified. Unless you actually have a LimiTTer (or connect directly a Libre 2), seeing this name means your bridge is not connected to xDrip+.

xDrip+ supports some of them for some sensors.  
**Libre H, Libre 2 US/CA/AUS are not supported.**  
You can use Diabox or Juggluco in [Libre patched app](/install/libre2patch/) mode.

Here below a compatibility table for supported bridge devices, for compatible sensors **minimum** firmware version is indicated.

|   Bridge    | - Libre 1 / Pro - | - 14 days US - | - Libre 2 EU - |
| :---------: | :---------------: | :------------: | :------------: |
|  MiaoMiao   |       `Yes`       |     `39*`      |     `39*`      |
| MiaoMiao 2  |       `Yes`       |      `7*`      |      `7*`      |
| MiaoMiao 3  |       `Yes`       |     `3A*`      |     `3A*`      |
|   Bubble    |       `Yes`       |     `2.6*`     |     `2.6*`     |
| Bubble mini |       `Yes`       |     `2.6*`     |     `2.6*`     |
|    Atom     |       `Yes`       |                |                |

*Note:*  
*`*` [external OOP add-on required](../../use/OOP)*

</br>

## Bridge settings

If you haven't yet, [check xDrip+ will not be put to sleep](../install/#make-sure-xdrip-will-not-be-put-to-sleep).

Before trying to connect your bridge verify your settings are correct to avoid frequent disconnections.

!!!xdrip "`Bluetooth Settings`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Less Common Settings  
    &ensp;&emsp;Bluetooth Settings  

Use settings as shown below to start with.

!!!xdripitem "Turn Bluetooth on&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Automatically turn on Bluetooth if it is switched off when we try to connect to a Bluetooth device.

Bluetooth must be on. **Enable** `Turn Bluetooth on`.

!!!xdripitem "Bluetooth Watchdog&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Reset Bluetooth by turning it off then on if we don't get anything within 20 minutes

**Enable** the Watchdog but read the info below.

!!!xdripitem "Dex Bluetooth Watchdog&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Reset Bluetooth by turning it off then on as a way to keep the Dex data source working. Without this, the Dex collector may fail.

**Enable** the Dex Watchdog but read the info below.

!!!info  
    Mind the Bluetooth watchdog ang Dex Bluetooth watchdog will turn off, then on your phone Bluetooth, this will lead to a temporary Bluetooth disconnection on all connected devices. You might want to disable this feature if you use AAPS and your bridge/pump doesn't recover automatically Bluetooth connection.

!!!xdripitem "Close GATT on BLE disconnect&emsp;&emsp;&emsp;☐"  
    &ensp;If the Bluetooth watchdog activates too often then you can try unchecking this option to see if it helps.

**Disable** close GATT.

!!!xdripitem "Use scanning&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Scan before connecting on xBridge and Libre Bluetooth.

If your bridge loses connection and scanning Bluetooth allows you to recover, you can try to enable `Use scanning`. Leave **disabled** to start.

!!!xdripitem "Trust auto-connect&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Use and trust Android Bluetooth auto-connect feature.

For Samsung phones you **must disable `Trust Auto-Connect`**! If your phone loses connection you should **disable** it.

!!!xdripitem "Use Background Scans&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Use Android 8+ background scanning feature.

For Android version 8 and above you can enable `Use Background Scans`. If you lose connection, **leave it disabled**.

!!!xdripitem "Bluetooth Wakelocks&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Older Bluetooth wakelocks which can can drain battery but might be needed for Bluetooth reception.  

!!!xdripitem "Constantly reset Bluetooth&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Reset Bluetooth by turning it off then on every few minutes! Only select if you are testing. It may disrupt anything else using Bluetooth.

Leave both the options above **disabled**.

!!!xdripitem "Transmitter (PL) support&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Experimental support for "Transmitter" device from @FPV-UAV - test only.

If your bridge is a Transmitter_T or a Droplet enable this else keep it **disabled**.

!!!xdripitem "xBridge+ Polling Mode&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Experimental support for xBridge+ polling feature.

If you have connection losses you can **enable** polling mode. It will not do anything useful but keep the phone Bluetooth awake.

!!!xdripitem "Allow BluCon unbonding&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Only suitable for phones which support automatic pairing. 

If your bridge is an old compatible BluCon you can enable this.  
*Note: only BluCon bonds to Android, other bridges don't.*

</br>

Restart your phone to make sure all parameters are being taken into account.

</br>

## Connect Bluetooth bridge

Make sure your bridge is not connected to anything else: any other device and any other app.  
Scan Bluetooth.

!!!xdrip "`Bluetooth Scan`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Bluetooth Scan  

If scan doesn't start automatically, select `SCAN`.

<img src="../../images/M-BTscan.png" style="zoom:75%;" />

If your bridge doesn't show up make sure it's fully charged (or has a new battery) and reset it.

Once visible select it.

If your bridge is a Blucon enter the code written on the side. 

<img src="../images/M-BT-BK.png" style="zoom:55%;" />

Position it correctly on your sensor. Some bridges have very little tolerance in respect with angle and distances to the sensor.

!!!info "External Add-on"  
    If your sensor requires an [out of process algorithm](../../use/OOP), make sure it is installed now.

</br>

Continue to [Start Sensor](../../use/startsensor/#libre)

## Stop Libre sensor

xDrip+ cannot physically stop a Libre sensor, it will stop running by itself after 14 days and 12 hours and keep showing the last value.

Still, when changing sensor it is strongly recommended to inform xDrip+ of the change by stopping the sensor.

!!!xdrip "`Stop Sensor`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Stop Sensor  

Confirm you really want to stop the sensor.

<img src="../images/M-StoSC.png" style="zoom:75%;" />

This will reset all calibrations and allow xDrip+ to start a new sensor.

</br>

[*Last modified 3/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)