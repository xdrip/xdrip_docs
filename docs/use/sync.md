!!!xdrip "`xDrip+ Sync`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_google_circles_communities_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Sync Settings

!!!warning "Old xDrip+ Sync"  
    In July 2024, Google shutdown the deprecated the [Firebase API](https://firebase.google.com/docs/cloud-messaging/migrate-v1) xDrip+ used for xDrip+ Sync.  
    Update xDrip+ to a version at least [July 23rd 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) to use the legacy Sync method.  
    Updating xDrip+ to minimum latest release is recommended.

!!!warning  
    [Google Play services](https://play.google.com/store/apps/details?id=com.google.android.gms) are mandatory to use this feature. Make sure they are present, enabled and not subject to battery optimization.

xDrip+ provides a unique real time sync mechanism between Android devices making BG and treatments sharing the easiest possible task.

The underlying security key can be customized instead of using the Google account key (not editable).

!!!xdripitem "Sync using custom security key"  
    &ensp;Key is used instead of Google account

##### Handset group security sync key

An unique key is created at xDrip+ install (it will be different if you reinstall xDrip+) and should match all devices using xDrip+ sync. Even if you can customize this key making it your own (letters and numbers) you will usually leave it as generated.

!!!xdripitem "Handset Group Security Sync Key"  
    &ensp;Handset sync grouping key

##### Be master for followers

The device getting BG data from the sensor will be Master, all others will be Followers.  
Only one master can use the same security key. If two masters are detected, the newly arrived one will be disabled and return to follower state.

!!!xdripitem "Be master for followers"  
    &ensp;This device will send data to followers

##### Accept followers actions

You can setup the master phone to receive and accept followers treatments and calibrations. Be extremely careful when using this feature if you use automatic calibrations. Also remember sensor start and stop might be sent by followers and accepted by the master.

!!!xdripitem "Accept followers actions"  
    &ensp;Treatments, Calibrations, and other actions from followers will be accepted.

##### Use xDrip Cloud

After Google shutdown the deprecated the [Firebase API](https://firebase.google.com/docs/cloud-messaging/migrate-v1) used for xDrip+ Sync in July 2024, a new sharing method has been developed.

!!!warning "Must be set identically on all phones"  
    Master and followers. Either it is ON for all, or OFF for all.

!!!xdripitem "Use xDrip Cloud"  
    &ensp;Use the new xDrip+ cloud servers. Master and follower must have this setting set the same.  

##### Whole house

Based on the [Parakeet](https://github.com/jamorham/wixel-xDrip) project, multiple **master** devices can create a whole house network.  
If you use Libre sensors you can also use this feature, see [here](https://github.com/tzachi-dar/LibreAllHouse) how to create your whole house network.

!!!xdripitem "Whole House"  
    &ensp;Participate in a Whole House Network

!!!xdripitem "Libre Whole House"  
    &ensp;This phone will be a collector in a Whole House Network

##### Parakeet geolocalization

And if you used a Parakeet your master could send actual position to followers.

!!!xdripitem "Parakeet geolocalization"  
    &ensp;Send Parakeet map location to followers

##### Remote snoozing

Remote snoozing allows the snooze request to propagate along the group. Master or followers can snooze alarms. Use with care.

!!!xdripitem "Remote snoozing"  
    &ensp;Sending and receiving remote snoozes

##### Disable sync

Disable Sync completely disables sharing. You might need to restart your phone when you enable it back.

You can use this option in case of complete Sync failure or when using a phone without Google Play Services.

!!!xdripitem "Disable all Sync features"  
    &ensp;Temporary work-around option, completely stops all synchronization. May need reboot after being re-enabled. Use with care!

### Desert Sync

Desert Sync allows xDrip+ sync without internet or phone data coverage.

!!!xdripitem "Desert Sync"  
    <img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xxhdpi/desert_sync.png" style="width:5%;" />&ensp;Off-grid following

Desert Sync allows you to share data between your xDrip+ master and followers when internet is not available. This can happen when traveling out of phone coverage or on a local intranet (no internet access).

Enable desert sync on all devices.

!!!xdripitem "Desert Sync"  
    &ensp;Enable local non-internet sync facilities

If you know the IP address of the master (this is for local intranets) enter it here.  
You will find the master IP in the phone Android settings - About phone - IP address.

!!!xdripitem "Master IP address"

Now display the master settings QR code and scan it on your followers using [auto configure](../copysettings/#auto-configure).

!!!xdripitem "Show QR Code"  
    Barcode for followers to scan to auto-configure them

If you want to secure your connection (local intranets and public wifi) you can enable https.

!!!xdripitem "Use HTTPS"  
    Add another layer of encryption for shared networks, e.g. public WiFi

If you're without mobile or Wi-Fi data, put the master phone in Wi-Fi hotspot mode and connect the followers through tethering. Maximum distance between devices will be limited. This will also weight heavily on the master battery, make sure you have a backup power bank available.  
When using tethering you will need to enable a [web service](../interapp/#web-service) on the master. Make sure the secret is identical on master and followers.

Look in system status to check everything is connecting correctly.

<img src="../images/M-S-SY8d2.png" style="zoom:75%;" />

</br>

[*Last modified 3/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)