

!!!xdrip "`Smart Watches`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Smart Watch Features

### xDrip+ direct integration

xDrip+ offers a wide range of smartwatch support.

#### [Android Wear Integration](../wear)

!!!xdripitem "Android Wear Integration" 

You'll find the most complete integration in Wear OS watches as they are running a part of the xDrip+ app locally.

The wear extension of xDrip+ is not under development anymore.

If you need more watchfaces or customizations you can use [Tasker](https://github.com/FreDiabetics/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/README.md) (but not as a standalone collector).

#### [Pebble Integration](../pebble)

!!!xdripitem "Pebble Integration" 

Pebble smartwatch use is a historic milestone of CGM in the Cloud. Pebble has been bought by Fitbit in 2016 and resources have moved to archives and [rebble.io](https://rebble.io/).

You need to download the watch app from [APKMirror](https://www.apkmirror.com/apk/pebble-technology-corp/pebble/pebble-4-4-2-1405-62d45d7d7-endframe-release/pebble-4-4-2-1405-62d45d7d7-endframe-android-apk-download/).

#### [AmazFit Sync Service](https://crazyinfo.de/2018/07/25/xdrip-smartwatch-widget-fuer-amazfit-pace-stratos/)

!!!xdripitem "AmazFit Sync Service" 

AmazFit was used only for Pace and Stratos models.  
**You cannot use this feature for other AmazFit watches.**

#### [BlueJay Watch](../bluejay)

!!!xdripitem "BlueJay Watch" 

BlueJay is an incredible companion of your Dexcom sensor, with or without xDrip+, with or without phone.

#### [LeFun Band](https://www.lefunsmart.com/collections/smartwatches)

!!!xdripitem "LeFun Band" 

LeFun band integration was an early implementation for smartbands, best if used in mmol/l.  
Unless you still own a LeFun W3, F3, F3S, F11 or F12 band this is not of any use now.

#### [MiBand](../miband)

!!!xdripitem "MiBand" 

MiBand integration is the result of the huge work of [Artem](https://bigdigital.home.blog/).  
Many smartwatches and smartbands are now supported using the companion app WatchDrip+.

**If you use WatchDrip+ you must disable MiBand.**

### Smartwatch Sensors

xDrip+ can use supported smartwatches sensors.

!!!xdripitem "Use Health data&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`" 

xDrip+ can request the heartbeat sensor to activate and you can smooth that graph.

!!!xdripitem "Heart Rate Sensor&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"

When available you can let xDrip+ collect health data like heartrate and steps.

Two additional icons will appear on the main view, and if enabled, graphic representations:

1.  A dark blue graph for heartrate
2. A light cyan cloud line for steps

<img src="../images/M-S-SW8c.png" style="zoom:75%;" />

### Other smartwatches

More smartwatches and devices can receive data from xDrip+ even if they are not directly integrated in the app.

!!!info  
    In order to have xDrip+ send data you need to enable xDrip+ [web service](../../use/interapp#web-service).

#### Fitbit

!!!warning "Google is discontinuing Sense/Ionic/Versa"  
    Consider these products will be end of life in the near future.

!!!warning "Not available for EU users"  
    Google has [removed](https://support.google.com/fitbit/answer/14237121?hl=en) the possibility since June 2024. Installed watchfaces are not impacted but new users can't install custom watchfaces anymore. You need to use a VPN as a workaround.

!!!warning "Android 9 and below"  
    Android users with a version below 10 need to downgrade the Fitbit app to a previous version like 3.58 and disable automatic updates. You can find it in [Aptoide](https://fitbit.en.aptoide.com/versions) and other apk hosting servers.

##### [Glance](https://gallery.fitbit.com/details/7b5d9822-7e8e-41f9-a2a7-e823548c001c)

Ionic/Sense/Versa/Versa 2/Versa 3/Versa 4/Versa Lite

[Web site](https://glancewatchface.com/)

##### [Sentinel](https://gallery.fitbit.com/developer/b50ac7f5-b932-441a-be18-e258b17c736b)

Sentinel Elite for Sense/Versa 3  
Sentinel Pro for  Ionic/Versa/Versa 2/Versa Lite

Facebook group: [Sentinel](https://www.facebook.com/groups/3185325128159614)

##### [Marclock](https://gallery.fitbit.com/details/9eacf714-5b23-40c8-9621-ded74bd9edf9)

Ionic/Sense/Versa/Versa 2/Versa Lite

[Instructions](https://github.com/cramis1/Marclock-with-CGM-weather/blob/master/README.md)

##### [Analog CGM](https://gallery.fitbit.com/details/4d7b46b1-aaba-49b4-aa10-183321014dd3)

##### [Orbits NS](https://gallery.fitbit.com/details/44de5c81-b77c-4f90-baa8-38f3e3d28695)

##### [Radial CGM](https://gallery.fitbit.com/details/0173730e-5381-4495-bc6e-6ec93c8df029)

Ionic/Versa/Versa 2/Versa Lite/Versa 3/Sense

#### Samsung Gear

[G-Watch](https://play.google.com/store/apps/details?id=sk.trupici.g_watch) is the easiest way to perform this. See the [wiki](https://github.com/trupici/G-Watch-Wear/wiki).

You can also use [Tasker](https://github.com/FreDiabetics/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/README.md) to display xDrip+ data on your Samsung Gear watch.

#### Garmin

Many Garmin watchfaces are available, check your model is supported.

By [Horsetooth](https://apps.garmin.com/en-US/developer/e985e9ec-bcf6-4aef-bfe9-77c1c93fc854/apps)

By [andreas-may](https://apps.garmin.com/en-US/developer/f9420c47-810f-47ac-a7dd-9fa7b8ecd22d/apps)

By [John_](https://apps.garmin.com/en-US/developer/b2d30711-2708-4f3a-8e83-009c16d07081/apps)

By [Roboleo1010](https://apps.garmin.com/en-US/developer/b61690c3-5e5c-4c4e-afe9-434db16542a9/apps)

</br>

[*Last modified 4/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
