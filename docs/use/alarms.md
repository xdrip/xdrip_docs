!!!xdrip "`Alarms and Alerts`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Alarms and Alerts

Many alerts can be setup with xDrip+.

It is recommended to enable at least three alerts if xDrip+ is your only glucose monitoring app:

- Low alert
- High Alert
- Missed readings alert

### Glucose Level Alerts List

!!!xdripitem "Glucose Level Alerts List"  

By default, one low and one high alert are defined.

Low alerts will trigger when BG is equal or below the alert value, high alerts when BG is equal or above.

To create a new alert, touch the `CREATE LOW` or `HIGH ALERT` title bar.

To modify an existing alert, long touch the alert

<img src="../images/M-S-AA-ALa.png" style="zoom:75%;" />

1. You can name an alert the name you want, as long as no other alert has the same name
2. The threshold is the BG level that will trigger the alarm, only one alarm can use this value
3. Default snooze is the delay that will be proposed when snoozing
4. The alarm will trigger again every x minutes if not acknowledged

<img src="../images/M-S-AA-ALb.png" style="zoom:75%;" />

You can customize the alert sound: touch `CHOOSE FILE`

<img src="../images/M-S-AA-ALc.png" style="zoom:75%;" />

System sound will allow you to choose from your phone ringtones, custom sound allows you to pick your sound/music and xDrip default sound uses the app default.

<img src="../images/M-S-AA-ALh.png" style="zoom:75%;" />

By default the alarm will be setup for the whole day.

<img src="../images/M-S-AA-ALd.png" style="zoom:75%;" />

If you unselect the checkbox you can customize activity hours (when to enable it).

<img src="../images/M-S-AA-ALe.png" style="zoom:75%;" />

1. You can disable the alarm (uncheck) when the phone is in silent mode (not recommended)
2. Force speaker will make the alarm sound on the phone even when you're using other speakers (like bluetooth)
3. Vibrate enables phone vibration
4. Disable alert completely disables it, it will show crossed in the Alert List

<img src="../images/M-S-AA-ALf.png" style="zoom:75%;" />

`TEST ALERT` will make this alert sound

`SAVE ALERT` will save this new or modified alert

`REMOVE ALERT` will delete this alert

`SNOOZE ALERT BEFORE IT FIRES` will allow you to avoid the alert to trigger, for example if you already treated an expected low or a high and know BG will move anyway you can avoid to hear the alarm for the time you want.

<img src="../images/M-S-AA-ALg.png" style="zoom:75%;" />

### Glucose Alerts Settings

!!!xdripitem "Glucose Alerts Settings"  

##### Alert volume profile

You can customize the volume of your alerts

!!!xdripitem "Alert volume profile"  
    &ensp;High&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;○  
    &ensp;Medium&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;○  
    &ensp;Ascending volume&emsp;&emsp;&emsp;&emsp;&emsp;  &emsp;&emsp;&emsp;&emsp;●  
    &ensp;Vibrate only&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;○  
    &ensp;Silent&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;○

Ascending volume is recommended if you don't want the alarm to blare immediately (useful during the night). You can also [delay](#delay-ascending-volume) ascending volume to filter noisy readings and limit the maximum volume.

##### Audio Focus

Audio Focus allows you to decide how to handle other sounds when an xDrip+ alarm or alert triggers.

!!!xdripitem "Audio Focus"  
    Choose what to do with other apps while playing alerts and adjusting system volume levels  

You can automatically lower the volume, pause the other apps playing sounds (like media players) or pause all other sounds in order to better focus on xDrip+ sound.

!!!xdripitem "Audio Focus"  
    &ensp;Don't adjust other app sounds&emsp;&ensp;&emsp;&emsp;&emsp;●  
    &ensp;Lower volume of other apps&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;○  
    &ensp;Pause other apps playing audio&nbsp;&ensp;&emsp;&emsp;&emsp;○  
    &ensp;Pause all other sounds&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;○ 

##### Smart snoozing

##### Smart alerting

Smart snoozing and alerting avoid the alert to trigger or re-raise if BG is going in the right direction (upwards for low alerts and downwards for highs). The threshold for acknowledging a sufficient change in the right direction are:

- Change is more than +4mg/dl in 5 minutes from low alert  
- Change is more than -1mg/dl in 5 minutes from high alert

!!!xdripitem "Smart snoozing&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Keep snoozing if glucose is heading in the right direction

!!!xdripitem "Smart alerting&nbsp;&emsp;&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Don't alert if glucose is heading in the right direction

##### Don't alarm during phone calls

Alarms will not sound if they trigger during a phone call.

!!!xdripitem "Don't alarm during phone calls&nbsp;&ensp;&emsp;&emsp;🗹"  
    &ensp;Alarms silenced during telephone calls

##### Buttons silence alarms

Button silence alarms is a quick way to snooze alarms by just pressing volume up or down.

!!!xdripitem "Buttons silence alarms&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Pressing the volume up or down button will snooze an active alarm when in the app

##### Alert buttons

Alert button will add an action button in the drop down view of the alert.

!!!xdripitem "Alert buttons&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;Show action buttons (like Snooze Alert) within alert notifications

<img src="../images/M-S-AA-GAm2.png" style="zoom:75%;" />

<img src="../images/M-S-AA-GAm3.png" style="zoom:75%;" />

##### Start snoozed

Start snoozed applies the snooze delay before triggering the alarm. Make sure the `Default snooze` delay is appropriate in the alarm.

!!!xdripitem "Start snoozed&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐"  
    &ensp;Alerts start out snoozed and must persist for a while to actually trigger

##### Wake Screen

Wake up screen during alerts.

!!!xdripitem "Wake Screen"  
    &ensp;Wake up screen during alerts. Might Unlock devices that don't have screen lock enabled

##### Use Camera Light

Flash the back camera light during alerts (when the phone is in charge).

!!!xdripitem "Use Camera Light"  
    &ensp;Flash camera light during alerts when connected to  charger

##### Shortcut to BG Level Alerts

You can add a shortcut entry to `Level Alerts` in xDrip+ main menu.

!!!xdripitem "Shortcut to BG Level Alerts"  
    &ensp;Create a shortcut from main navigation to BG level screen

##### Suppress alerts if missed readings

!!!xdripitem "Suppress Alerts if missed readings"

Level alerts remain active even if there is no signal (sensor change for example, or follower without network). This option allows you to suppress them. Make sure you have a missed alert enabled if you use this feature.

!!!xdripitem "Suppress Alerts if missed readings&emsp;☐"  
    &ensp;Suppress snoozed and active alerts after predefined period of missed readings

You can define the number of minutes after which you want alerts to stop.

!!!xdripitem "Suppress snoozed and active alerts after .. minutes (minimum 10)"  
    &ensp;Suppress snoozed and active alerts after predefined period of missed readings

##### Notification Channels

With Android 8 and above you can use the notification channels for your alerts. This will allow you to customize notifications at Android level.

!!!xdripitem "Notification Channels"

In order to setup this feature, go to Android Settings / Notifications / Apps / xDrip+ and allow sound and vibration.  
You'll then be able to decide each notification behaviour. If you have multiple notification and alarms, disable the unwanted ones here.

<img src="../images/M-S-AA-GAj2.png" style="zoom:75%;" />

##### Ascending Volume settings

!!!xdripitem "Ascending Volume settings"

##### Delay Ascending Volume

You can delay the start of the ascending volume alert without delaying vibration that will start as soon as the alert is triggered.

!!!xdripitem "Delay Ascending Volume"  
    &ensp;For ascending volume profile, delay the start of the alert sound by 3 minutes. The vibration (if enabled) starts as soon as the alert triggers regardless of this setting

##### Ascend to medium

You can limit the maximum volume of the ascending volume alerts and alarms to medium instead of maximum.

!!!xdripitem "Ascend to medium"  
    &ensp;When enabled, ascending volume profile will ascend to medium voulume instead of maximum

### Calibration Alerts

If your sensor requires periodic calibration you can setup xDrip+ to alert you when calibration is due.

You can setup the period between calibrations, sound to be played, etc ...

!!!xdripitem "Calibration Alerts"  
    &ensp;Calibration Alerts  
    &ensp;Hours between calibrations  
    &ensp;Calibration request sound  
    &ensp;Override Silent mode  
    &ensp;Even when charging  
    &ensp;Repeat Alerts  
    &ensp;Alert Repeat minutes

##### Initial alert

Initial calibration alert is used when starting a sensor requiring initial calibration: it will trigger when enough good readings are available to calibrate.

!!!xdripitem "Initial Alert"  
    &ensp;Play sound when Initial Calibration is requested

### Missed Reading Alert

!!!xdripitem "Missed Reading Alert"

When relying on xDrip+ to alert you for lows and highs, it is essential to make sure that it is actually receiving BG readings. For this, if you don't have any other alarms, enable this feature for your safety.

Setup is similar to [glucose level alerts](#glucose-level-alerts-list). **The alarm sound has to be defined in Other Alerts** (See [below](#alert-preferences)).  In order to test it, put your phone in airplane mode until it triggers.

<img src="../images/M-S-AA-MRA.png" style="zoom:75%;" />

### Other Alerts

#### Noisy Readings

If you enable this feature and your sensor supports it, you can setup an alert for noisy readings.

!!!xdripitem "Noisy Readings"  
    &ensp;Bad (noisy) Value Alerts&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐  
    &ensp;Alert after x minutes of noisy values  
    &ensp;Alert snooze 
    &ensp;Reraise alerts before snooze time  
    &ensp;Alert reraise time

#### Falling or rising BG

You can also setup alerts for fast BG changes and define the 1 minute change triggering value. For example 3 minutes means 15 mg/dl (0.85 mmol/l) every 5 minutes.

!!!xdripitem "Falling/Rising BG"  
    &ensp;BG falling fast&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐  
    &ensp;falling threshold  
    &ensp;BG rising fast&nbsp;&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;☐  
    &ensp;rising threshold  

##### Alert preferences

The alerts above and **also Missed Readings** use the sound defined below.  
Some recent Android versions do not ring it unless you use [Notification channels](#notification-channels).

!!!xdripitem "Alert Preferences (For these Alerts)"  
    &ensp;Alert Sound  
    &ensp;Override Silent mode on these alerts&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹

### Extra Alerts

##### Persistent High Alert

Instead of a high alert that will trigger as soon as BG reaches the trigger value, you can setup a persistent high alert that will only trigger when BG remains above the setup value for more than a certain time.

!!!xdripitem "Persistent High Alert"  
    &ensp;Persistent High Alert  
    &ensp;for longer than (minutes)  
    &ensp;Repeating max every (minutes)  
    &ensp;Persistent High Sound  

##### Forecasted Low Alert

You can set an alarm on forecasted low value. This feature will use the **momentum** (extrapolation of the current BG trend) and **not** the [prediction](../predictions) settings. Forecasted low (min) is the time in which a low will be forecasted (the one that usually displays in yellow on the graph screen).

Forecast Lows will display a message on xDrip+ screen. In order to have an alarm sounds when a low is forecast, enable Raise alarm on Forecast Low.

!!!xdripitem "Forecasted Low Alert"  
    &ensp;Forecasted Lows  
    &ensp;Raise alarm on Forecast Low  
    &ensp;Alarm at Forecast Low mins  
    &ensp;Predicted Low Sound  

In the example below if you set Alarm at forecasted low (min) to 50 minutes, il will trigger. The red dotted line is the forecasted BG trend, extrapolated from the previous measurements.

<img src="../images/M-S-AA-EAb2.png" style="zoom:75%;" />

##### Other xDrip+ alerts

Some extra alerts are available.  
Battery alerts are available if your bridge sends this information to xDrip+ (historically G4 now Libre bridges).

!!!xdripitem "Other xDrip+ Alerts"  
    &ensp;Collector battery alerts  
    &ensp;Low battery percentage  
    &ensp;Sensor expiry  
    &ensp;Parakeet related alerts  
    &ensp;Silent alert when charging  
    &ensp;Follower Chime New 

<img src="../images/M-S-AA-EAc.png" style="zoom:75%;" />

##### Sensor expiry alerts

Enable a notification when the sensor is close to expiry time.

##### Follower Chime New

After missed readings, a notification will sound when new data is received after more than 20 minutes.

## Snooze Alert

!!!xdrip "`Snooze Alert`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Snooze Alert

If there is no active alert, you can **pre-snooze** alerts from this menu so that they won't trigger for a certain time.

<img src="../images/M-SNOa.png" style="zoom:75%;" />  

You will be proposed a default snooze period.

<img src="../images/M-SNOb.png" style="zoom:75%;" />  

If an alert triggers you will see the notification in your phone drop down panel, and eventually hear the sound.

You can snooze the alert swiping the notification, you can customize it further tapping it.

<img src="../images/M-SNOc.png" style="zoom:75%;" />  

You can access the snooze menu by touching the notification or from xDrip+ main menu, snooze alert.

At this point, the snooze menu will also display the active alert.  
Touching snooze will snooze it for the period selected.

<img src="../images/M-SNOd.png" style="zoom:75%;" />  

##### ALL ALERTS CURRENTLY DISABLED

If you pre-snooze (disable) all alerts, you will see this warning message.

<img src="../images/M-SNOe.png" style="zoom:75%;" />  

To remove it you need to re-enable alerts.

<img src="../images/M-SNOf.png" style="zoom:75%;" />  

</br>

## Visible alert notification

Available for Android 8 and above.

When an alert triggers you will see it in the notifications drop down panel.

<img src="../images/M-SNOg.png" style="zoom:75%;" />  

Swiping it will snooze it, touching it will open a preferences menu.  
Deliver quietly will remove [notifications channel](#notification-channel) sound and vibration.

<img src="../images/M-SNOh.png" style="zoom:75%;" />

You can restore it with allow sound and vibration with the [notifications channel](#notification-channel).

<img src="../images/M-SNOi.png" style="zoom:75%;" />  

Settings will drive you to your phone notifications setup settings.

<img src="../images/M-SNOk.png" style="zoom:75%;" />  

You can also completely turn off [notifications channel](#notification-channel) for xDrip+.

<img src="../images/M-SNOj.png" style="zoom:75%;" />  



[*Last modified 4/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
