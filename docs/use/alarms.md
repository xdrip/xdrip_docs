!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_add_alert_grey600_48dp.png" style="width:5%;" />&ensp;Alarms and Alerts

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

!!!xDrip "☰&emsp;Alert List"  
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;CREATE LOW ALERT&emsp;</div> 

     <small>&emsp;&emsp;Low alert&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;70&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;All day</small>  
    <small>Override silent mode&emsp;&emsp;&emsp;Default ringtone (Unknown ringtone)</small>  
      
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;CREATE HIGH ALERT&emsp;</div>  
    <small>&emsp;&emsp;High alert&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;224&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;All day</small>  
    <small>Override silent mode&emsp;&emsp;&emsp;Default ringtone (Unknown ringtone)</small>  

1. You can name an alert the name you want, as long as no other alert has the same name
2. The threshold is the BG level that will trigger the alarm, only one alarm can use this value
3. Default snooze is the delay that will be proposed when snoozing
4. The alarm will trigger again every x minutes if not acknowledged

!!!xDrip "☰&emsp;Edit Alert"  
    &emsp;&emsp;&emsp;editing low alert  
       

    &emsp;&emsp;<small>Alert Name: <u>Low Alert</u></small>&emsp;<span style="background-color: green; color: white; text-align: center;">1</span>  
    &emsp;&emsp;<small>Threshold: <u>70</u></small>&emsp;<span style="background-color: green; color: white; text-align: center;">2</span>  
    &emsp;&emsp;<small>Default Snoze: <u>35</u></small>&emsp;<span style="background-color: green; color: white; text-align: center;">3</span>  
    &emsp;&emsp;<small>Re-raise every x minutes: <u>1</u></small>&emsp;<span style="background-color: green; color: white; text-align: center;">4</span>  
    &emsp;&emsp;<small>if unacknowledged</small>  
    
    &emsp;&emsp;<small>Alert Tone: <u>Default ringtone (unknown ringtone)</u></small>&emsp;<span style="background-color: green; color: white; text-align: center;">5</span>  

&emsp;5. You can customize the alert sound: touch CHOOSE FILE to select the default ringtone for this alarm.

- System sound will allow you to choose from your phone ringtones.

- Custom sound allows you to pick your sound/music.

- xDrip default sound uses the app default.

!!!xdripitem "What type of Alert?"  
    &emsp;System sound/Alarm  
    &emsp;Custom Sound/Alarm  
    &emsp;Default xDrip Sound

By default the alarm will be setup for the whole day.

!!!xdripitem "<small>Select time for Alert</small>"  
    &emsp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;✅&ensp;all day

If you unselect the checkbox you can customize activity hours.  
Touch the start hour and end hour to define from what time to what time the alarm will be enabled.

!!!xdripitem "<small>Select time for Alert</small>"  
    &emsp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;☐&ensp;all day  
    &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;0:00&emsp;-&emsp;0:00  
You can disable the alarm (uncheck) when the phone is in silent mode (disabling is not recommended)

!!!xdripitem "<small>Override phone silent mode</small><span class='symbol'><small>✅</small></span>"  

Force speaker will make the alarm sound on the phone even when you're using other speakers (like Bluetooth)

!!!xdripitem "<small>Force Speaker</small><span class='symbol'><small>✅</small></span>"  

Vibrate enables phone vibration

!!!xdripitem "<small>Vibrate on alert</small><span class='symbol'><small>✅</small></span>"  

Disable alert completely disables it, it will show crossed in the Alert List

!!!xdripitem "<small>Disable alert</small><span class='symbol'><small>☐</small></span>"  

<span style="background-color: gray; color: white;">&ensp;TEST ALERT&ensp;</span> will make this alert sound

<span style="background-color: gray; color: white;">&ensp;SAVE ALERT&ensp;</span> will save this new or modified alert

<span style="background-color: gray; color: white;">&ensp;REMOVE ALERT&ensp;</span> will delete this alert

<span style="background-color: gray; color: white;">&ensp;SNOOZE ALERT BEFORE IT FIRES&ensp;</span> will allow you to avoid the alert to trigger, for example if you already treated an expected low or a high and know BG will move anyway you can avoid to hear the alarm for the time you want.

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

!!!xdripitem "Smart snoozing <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Keep snoozing if glucose is heading in the right direction

!!!xdripitem "Smart alerting <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Don't alert if glucose is heading in the right direction

##### Don't alarm during phone calls

Alarms will not sound if they trigger during a phone call.

!!!xdripitem "Don't alarm during phone calls <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Alarms silenced during telephone calls

##### Buttons silence alarms

Button silence alarms is a quick way to snooze alarms by just pressing volume up or down.

!!!xdripitem "Buttons silence alarms <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Pressing the volume up or down button will snooze an active alarm when in the app

##### Alert buttons

Alert button will add an action button in the drop down view of the alert.

!!!xdripitem "Alert buttons <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Show action buttons (like Snooze Alert) within alert notifications

<img src="../images/M-S-AA-GAm2.png" style="zoom:75%;" />

<img src="../images/M-S-AA-GAm3.png" style="zoom:75%;" />

##### Start snoozed

Start snoozed applies the snooze delay before triggering the alarm. Make sure the `Default snooze` delay is appropriate in the alarm.

!!!xdripitem "Start snoozed <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Alerts start out snoozed and must persist for a while to actually trigger

##### Wake Screen

Wake up screen during alerts.

!!!xdripitem "Wake Screen<img src="../../images/OFF.png" style="zoom:75%;" />"  
    &ensp;Wake up screen during alerts. Might Unlock devices that don't have screen lock enabled

##### Use Camera Light

Flash the back camera light during alerts (when the phone is in charge).

!!!xdripitem "Use Camera Light<img src="../../images/OFF.png" style="zoom:75%;" />"  
    &ensp;Flash camera light during alerts when connected to  charger

##### Shortcut to BG Level Alerts

You can add a shortcut entry to `Level Alerts` in xDrip+ main menu.

!!!xdripitem "Shortcut to BG Level Alerts<img src="../../images/DIS.png" style="zoom:75%;" />"  
    &ensp;Create a shortcut from main navigation to BG level screen

##### Suppress alerts if missed readings

!!!xdripitem "Suppress Alerts if missed readings"

Level alerts remain active even if there is no signal (sensor change for example, or follower without network). This option allows you to suppress them. Make sure you have a missed alert enabled if you use this feature.

!!!xdripitem "Suppress Alerts if missed readings <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
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

!!!xdripitem "Delay Ascending Volume<img src="../../images/EN.png" style="zoom:75%;" />"  
    &ensp;For ascending volume profile, delay the start of the alert sound by 3 minutes. The vibration (if enabled) starts as soon as the alert triggers regardless of this setting

##### Ascend to medium

You can limit the maximum volume of the ascending volume alerts and alarms to medium instead of maximum.

!!!xdripitem "Ascend to medium<img src="../../images/DIS.png" style="zoom:75%;" />"  
    &ensp;When enabled, ascending volume profile will ascend to medium volume instead of maximum

### Calibration Alerts

If your sensor requires periodic calibration you can setup xDrip+ to alert you when calibration is due.

You can setup the period between calibrations, sound to be played, etc ...

!!!xdrip "Calibration Alerts"

!!!xdripitem "Calibration Alerts<img src="../../images/OFF.png" style="zoom:75%;" />"  
    &ensp;Alert when a calibration is requested

!!!xdripitem "Hours between calibrations"  
    &ensp;How many hours between calibration requests

!!!xdripitem "Calibration request sound"  
    &ensp;Default

!!!xdripitem "Override Silent mode<img src="../../images/END.png" style="zoom:75%;" />"

!!!xdripitem "Even when charging<img src="../../images/END.png" style="zoom:75%;" />"  
    &ensp;Uncheck to not ask calibrations when phone is charging

!!!xdripitem "Repeat Alerts<img src="../../images/END.png" style="zoom:75%;" />"  
    &ensp;Keep alerting if no calibration is performed

!!!xdripitem "Alert Repeat minutes"  
    &ensp;20

##### Initial alert

Initial calibration alert is used when starting a sensor requiring initial calibration: it will trigger when enough good readings are available to calibrate.

!!!xdripitem "Initial Alert<img src="../../images/ON.png" style="zoom:75%;" />"  
    &ensp;Play sound when Initial Calibration is requested

### Missed Reading Alert

!!!xdripitem "Missed Reading Alert"

When relying on xDrip+ to alert you for lows and highs, it is essential to make sure that it is actually receiving BG readings. For this, if you don't have any other alarms, enable this feature for your safety.

Setup is similar to [glucose level alerts](#glucose-level-alerts-list). **The alarm sound has to be defined in Other Alerts** (See [below](#alert-preferences)).  In order to test it, put your phone in airplane mode until it triggers.

!!!xDrip "☰&emsp;Configure Missed Readings"  
    &emsp;<small>✅ Enable missed reading alert</small>  
    &emsp;<small>Alert if no data is received in:</small>  
    &emsp;<small><u>&ensp;30&ensp;</u>&ensp;minutes</small>  
    &emsp;<small>Select time for alert:</small>  
    &emsp;<small>✅ All day</small>  
        
    &emsp;<small>Wait before raising the same alert after snooze:</small>  
    &emsp;<small><u>&ensp;20&ensp;</u>&ensp;minutes</small>  
    &emsp;<small>☐ Reraise alerts before snooze time</small>  
    &emsp;<small>Alert Reraise time:</small>  
    &emsp;<small><u>&ensp;60&ensp;</u>&ensp;seconds</small>  

### Other Alerts

!!!xdrip "Other Alerts"

#### Noisy Readings

!!!xdripitem "<small>NOISY READINGS</small>"

If you enable this feature and your sensor supports it, you can setup an alert for noisy readings.

!!!xdripitem "Bad (noisy) Value Alerts<img src="../../images/DIS.png" style="zoom:75%;" />"

!!!xdripitem "Alert after x minutes of noisy values"  
    &ensp;90

!!!xdripitem "Alert snooze"  
    &ensp;Number of minutes before raising the same alert after snooze

!!!xdripitem "Reraise alerts before snooze time<img src="../../images/DIS.png" style="zoom:75%;">"  
    &ensp;Reraise the alert if not snoozed sooner

!!!xdripitem "Alert reraise time"  
    &ensp;Number of SECONDS to pass before raising the same alert

#### Falling or rising BG

!!!xdripitem "<small>FALLING/RISING BG</small>"

You can also setup alerts for fast BG changes and define the 1 minute change triggering value. For example 3 minutes means 15 mg/dl (0.85 mmol/l) every 5 minutes.

!!!xdripitem "BG falling fast<img src="../../images/DIS.png" style="zoom:75%;">"

!!!xdripitem "falling rate threshold"  
    &ensp;3mg/dl/min (0.17mmol/l/min)

!!!xdripitem "BG rising fast<img src="../../images/DIS.png" style="zoom:75%;">"

!!!xdripitem "rising rate threshold "  
    &ensp;3mg/dl/min (0.17mmol/l/min)

##### Alert preferences

!!!xdripitem "<small>ALERT PREFERENCES (FOR THESE ALERTS)</small>"

The alerts above and **also Missed Readings** use the sound defined below.  
Some recent Android versions do not ring it unless you use [Notification channels](#notification-channels).

!!!warning "Make sure to test the alarm"  
    This is an important feature to sleep safely. Reduce the missed readings period and put your phone in airplane mode (no Wi-Fi) to force the alarm to ring.

!!!xdripitem "Alert sound"  
    &ensp;Default

!!!xdripitem "Override Silent mode on these alerts<img src="../../images/EN.png" style="zoom:75%;" />"

### Extra Alerts

!!!xdrip "Extra Alerts (xDrip+)"

##### Persistent High Alert

!!!xdripitem "Persistent High Alert"

Instead of a high alert that will trigger as soon as BG reaches the trigger value, you can setup a persistent high alert that will only trigger when BG remains above a setup value for more than a certain time. You can use either xDrip+ [High Value](../../use/settings/#glucose-units) or a value you decide for triggering this alert.

!!!xdripitem "Enable<img src="../../images/OFF.png" style="zoom:75%;">"  
    &ensp;Notify if above threshold for longer than the time specified below

!!!xdripitem "Threshold: High Value<img src="../../images/ON.png" style="zoom:75%;">"  
    &ensp;When enabled, High value is the threshold.  
    &ensp;When disabled, the threshold is the value defined below.  

!!!xdripitem "Threshold"  
    &ensp;170 mg/dl

!!!xdripitem "for longer than (minutes)"  
    &ensp;60

!!!xdripitem "Repeating max every (minutes)"  
    &ensp;20

!!!xdripitem "Alert Sound  "  
    &ensp;Chose the sound used for the alarm

##### Forecasted Low Alert

!!!xdripitem "Forecasted Low Alert"

You can set an alarm on forecasted low value. This feature will use the **momentum** (extrapolation of the current BG trend) and **not** the [prediction](../predictions) settings. Forecasted low (min) is the time in which a low will be forecasted (the one that usually displays in yellow on the graph screen).

Forecast Lows will display a message on xDrip+ screen. In order to have an alarm sounds when a low is forecast, enable Raise alarm on Forecast Low.

!!!xdripitem "Forecasted Lows<img src="../../images/ON.png" style="zoom:75%;">"  
    &ensp;Extrapolate data to try to predict lows

!!!xdripitem "Raise alarm on Forecast Low<img src="../../images/DIS.png" style="zoom:75%;">"  
    &ensp;Notify when predicted low time reaches threshold

!!!xdripitem "Alarm at Forecast Low min"  
    &ensp;40

!!!xdripitem "Predicted Low Sound "  
    &ensp;Choose the sound used for the alarm

In the example below if you set Alarm at forecasted low (min) to 50 minutes, il will trigger. The red dotted line is the forecasted BG trend, extrapolated from the previous measurements.

<img src="../images/M-S-AA-EAb2.png" style="zoom:75%;" />

##### Other xDrip+ alerts

!!!xdripitem "Other xDrip+ Alerts"

Some extra alerts are available.  
Battery alerts are available if your bridge sends this information to xDrip+ (historically G4 now Libre bridges).

!!!xdripitem "Collector battery alerts<img src="../../images/ON.png" style="zoom:75%;"> "  
    &ensp;Notify when battery level goes below

!!!xdripitem "Low battery percentage "  
    &ensp;30

!!!xdripitem "Parakeet related alerts "  
    &ensp;Notify when Parakeet device stops checking in

!!!xdripitem "Silent alert when charging<img src="../../images/DIS.png" style="zoom:75%;"> "  
    &ensp;Raise Parakeet notification silently when charging

##### Follower Chime New

After missed readings, a notification will sound when new data is received after more than 20 minutes.

!!!xdripitem "Follower Chime New<img src="../../images/OFF.png" style="zoom:75%;">  "  
    &ensp;Notify when data arrives from the master if the interval is > 20 mins.

## Snooze Alert

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Snooze Alert

If there is no active alert, you can **pre-snooze** alerts from this menu so that they won't trigger for a certain time.

!!!xdrip "<img src="../../images/BDM.png" style="zoom:75%;" />Snooze"  
    <div style="text-align: center;"> No active alert exists</div>  
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;Disable Low Alerts&emsp;</div>  
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;Disable High Alerts&emsp;</div>  
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;Disable All Alerts&emsp;</div>

You will be proposed a default snooze period. Scroll up and down to change it.

!!!xdrip "Default Snooze"  
    <div style="background-color: darkgray; color: dimgray; text-align: center;">&nbsp;  
        50 minutes  
      </div>
      <div style="background-color: darkgray; color: black; text-align: center;">&nbsp;  
        60 minutes  
      </div>
      <div style="background-color: darkgray; color: dimgray; text-align: center;">&nbsp;  
        70 minutes  
    </div>

If an alert triggers you will see the notification in your phone drop down panel, and eventually hear the sound.

You can snooze the alert swiping the notification, you can customize it further tapping it.

<img src="../images/M-SNOc.png" style="zoom:75%;" />  

You can access the snooze menu by touching the notification or from xDrip+ main menu, snooze alert.

At this point, the snooze menu will also display the active alert.  
Touching snooze will snooze it for the period selected.

!!!xdrip "<img src="../../images/BDM.png" style="zoom:75%;" />Snooze"  
    <div style="background-color: dimgray; color: white; text-align: center;">  
    <big><big>Snooze</big></big></div> 
    <div style="background-color: dimgray; color: white; text-align: center;">&nbsp;  
    <div style="background-color: black; color: dimgray; text-align: center;">&nbsp;  
        20 minutes  
      </div>
      <div style="background-color: black; color: darkgray; text-align: center;">&nbsp;  
        30 minutes  
      </div>
      <div style="background-color: black; color: dimgray; text-align: center;">&nbsp;  
        40 minutes  
    </div></div>  
​    

    Active alert exists named "Night" alert will rerise at 1:25:01 (0 minutes left)  
      
    <div style="background-color: dimgray; color: white; text-align: center;">  &emsp;Disable Low Alerts&emsp;</div>  
    <div style="background-color: dimgray; color: white; text-align: center;">  &emsp;Disable High Alerts&emsp;</div>  
    <div style="background-color: dimgray; color: white; text-align: center;">  &emsp;Disable All Alerts&emsp;</div> 

##### ALL ALERTS CURRENTLY DISABLED

If you pre-snooze (disable) all alerts, you will see this warning message.

<img src="../images/M-SNOe.png" style="zoom:75%;" />  

To remove it you need to re-enable alerts.

!!!xdrip "<img src="../../images/BDM.png" style="zoom:75%;" />Snooze"  
    <div style="text-align: center;"> All alerts disabled until 15:09:12</div>  
    <div style="background-color: gray; color: white; text-align: center;">  &emsp;Re-Enable All Alerts&emsp;</div>  

</br>

## Visible alert notification

Available for Android 8 and above.

When an alert triggers you will see it in the notifications drop down panel.

<img src="../images/M-SNOg.png" style="zoom:75%;" />  

Swiping it will snooze it, touching it will open a preferences menu.  
Deliver quietly will remove [notifications channel](#notification-channels) sound and vibration.

<img src="../images/M-SNOh.png" style="zoom:75%;" />

You can restore it with allow sound and vibration with the [notifications channels](#notification-channels).

<img src="../images/M-SNOi.png" style="zoom:75%;" />  

Settings will drive you to your phone notifications setup settings.

<img src="../images/M-SNOk.png" style="zoom:75%;" />  

You can also completely turn off [notifications channels](#notification-channels) for xDrip+.

<img src="../images/M-SNOj.png" style="zoom:75%;" />  



[*Last modified 4/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
