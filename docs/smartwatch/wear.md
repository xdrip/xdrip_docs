You will find the reference documentation [here](https://github.com/NightscoutFoundation/xDrip/blob/master/Documentation/WatchGuide.md).

!!!xdrip "`Android Wear extension in xDrip+`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Smart Watch Features  
    &emsp;  Android Wear Integration

!!!xdripitem "Android Wear Integration&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Send data to Android Wear Watchface

Once you have installed xDrip+ on the watch paired with your phone, you can enable Wear.  
xDrip+ will then communicate with a reduced version of itself on the watch.

!!!xdripitem "Enable Wear Collection Service&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Connect Wear to BT Collector when phone is out-of-range

For few combinations of sensors and smartwatch, xDrip+ can be used directly from the watch itself without needing the phone presence. See below for more information.

Enable wear allows the watch to take over from the phone when the phone xDrip+ is losing connection to the sensor/bridge.

!!!xdripitem "Force Wear Collection Service&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Force phone to use Wear Collection Service

Force wear is forcing the watch to act as the main device connected to the sensor/bridge even if the phone is nearby (recommended).

!!!xdripitem "Disable Force on Low Battery&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    Disable Force Wear Collection Service on Wear low battery alert

Disable force on low battery will make the watch drop sensor/bridge connection to give it back to the phone when its battery level is too low.

!!!xdripitem "Disable Force on Missed Readings&emsp;&emsp;`OFF`←"  
    Disable Force Wear Collection Service on minutes since last reading from Wear  

Disable force on missed readings will make the watch drop sensor/bridge connection to give it back to the phone after a certain time of missed readings, defined in the menu below.

!!!xdripitem "Use only Wear&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    If you plan to use a Wear Collector and never your phone

Only use wear can be enabled if you have setup the watch once but will not use your phone to connect to the sensor/bridge.

!!!xdripitem "Device Running Collection Service"  

If you have several Android Wear smartwatch with xDrip+, you can select which one will be the collector. The other will only display xDrip+ data.

!!!note "Switching watch"  
    When switching between watches, xDrip+ might not be able to communicate its intention to both watches if one is switched off. If you want to change the collecting watch, force collector in xDrip+ and also force collector in the watch xDrip Prefs menu.

!!!xdripitem "Sync Wear Logs&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    Send Wear logs to Event Viewer

Sync wear logs is a very useful feature when troubleshooting: it will add the watch logs in xDrip+ [events log](../../use/3dotsmenu/#events-log) with a prefix to identify the activity is on the watch. By default the prefix is `wear` but you can customize it. It is recommended to keep it enabled.

!!!xdripitem "Show Treatments&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    Show Treatment points on graph

Show treatments add treatments symbols on the watch graph.

## Standalone collector mode

The xDrip+ wear extension also contains the part of xDrip+ that connects to some sensors, meaning you can make the watch act in lieu of the phone and take ownership of the communication and readings, without have your phone nearby.

This feature is not available for all sensors, see the table below:

| Sensor                       | Wear 1.x | Wear 2.x | Wear 3+ |
| ---------------------------- | -------- | -------- | ------- |
| G5/G6/1                      | Yes      | Limited* | No      |
| G7/1+                        | No       | No       | No      |
| Libre 1 with bridge          | Yes      | Yes      |         |
| Libre 14 days US with bridge | Yes**    | Yes**    |         |
| Libre 2 EU without bridge    | No       | No       |         |
| Libre 2 EU with bridge       | Yes**    | Yes**    |         |

***Limited\*:*** There are some bugs present on most Android Wear smartwatches which prevent them working correctly with the G5/G6. In the best case scenario you will have a reading every 10 minutes. Some watches could be [patched](https://github.com/NightscoutFoundation/xDrip/wiki/Patching-Android-Wear-devices-for-use-with-the-G5) to achieve 5 minutes readings.

***Yes\*\*:*** You need to have a phone working with [OOP1](../../use/OOP/) or [OOP2](../../use/OOP/#oop2) and also need that same OOP app [sideloaded](../../troubleshoot/ADB/#smartwatch) to your watch. Some bridges might not be compatible.

### Prerequisites

The feature is available for sensor/watch combinations described above.

xDrip+ extension is installed on the watch with the same version than the one on your phone.

xDrip+ connectivity is good on your phone (meaning Bluetooth parameters are correctly defined).

xDrip+ on the watch must be authorized to access location.  
<img src="../images/M-S-SW-AW33.png" style="zoom:75%;" />

### Recommended sequence

First time attempt or failure recovery:

1 - On your phone xDrip+: disable force collector, then disable collection, then disable Wear in this order.  
!!!xdripitem "Force Wear Collection Service&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;☐ `1`"

!!!xdripitem "Enable Wear Collection Service&emsp;&emsp;&emsp;&emsp;&emsp;☐ `2`"

!!!xdripitem "Android Wear Integration&ensp;&emsp;&emsp;&emsp;&emsp;&emsp; `OFF`← `3`"

2 - Enable wear logs.  
!!!xdripitem "Sync Wear Logs&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    Send Wear logs to Event Viewer

3 - Restart your smartwatch. Wait until it's fully running.

4 - On you phone enable only Wear.  
!!!xdripitem "Android Wear Integration&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  

5 - Wait until the xDrip+ graph is fully displayed on the watch (waiting for a new measurement doesn't hurt).

6 - Make sure you keep phone, watch and sensor close together and enable first collection then force collector.  

!!!xdripitem "Enable Wear Collection Service&emsp;&emsp;&emsp;&emsp;&emsp;🗹 `1`"

!!!xdripitem "Force Wear Collection Service&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹 `2`"

7 - Pairing process will take typically 10 minutes, open the phone xDrip+ event logs and wait for events starting by `wear`.  
<img src="../images/M-S-SW-AW31.png" style="zoom:75%;" />

8 - If things went smooth you should now have the watch in standalone mode.

##### If the watch doesn't connect to the bridge:

- In the watch xDrip Prefs menu, check Force Collector.  
  <img src="../images/M-S-SW-AW-ST3b.png" style="zoom:75%;" />
- From the xDrip+ watchface 3 dots menu, Restart Collector.  
  <img src="../images/M-S-SW-AW-3DM.png" style="zoom:75%;" />
- In the watch Bluetooth settings, find your bridge device and pretend to pair it (you can't pair Miaomiao/Bubble with the watch but it will try to establish a link to it). After pairing fails, wait 10 minutes for readings to show-up.
- If readings don't appear, disable Force collector and retry the sequence.

## Sharing data in standalone mode

If you want the watch to share data (xDrip+ Sync, Nightscout, ...) it needs to be connected to your phone and your phone needs to be connected to the internet.

This doesn't mean they need to be in the same place but the watch itself will not share data directly: it will send them to your phone, and it is your phone that will share. If the watch is connected to the internet through Wi-Fi or a SIM with a data plan, it will need to send them to your phone (connected to the internet also) and your phone itself will share the data. As long as they are both connected to the internet they don't need to be close one to the other.

<img src="../images/M-S-SW-AW-XP24.png" style="zoom:75%;" />

</br>

[*Last modified 4/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
