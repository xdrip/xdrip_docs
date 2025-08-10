!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_google_circles_communities_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Sync Settings

!!!warning "Old xDrip+ Sync"  
    In July 2024, Google shutdown the deprecated the [Firebase API](https://firebase.google.com/docs/cloud-messaging/migrate-v1) xDrip+ used for xDrip+ Sync.  
    Update xDrip+ to a version at least [July 23rd 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) to use the legacy Sync method.  
    Updating xDrip+ to minimum latest release is recommended.

xDrip+ provides a unique real time sync mechanism between Android devices making BG and treatments sharing the easiest possible task.

</br>

[Here the original reference video](https://www.youtube.com/watch?v=LcgjfbYcWkE).

### Prerequisites

!!!warning  
    [Google Play services](https://play.google.com/store/apps/details?id=com.google.android.gms) are mandatory to use this feature. Make sure they are present, enabled and not subject to battery optimization.

xDrip+ master phone is the device that is actually getting directly glucose readings from a sensor, a bridge, an app.  
Having a follower device being xDrip+ sync master adds little value unless the follower device can't use the same data source.

Your master should receive data reliably. Always troubleshoot the master first if you don't have data on your follower.

## Setup master

Make the primary data source phone master (enable checkbox):

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_google_circles_communities_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Sync Settings  
    

    &emsp;&emsp;&emsp;&emsp;**Be Master for Followers <span class='symbol' style="float: right;"><img src="../../images/EN.png" style="zoom:75%;" />&emsp;&emsp;</span>**

</br>

### Copy the Sync Key

#### Option 1 (recommended)

On the master phone display the Sync Key QR code:

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_qrcode_grey600_48dp.png" style="width:5%;" />&ensp;Show settings QR code  
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;XDRIP PLUS SECURITY KEY SETTINGS ONLY&emsp;</div>

Leave the master phone on this picture for the moment.

<img src="../../use/images/M-S-QRe.png" style="zoom:75%;" />

##### Option 1 bis (follower phone cannot read the QR code)

Take a screenshot of the QR code and send it it the follower phone (MMS, WhatsApp, upload to Google Cloud, ...).

#### Option 2 (complicated)

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_google_circles_communities_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Sync Settings  
    
    &emsp;&emsp;&emsp;&emsp;**Handset Group Security Sync Key**

<img src="../../use/images/M-S-SY2.png" style="zoom:75%;" />

</br>

## Setup follower

Make all other phones followers (disable checkbox):

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_google_circles_communities_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Sync Settings  
    

    &emsp;&emsp;&emsp;&emsp;**Be Master for Followers <span class='symbol' style="float: right;"><img src="../../images/DIS.png" style="zoom:75%;" />&emsp;&emsp;</span>**

</br>

!!!warning "Use xDrip Cloud must be set identically on all phones"  
    Master and followers. Either it is ON for all, or OFF for all.

!!!xdripitem "Use xDrip Cloud"  
    &ensp;Use the new xDrip+ cloud servers. Master and follower must have this setting set the same.  

### Copy the Sync Key from the master

#### Option 1 (recommended)

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &ensp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_qrscan.png" style="width:5%;" />&ensp;Auto Configure  
    &emsp;&emsp;&emsp;Camera

You need to authorize xDrip+ to access the phone camera.  
Scan the QR code displayed on your master phone.

<img src="../../use/images/M-S-ACS.png" style="zoom:75%;" />

You will be asked to confirm you want to import these settings (make sure you import safe settings).

!!!xdripitem "Are you sure?"  
    &ensp;Only import settings from sources you trust!  
    &ensp;Please confirm to import the following settings:  
      
    &ensp;setting1  
    &ensp;setting2  
    &ensp;setting3  
      
    No&emsp;&emsp;<span style="background-color: gray; color: white; text-align: center;">&ensp;Yes&ensp;</span>     

#### Option 1 bis (follower phone cannot read the QR code)

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &ensp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_qrscan.png" style="width:5%;" />&ensp;Auto Configure  
    &emsp;&emsp;&emsp;Image file

Select the image containing the QR code.

<img src="../../use/images/M-S-SY3.png" style="zoom:75%;" />

!!!xdripitem "Are you sure?"  
    &ensp;Only import settings from sources you trust!  
    &ensp;Please confirm to import the following settings:   
    
    &ensp;setting1  
    &ensp;setting2  
    &ensp;setting3  
    
    No&emsp;&emsp;<span style="background-color: gray; color: white; text-align: center;">&ensp;Yes&ensp;</span>  

#### Option 2 (complicated)

Edit the key field and type **exactly** the same key than the master.

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_google_circles_communities_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Sync Settings  
    
    &emsp;&emsp;&emsp;&emsp;**Handset Group Security Sync Key**

<img src="../../use/images/M-S-SY2.png" style="zoom:75%;" />

</br>

[*Last modified 15/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)