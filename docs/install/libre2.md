!!!info "Only Libre 2 Europe sensor model is supported"

!!!note  
    Reference documentation [here](https://www.minimallooper.com/post/how-to-setup-freestyle-libre-2-and-oop2-to-use-a-native-bluetooth-connection-in-xdrip).

## Settings

Verify your settings are correct.

`Menu` / `Settings` / `Less Common Settings` / `Bluetooth Settings`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-S.png" style="zoom:75%;" />

<img src="../../images/M-S-LCS.png" style="zoom:75%;" />

<img src="../../images/M-S-LCS-BT.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-BT-L1.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-BT-L2.png" style="zoom:75%;" />

For Samsung phones disable `Trust Auto-Connect`!

<img src="../../images/M-S-LCS-BT-TAC.png" style="zoom:75%;" />

For Android version 8 and above you can enable `Use Background Scans`

<img src="../images/M-S-LCS-BT-L3.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-BT-MK.png" style="zoom:75%;" />

If you have connection losses you can enable polling mode. It will not do anything useful but keep the Bluetooth link awake.

<img src="../images/M-S-LCS-BT-L4.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-BT-L6.png" style="zoom:87%;" />

<img src="../images/M-S-LCS-BT-L5.png" style="zoom:75%;" />

</br>

## Enable NFC scan

See [here](../libreNFC/#enabling-nfc) for details. Match exactly the settings.

Select Starting Bluetooth Connection with Libre 2 sensors

<img src="../images/M-S-HDS-NFC2.png" style="zoom:87%;" />

And set it to: Always connect to Libre 2 sensors.

<img src="../images/M-S-HDS-NFC-L2.png" style="zoom:87%;" />

Restart your phone to make sure all parameters are being taken into account.

</br>

## Start the sensor

Use the vendor app, or the reader to start the sensor. There are no alternative solution.  
Wait until the sensor is actually started and you can read your BG.

Remove location authorization to the vendor app, if your started the sensor with the Bluetooth reader make sure to shield it before continuing.

!!!warning "Sensor warranty"  
    Connecting a Libre 2 to xDrip+ will **disconnect Bluetooth from the vendor app or the sensor reader without possible recovery**. Make sure you understand the implications on sensor warranty.





