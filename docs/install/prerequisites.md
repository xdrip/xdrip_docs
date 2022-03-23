You need an Android phone.

- Minimum supported Android version is 4.4 but 6 and above is recommended.
- If you will connect xDrip+ to a sensor your phone must support Bluetooth Low Energy (BLE): you can use utilities [like this one](https://play.google.com/store/apps/details?id=com.treeteam.blechecker) to check.
- If you want to use the embedded master - follower function of xDrip+ (called xDrip+ Sync) both phones must have the [Google Play Services](https://play.google.com/store/apps/details?id=com.google.android.gms) installed.
- In order to use NFC scanning features for Libre sensors, or to connect directly to a Libre 2 (EU) sensor your phone needs a compatible NFC reader.
- If using Android 10 and above make sure you use a recent version of xDrip+.

### Family Link

To install xDrip+ on a phone monitored by [Google Family Link](https://families.google.com/families) you must disable it until you've installed the app.  
If you want to enable it again afterwards make sure xDrip+ has all rights and no time limitations.

### Work profile

If you use a company controlled phone, you might not be able to install xDrip+ due to corporate policies.

You can try to sideload the app with [Android Debug](../../troubleshoot/ADB) using a computer after enabling developer options on your phone. Remember to delete xDrip+ in your work profile if necessary, as it might be installed in both environments.

### Phone time accuracy

Synchronize your phone clock to the network (Android Settings -> [Date & Time](https://support.google.com/android/answer/2841106)).  
Make sure you are on the correct time zone and daylight settings are correct.

<img src="../images/Install16.png" style="zoom:100%;" />

### Enable location

For newer Android versions (6 and above), location is [mandatory](https://developer.android.com/training/location/permissions) to allow Bluetooth Low Energy connection.  
If you use xDrip+ with a Bluetooth sensor or bridge you **must** enable location (Android Settings -> [Location](https://support.google.com/android/answer/3467281)) and authorize xDrip+ to access it. Consult your phone manual as  it will depend on Android version and manufacturer.

<img src="../images/Install17.png" style="zoom:100%;" />

### Energy savings

**Disable** all phone energy savings/battery Android settings before installing xDrip+.  
You can try to restore some after verifying xDrip+ is working correctly, never optimize xDrip+.

</br>

[Proceed to downloading xDrip+](../download)
