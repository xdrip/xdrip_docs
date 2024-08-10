<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-AAA.png" style="zoom:75%;" />

Many alerts can be setup with xDrip+.

<img src="../images/M-S-AAM.png" style="zoom:75%;" />

It is recommended to enable at least three alerts if xDrip+ is your only glucose monitoring app:

- Low alert
- High Alert
- Missed readings alert

### Glucose Level Alerts List

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

##### Alert volume settings

You can customize the volume of your alerts

<img src="../images/M-S-AA-GAa.png" style="zoom:75%;" />

Ascending volume is recommended if you don't want the alarm to blare immediately (useful during the night).

##### Audio Focus

Audio Focus allows you to decide how to handle other sounds when an xDrip+ alarm or alert triggers.

<img src="../images/M-S-AA-GAl.png" style="zoom:75%;" />

You can automatically lower the volume, pause the other apps playing sounds (like media players) or pause all other sounds in order to better focus on xDrip+ sound.

<img src="../images/M-S-AA-GAl2.png" style="zoom:75%;" />

##### Smart snoozing

##### Smart alerting

Smart snoozing and alerting avoid the alert to trigger or re-raise if BG is going in the right direction (upwards for low alerts and downwards for highs). The threshold for acknowledging a sufficient change in the right direction are:

Change is more than +4mg/dl in 5 minutes from low alert  
Change is more than -1mg/dl in 5 minutes from high alert

<img src="../images/M-S-AA-GAc.png" style="zoom:75%;" />

##### Don't alarm during phone calls

Alarms will not sound if they trigger during a phone call.

<img src="../images/M-S-AA-GAd.png" style="zoom:75%;" />

##### Buttons silence alarms

Button silence alarms is a quick way to snooze alarms by just pressing volume up or down.

<img src="../images/M-S-AA-GAe.png" style="zoom:75%;" />

##### Alert buttons

Alert button will add an action button in the drop down view of the alert.

<img src="../images/M-S-AA-GAm.png" style="zoom:78%;" />

<img src="../images/M-S-AA-GAm2.png" style="zoom:75%;" />

<img src="../images/M-S-AA-GAm3.png" style="zoom:75%;" />

##### Start snoozed

Start snoozed applies the snooze delay before triggering the alarm. Make sure the `Default snooze` delay is appropriate in the alarm.

<img src="../images/M-S-AA-GAf.png" style="zoom:75%;" />

##### Wake Screen

Wake up screen during alerts.

<img src="../images/M-S-AA-GAn.png" style="zoom:75%;" />

##### Use Camera Light

Flash the back camera light during alerts (when the phone is in charge).

<img src="../images/M-S-AA-GAo.png" style="zoom:75%;" />

##### Glucose Level Alert List

You can add a additional line to `Glucose Level Alert List` in the main menu.

<img src="../images/M-S-AA-GAg.png" style="zoom:75%;" />

##### Suppress alerts if missed readings

Level alerts remain active even if there is no signal (sensor change for example, or follower without network). This option allows you to suppress them. Make sure you have a missed alert enabled if you use this feature.

<img src="../images/M-S-AA-GAh.png" style="zoom:75%;" />

##### Suppress snoozed and active alerts

You can also suppress alerts after a certain amount of time, make sure this is really what you want.

<img src="../images/M-S-AA-GAi.png" style="zoom:75%;" />

##### Notification channel

With Android 8 and above you can use the notification channels for your alerts. This will allow you to customize notifications at Android level.

<img src="../images/M-S-AA-GAj.png" style="zoom:75%;" />

In order to setup this feature, go to Android Settings / Notifications / Apps / xDrip+ and allow sound and vibration.  
You'll then be able to decide each notification behaviour. If you have multiple notification and alarms, disable the unwanted ones here.

<img src="../images/M-S-AA-GAj2.png" style="zoom:75%;" />

##### Delay ascending volume

You can delay the start of the ascending volume alert without delaying vibration that will start as soon as the alert is triggered.

<img src="../images/M-S-AA-GAk.png" style="zoom:75%;" />

### Calibration Alerts

If your sensor requires periodic calibration you can setup xDrip+ to alert you when calibration is due.

You can setup the period between calibrations, sound to be played, ...

<img src="../images/M-S-AA-CAa.png" style="zoom:75%;" />

##### Initial alert

Initial calibration alert is used when starting a sensor requiring initial calibration, it will trigger when enough readings are available to calibrate.

<img src="../images/M-S-AA-CAb.png" style="zoom:75%;" />

### Missed Reading Alert

When relying on xDrip+ to alert you for lows and highs, it is essential to make sure that it is actually receiving BG readings. For this, if you don't have any other alarms enable this feature for your safety.

Setup is similar to [glucose level alerts](#glucose-level-alerts-list). The alarm sound has to be defined in Other Alerts (See below).  In order to test it put your phone in airplane mode until it triggers.

<img src="../images/M-S-AA-MRA.png" style="zoom:75%;" />

### Other Alerts

If you enabled this feature and your sensor supports it, you can setup an alert for noisy readings.

<img src="../images/M-S-AA-OAa.png" style="zoom:75%;" />

##### Falling or rising BG

You can also setup alerts for fast BG changes.

<img src="../images/M-S-AA-OAb.png" style="zoom:75%;" />

##### Alert preferences

The alerts above and also Missed Readings use the sound defined below.  
Some recent Android versions do not ring it unless you use [Notification channels](#notification-channel).

<img src="../images/M-S-AA-OAc.png" style="zoom:75%;" />

### Extra Alerts

##### Persistent high

Instead of a high alert that will trigger as soon as BG reaches the trigger value, you can setup a persistent high alert that will only trigger when BG remains above the setup value for more than a certain time.

<img src="../images/M-S-AA-EAa.png" style="zoom:75%;" />

##### Forecasted low

You can set an alarm on forecasted low value. This feature will use the momentum (extrapolation of the current BG trend) and **not** the [prediction](/use/predictions) settings. Forecasted low (min) is the time in which a low will be forecasted (the one that usually displays in yellow on the graph screen).

<img src="../images/M-S-AA-EAb.png" style="zoom:75%;" />

In the example below if you set Alarm at forecasted low (min) to 50 minutes, il will trigger. The red dotted line is the forecasted BG trend, extrapolated from the previous measurements.

<img src="../images/M-S-AA-EAb2.png" style="zoom:75%;" />

##### Other xDrip+ alerts

Some extra alerts are available.  
Battery alerts are available if your bridge sends this information to xDrip+.

<img src="../images/M-S-AA-EAc.png" style="zoom:75%;" />

##### Sensor expiry alerts

Enable a notification when the sensor is close to expiry time.

<img src="../images/M-S-AA-EAd.png" style="zoom:75%;" />

## Snooze Alert

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../images/M-SNO.png" style="zoom:75%;" />  

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
