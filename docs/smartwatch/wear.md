You will find the reference documentation [here](https://github.com/NightscoutFoundation/xDrip/blob/master/Documentation/WatchGuide.md).

## Android Wear extension in xDrip+

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SW.png" style="zoom:75%;" />  
<img src="../images/M-S-SW2.png" style="zoom:75%;" />

Once you have installed xDrip+ on the watch paired with your phone, you can enable Wear.  
xDrip+ will then communicate with a reduced version of itself on the watch.

<img src="../images/M-S-SW-AW18.png" style="zoom:75%;" />

For certain combinations of sensors and smartwatch, xDrip+ can be used directly from the watch itself without needing the phone presence. See here for more information.

Enable wear allows the watch to take over from the phone when the phone xDrip+ is losing connection to the sensor/bridge.

 <img src="../images/M-S-SW-AW19.png" style="zoom:75%;" />

Force wear is forcing the watch to act as the main device connected to the sensor/bridge even if the phone is nearby (recommended).

<img src="../images/M-S-SW-AW20.png" style="zoom:75%;" />

Disable force on low battery will make the watch drop sensor/bridge connection to give it back to the phone when its battery level is too low.

<img src="../images/M-S-SW-AW21.png" style="zoom:75%;" />

Disable force on missed readings will make the watch drop sensor/bridge connection to give it back to the phone after a certain time of missed readings, defined in the menu below.

<img src="../images/M-S-SW-AW22.png" style="zoom:75%;" />

Only use wear can be enabled if you have setup the watch once but will not use your phone to connect to the sensor/bridge.

<img src="../images/M-S-SW-AW23.png" style="zoom:75%;" />

If you have several Android Wear smartwatch with xDrip+, you can select which one will be the collector. The other will only display xDrip+ data.

!!!note "Switching watch"  
    When switching between watches, xDrip+ might not be able to communicate its intention to both watches if one is switched off. If you want to change the collecting watch, force collector in xDrip+ and also force collector in the watch xDrip Prefs menu.

<img src="../images/M-S-SW-AW24.png" style="zoom:75%;" />

Sync wear logs is a very useful feature when troubleshooting: it will add the watch logs in xDrip+ [events log](../../use/3dotsmenu/#events-log) with a prefix to identify the activity is on the watch. By default the prefix is `wear` but you can customize it. It is recommended to keep it enabled.

<img src="../images/M-S-SW-AW25.png" style="zoom:75%;" />

Show treatments add treatments symbols on the watch graph.

<img src="../images/M-S-SW-AW26.png" style="zoom:75%;" />

