<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-SY.png" style="zoom:75%;" />

</br>

!!!warning "Work in progress"  
    In July 2024, Google shutdown the deprecated the [Firebase API](https://firebase.google.com/docs/cloud-messaging/migrate-v1) xDrip+ used for xDrip+ Sync.  
    A workaround solution was implemented in [July 23rd pre-release](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) but outstanding issues make the follower app lose connection after few minutes.  
    If you need to use xDrip+ Sync, the master device must be of a minimum version [July 23rd 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) but the followers should be of a maximum version [June 28th 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.06.28).

xDrip+ provides a unique real time sync mechanism between Android devices making BG and treatments sharing the easiest possible task.

</br>

[**Here the reference video**](https://www.youtube.com/watch?v=LcgjfbYcWkE).

### Prerequisites

!!!warning  
    [Google Play services](https://play.google.com/store/apps/details?id=com.google.android.gms) are mandatory to use this feature. Make sure they are present, enabled and not subject to battery optimization.

xDrip+ master phone is the device that is actually getting directly glucose readings from a sensor, a bridge, an app.  
Having a follower device being xDrip+ sync master adds little value unless the follower device can't use the same data source.

Your master should receive data reliably. Always troubleshoot the master first if you don't have data on your follower.

## Setup master

Make the primary data source phone master (enable checkbox):

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SY.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SY3.png" style="zoom:75%;" />

</br>

### Copy the Sync Key

#### Option 1 (recommended)

On the master phone display the Sync Key QR code:

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-QR.png" style="zoom:75%;" />

<img src="../../use/images/M-S-QRa.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-QRb.png" style="zoom:75%;" />

Leave the master phone on this picture for the moment.

<img src="../../use/images/M-S-QRe.png" style="zoom:75%;" />

#### Option 2 (complicated)

Write down the master key.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SY.png" style="zoom:75%;" />   
<img src="../../use/images/M-S-SY2.png" style="zoom:75%;" />

</br>

## Setup follower

### Copy the Sync Key from the master

#### Option 1 (recommended)

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-AC.png" style="zoom:75%;" />

You need to authorize xDrip+ to access the phone camera.  
Scan the QR code displayed on your master phone.

<img src="../../use/images/M-S-ACS.png" style="zoom:75%;" />

#### Option 2 (complicated)

Edit the key field and type **exactly** the same key than the master.

<img src="../../use/images/M-S-SY2.png" style="zoom:75%;" />

</br>

### Disable master

Make sure the follower phone is not master (disable checkbox).

<img src="../../use/images/M-S-SY3b.png" style="zoom:75%;" />

Set the follower to xDrip+ Sync follower data source.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../../install/images/M-S-HDS-SF.png" style="zoom:75%;" /> 

You might need to reboot the follower phone to validate everything and get data.

</br>

[*Last modified 3/8/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.08.03)