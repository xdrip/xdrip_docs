<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SW.png" style="zoom:75%;" />

<img src="../images/M-S-SW-MB1.png" style="zoom:75%;" />

You can use these guidelines for the official xDrip+ release and forked versions.

xDrip+ Official Release supports MiBand 2, 3 and 4.

Artem's forked releases support more models (table below). If you want updates on future models read [here](https://www.patreon.com/posts/67845754).

| Forked release                                               | Base xDrip+ version | MiBand        | AmazFit                                                      |
| ------------------------------------------------------------ | ------------------- | ------------- | ------------------------------------------------------------ |
| [Broadcast 0.3](https://www.dropbox.com/s/8xtboyvlsd3wo14/xdrip_BroadcastAPI_0.3.apk?dl=0) | 02.06.2022          | 2, 3, 4, 5, 6 | Bip, Bip Lite, Bip S, Bip S Lite<br/>GTR, GTR2, GTR2e, GTS2, GTS2e, GTR42, GTS2 mini |
| [0.7](https://www.dropbox.com/s/j3es4pzv0advssa/xdrip-miband_0.7.apk?dl=1) | 13.01.2022          | 2, 3, 4, 5, 6 | Bip, Bip Lite, Bip S<br/>GTR, GTR2, GTR2e, GTS2, GTS2e, GTR42, GTS2 mini |
| [0.6.3](https://www.dropbox.com/s/87le7l9y9xyqe6v/xdrip-miband_0.6.3.apk?dl=1) CareLink Follow | 24.04.2021          | 2, 3, 4, 5, 6 | Bip, Bip Lite, Bip S<br/>GTR, GTR2, GTR2e, GTS2, GTS2e, GTR42 |

!!!warning "Forked versions"  
    If you want to change xDrip+ to a forked version make sure to [backup](../../troubleshoot/reinstall/) your data before uninstalling xDrip+.  
    If you don't you'll most probably lose all your settings and data.

!!!note "Prerequisite"  
    Make sure you have BG readings in xDrip+ before trying to have them on your watch.  
    If xDrip+ doesn't receive readings on your phone, they won't be displayed on the watch.

## Install

### Obtain an authentication key

#### If you already paired your watch with the vendor app

- Unpair the watch.
- Uninstall MiFit or Zepp, or whatever app you used to connect your watch.

- **Delete the old key files** (use a file browser on your phone) in the phone memory `freemyband` folder.  
  Recommended if you can't get xDrip+ to connect to the watch.  
  *Note: the name below is an example*

<img src="../images/MiBand1.png" style="zoom:75%;" />

#### Install the patched app matching your watch

Go to [https://www.freemyband.com/](https://www.freemyband.com/)

Download and install [Zepp](https://www.freemyband.com/2019/08/amazfit-gtr-auth-key.html) for Amazfit watches.  
(or)  
Download and install [MiFit](https://www.freemyband.com/2019/08/mi-band-4-auth-key.html) for Xiaomi smartbands.

Authenticate with mail and password. Create an account if necessary.

Pair your smartband.

Enable watch visibility. If you don't find this option make sure you have set your age to 18 and above.

Check a key file was created in the phone memory `freemyband` folder.

You can uninstall the patched app. This is not mandatory. If you want to install the original app, use the same email account to login.

## xDrip+ official and forked versions **not** using WatchDrip+

### Setup xDrip+

Switch the MiBand feature on. Keep your watch close to your phone until it gets detected.

<img src="../images/M-S-SW-MB-I1.png" style="zoom:75%;" />

Mac Address should populate automatically.

<img src="../images/M-S-SW-MB2a.png" style="zoom:75%;" />

**If it doesn't** (unexpected)**:**   
Delete the file(s) in the  `freemyband` folder.  
Open the patched watch app.  
Retry: switch off then on the MiBand feature.

You can also try to enter the watch mac address manually. You will find it in the filename in the `freemyband` folder.  
For example if the name is `mibandFFEEDDCCBBAA.txt` the corresponding mac address will be `FF:EE:DD:CC:BB:AA`.

<img src="../images/M-S-SW-MB-I2.png" style="zoom:75%;" />

Keep an eye on toast messages: during smartwatch authentication you should see the following:

<img src="../images/M-S-SW-MB-I3.png" style="zoom:75%;" />

If authorization fails, delete the file(s) in the `freemyband` folder and open the patched app to regenerate it.

<img src="../images/M-S-SW-MB-I4.png" style="zoom:75%;" />

If xDrip+ can't get the authentication key automatically, you can try to insert it manually. You will find it editing the file.

<img src="../images/M-S-SW-MB-I5.png" style="zoom:75%;" />

Make sure the watch is connected and matches the mac address before manually entering the key.

<img src="../images/M-S-SW-MB-I6.png" style="zoom:75%;" />

Once connected and authenticated, enable Send Readings. Wait for the next value in xDrip+, the watchface should update.

<img src="../images/M-S-SW-MB3.png" style="zoom:75%;" />

To force the watch to update, you can manually send a reading. Look carefully at toast messages.

<img src="../images/M-S-SW-MB5.png" style="zoom:75%;" />

If you have trouble displaying the graph, try to disable high MTU values.

<img src="../images/M-S-SW-MB4.png" style="zoom:75%;" />

### Features

You can enable and disable MiBand integration with the main switch. When troubleshooting don't hesitate to turn it off then on to restart it.

<img src="../images/M-S-SW-MB1.png" style="zoom:75%;" />

The watch mac address should be detected automatically when the field is left empty. You can manually edit it and write the 6 two-digits hex values, colon separated, of your watch.

<img src="../images/M-S-SW-MB2.png" style="zoom:75%;" />

 When a valid mac address is found you will also see the key field. If it's not filled automatically you can manually enter the 32 characters authentication key.

<img src="../images/M-S-SW-MB-I6.png" style="zoom:75%;" />

You must enable this to have readings sent to the watch.

<img src="../images/M-S-SW-MB3.png" style="zoom:75%;" />

You can enable various options to have the watch vibrate on readings, receive alarms or receive notifications as phone calls.

<img src="../images/M-S-SW-MB6.png" style="zoom:75%;" />

You can force watchface refresh using Update BG manually.

<img src="../images/M-S-SW-MB5.png" style="zoom:75%;" />

More customizations are available in this menu.

<img src="../images/M-S-SW-MB7.png" style="zoom:75%;" />

<img src="../images/M-S-SW-MB8.png" style="zoom:75%;" />

You can create your own watchface and modify the background image using these features.  
Keep them disabled unless you have correctly set the files required in the phone xdrip folder.

For tips an example look [here](https://github.com/twinko).

<img src="../images/M-S-SW-MB9.png" style="zoom:75%;" />

Disable High MTU can be used when experiencing watchface display issues.

<img src="../images/M-S-SW-MB4.png" style="zoom:75%;" />

## Forked version with WatchDrip+

This feature is pending merging with xDrip+ official repository.

### Install [WatchDrip](https://bigdigital.home.blog/2022/06/16/watchdrip-a-new-application-for-xdrip-watch-integration/)+

### Setup xDrip+

Enable Broadcast Service API in Settings -> Inter-app Settings

<img src="../../use/images/M-S-IASi.png" style="zoom:76%;" />

</br>

[*Last modified 1/7/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.07.01)
