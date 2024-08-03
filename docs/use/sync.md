<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-SY.png" style="zoom:75%;" />

!!!warning "Work in progress"  
    In July 2024, Google shutdown the deprecated the [Firebase API](https://firebase.google.com/docs/cloud-messaging/migrate-v1) xDrip+ used for xDrip+ Sync.  
    A workaround solution was implemented in [July 23rd pre-release](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) but outstanding issues make the follower app lose connection after few minutes.  
    If you need to use xDrip+ Sync, the master device must be of a minimum version [July 23rd 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) but the followers should be of a maximum version [June 28th 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.06.28).

!!!warning  
    [Google Play services](https://play.google.com/store/apps/details?id=com.google.android.gms) are mandatory to use this feature. Make sure they are present, enabled and not subject to battery optimization.

xDrip+ provides a unique real time sync mechanism between Android devices making BG and treatments sharing the easiest possible task.

The underlying security key can be customized instead of using the Google account key (not editable).

<img src="../images/M-S-SY1.png" style="zoom:75%;" />

##### Handset group security sync key

An unique key is created at xDrip+ install (it will be different if you reinstall xDrip+) and should match all devices using xDrip+ sync. Even if you can customize this key making it your own (letters and numbers) you will usualy leave it as generated.

<img src="../images/M-S-SY2.png" style="zoom:75%;" />

##### Be master for followers

The device getting BG data from the sensor will be Master, all others will be Followers.  
Only one master can use the same security key. If two masters are detected, the newly arrived one will be disabled and return to follower state.

<img src="../images/M-S-SY3.png" style="zoom:75%;" />

##### Accept followers actions

You can setup the master phone to receive and accept followers treatments and calibrations. Be extremely careful when using this feature if you use automatic calibrations. Also remember sensor start and stop might be sent by followers and accepted by the master.

<img src="../images/M-S-SY4.png" style="zoom:75%;" />

##### Whole house

Based on the Parakeet project, multiple master devices can create a whole house network.  
If you use Libre sensors you can also use this feature, see [here](https://github.com/tzachi-dar/LibreAllHouse) how to create your whole house network.

<img src="../images/M-S-SY5.png" style="zoom:75%;" />

##### Parakeet geolocalization

And if you used a Parakeet you could send actual position to followers.

<img src="../images/M-S-SY6.png" style="zoom:75%;" />

##### Remote snoozing

Remote snoozing allows the snooze request to propagate along the group. Master or followers can snooze alarms. Use with care.

<img src="../images/M-S-SY7.png" style="zoom:75%;" />

##### Disable sync

Disable Sync completely disables sharing. You might need to restart your phone when you enable it back.

<img src="../images/M-S-SY9.png" style="zoom:75%;" />

### Desert Sync

Desert Sync allows xDrip+ sync without internet or phone data coverage.

<img src="../images/M-S-SY8.png" style="zoom:75%;" />

Desert Sync allows you to share data between your xDrip+ master and followers when internet is not available. This can happen when traveling out of phone coverage or on a local intranet (no internet access).

Enable desert sync on all devices.

<img src="../images/M-S-SY8a.png" style="zoom:75%;" />

If you know the IP address of the master (this is for local intranets) enter it here.  
You will usually find the master IP in the phone Android settings - About phone.

<img src="../images/M-S-SY8b.png" style="zoom:75%;" />

Now display the master settings QR code and scan it on your followers using [auto configure](../copysettings/#auto-configure).

<img src="../images/M-S-SY8c.png" style="zoom:75%;" />

If you want to secure your connection (local intranets and public wifi) you can enable https.

<img src="../images/M-S-SY8d.png" style="zoom:75%;" />

If you're without mobile or Wi-Fi data, put the master phone in Wi-Fi hotspot mode and connect the followers through tethering. Maximum distance between devices will be limited. This will also weight heavily on the master battery, make sure you have a backup power bank available.  
When using tethering you will need to enable a [web service](../interapp/#web-service) on the master. Make sure the secret is identical on master and followers.

Look in system status to check everything is connecting correctly.

<img src="../images/M-S-SY8d2.png" style="zoom:75%;" />

</br>

[*Last modified 3/8/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.08.03)