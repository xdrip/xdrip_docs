!!!xdrip "Other app → `Libre (patched app)`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Hardware Data Source  
    &ensp;&emsp;Libre (patched app)

**This is a generic data source for various apps, not only the vendor patched app.**

The apps listed below use the same protocol to send data to xDrip+.

!!!note  
    External apps readings will be treated like sensor data in all effects, this includes [calibration limitations](../../calibrate/calibrate/#libre-2-patched-app).

It shouldn't be necessary anymore but if you don't see data in xDrip+ [Start sensor](../../use/startsensor/#followers-and-companion-apps).

</br>

#### Libre 2 EU [Patched App](../../troubleshoot/libre2/#patched-app)

!!!info "Patched app"  
    The patched app itself is only available for the European version of Libre 2.  
    Being an old app, it is **rarely compatible with Android versions above 12**.

</br>

#### Juggluco

If you use [Juggluco](https://www.juggluco.nl/Juggluco/index.html) you can broadcast to xDrip+ enabling Send to xDrip. You must have data streaming in Juggluco in order to see measurements in xDrip+.

<img src="../images/Juggluco.png" style="zoom:50%;" />

</br>

#### Diabox

If you use a recent [Diabox](https://sirius.thetaphi.de/diabox/) version, you can broadcast to xDrip+ enabling the option below:

<img src="../images/Diabox4.png" style="zoom:75%;" />

</br>

#### LinkUpConnect

LinkUpConnect is a vendor server follower, you need a Libre 3 to have CGM data in the app.  
Data should be available in the vendor follower app.  
Enable the `Forward to xDrip` flag.

<img src="../images/LinkUpConnect.png" style="zoom:75%;" />

</br>

#### Smoothing

!!!note  
    Smoothing will apply to any external data source app using the `Libre2 (patched app)` data source.

The original implementation included a 25 minutes smoothing algorithm to remove noise and make DIY close looping safer with Libre sensors. You can now reduce the smoothing period to 10, 15 or 25 minutes with the menu `Smooth Libre 3 data when using xxx method` in the NFC scan features menu.

!!!xdrip "`NFC Scan Features`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;NFC Scan Features

!!!xdripitem "Smooth Libre 3 data when using xxx method"  
    &ensp;Number of minutes to take in consideration when using librex data

Smoothing adds a delay in xDrip+ BG from raw data. The delay is about half the smoothing period. Set the delay accordingly to the sensor behavior for your safety. If you don't use a DIY closed loop system with xDrip+ providing glucose values, set it to 10 minutes.

<img src="../images/M-S-HDS-NFC8.png" style="zoom:75%;" />

</br>

[*Last modified 3/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
