<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-DS.png" style="zoom:75%;" />

This menu allows you to customize many visual aspect settings of xDrip+.

<img src="../images/M-S-DS1.png" style="zoom:75%;" />

*Note: Check [Graph settings](#graph-settings) features before using Color settings.*

### Color Settings

<img src="../images/M-S-DS2.png" style="zoom:75%;" />

The example chart on top will show the effect of what you modify.

<img src="../images/M-S-DS2a.png" style="zoom:75%;" />

When modifying a color you can chose

1. hue and saturation
2. lightness/darkness
3. transparency.

The result will show compared to the original color.

You can revert the color to default or save it.

<img src="../images/M-S-DS2a2.png" style="zoom:75%;" />

##### Glucose values and lines

You can customize the main BG plot. High and Low limits are defined in [Glucose Units settings.](../settings/#glucose-units)

High, In-range and Low Values color will change the graph and limit lines on your main view, notification and widget charts.

<img src="../images/M-S-DS2b.png" style="zoom:75%;" />

<img src="../images/M-S-DS2b2.png" style="zoom:75%;" />

##### Colors of BG readings and Trend Arrows

You can also customize the current BG value and trend arrow color in respect with range limits.

<img src="../images/M-S-DS2b3.png" style="zoom:76%;" />

<img src="../images/M-S-DS2c.png" style="zoom:75%;" />

Filtered values can be seen with sensors supporting raw data.

<img src="../images/M-S-DS2d.png" style="zoom:75%;" />

<img src="../images/M-S-DS2d2.png" style="zoom:75%;" />

##### Treatments and predictions curves

1. Insulin on board ([treatment](../mainUI/#units-of-insulin) main curve)
2. Insulin activity (small dotted line)

<img src="../images/M-S-DS2e.png" style="zoom:78%;" />

<img src="../images/M-S-DS2e2.png" style="zoom:75%;" />

1. Glucose [prediction](../predictions) (main prediction graph)
2. [Carbs](../mainUI/#grams-of-carbs) on board (small dotted line)

<img src="../images/M-S-DS2f.png" style="zoom:78%;" />

<img src="../images/M-S-DS2f2.png" style="zoom:75%;" />

##### Average and target lines

1. 8-Hour average line
2. 24-Hour average line
3. Target line

<img src="../images/M-S-DS2g.png" style="zoom:75%;" />

<img src="../images/M-S-DS2g2.png" style="zoom:75%;" />

##### Annotations and dots

[Blood tests (also calibrations), and treatments.](../mainUI/#treatments)

<img src="../images/M-S-DS2h.png" style="zoom:75%;" />

<img src="../images/M-S-DS2h2.png" style="zoom:75%;" />

##### Backgrounds

Graphs backgrounds, main

<img src="../images/M-S-DS2i.png" style="zoom:75%;" />

##### [Notifications](../misc/#run-collector-in-foreground)

<img src="../images/M-S-DS2j.png" style="zoom:75%;" />

<img src="../images/M-S-DS2j2.png" style="zoom:75%;" />

##### [Widget](../mainUI/#widget)

<img src="../images/M-S-DS2k.png" style="zoom:75%;" />

##### Plugins and features

If you use a [plugin](../../calibrate/advancedcal/#plugins) you can also display the plugin glucose value as a secondary graph.   
Plugin plot on graph must be enabled.

<img src="../images/M-S-DS2l.png" style="zoom:75%;" />

<img src="../images/M-S-DS2l2.png" style="zoom:75%;" />

If you have steps and heart rate from a [wearable device](../../smartwatch/smartwatch/#smartwatch-sensors) you can customize graphs colors. 

<img src="../images/M-S-DS2m.png" style="zoom:75%;" />

In the example below 1. heart rate and 2. step counter.

<img src="../../smartwatch/images/M-S-SW8c.png" style="zoom:75%;" />

##### Basal and SMB

If you manage to display basal ([from AAPS](#basal-information) or [manual setup](../predictions/#basal-profile-editor)) you can also customize the color.

<img src="../images/M-S-DS2n.png" style="zoom:75%;" />

<img src="../images/M-S-DS2n2.png" style="zoom:75%;" />

[SMB](#smb)s are icons decluttering the graph for micro-bolus treatments.

<img src="../images/M-S-DS2o.png" style="zoom:75%;" />

<img src="../images/M-S-DS2o2.png" style="zoom:75%;" />

##### Flair colors

If you want to put some color on the top and bottom bars of your Android screen, enable flair colors.

<img src="../images/M-S-DS2p.png" style="zoom:78%;" />

<img src="../images/M-S-DS2p2.png" style="zoom:75%;" />

<img src="../images/M-S-DS2p3.png" style="zoom:75%;" />

### Language

By default xDrip+ will use your phone language. You can select another language for xDrip+ and force it to display instead of the phone language. For this: select the language in Choose a specific language, then toggle the Force language Text switch.

<img src="../images/M-S-DS3.png" style="zoom:75%;" />

<img src="../images/M-S-DS3a.png" style="zoom:75%;" />

### Smooth sensor noise

Smoothing displays the smoothed curve, useful for noisy measurements.  
You can also try [Graph smoothing](#graph-smoothing) to clean your graph.

<img src="../images/M-S-DS4.png" style="zoom:75%;" />

<img src="../images/M-S-DS4a.png" style="zoom:75%;" />

### Show interface hints

After you first installed xDrip+ you will see hints during first opening of some features, you can disable this behavior or reset it.

<img src="../images/M-S-DS5.png" style="zoom:75%;" />

<img src="../images/M-S-DS5a.png" style="zoom:75%;" />

### Graph Settings

You can customize most of the items that will display on the main graph.

<img src="../images/M-S-DS6.png" style="zoom:75%;" />

##### Graph smoothing

Graph smoothing will apply a smoothing filter to the graph to make it easier to follow (less noise).  
This is only a visual effect and doesn't impact readings.

<img src="../images/M-S-DS6aa9.png" style="zoom:76%;" />

<img src="../images/M-S-DS6aa9b.png" style="zoom:76%;" />  

<img src="../images/M-S-DS6aa9c.png" style="zoom:76%;" />

##### Rewrite history

Rewrite history will soften transitions after adding a new calibration to reduce the step like effect.  
Make sure this is also enabled on followers to avoid different visualization of past BG values. 

<img src="../images/M-S-DS6a.png" style="zoom:75%;" />

<img src="../images/M-S-DS6a2.png" style="zoom:75%;" />

##### Widget range lines

You can select to visualize high and low limit lines on the widget.

<img src="../images/M-S-DS6b.png" style="zoom:75%;" />

<img src="../images/M-S-DS6b2.png" style="zoom:75%;" />

##### Main graph lines

You can disable vertical time lines on the main graph.

<img src="../images/M-S-DS6c.png" style="zoom:75%;" />

<img src="../images/M-S-DS6c2.png" style="zoom:75%;" />

You can disable horizontal glucose lines on the main graph.

<img src="../images/M-S-DS6d.png" style="zoom:75%;" />

<img src="../images/M-S-DS6d2.png" style="zoom:75%;" />

##### Filtered data

Filtered or smoothed plot adds another graph curve and will eventually add missing data.

<img src="../images/M-S-DS6e.png" style="zoom:75%;" />

<img src="../images/M-S-DS4a.png" style="zoom:75%;" />

For some data sources (like patched LL app) this will expose the unfiltered raw data as xDrip+ BG display is already filtered.

<img src="../images/M-S-DS6e2.png" style="zoom:75%;" />

##### Raw data

Raw data that can be displayed by xDrip+ if available.

<img src="../images/M-S-DS6f.png" style="zoom:75%;" />

G4, G5 and [old G6](../../troubleshoot/connection/#firefly-transmitters) provide raw data.

<img src="../images/M-S-DS6f2.png" style="zoom:75%;" />

Now raw data are mainly visible for Libre sensors.

<img src="../images/M-S-DS6f3.png" style="zoom:75%;" />

##### Basal information

If basal information is available from an external source ([AAPS NSClient](https://androidaps.readthedocs.io/en/latest/index.html)) it can be displayed by xDrip+.

In AAPS/NSClient config builder, xDrip+ Statusline, enable Show detailed IoB.

<img src="../images/NSClient.png" style="zoom:75%;" />

In xDrip+:  
Settings - Less common settings - enable Extra status line, enable [External status](../lesscommon/#extra-status-line).  
Settings - Inter-app - enable [Accept treatments](../interapp/#receiving-from-nsclient).  
Enable Show basal TBR.

<img src="../images/M-S-DS6g.png" style="zoom:75%;" />

<img src="../images/M-S-DS2n2.png" style="zoom:75%;" />

Basal information will also be uploaded to [Tidepool](../cloud/#tidepool).

##### Target and average lines

You can visualize various reference lines on the graph:

1. 8-Hour average line
2. 24-Hour average line
3. Target line

<img src="../images/M-S-DS6h.png" style="zoom:75%;" />

<img src="../images/M-S-DS2g2.png" style="zoom:75%;" />

##### Libre trend

[Libre trend](../3dotsmenu/#libre-trend) enables a small graph available in the three dots menu on the main view.

<img src="../images/M-S-DS6i.png" style="zoom:75%;" />

##### G6 predictions

G6 prediction is a built-in feature of the G6 transmitter showing as small grey dots.

<img src="../images/M-S-DS6j.png" style="zoom:75%;" />

<img src="../images/M-S-DS6j2.png" style="zoom:75%;" />

##### SMB

SMBs are icons decluttering the graph for micro-bolus treatments. Touching the SMB gives the amount in insulin in the information line.

<img src="../images/M-S-DS6k.png" style="zoom:75%;" />

<img src="../images/M-S-DS6k2.png" style="zoom:75%;" />

Display the Medtrum secondary sensor values.

<img src="../images/M-S-DS6l.png" style="zoom:75%;" />

##### Noise workings

Additional noise calculation information, yellow line.

<img src="../images/M-S-DS6m.png" style="zoom:75%;" />

<img src="../images/M-S-DS6e2.png" style="zoom:75%;" />

##### Backfilled data

Backfilled data can be indicated with a different dot style.

<img src="../images/M-S-DS6n.png" style="zoom:75%;" />

<img src="../images/M-S-DS6n2.png" style="zoom:75%;" />

##### Widget graph

You can hide the graph on the [widget](../mainUI/#widget) and keep only the value.

<img src="../images/M-S-DS6o.png" style="zoom:75%;" />

<img src="../images/M-S-DS6o2.png" style="zoom:75%;" />

These two options are only available for developers.

<img src="../images/M-S-DS6p.png" style="zoom:75%;" />

<img src="../images/M-S-DS6q.png" style="zoom:75%;" />

##### Customize Y axis range

You can arbitrarily fix lower and upper value for the Y axis. Whenever readings will be out of this range, the graph will extend the range to make them visible. Y scale will then return to these settings when out of fixed range values are not displayed anymore.

<img src="../images/M-S-DS7.png" style="zoom:75%;" />

<img src="../images/M-S-DS7a.png" style="zoom:75%;" />

### Glucose number from Filtered

Filtering might delay readings and is not recommended.  
Filtering of 20 minutes is hardware coded for [Patched Libre 2 app data source](../../install/libre2patch/).

<img src="../images/M-S-DS6r.png" style="zoom:75%;" />

<img src="../images/M-S-DS6e2.png" style="zoom:75%;" />

### Bolus Wizard Preview

BWP will show insulin on board (IoB) and suggest corrections based on the [predictive](../predictions) parameters entered in xDrip+.  
This is an indication. Make sure you understand the EULA before using it.  
Never follow the suggestions when BG is fast changing.

<img src="../images/M-S-DS6s.png" style="zoom:75%;" />

<img src="../images/M-S-DS6s3.png" style="zoom:75%;" />

If you force always show BWP it will always suggest a correction (insulin or carbs).

<img src="../images/M-S-DS6s2.png" style="zoom:75%;" />

### High Priority Notifications

This will bring xDrip+ [graph and notifications](../misc/#run-collector-in-foreground) at the top of the list, disabling it brings it down.

<img src="../images/M-S-DS6t.png" style="zoom:75%;" />

<img src="../images/M-S-DS2j2.png" style="zoom:75%;" />

### Public Notifications

This makes notifications visible on locked screen.

<img src="../images/M-S-DS6u.png" style="zoom:75%;" />

### Parakeet and Extra Test Features

You might have wanted to use these settings with a [Parakeet](https://github.com/jamorham/wixel-xDrip/blob/parakeet-gsm-modem/README.md).

<img src="../images/M-S-DS6v.png" style="zoom:75%;" />

### Enable Reminder Features

Enabled by default, you'll find reminders in the [three dots menu](../3dotsmenu) top right on the main view.

<img src="../images/M-S-DS6w.png" style="zoom:75%;" />

### Enable xDrip+ Accessibility

xDrip+ can interface with Android accessibility if your phone supports it.

<img src="../images/M-S-DS6x.png" style="zoom:75%;" />

<img src="../images/M-S-DS6x2.png" style="zoom:75%;" />

<img src="../images/M-S-DS6x3.png" style="zoom:75%;" />

### Numbered wall on Locked Screen

xDrip+ can display your BG value on the phone locked screen.  
Some features requires Android 7 and above.

<img src="../images/M-S-DS6z.png" style="zoom:75%;" />

This menu allows you to customize the number displayed.

<img src="../images/M-S-DS6z1.png" style="zoom:75%;" />

1. You will see a real time preview of the result (123 ⇅)
2. Change the font size
3. Change the vertical position (or vertical distance between numbers)
4. Change the horizontal position (or horizontal distance between numbers)
5. Change the number color
6. Select the background image
7. The actual numbered wall

<img src="../images/M-S-DS6z1.png" style="zoom:75%;" />

<img src="../images/M-S-DS6z2.png" style="zoom:75%;" />

Locked screen display can be enabled on Android 7+.

<img src="../images/M-S-DS6z3.png" style="zoom:75%;" />

You can change the text and background color.

<img src="../images/M-S-DS6z4.png" style="zoom:75%;" />

Enable and disable the feature for a defined period of the day.

<img src="../images/M-S-DS6z5.png" style="zoom:75%;" />

### Number Icon in Notification Area

xDrip+ can display your BG number as an icon in the top left notification area and in the drop down notifications.

<img src="../images/M-S-DS6aa6.png" style="zoom:75%;" />

<img src="../images/M-S-DS6aa1.png" style="zoom:75%;" />

You should test the feature before using it as it might crash on some phones.

<img src="../images/M-S-DS6aa2.png" style="zoom:75%;" />

<img src="../images/M-S-DS6aa5.png" style="zoom:75%;" />

You phone will vibrate a few times during the test and you should see the BG icon 123 top left.

<img src="../images/M-S-DS6aa7.png" style="zoom:75%;" />

If this doesn't work it means you shouldn't enable the feature.

**Once functionality is confirmed** you can enable it.

<img src="../images/M-S-DS6aa3.png" style="zoom:75%;" />

You can also enable a large icon, with or without arrow in the notifications area.

<img src="../images/M-S-DS6aa4.png" style="zoom:75%;" />

<img src="../images/M-S-DS6aa8.png" style="zoom:75%;" />

### Show xDrip on Boot

This will make xDrip+ open automatically when your phone restarts.

<img src="../images/M-S-DS6y.png" style="zoom:75%;" />

</br>

[*Last modified 3/15/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.15.03)