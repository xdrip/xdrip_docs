This menu will only appear if a [Libre hardware data source](../../install/datasource/#libre) is selected.

If your phone has an **ISO 15693 compatible NFC chip**, you can use the xDrip+ NFC feature with Libre 1/14 days/Pro and 2/2+ (EU).

Remember to first enable the NFC feature in Android settings.

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_nfc_grey600_48dp.png" style="width:5%;" />&ensp;NFC Scan features

!!!xdripitem "Use NFC Feature <span class='symbol'><img src="../../images/ON.png" style="zoom:75%;" /></span>"  
    &ensp;Allow sensors to be scanned when the app is open. Historic data will be backfilled.

You can display sensor age at the bottom of the main graph (xDrip+ master).

!!!xdripitem "Sensor Age or Expiry <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"   
    Show the sensor age on the main screen

In order to automatically open xDrip+ upon NFC sensor detection you should **enable** Scan when not in xDrip+ (recommended). If several apps can scan NFC devices, you will be asked to select the one to use each scan.

!!!xdripitem "Scan when not in xDrip+ <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;NFC scanning will also work from your app launcher screen.

You can decide how xDrip+ will inform you that the scan completed.  Vibration and sound are helpful during (long) NFC scans, you should **enable** both.

When scanning remember that you need to keep the phone in the NFC antenna spot for some seconds to allow a correct scan. Consult your phone manufacturer documentation to find where it is located.

!!!xdripitem "Vibrate to indicate scanning status <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>" 

!!!xdripitem "Beep when scanning within xDrip+ app <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>" 

Faster scan should remain **disabled** to start. You can try to enable it once successful in scanning sensors.

!!!xdripitem "Use faster multi-block reading method <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>" 

If you have trouble with your phone NFC, try to **enable** Any tag method.

!!!xdripitem "Use any-tag optimized reading method <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>" 

## Starting Bluetooth connection with Libre2 sensors

This feature allows xDrip+ to take ownership of the sensor Bluetooth connection. On most phones this is not compatible with the vendor app (only one app can connect to the same sensor). Some users report the possibility to connect both the vendor app and xDrip+ at the same time, but this is not granted: uninstall the vendor app if you want xDrip+ to be connected to the sensor.

!!!xdripitem "Starting Bluetooth connection with Libre2 sensors"  
    &ensp;Connect to Libre2 sensors after scanning them. This will stop Libre reader and Librelink from receiving alerts

This selection will pop-up when you scan a new Libre 2 sensor only if you selected Ask me every time.

Be aware that Always connect to Libre2 sensors will most probably disconnect any other app or device connected to the sensor. If xDrip+ successfully pairs, there will be no possible connection recovery from the other device/app.

!!!xdripitem "Starting Bluetooth connection with Libre2 sensors"  
    &emsp;Always connect to Libre2 sensors<span style="float: right;">●&emsp;</span>&emsp;&emsp;&emsp;  
    &emsp;Ask me every time<span style="float: right;">○&emsp;</span>  
    &emsp;Never connect to Libre2 sensors<span style="float: right;">○&emsp;</span>  

## Smooth libre 3 data when using xxx method

!!!note  
    Smoothing will apply to any external data source app using the `Libre2 (patched app)` data source.

The original implementation included a 25 minutes smoothing algorithm to remove noise and make DIY close looping safer with Libre sensors. You can change the smoothing period to 10, 15 or 25 minutes.

!!!xdripitem "Smooth Libre 3 data when using xxx method"  
    &ensp;Number of minutes to take in consideration when using librex data

Smoothing adds a delay in xDrip+ BG from raw data. The delay is about half the smoothing period. Set the delay accordingly to the sensor behavior for your safety. If you don't use a DIY closed loop system with xDrip+ providing glucose values, set it to 10 minutes.

!!!xdripitem "Starting Bluetooth connection with Libre2 sensors"  
    &emsp;10 minutes<span style="float: right;">○&emsp;</span>&emsp;&emsp;&emsp;  
    &emsp;15 minutes<span style="float: right;">○&emsp;</span>  
    &emsp;25 minutes ><span style="float: right;">●&emsp;</span>  

</br>

[*Last modified 15/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)