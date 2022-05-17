<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistE.png" style="zoom:75%;" />

This is the reference video: [https://www.youtube.com/watch?v=LcgjfbYcWkE](https://www.youtube.com/watch?v=LcgjfbYcWkE)

</br>

### Prerequisites

xDrip+ master phone is the device that is actually getting directly glucose readings from a sensor, a bridge, an app.  
Having a follower device being xDrip+ sync master adds little value unless the follower device can't use the same data source.

Your master should receive data reliably. Always troubleshoot the master first if you don't have data on your follower.

### Setup master

Make the primary data source phone master (enable checkbox):

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SY.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SY3.png" style="zoom:75%;" />

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

### Setup follower

Make sure the follower phone is not master (disable checkbox).

<img src="../../use/images/M-S-SY3b.png" style="zoom:75%;" />

Set the follower to xDrip+ Sync follower data source.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDS-SF.png" style="zoom:75%;" /> 

You might need to reboot the follower phone to validate everything and get data.

</br>

[*Last modified 29/3/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.28)
