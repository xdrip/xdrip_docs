<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistG.png" style="zoom:75%;" />

!!!info "Patched app"  
    The patched app itself is only available for the European version of Libre 2.  
    Being an old app, it is rarely compatible with Android versions above 12.

</br>

Other apps listed below use the same protocol to send data to xDrip+:

***Note:*** *external apps readings will be treated like sensor data in all effects, this includes [calibration limitations](../../calibrate/calibrate/#libre-2-patched-app).* 

It shouldn't be necessary anymore but if you don't see data in xDrip+ [Start sensor](../../use/startsensor/#followers-and-companion-apps).

</br>

#### Smoothing

!!!note  
    Smoothing will apply to any external data source app using the `Libre2 (patched app)` data source.

The original implementation included a 25 minutes smoothing algorithm to remove noise and make DIY close looping safer with Libre sensors. You can now reduce the smoothing period to 10, 15 or 25 minutes with the menu `Smooth Libre 3 data when using xxx method`.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-HDS-NFC.png" style="zoom:75%;" />

<img src="../images/M-S-HDS-NFC7.png" style="zoom:75%;" />

Smoothing adds a delay in xDrip+ BG from raw data. The delay is about half the smoothing period. Set the delay accordingly to the sensor behavior for your safety. If you don't use a DIY closed loop system with xDrip+ providing glucose values, set it to 10 minutes.

<img src="../images/M-S-HDS-NFC8.png" style="zoom:75%;" />

</br>

#### Juggluco

If you use [Juggluco](https://play.google.com/store/apps/details?id=tk.glucodata) you can broadcast to xDrip+ enabling Send to xDrip. You must have data streaming in Juggluco in order to see measurements in xDrip+.

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

[*Last modified 21/06/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.06.17)
