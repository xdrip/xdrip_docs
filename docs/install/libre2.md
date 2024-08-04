!!!xdrip "Libre 2 (EU)  → `Libre Bluetooth`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Hardware Data Source  
    &ensp;&emsp;Libre Bluetooth

### Libre 2 Direct

This describes how to enable direct Bluetooth connection between the sensor & xDrip+, without the need for a bridge.

#### Prerequisites

The phone on which you installed xDrip+ has an NFC reader.

If the vendor app is installed on the same phone you're using for xDrip+, **you uninstalled it**.  
If it is installed on another phone or you're using the Bluetooth reader, you've put these devices far away, or shielded them so that they won't interfere.

#### Setting Up for the first time

(Click [Start Sensor](#starting-libre-2-sensors) for subsequent sensors).

!!!info "Only Libre 2 Europe sensor model is supported"  
    You need to install the [latest OOP2 app](../../use/OOP/#oop2).


Libre 2 reference documentation is [here](https://www.minimallooper.com/post/how-to-setup-freestyle-libre-2-and-oop2-to-use-a-native-bluetooth-connection-in-xdrip) but is not up to date anymore.

</br>

!!!warning  
    **Uninstall any app connected to the sensor and shield the reader before attempting to connect to xDrip+.**  
    If you connect your sensor directly to xDrip+ you will permanently lose alarms on the vendor app or reader without possibility to recover.  
    If you're not sure this will work, use a sensor at end of life to test the system.  
    Like Libre bridges, success and reliability will vary depending on your phone.  
    Linking your sensor to xDrip+ will void the vendor warranty on the sensor Bluetooth feature.

#### Setup xDrip+

As a shortcut, you can scan the QR code shown below to load the settings needed for Libre 2 direct using xDrip+ [Auto Configure](/use/copysettings/#auto-configure) feature. (They set calibration to off - recommended for first use. If instead you want calibration, [follow this](../libre2direct-calib)). The full list of imported settings is shown [here](../libre2direct-qr-settings).

QR Codes - Click image to expand

No Calibration             |  With Calibration
:-------------------------:|:-------------------------:
[<img src="../images/qr_libre2direct-nocalib-30.png" style="zoom:50%;" />](../libre2direct-qr-settings) | [<img src="../images/qr_libre2direct-calib-30.png" style="zoom:50%;" />](../libre2direct-calib)

If you used the QR codes, you can skip to [Starting Libre 2 Sensors](#starting-libre-2-sensors)

#### Configure NFC

Configure NFC exactly [like this](../libreNFC/#enabling-nfc).

#### Starting Libre 2 Sensors

Physically insert your Libre2 sensor and start it using either the reader device, or LibreLink. Make a note of the time that the sensor will be ready. If using the same phone as xDrip, disable LibreLink on the phone. You should see BG values when scanning it. Now wait 60 minutes until the sensor has warmed up and self-calibrated.

#### Connect to the sensor

!!!xdrip "`Stop Sensor`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Stop Sensor  

If you have a previous sensor connected to xDrip+, stop the old sensor.

Scan the sensor with xDrip+ NFC and make sure you see the toast messages "Scanning.." and then  "Scanned OK!".

!!!note  
    Hold the phone steady when scanning the sensor and don't move it: it's taking longer than reading the sensor as you usually do with the vendor app.  
    Remember you should wait one minute between two successive NFC scans.

!!!xdrip "`Start Sensor`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Start Sensor  

Start the sensor in xDrip+. When required to enter the time you physically started the sensor, do not put a time earlier than reality to avoid having inconsistent values.

Wait 60 seconds and scan again with xDrip+. This adds the sensor as the BT device that xDrip+ will take the readings from. Expect to see NEW SENSOR STARTED notification. If you are set to No Calibration", you should see the first reading immediately. If you have set Calibration, you should then be in the "Collecting Initial Readings" screen.
You will now need to wait between 3 and 15 minutes for 3 readings to be received, and then you will be taken to the **Calibrate Sensor?** prompt.
After entering the calibration data, the Libre 2 sensor should be bonded to xDrip+, and should deliver readings every 5 minutes.

You can confirm that all is working by comparing to "How it should look" [here](../../troubleshoot/libre2direct/## What it should look like)

If you have trouble getting data directly from the sensor, scan it every 5 minutes with xDrip+ NFC until you reach the calibration request (applies if you selected the [calibration option](../../use/misc/#oop2) with OOP2).

</br>

[*Last modified 3/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)

