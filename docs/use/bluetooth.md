The amount of Android phones manufacturers and sensors/bridges particularities has made Bluetooth connection reliability a major difficulty for xDrip+. This menu contains a lot of deep settings that cannot be standardized for all systems.

Trial and error approach is recommended, but change only one setting at a time to avoid further confusion.

!!!xdrip "`Bluetooth Settings`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Less common settings  
    &ensp;&emsp;Bluetooth Settings

!!!xdripitem "Turn Bluetooth on&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Automatically enable Bluetooth if it is switched off when we try to connect to a Bluetooth device 

This option will make xDrip+ try to enable Bluetooth.

If xDrip+ is connecting to a Bluetooth device, Turn Bluetooth on is mandatory.  
xDrip+ might not be able to fully override your phone settings, meaning that if you disable Bluetooth in Android settings or put your phone in airplane mode it might not be able to turn it on. Bluetooth must be enabled in Android settings if you want xDrip+ to use it.  

!!!xdripitem "Bluetooth Watchdog&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Automatically enable Bluetooth if it is switched off when we try to connect to a Bluetooth device

In case of missing data due to Bluetooth connection loss, you can make xDrip+ switch off then on your phone Bluetooth, default timing is 20 minutes without data. You can customize this value.

If you see the message that **xDrip+ turned off Bluetooth** this is probably because watchdog triggered and xDrip+ is trying to recover connection with the sensor.

!!!info  
    Mind the Bluetooth watchdog ang G5 Bluetooth watchdog activating will lead to a temporary Bluetooth disconnection on all connected devices. You might want to disable this feature if you use AAPS and your bridge/pump doesn't recover automatically Bluetooth connection.  
    Note that G6/G7/1/1+ Bluetooth watchdog is not controlled by this setting

!!!xdripitem "Dex Bluetooth Watchdog&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Reset Bluetooth by turning it off then on as a way to keep the Dex data source working. Without this, the Dex collector may fail.

For G5 sensors you can systematically have xDrip+ turn off and on Bluetooth. Keep it enabled if you have connection issues.

!!!xdripitem "Close GATT on BLE disconnect&nbsp;&emsp;&emsp;☐"  
    &ensp;If the Bluetooth watchdog activates too often then you can try unchecking this option to see if it helps

When this option is enabled, xDrip+ will go through complete disconnection then reconnection of your Bluetooth device (close link, discover and connect) when connection is lost. Since this might not be efficient, it is recommended to leave it **disabled** so that it's maintained in memory and will only try to connect back to it as a known BLE device.

!!!xdripitem "Use scanning&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Scan before connecting on xBridge and Libre Bluetooth

Use scanning will perform the equivalent of Bluetooth Scan from the main menu to attempt recovering a lost connection. This is not always efficient with newer phones. Leave it initially **disabled** unless it proves useful.

!!!xdripitem "Trust auto-connect&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Use and trust Android Bluetooth auto-connect feature

Trust Auto-Connect really depends on your phone. If you have a Samsung, Xiaomi, OnePlus, Oppo, Huawei or Realme you should probably leave it disabled. If you frequently lose connection and can't manage to recover leave it **disabled**.

!!!xdripitem "Use Background Scans&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Use Android 8+ background scanning feature

Use Background scan is a feature of newer Android versions. If you regularly lose connection, leave it **disabled**.

!!!xdripitem "Companion Bluetooth&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Use Bluetooth with Companion app data source

Companion Bluetooth allows the app to work connected together with the Dex master app connected to the sensor.

!!!xdripitem "Bluetooth Wakelocks&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Older Bluetooth wakelocks which can can drain battery but might be needed for Bluetooth reception.  

Bluetooth wakelocks are not recommended and should be left **disabled**.

!!!xdripitem "Constantly reset Bluetooth&ensp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Reset Bluetooth by turning it off then on every few minutes! Only select if you are testing. It may disrupt anything else using Bluetooth.

Constantly reset Bluetooth is not recommended. Leave it **disabled**,

!!!xdripitem "Transmitter (PL) support&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Experimental support for "Transmitter" device from @FPV-UAV - test only

If you use a Transmitter_T or a Droplet bridge for Libre sensors (we miss you [Marek](https://github.com/MarekM60)) you must enable this option, else leave it **disabled**.

!!!xdripitem "RFduino support&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Experimental support for RFduino from Tomasz Stachowicz.

RFDuino support is only necessary if you use a [DIY bridge with RFDuino](https://github.com/TomaszStachowicz/Transmiter-xBridgePlus). Obsolete. Leave **disabled**.

!!!xdripitem "xBridge+ Polling Mode&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Experimental support for xBridge+ polling feature

xBridge+ polling mode allows xDrip+ to send requests to the bridge. Even if it doesn't have any effect with other Bluetooth devices you can leave it enabled if you have frequent connection loss as it will anyway keep your phone Bluetooth busy trying to connect.

!!!xdripitem "Always discover services&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Probe Bluetooth service on every connect

Enabled by default.

!!!xdripitem "Allow BluCon unbonding&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Only suitable for phones which support automatic pairing

Allow BluCon unbonding is only useful if you use a BluCon bridge as others don't bond with your phone. If you have frequent pairing request with this bridge, disable it.

</br>

[*Last modified 22/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.07)