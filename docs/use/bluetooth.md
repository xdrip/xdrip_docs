The amount of Android phones manufacturers and sensors/bridges particularities has made Bluetooth connection reliability a major difficulty for xDrip+. This menu contains a lot of deep settings that cannot be standardized for all systems.

Trial and error approach is recommended, but change only one setting at a time to avoid further confusion.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-LCS.png" style="zoom:75%;" />  
<img src="../images/M-S-LCS4.png" style="zoom:75%;" />

If xDrip+ is connecting to a Bluetooth device, Turn Bluetooth On is mandatory.  
xDrip+ might not be able to fully override your phone settings, meaning that if you disable Bluetooth in Android settings or put your phone in airplane mode it might not be able to turn it on. Bluetooth must be enabled in Android settings if you want xDrip+ to use it.  
This option will make xDrip+ try to enable Bluetooth.

<img src="../images/M-S-LCS4a.png" style="zoom:75%;" />

In case of missing data you can make xDrip+ switch off then on your phone Bluetooth, default timing is 20 minutes without data. You can customize this value.  
If you see the message that xDrip+ turned off Bluetooth this is probably because watchdog triggered and is trying to recover connection with the sensor.

<img src="../images/M-S-LCS4b.png" style="zoom:75%;" />

For G5 sensors you can systematically have xDrip+ turn off and on Bluetooth. Keep it enabled if you have connection issues.

<img src="../images/M-S-LCS4c.png" style="zoom:75%;" />

When this option is enabled, xDrip+ will go through complete disconnection then reconnection of your bluetooth device (close link, discover and connect) when connection is lost. Since this might not be efficient, it is recommended to leave it **disabled** so that it's maintained in memory and will only try to connect back to it as a known BLE device.

<img src="../images/M-S-LCS4d.png" style="zoom:75%;" />

Use scanning will perform the equivalent of Bluetooth Scan from the main menu to attempt recovering a lost connection. This is not always efficient with newer phones. Leave it initially **disabled** unless it proves useful.

<img src="../images/M-S-LCS4e.png" style="zoom:75%;" />

Trust Auto-Connect really depends on your phone. If you have a Samsung phone you should leave it disabled. If you frequently lose connection and can't manage to recover leave it **disabled**.

<img src="../images/M-S-LCS4f.png" style="zoom:75%;" />

Use Background scan is a feature of newer Android versions. If you regularly lose connection, leave it **disabled**.

<img src="../images/M-S-LCS4g.png" style="zoom:75%;" />

Bluetooth wakelocks are not recommended and should be left **disabled**.

<img src="../images/M-S-LCS4h.png" style="zoom:75%;" />

Constantly reset Bluetooth is not recommended. Leave it **disabled**,

<img src="../images/M-S-LCS4i.png" style="zoom:75%;" />

If you use a Transmitter_T or a Droplet bridge for Libre sensors you must enable this option else leave it **disabled**.

<img src="../images/M-S-LCS4j.png" style="zoom:75%;" />

RFDuino support is only necessary if you use a [DIY bridge with RFDuino](https://github.com/TomaszStachowicz/Transmiter-xBridgePlus). Obsolete. Leave **disabled**.

<img src="../images/M-S-LCS4k.png" style="zoom:75%;" />

xBridge+ polling mode allows xDrip+ to send requests to the bridge. Even if it doesn't have any effect with other Bluetooth devices you can leave it enabled if you have frequent connection loss as it will anyway keep your phone Bluetooth busy trying to connect.

<img src="../images/M-S-LCS4l.png" style="zoom:75%;" />

Enabled by default.

<img src="../images/M-S-LCS4m.png" style="zoom:75%;" />

Allow BluCon unbonding is only useful if you use a BluCon bridge as others don't bond with your phone.

<img src="../images/M-S-LCS4n.png" style="zoom:75%;" />

</br>

[*Last modified 28/3/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)