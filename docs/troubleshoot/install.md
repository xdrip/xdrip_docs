## My phone says this app is very dangerous

GitHub releases from the [official repository](https://github.com/NightscoutFoundation/xDrip/releases) are safe. Ignore this message.

<img src="../images/Install18.png" style="zoom:75%;" />

</br>

## I cannot find the file I downloaded

Open a file explorer and look into the Downloads folder of your phone internal storage: you should see the a file called somehow like `xDrip-plus-20yymmdd-cccccccc.apk`

</br>

## When I touch the xDrip+ .apk it opens a file list

If the xDrip-plus file ends with .zip, rename it to .apk and retry.

If there's no way to open it with the installer package try with an [APK installer](https://play.google.com/store/apps/details?id=com.apkinstaller.ApkInstaller).

</br>

## I cannot install unknown apps

<img src="../images/Install19.png" style="zoom:75%;" />

In Android settings -> [Security settings](https://developer.android.com/distribute/marketing-tools/alternative-distribution#unknown-sources) you need to allow the app you're using to open the downloaded file to install files from unknown sources, if available select only this time.

Below the example for Chrome, you might be using another app to open the xDrip+ .apk file.

<img src="../images/Install20.png" style="zoom:75%;" />

</br>

## I cannot install the app

<img src="../images/Install23.png" style="zoom:75%;" />

Make sure you don't have a different version of xDrip+ installed: you can update or downgrade only apps from the same developer. If necessary [reinstall](../reinstall) xDrip+ to switch from the official version to a forked version (and vice versa).

</br>

## xDrip+ needs background location

<img src="../images/Install21.png" style="zoom:60%;" />

If you want xDrip+ to connect to a Bluetooth device it needs to have permanent [access to location](../../install/prerequisites/#enable-location).

For newer Android versions go to Android Settings -> Location -> Apps -> xDrip+ or Android Settings -> Apps -> xDrip+ -> Location and check Allow all the time is enabled.

<img src="../images/Install21b.png" style="zoom:100%;" />

</br>

## xDrip+ needs battery optimization whitelisting

<img src="../images/Install22.png" style="zoom:60%;" />

xDrip+ should not be optimized at all.

This setting location will vary from brand to brand and Android version, you will usually find it in Android Settings -> Apps -> xDrip+ -> Battery

<img src="../images/Install22b.png" style="zoom:100%;" />

You might need to reboot your phone to apply these changes. If the warning message remains, make sure you are using a recent xDrip+ version: update it if necessary.

</br>

[*Last modified 28/3/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)
