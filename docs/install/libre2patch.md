!!!xdrip "Other app → `Libre (patched app)`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
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

This data source is subject to 25 minutes default smoothing. The smoothing period can be adjusted in the [NFC menu](../../use/NFC/#smooth-libre-3-data-when-using-xxx-method) to decrease the delay generated, if the noise level allows it.

</br>

[*Last modified 3/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
