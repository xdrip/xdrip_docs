!!!xdrip "`Glucose Meters`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_touch_app_grey600_48dp.png" style="width:5%;" />&ensp;Glucose Meters

</br>

##### NFC meter

If you use a  Glucomen Aero meter with an NFC reader capable phone you can scan it to get the last reading.

!!!xdripitem "Use NFC Meter&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Download glucose records from NFC meter when xDrip is open

##### If you use a compatible Bluetooth meter

In order to enable Use Bluetooth Meter you need to pair a Bluetooth meter first.  
If this is a new meter **make sure you have measured BG at least once before trying to pair it**.

Do **<u>not</u>** enable the Bluetooth meter option in xDrip+ now.

!!!xdripitem "Use Bluetooth Meter&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; `OFF`←"  
    &ensp;Automatically connect and retrieve data from a standard's compliant glucose meter like the Contour Next One

Scan for Bluetooth meter:

!!!xdripitem "Scan for Bluetooth Meter"

Put your meter in pairing mode and touch scan in the Scan for Bluetooth Meter menu.

<img src="../images/M-S-GMb.png" style="zoom:75%;" />

<img src="../images/M-S-GMc.png" style="zoom:75%;" />

Once paired you can enable the meter in the menu.

!!!xdripitem "Use Bluetooth Meter&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Automatically connect and retrieve data from a standard's compliant glucose meter like the Contour Next One

Your meter your now be shown below:

!!!xdripitem "Scan for Bluetooth Meter"  
    &ensp;Bayer HealthCare LLC AA:BB:CC:DD:EE:FF:00

You can enable sounds to indicate connection, disconnection and data collection.

!!!xdripitem "Sound effect indicators"  
    &ensp;Enable this to play sound effects when the meter connects, disconnects or syncs data

You can have xDrip+ suggest to use the result to calibrate your connected sensor (if it supports calibration).

!!!xdripitem "Use meter for calibrations&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 🗹"  
    &ensp;When a new blood glucose result is received, ask if that should be used to calibrate with

It is not recommended to enable automatic calibration.

!!!xdripitem "Automatic calibration&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ☐"  
    &ensp;Calibrate using new blood glucose readings if the conditions appear right to do so without asking confirmation (experimental)

When you enable the use of the Bluetooth meter, all blood tests will automatically transfer into xDrip+ as [treatments](../mainUI/#treatments).

</br>

[*Last modified 4/5/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.05.04)