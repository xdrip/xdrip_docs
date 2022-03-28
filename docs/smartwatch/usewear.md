You will find the reference documentation [here](https://github.com/NightscoutFoundation/xDrip/blob/master/Documentation/WatchGuide.md).

## Discover Wear Extension

Four native watchfaces are available from xDrip+.

|                           XDrip                            |                      XDrip(BigChart)                       |
| :--------------------------------------------------------: | :--------------------------------------------------------: |
| <img src="../images/M-S-SW-AW-W1.png" style="zoom:75%;" /> | <img src="../images/M-S-SW-AW-W2.png" style="zoom:75%;" /> |
|                      **XDrip(Large)**                      |                     **XDrip(Circle)**                      |
| <img src="../images/M-S-SW-AW-W3.png" style="zoom:75%;" /> | <img src="../images/M-S-SW-AW-W4.png" style="zoom:75%;" /> |

Graph based watchfaces contain some common elements with the xDrip+ main display.

1. What's the last measured BG value.  
   What's the BG difference with the previous value received.  
   What's the trend in respect with the previous measurement.
2. A status line.
3. A BG graph.

 <img src="../images/M-S-SW-AW-SC1.png" style="zoom:75%;" />

Double tapping the graph changes the time scale.

<img src="../images/M-S-SW-AW-SC2.png" style="zoom:75%;" />

Since xDrip+ wear extension contains some of the app code, you will find xDrip+ menu items on the watch. You will find them inside the watch apps, some can also be accessed from the watch graph using the three dots menu present on all watchfaces.

<img src="../images/M-S-SW-AW-3DM.png" style="zoom:75%;" />

### xDrip Prefs.

This menu contains display options for your watchface.  
When the watch is setup in standalone collector, more items will be visible. See below.

<img src="../images/M-S-SW-AW-XP.png" style="zoom:75%;" />

Dark theme shows a black background and white text/graph.  Disabling this reverts colors.

<img src="../images/M-S-SW-AW-XP3.png" style="zoom:75%;" />

Refresh on change updates the watchface every data change (5 minutes minimum). If you disable it the watch will update its watchface every minute (will use more battery).

<img src="../images/M-S-SW-AW-XP4.png" style="zoom:75%;" />

Show treatment adds treatment dots on the graph watchfaces.

<img src="../images/M-S-SW-AW-XP5.png" style="zoom:75%;" />

24 hours format forces this time format to display.

<img src="../images/M-S-SW-AW-XP6.png" style="zoom:75%;" />

Show date also shows the date on the watchface.

<img src="../images/M-S-SW-AW-XP7.png" style="zoom:75%;" />

If your watch is setup to use its own locale (language) you can force it to use the phone settings.

<img src="../images/M-S-SW-AW-XP8.png" style="zoom:75%;" />

Toasts are pop-up messages, you can enable them and have extra information tapping steps and status on the watch.

<img src="../images/M-S-SW-AW-XP9.png" style="zoom:75%;" />

If your watch supports it and you authorized xDrip Prefs. to access sensor data on the watch you will have the step counter on the watchface and can have [steps data](../../use/display/) displayed on your phone xDrip+.

<img src="../images/M-S-SW-AW-XP10.png" style="zoom:75%;" />

If your watch supports it and you authorized xDrip Prefs. to access sensor data on the watch you will have hearth rate on the watchface and can have [hearth rate data](../../use/display/) displayed on your phone xDrip+.

<img src="../images/M-S-SW-AW-XP11.png" style="zoom:75%;" />

If you use an open source closed loop system (like AAPS) broadcasting data to xDrip+, you can have loop status added to the status line.

<img src="../images/M-S-SW-AW-XP12.png" style="zoom:75%;" />

By default the watchface will display the collecting device battery as `uploader` or `wear`. This is a legacy definition that doesn't add value if you're not using xDrip+ as master: it will not display the master phone battery level nor an eventual bridge device battery but only your phone and watch battery.

<img src="../images/M-S-SW-AW-XP13.png" style="zoom:75%;" />

Allows you to display cards (alerts) with a plain background to improve readability.

<img src="../images/M-S-SW-AW-XP14.png" style="zoom:75%;" />

You can change the font size of the status line. 10 or 12 points.

<img src="../images/M-S-SW-AW-XP15.png" style="zoom:75%;" />

You can change the chart timeframe, same as double tapping it.

<img src="../images/M-S-SW-AW-XP16.png" style="zoom:75%;" />

In this menu you'll find customizations for the circle watchface.

<img src="../images/M-S-SW-AW-XP17.png" style="zoom:75%;" />

Low color.

<img src="../images/M-S-SW-AW-XP18.png" style="zoom:75%;" />

On xDrip+ and xDrip+ Large, change the divider (status line) color to match backround.

<img src="../images/M-S-SW-AW-XP19.png" style="zoom:75%;" />

Force update is available for Wear 2.0 and above watches if available for the current version and enabled as explained [here](../wearinstall/#wear-os-20-and-above).

<img src="../images/M-S-SW-AW-XP20.png" style="zoom:75%;" />

Demigod is available for [patched watches](https://github.com/NightscoutFoundation/xDrip/wiki/Patching-Android-Wear-devices-for-use-with-the-G5).

<img src="../images/M-S-SW-AW-XP21.png" style="zoom:75%;" />

### Keypad Treatment

Keypad treatment is identical to xDrip+ [syringe icon](../../use/mainUI/#treatments).

<img src="../images/M-S-SW-AW-KT.png" style="zoom:75%;" />

<img src="../images/M-S-SW-AW-XP22.png" style="zoom:75%;" />

### Spoken treatment

Spoken treatment is identical to xDrip+.

<img src="../images/M-S-SW-AW-ST.png" style="zoom:75%;" />

<img src="../images/M-S-SW-AW-XP23.png" style="zoom:75%;" />

### Snooze Alert

Not all alerts and alarms are available on the watch.

<img src="../images/M-S-SW-AW-SA.png" style="zoom:75%;" />

On wear 1.x alarms and alerts that drive to to opening on the phone means you need to perform snooze from within the phone xDrip+ app.

<img src="../images/M-S-SW-AW-SA2.png" style="zoom:75%;" />

On wear 2.x and above alerts might show as notifications and you will need to manually open the snooze alert phone app or snooze them from the phone xDrip+ app.

<img src="../images/M-S-SW-AW-SA3.png" style="zoom:75%;" />

## [Standalone collector mode](../wear/#standalone-collector-mode)

xDrip Prefs. menu will contain additional information mirrored from xDrip+ on the phone when both are connected together.

#### Validation

A validation mechanism will make sure both use the same settings. If the watch doesn't accept the settings change from xDrip+, they will be modified automatically to match the watch settings when both are connected.

1. Settings are modified on the phone
2. Changes are sent to the watch, when connected
3. Watch tries to implement settings modifications
4. Watch settings are sent back to the phone (modified or not)
5. Phone settings are updated to reflect the watch settings, when connected

<img src="../images/M-S-SW-AW-XP1.png" style="zoom:75%;" />

This also works the other way round. If the watch settings are modified, they will be sent to the phone when connected. xDrip+ on the phone will validate the changes and send them back to the watch as a confirmation.

1. Settings are modified on the watch
2. Changes are sent to the phone, when connected
3. xDrip+ on the phone validates settings modifications
4. Phone settings are sent back to the watch (validated or not)
5. Watch settings are updated to reflect the phone settings, when connected

<img src="../images/M-S-SW-AW-XP2.png" style="zoom:75%;" />

#### xDrip Prefs.

When standalone collector is enabled you'll find additional entries in the menu.

BT collector is an information on which hardware data source collector is set on your phone xDrip+.

<img src="../images/M-S-SW-AW-ST1.png" style="zoom:75%;" />

Enable collector matches the setting in [Wear integration](../wear/#standalone-collector-mode).

<img src="../images/M-S-SW-AW-ST2.png" style="zoom:75%;" />

So does force collector. If the watch is not connected to the phone and you lost connection to your sensor you can try to trigger this to force a reconnection attempt.

<img src="../images/M-S-SW-AW-ST3.png" style="zoom:75%;" />

When in standalone collector mode you can use the watch local alerts (some). They will be snoozed on the watch.

<img src="../images/M-S-SW-AW-ST4.png" style="zoom:75%;" />

Including persistent high alert.

<img src="../images/M-S-SW-AW-ST5.png" style="zoom:75%;" />

If your watch has a speaker it can also ring the alarms.

<img src="../images/M-S-SW-AW-ST6.png" style="zoom:75%;" />

If you're connecting to a G5 or G6 you'll find additional settings.

<img src="../images/M-S-SW-AW-ST8.png" style="zoom:75%;" />

These are replications of the phone G5/G6 Debug Settings -  Old G5 Collector Settings.

<img src="../images/M-S-SW-AW-ST9.png" style="zoom:75%;" />

<img src="../images/M-S-SW-AW-ST10.png" style="zoom:75%;" />

<img src="../images/M-S-SW-AW-ST11.png" style="zoom:75%;" />

<img src="../images/M-S-SW-AW-ST12.png" style="zoom:75%;" />

Force screen on makes sure the watch will be fully awake when scanning.

<img src="../images/M-S-SW-AW-ST13.png" style="zoom:75%;" />

</br>

[*Last modified 28/4/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)

