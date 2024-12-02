!!!xdrip "`xDrip+ Display Settings`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_chart_areaspline_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Display Settings

This menu allows you to customize many visual aspect settings of xDrip+.

!!!xdripitem "xDrip+ Display Settings"  

*Note: Check [Graph settings](#graph-settings) features before using Color settings.*

### Color Settings

!!!xdripitem "xDrip+ Color Settings"  
      &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_palette_grey600_48dp.png" style="width:8%;" />&ensp;Customize Colors

The example chart on top will show the effect of what you modify.

!!!xdripitem "Example Chart"  
      &emsp;<img src="../images/M-S-DS2a.png" style="zoom:75%;" />

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

By default xDrip+ will use your phone language. You can select another language for xDrip+ and force it to display instead of the phone language.

For this: 

1. Select the language in Choose a specific language.
2. Toggle the Force language Text switch to ON.

!!!xdripitem "Force English Text&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  

!!!xdripitem "Choose a specific language"  

<img src="../images/M-S-DS3a.png" style="zoom:75%;" />

### Smooth sensor noise

Smoothing displays the smoothed curve (it does not change readings), useful for noisy measurements.  
You can also try [Graph smoothing](#graph-smoothing) to clean your graph.

!!!xdripitem "Smooth sensor noise&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Try to work around noisy readings

<img src="../images/M-S-DS4a.png" style="zoom:75%;" />

### Show interface hints

After you first installed xDrip+ you will see hints during first opening of some features, you can disable this behavior or reset it.

!!!xdripitem "Show interface hints&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 🗹"  
    &ensp;Show tips/hints describing buttons functions etc. Uncheck and recheck to reset to the beginning.

<img src="../images/M-S-DS5a.png" style="zoom:75%;" />

### Graph Settings

You can customize most of the items that will display on the main graph.

!!!xdripitem "Graph Settings"  
      &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_chart_areaspline_grey600_48dp.png" style="width:8%;" />&ensp;Adjust chart items

##### Graph smoothing

Graph smoothing will apply a smoothing filter to the graph to make it easier to follow (less noise).  
This is only a visual effect and doesn't impact readings.

!!!xdripitem "Graph Smoothing&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Simplify graphs by smoothing out irregularities

<img src="../images/M-S-DS6aa9b.png" style="zoom:76%;" />  

<img src="../images/M-S-DS6aa9c.png" style="zoom:76%;" />

##### Rewrite history

Rewrite history will soften transitions after adding a new calibration to reduce the step like effect.  
Make sure this is also enabled on followers to avoid different visualization of past BG values. 

!!!xdripitem "Rewrite History"  
    &ensp;After calibration, adjust recent raw graph to smooth to the new calibration

<img src="../images/M-S-DS6a2.png" style="zoom:75%;" />

##### Widget range lines

You can select to visualize high and low limit lines on the widget.

!!!xdripitem "Widget Range Lines"  
    &ensp;Show a high and low line on the widget

<img src="../images/M-S-DS6b2.png" style="zoom:75%;" />

##### Main graph lines

You can disable vertical time lines on the main graph.

!!!xdripitem "Show Graph grid time lines"  
    &ensp;Grid time lines visible

<img src="../images/M-S-DS6c2.png" style="zoom:75%;" />

You can disable horizontal glucose lines on the main graph.

!!!xdripitem "Show Graph grid glucose lines"  
    &ensp;Grid glucose lines visible

<img src="../images/M-S-DS6d2.png" style="zoom:75%;" />

##### Filtered data

Filtered or smoothed plot adds another graph curve and can eventually create missing data.

!!!xdripitem "Display Filtered Plot"  
    &ensp;Useful for noise and missed readings

!!!xdripitem "Create missing filtered"  
    &ensp;Make filtered data as needed

<img src="../images/M-S-DS4a.png" style="zoom:75%;" />

For some data sources (like patched LL app) this will expose the unfiltered raw data as xDrip+ BG display is already filtered.

<img src="../images/M-S-DS6e2.png" style="zoom:75%;" />

##### Raw data

Raw data that can be displayed by xDrip+ if available.

!!!xdripitem "Display raw data plot"

G4, G5 and rebatteried G6 provide raw data.

<img src="../images/M-S-DS6f2.png" style="zoom:75%;" />

Now raw data are mainly visible for Libre sensors but not with this option.  
For Libre sensor raw data use [Advanced Settings for Libre 2](../lesscommon/#advanced-settings-for-libre-2).

##### Basal information

If basal information is available from an external source ([AAPS NSClient](https://androidaps.readthedocs.io/en/latest/index.html)) it can be displayed by xDrip+.

In AAPS/NSClient:

- Config builder

- Synchronization - xDrip+ settings
- Enable Send status line to xDrip+

<img src="../images/NSClient.png" style="zoom:75%;" />

In xDrip+: 

- Settings - Less common settings - Enable Extra status line - Enable [External status](../lesscommon#extra-status-line)
- Settings - Inter-app - Enable [Accept treatments](../interapp#receiving-from-nsclient)
- Enable Show basal TBR

!!!xdripitem "Show Basal TBR"

<img src="../images/M-S-DS2n2.png" style="zoom:75%;" />

Basal information will also be uploaded to [Tidepool](../cloud/#tidepool).

##### Target and average lines

You can visualize various reference lines on the graph:

!!!xdripitem "Show Graph target line"

!!!xdripitem "Show Graph recent average"

!!!xdripitem "Show Graph total average"

1. 8-Hour average line (recent)
2. 24-Hour average line (total)
3. [Target](../predictions#low-level-prediction) line

<img src="../images/M-S-DS2g2.png" style="zoom:75%;" />

##### Libre trend

[Libre trend](../3dotsmenu/#libre-trend) enables a small graph available in the three dots menu on the main view.

!!!xdripitem "Show Libre trend"

##### G6 predictions

G6 prediction is a built-in feature of the G6 transmitter showing as small grey dots.

!!!xdripitem "G6 prediction"

<img src="../images/M-S-DS6j2.png" style="zoom:75%;" />

##### SMB

SMBs are icons decluttering the graph for micro-bolus treatments. Touching the SMB gives the amount in insulin in the information line.

!!!xdripitem "Show micro bolus icons"

<img src="../images/M-S-DS6k2.png" style="zoom:75%;" />

!!!xdripitem "Medtrum Secondary"

Display the Medtrum A6 secondary sensor values.

##### Trend momentum

!!!xdripitem "Show momentum working curve"

Displays a red dotted line (1) momentum extrapolating current BG trend for predicted lows/highs.  
It is completely independent from [predictions](../predictions#use-trend-momentum) (2) and doesn't take in consideration carbs or insulin models.

<img src="../images/M-S-PS5b.png" style="zoom:75%;" />

##### Noise workings

Additional noise calculation visual information, five dots yellow line on the right of the curve.

!!!xdripitem "Show Noise workings"

<img src="../images/M-S-DS6e2.png" style="zoom:75%;" />

##### Backfilled data

Backfilled data can be indicated with an empty blue dot.

!!!xdripitem "Show backfilled data"

<img src="../images/M-S-DS6n2.png" style="zoom:75%;" />

##### Widget graph

You can hide the graph on the [widget](../mainUI/#widget) and keep only the value.

!!!xdripitem "Hide widget graph"

<img src="../images/M-S-DS6o2.png" style="zoom:75%;" />

These two options are only available for developers.

!!!xdripitem "Illustrate remote data"

##### Customize Y axis range

The main screen vertical axis has a default minimum of 40 mg/dl (2.22 mmol/l) and default maximum of 250 mg/dl (13.9 mmol/l).

You can arbitrarily fix lower and upper value for the Y axis. Whenever readings will be out of this range, the graph will extend the range to make them visible. Y scale will then return to these settings when out of fixed range values are not displayed anymore.

!!!xdripitem "Customize y axis range"

### Glucose number from Filtered

Filtering might delay readings and is not recommended.  
Filtering is hardware coded for [Patched Libre 2 app data source](../../install/libre2patch/).

!!!xdripitem "Glucose number from filtered"

<img src="../images/M-S-DS6e2.png" style="zoom:75%;" />

### Bolus Wizard Preview

BWP will show insulin on board (IoB) and suggest corrections based on the [predictive](../predictions) parameters entered in xDrip+.  
This is an indication. Make sure you understand the EULA before using it.  
Never follow the suggestions when BG is fast changing.

Bolus Wizard Preview will show only when either carbs or insulin are present.

!!!xdripitem "Show Bolus Wizard Preview"  
    &ensp;Display Insulin/Carb calculations

<img src="../images/M-S-DS6s3.png" style="zoom:75%;" />

!!!xdripitem "Always show Bolus Wizard Preview"  
    &ensp;Display Insulin/Carb calculations all the time

If you force always show BWP it will always suggest a correction (insulin or carbs).

<img src="../images/M-S-DS6s2.png" style="zoom:75%;" />

### High Priority Notifications

This will bring xDrip+ [graph and notifications](../misc/#run-collector-in-foreground) at the top of the list, disabling it brings it down.

You can disable High Priority Notifications, but you shouldn't disable it completely with [Run collector in foreground](../misc#run-collector-in-foreground) if you don't want xDrip+ to be put to sleep by Android.

!!!xdripitem "High Priority Notifications&ensp;&emsp;&emsp;&emsp;&emsp;&emsp; 🗹"  
    &ensp;Show notifications and graph at the top (also useful on lock screen).

<img src="../images/M-S-DS2j2.png" style="zoom:75%;" />

### Public Notifications

This makes notifications visible on locked screen.

!!!xdripitem "Public Notifications"

### Parakeet and Extra Test Features

You might have wanted to use these settings with a [Parakeet](https://github.com/jamorham/wixel-xDrip/blob/parakeet-gsm-modem/README.md).

!!!xdripitem "Parakeet and Extra Test Features"

### Enable Reminder Features

Enabled by default, you'll find reminders in the [three dots menu](../3dotsmenu) top right on the main view.

!!!xdripitem "Enable Reminder Features"

### Always on display widget

xDrip+ can use Android accessibility to display its widget in the always on display screen, if your phone supports it.

!!!xdripitem "Enable xDrip Accessibility"  
    &ensp;If your phone has Always On Display you can enable the xDrip widget there by enabling the xDrip accessibility service from the Android System Settings page.

<img src="../images/M-S-DS6x2.png" style="zoom:75%;" />

<img src="../images/M-S-DS6x3.png" style="zoom:75%;" />

### Numbered wall on Locked Screen

xDrip+ can display your BG value on the phone locked screen.  
Some features requires Android 7 and above.

!!!xdripitem "Numbered wall on Locked Screen"

This menu allows you to customize the number displayed.

!!!xdripitem "Configure Number wall"

You will see a real time preview of the result (123 ⇅)

1. Change the font size
2. Change the vertical position (or vertical distance between numbers)
3. Change the horizontal position (or horizontal distance between numbers)
4. Change the number color
5. Select the background image
6. The actual numbered wall

<img src="../images/M-S-DS6z2.png" style="zoom:75%;" />

Enable Locked screen display to show the numbered wall (Android 7 and above).

!!!xdripitem "Use on Lock screen&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Show on lock screen. Android 7 and above only!

You can change the text and background color.

<img src="../images/M-S-DS6z4.png" style="zoom:75%;" />

Enable and disable the feature for a defined period of the day. By default it enables all day long.

!!!xdripitem "Turn On (all day)"

!!!xdripitem "Turn Off Time"

### Number Icon in Notification Area

xDrip+ can display your BG number as an icon in the top left notification area and in the drop down notifications.

<img src="../images/M-S-DS6aa6.png" style="zoom:75%;" />

!!!xdripitem "Number Icon in Notification Area"

**You should test the feature before using it as it might crash on some phones.**

!!!xdripitem "Run Number Icon Test"  
    &ensp;Number icons crash some phones! Tap to run the test before enabling the feature!

<img src="../images/M-S-DS6aa5.png" style="zoom:75%;" />

You phone will vibrate a few times during the test and you should see the BG icon 123 top left.

<img src="../images/M-S-DS6aa7.png" style="zoom:75%;" />

If this doesn't work it means you shouldn't enable the feature.

**Once functionality is confirmed** you can enable it.

!!!xdripitem "Number Icon tested&nbsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;When you have confirmed your device can display a number icon

!!!xdripitem "Show Small Number Icon&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Shows the current glucose number as an icon for the notification bar and lock screen

You can also enable a large icon (1), with or without arrow (2) **in the notifications area**.

!!!xdripitem "Use Large Number Icon&ensp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Shows a large number in the notification area only visible when opened

!!!xdripitem "Show Arrow in Large Icon&nbsp;&ensp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Shows the trend arrow in the large icon

<img src="../images/M-S-DS6aa8.png" style="zoom:75%;" />

### Show xDrip on Boot

This will make xDrip+ open automatically when your phone restarts.

It might be a good idea to enable this feature if your phone performs automatic updates and reboots (not recommended) and xDrip+ is not starting automatically at reboot. 

!!!xdripitem "Show xDrip on Boot"  
    &ensp;Bring up xDrip screen automatically after device boots

</br>

[*Last modified 9/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.09.04)