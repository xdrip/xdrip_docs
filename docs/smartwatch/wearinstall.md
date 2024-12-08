You will find the reference documentation [here](https://github.com/NightscoutFoundation/xDrip/blob/master/Documentation/WatchGuide.md).

!!!info "Fun fact"  
    You can use some of these methods with the Dexcom master app and AAPS.

### Prerequisites

Your watch needs to be compliant with Android Wear OS and bear the following logo:

<img src="https://play-lh.googleusercontent.com/WmoV-m8b6x16sDRfzebu5b2vstcyBHRrpzCj6ODoh6hGuMa9Gg39EvnOk7z3qMa0_WM=s180-rw" style="zoom:50%;" align="left"/>

Recent watches can be found [here](https://wearos.google.com/).  
All Wear OS smartwatches are directly compatible with xDrip+ but Wear OS [Google changes](https://www.androidpolice.com/2021/02/12/wear-os-is-making-app-sideloading-much-more-difficult/) have made it more complex to install it.  
Further Samsung and Google Wear OS 5 behavioral changes have made that even more complicated.

### Wear OS versions

Legacy Wear OS like 1.5 and 1.6 are now more complex to use with modern phones.  
Wear OS 2 and 3 are fully supported.  
Wear OS 4 and 5 might present challenges.

### Wear OS 1.x

!!!warning "Android 15"  
    The old Android Wear 2.9 package is not compatible with Android 15.

Usually it's the Sony Smartwatch 3 ([SWR50](https://www.sony.com/electronics/support/other-products-xperia-smart-devices/swr50)). 

#### Method 1 (easiest)

1. Unpair the watch from your phone if it was already paired.
2. Uninstall Wear OS from your phone if it is installed.  
   If you have other Android Wear watches connected you might need to pair them again.
3. Disable the Google Play apps auto-update feature.
4. Install [Android Wear 2.9.0.185084575 GMS](https://www.apkmirror.com/apk/google-inc/android-wear/android-wear-2-9-0-185084575-gms-release/android-wear-smartwatch-2-9-0-185084575-gms-android-apk-download/).
5. Open Android Wear and pair the watch, accept and allow everything: if you want to disable some features you'll do that when you're done with xDrip+ install.
6. When pairing completes check your watch Google Play version is **above 9**.  
   Settings -> About -> Versions  
   <img src="../images/M-S-SW-AW3.png" style="zoom:75%;" />  
   If it isn't: tap it 3 times to force update, and wait (up to hours).  
   <img src="../images/M-S-SW-AW3a.png" style="zoom:75%;" />
7. Select an xDrip+ watchface on the phone Android Wear app  
   <img src="../images/M-S-SW-AW1.png" style="zoom:75%;" />   
   <img src="../images/M-S-SW-AW2.png" style="zoom:75%;" /> 
8. Enable Google Play apps Auto-update and update manually to [Wear OS](https://play.google.com/store/apps/details?id=com.google.android.wearable.app).

#### Method 2 (with a computer)

1. Install [Wear OS](https://play.google.com/store/apps/details?id=com.google.android.wearable.app) and pair the watch to your phone.
2. Check your watch Google Play services version is above 9 (manufacturing default for latest firmware is 8.7).  
   Settings -> About -> Versions  
   <img src="../images/M-S-SW-AW3.png" style="zoom:75%;" />   
   <img src="../images/M-S-SW-AW3a.png" style="zoom:75%;" />   
   If it is, you're done: see above how to select an xDrip+ watchface.  
   Else continue below.
3. [Download](https://www.apkmirror.com/apk/google-inc/google-play-services-android-wear/google-play-services-android-wear-9-8-41-release/google-play-services-9-8-41-534-130237018-android-apk-download/download/) a more recent version of Google Play services. Rename the file to a shorter name, like `GPS.apk`.
4. [Install ADB and sideload it to the watch](../../troubleshoot/ADB).

### Wear OS 2.x and 3.x

#### Method 1 (easiest)

This might not be always possible to complete this procedure, if it fails try Method 2.

1. Unpair the watch from your phone if it was already paired.
2. Uninstall Wear OS from your phone if it is installed.  
   If you have other Android Wear watches connected you might need to pair them again.
3. Disable the Google Play apps auto-update feature.
4. Install an old version of Wear OS [2.51.0.398446042.gms](https://www.apkmirror.com/apk/google-inc/android-wear/android-wear-2-51-0-398446042-gms-release/wear-os-by-google-smartwatch-2-51-0-398446042-gms-android-apk-download/).
5. Open Android Wear and pair the watch, accept and allow everything: if you want to disable some features you'll do that when you're done with xDrip+ install.
6. On the watch, open Settings, Aps & Notifications, App Info, System Apps and search Google Play Store. Select Remove Upgrades. Confirm. (Note the watch will automatically upgrade its app, you need to be fast once downgraded.)  
   <img src="../images/M-S-SW-AW6.png" style="zoom:65%;" />
7. On the watch, open Google Play Store and scroll to Apps on my Phone. Select and install xDrip+.  
   <img src="../images/M-S-SW-AW7.png" style="zoom:65%;" />
8. Change the watchface to an xDrip+ one with a long touch on the current watchface.

#### Method 2 (best)

**Recommended:** follow [this video](https://www.youtube.com/watch?v=ejrmH-JEeE0) that details the process.

You need to be connected to Wi-Fi. So should your watch.

1. Install [Wear OS](https://play.google.com/store/apps/details?id=com.google.android.wearable.app) and pair your watch.
2. Install and open [Wear Installer 2](https://play.google.com/apps/testing/org.freepoc.wearinstaller2) on your phone.  
   <img src="../images/M-S-SW-AW9.png" style="zoom:75%;" />
3. Enable Developer mode on the watch (Instructions [here](../../troubleshoot/ADB/#smartwatch). Only on the watch, then come back)
4. Enable ADB Debug over Wi-Fi on the Watch.  
   <img src="../images/M-S-SW-AW8.png" style="zoom:65%;" />
5. Write down the watch IP address.  
   <img src="../images/M-S-SW-AW10.png" style="zoom:65%;" />
6. Open the app on the watch and copy the IP address to the app on the phone.  
   Tape `Done`  
   <img src="../images/M-S-SW-AW11.png" style="zoom:75%;" />
7. Select xDrip+  
   <img src="../images/M-S-SW-AW12.png" style="zoom:75%;" />  
   Wear Installer will extract the wear smartwatch apk.  
   <img src="../images/M-S-SW-AW13.png" style="zoom:75%;" />  
   Make sure to accept debug authorisation on your watch if required.  
   <img src="../images/M-S-SW-AW14.png" style="zoom:75%;" />
8. Once ready, select `INSTALL` and let the app do its work without interfering, it might take a few minutes to complete.  
   <img src="../images/M-S-SW-AW15.png" style="zoom:75%;" />
9. Look for messages during the process but don't interfere.  
   <img src="../images/M-S-SW-AW16.png" style="zoom:75%;" />
10. When complete, select `FINISH`.  
    <img src="../images/M-S-SW-AW17.png" style="zoom:75%;" />
11. If xDrip+ failed to install on the watch, try again.

##### Method 2 alternatives

Use [GeminiMan Wear OS Manager](https://play.google.com/store/apps/details?id=com.geminiman.wearosmanager) or [Easy Fire Tools](https://play.google.com/store/apps/details?id=de.agondev.easyfiretools) (similar to above).

#### Method 3 (with a computer)

1. Install [ADB](../../troubleshoot/ADB).
2. Download xDrip+ on a computer and extract the APK (it's a zipped file).  
   **It must be exactly the same version you have on your phone.**
3. Browse the the `/res/raw` folder of the xDrip+ package and copy the file `android_wear_micro_apk.apk` into your ADB folder.
4. Sideload the xDrip+ wear extension to the watch.

### Wear OS 5

Google and Samsung have brought important changes to Wear OS 5 and do not easily allow custom watchfaces.

Installing the AAPS Watch Face has to be done with Wear Installer 2 following [this video](https://www.youtube.com/watch?v=yef_qGvcCnk) until 3:56. At this point you need to select xDrip+ in the installed apps, not a custom APK.
Accidental change of the Watch Face to another one requires the procedure above to be repeated.

### Update xDrip+ on your watch

#### Wear OS 1.x

To force the watch app to update, just synchronize all apps.  
<img src="../images/M-S-SW-AW32.png" style="zoom:75%;" />

#### Wear OS 2.0 to 4.0

You will need to uninstall and reinstall the wear app every time you want to [update](../../use/update) your phone xDrip+ in order to maintain the apps sync'ed.

Starting with April 13th 2021, xDrip+ can automatically update your wear version if you already have a compatible version installed (which is minimum [Nightly build 13th Apr 2021](https://github.com/NightscoutFoundation/xDrip/releases/tag/2021.04.13)).

For the updated version the [instructions](https://github.com/NightscoutFoundation/xDrip/issues/1648) are as follows:

- Install the latest nightly xDrip WearOs component to the watch, eg using Wear Installer app, downgrading play store or via adb manually (see above).
- Make sure developer mode and wifi adb debugging are enabled on the Watch (see above: Wear OS 2 Method 2 step 4)
- Go to xDrip Prefs on the Watch, scroll till you see `Force Update` - tap it
- It should check ADB, and ask for authorization, select `Always Allow`
- Probably it will tell you ADB isn't working due to needing the authorization
- Go in to xDrip Prefs again on the watch and click Force Update
- This time it should say ADB looks good and then ask xDrip phone app to send the latest version
- This should download and then xDrip will install itself.

When the versions are identical this won't really do much, but this process can be used to force xDrip to send the latest version in future but it should also automatically detect version changes and update in the background. For fun you could install the latest nightly on the watch then downgrade your phone and check that the update process then downgrades your watch app version. The version information should be displayed next to the `Force Update` text.

The idea is that you no longer need to use Wear Installer or whatever method you used to install the first time around (eg PC based adb or downgrading play store) as xDrip can update itself.

#### Wear OS 5.0

Reinstall the watchface with [Wear Installer 2](#wear-os-5).

</br>

[*Last modified 8/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)