<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistC.png" style="zoom:75%;" />

!!!info "Only Libre 2 Europe sensor model is supported"

Libre 2 reference documentation is [here](https://www.minimallooper.com/post/how-to-setup-freestyle-libre-2-and-oop2-to-use-a-native-bluetooth-connection-in-xdrip).

</br>

!!!warning  
    **Uninstall any app connected to the sensor and shield the reader before attempting to connect to xDrip+.**  
    If you connect your sensor directly to xDrip+ you will permanently lose alarms on the vendor app or reader without possibility to recover.  
    If you're not sure this will work, use a sensor at end of life to test the system.  
    Like Libre bridges, success and reliability will vary depending on your phone.  
    Linking your sensor to xDrip+ will void the vendor warranty on the sensor Bluetooth feature.

## Prerequisites

Your Libre 2 sensor is started and you can see BG values when scanning it with the reader or the vendor app.

The phone on which you installed xDrip+ has an NFC reader.

If the vendor app is installed on the same phone you're using for xDrip+, **you uninstalled it**.  
If it is installed on another phone or you're using the Bluetooth reader, you've put these devices far away, or shielded them so that they won't interfere.

## Setup xDrip+

Configure NFC exactly [like this](../libreNFC/#enabling-nfc).

<img src="../images/M-S-HDS-NFC-L2.png" style="zoom:75%;" />

In Starting Bluetooth connection with Libre2 sensors, allow xDrip+ to always connect with Libre 2 sensors.

<img src="../images/M-S-HDS-NFC-L2b.png" style="zoom:75%;" />

Install the right [Out Of Process Algorithm (OOP2)](../../use/OOP/#oop2) and [configure it in xDrip+](../../use/misc/#out-of-process-algorithm).

<img src="../../use/images/M-S-LCS15h.png" style="zoom:75%;" />

<img src="../../use/images/M-S-LCS15i2.png" style="zoom:75%;" />

Verify xDrip+ [Bluetooth settings](../libreBT/#bridge-settings) are correct.

<img src="../images/M-S-LCS-BT-L2a.png" style="zoom:75%;" />

## Connect to the sensor

If you have a previous sensor connected to xDrip+, [stop](../../use/stopsensor) the old sensor.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-StoS.png" style="zoom:75%;" />

Confirm you really want to stop the sensor.

<img src="../images/M-StoSC.png" style="zoom:75%;" />

Scan the sensor with xDrip+ [NFC](../libreNFC) feature and make sure you see the toast message "Scanned OK!".

!!!note  
    Hold the phone steady when scanning the sensor and don't move it: it's taking longer than reading the sensor as you usually do with the vendor app.  
    Remember you should wait one minute between two successful NFC scans.

Start the sensor in xDrip+.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-StaS.png" style="zoom:75%;" />

Confirm `START SENSOR`

<img src="../images/M-StaSC.png" style="zoom:75%;" />

Continue to [Start Sensor](../../use/startsensor/#libre)

If you have trouble getting data directly from the sensor, scan it every 5 minutes with xDrip+ NFC until you reach the calibration request (applies if you selected the [calibration option](../../use/misc/#oop2) with OOP2).

</br>

[*Last modified 2/2/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.02.02)

