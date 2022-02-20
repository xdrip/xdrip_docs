<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-IA.png" style="zoom:75%;" />

Inter-app settings offers two ways to interface xDrip+ with other apps: local broadcast (internal to this phone) and web service (internal and external).

<img src="../images/M-S-IASa.png" style="zoom:75%;" />

### Local Broadcast

Broadcast locally will make xDrip+ send internal messages that can be used by other apps like Nightwatch or AAPS.

<img src="../images/M-S-IASb.png" style="zoom:75%;" />

If you're using calibration plugins or filtering, you can select to broadcast raw data or filtered/calibrated data.  
You can also block noisy data broadcast for safety.

<img src="../images/M-S-IASc.png" style="zoom:75%;" />

Recent apps/phones should accept compatible broadcast. Do not uncheck.

<img src="../images/M-S-IASd.png" style="zoom:75%;" />

You specify the identified receiver if you want xDrip+ to send messages only to a specific app. One of the most common use is when xDrip+ is [AAPS](https://androidaps.readthedocs.io/en/latest/Configuration/xdrip.html#identify-receiver) data source.

<img src="../images/M-S-IASe.png" style="zoom:75%;" />

xDrip+ can also receive messages using this feature, you can enable or disable receiving data and treatments from other broadcasting apps.

<img src="../images/M-S-IASf.png" style="zoom:75%;" />

### Web Service

Web service will open a local web service on your device to allow other devices (smartwatches) and apps to receive data from it.

<img src="../images/M-S-IASg.png" style="zoom:75%;" />

By default the web service is only available to your device, you can open it so that other devices on the network can access it.  
For safety reason (anybody on the network can access this service) you should protect it with a password, if you have a Nightscout site use your API_SECRET.

<img src="../images/M-S-IASh.png" style="zoom:75%;" />