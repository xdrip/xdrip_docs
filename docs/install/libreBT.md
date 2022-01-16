# Libre and bridge

Many NFC to Bluetooth bridges are available on the market for Libre sensors.

The original project was developed by JoernL: [LimiTTer](https://github.com/JoernL/LimiTTer). You need to remember this name as it will appear as the default bridge name when the actual device is not identified. Unless you actually have a LimiTTer, seeing this name means your bridge is not connected to xDrip+.

xDrip+ supports some of them for some sensors.  
**Libre Pro/H, Libre 2 US/CA/AUS are not supported.**

Here below a compatibility table for supported bridge devices, for compatible sensors **minimum** firmware version is indicated.

|   Bridge    | - Libre 1 - | - 14 days US - | - Libre 2 EU - |
| :---------: | :---------: | :------------: | :------------: |
|   BluCon    |    `Yes`    |    `4.2**`     |     `4.2*`     |
|  miaomiao   |    `Yes`    |     `39**`     |     `39*`      |
| miaomiao 2  |    `Yes`    |     `7**`      |      `7*`      |
| miaomiao 3  |    `Yes`    |     `3A**`     |     `3A*`      |
|   Bubble    |    `Yes`    |    `2.6**`     |     `2.6*`     |
| Bubble mini |    `Yes`    |    `2.6**`     |     `2.6*`     |
|   Droplet   |    `Yes`    |       No       |     `2.2*`     |
|    Atom     |    `Yes`    |                |                |

*Note:*  
*`*` external add-on required*  
*`**` external add-on required, not compatible with Android 10+*

</br>

## Bridge settings

Before trying to connect your bridge verify your settings are correct to avoid frequent disconnections.

`Menu` / `Settings` / `Less Common Settings` / `Bluetooth Settings`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-S.png" style="zoom:75%;" />

<img src="../../images/M-S-LCS.png" style="zoom:75%;" />

<img src="../../images/M-S-LCS-BT.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-BT-L1.png" style="zoom:75%;" />

If your bridge loses connection and scanning Bluetooth allows you to recover, enable `Use scanning`.

<img src="../images/M-S-LCS-BT-L2.png" style="zoom:75%;" />

For Samsung phones disable `Trust Auto-Connect`!

<img src="../../images/M-S-LCS-BT-TAC.png" style="zoom:75%;" />

For Android version 8 and above you can enable `Use Background Scans`

<img src="../images/M-S-LCS-BT-L3.png" style="zoom:75%;" />

If your bridge is a Transmitter_T or a Droplet enable this else keep it disabled.

<img src="../images/M-S-LCS-BT-MK.png" style="zoom:75%;" />

If you have connection losses you can enable polling mode. It will not do anything useful but keep the Bluetooth link awake.

<img src="../images/M-S-LCS-BT-L4.png" style="zoom:75%;" />

If your bridge is a BluCon you can enable this else keep it disabled.  
*Note: only BluCon bonds to Android, other bridges don't.*

<img src="../images/M-S-LCS-BT-L5.png" style="zoom:75%;" />

</br>

Restart your phone to make sure all parameters are being taken into account.

</br>

## Connect Bluetooth bridge

Make sure your bridge is not connected to anything else: any other device and any other app then scan Bluetooth.

`Menu` / `Bluetooth Scan` 

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-BTS.png" style="zoom:75%;" />

<img src="../../images/M-BTscan.png" style="zoom:75%;" />

If your bridge doesn't show up make sure it's fully charged (or has a new battery) and reset it.

Once visible select it.

Position it correctly on your sensor. Some bridges have very little tolerance in respect with angle and distances to the sensor.

</br>

Continue to [Start sensor](../startLsensor).