### Meet the user interface

Welcome to xDrip+!

<img src="../images/UI-basic.png" style="zoom:50%;" />

If you've just setup xDrip+ you want to start with basic customizations:

1. [Setup the unit you want to display your blood glucose with](../settings)
2. [Add alarms](../alarms)
3. If you're connecting xDrip+ to a sensor, [share data to another phone with xDrip+](../../install/xdripfollower/) or to the [cloud](../cloud)
4. Display xDrip+ on the phone when [screen is locked](../display/#numbered-wall-on-locked-screen)
5. Add a [widget](#widget) to your phone home screen
6. Add a [smartwatch](../../smartwatch/smartwatch)

### Basic indications

You will see these default indications when xDrip+ receives data.

<img src="../images/UI-indications.png" style="zoom:75%;" />

1. How long ago was the reading received and what's the BG difference with the previous value received.
2. What's the last measured BG value.
3. What's the trend in respect with the previous measurement.

!!!note "Trend arrow"  
    Note that the arrow gives the trend difference with the previous measurement, other CGM applications use an algorithm to give this indication and the result might not match.  
    In case of missing readings, the arrow might indicate fast rise or drop, always correlate with the indication in `1`.

You can customize the information shown in `1` with [Graph Settings](../display/#graph-settings).

You can [customize the trend arrow aspect](#blood-drop-menu) but not behavior.

### Treatments

You can log treatments with the syringe icon.

<img src="../images/UI-Treat.png" style="zoom:75%;" />

Add one or more elements to your treatment.

#### Blood test

It will display in the unit selected in xDrip+.

<img src="../images/UI-Treat1.png" style="zoom:75%;" />

#### Grams of carbs

<img src="../images/UI-Treat2.png" style="zoom:75%;" />

#### Units of insulin

!!!note  
    If you enabled [multiple insulin types](../predictions/#multiple-insulin-types), you should also select the insulin type for this treatment.

<img src="../images/UI-Treat3.png" style="zoom:75%;" />

#### Time

And eventually the time of the treatment (if not now) expressed in 24 hours format, with or without a separator.

<img src="../images/UI-Treat4.png" style="zoom:75%;" />

Treatments are valid when the green check mark appears in the upper right corner. Touch it to confirm the entries.

<img src="../images/UI-Treat6.png" style="zoom:75%;" />

A summary is displayed. Touch the green `+` icon to confirm or red `x` icon to discard.

<img src="../images/UI-Treat5.png" style="zoom:75%;" />

Once done, new symbols will appear on your graph.

Units and carbs show like this:

<img src="../images/UI-Treat7.png" style="zoom:75%;" />

And blood tests like this (note the symbol is square unlike [calibrations](/calibrate/calibrate) that are round):

<img src="../images/UI-Treat8.png" style="zoom:75%;" />

#### Edit and delete

When visible, you can delete treatments like this:

- Touch the treatment, look at the bottom of the screen: touch Add Note or Blood Test.

<img src="../images/UI-Treat9.png" style="zoom:75%;" />

- You can enter a note or touch Delete to delete the entry. This applies to blood tests, carbs and insulin.

<img src="../images/UI-Treat10.png" style="zoom:75%;" />

Note that if you touch a blood test and edit it you can also convert it to a calibration using Calibrate. This is possible if you didn't select `Never use them` in [Advanced Calibrations](../../calibrate/advancedcal).

<img src="../images/UI-Treat11.png" style="zoom:75%;" />

You can use the microphone icon to verbally enter treatments or advanced commands.

A long touch on the microphone icon will allow you to write advanced commands.

### Treatment notes

Independently of treatments you can enter notes.

<img src="../images/UI-Note.png" style="zoom:75%;" />

Enter the comment you want (like slow acting insulin units), or use the microphone icon to speak the note.

<img src="../images/UI-Note1.png" style="zoom:75%;" />

They will be added to the graph like this:

<img src="../images/UI-Note2.png" style="zoom:75%;" />

By touching them you can edit or delete them.

### Undo and Redo

1. Undo will step backwards through treatments simulations, calibrations and notes. After 30 minutes it will hide again.
2. Redo can step forwards through treatments simulations, calibrations and notes. After 30 minutes it will hide again.

<img src="../images/UI-UndoRedo.png" style="zoom:77%;" />

### [Main menu](../hamburger)

Also called hamburger or drawer menu, this is the main menu in which you'll be able to find or add the most common actions you need and also all settings and customizations.

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

### Blood drop menu

With a long touch on the central area between main and three dots menu you can open another menu for customizing the user interface.

<img src="../../images/UImenu.png" style="zoom:75%;" />

##### Source Wizard Button

Shows the button driving you through the data source selection as described [here](../../install/datasource).

<img src="../../install/images/Install12.png" style="zoom:75%;" />

##### Show Time Buttons

Adds a row of four presets for the main graph time range: 24, 12, 6 and 3 hours.  
If you long press a time button you can lock the view to that time period.

<img src="../images/UI-TimeButtons.png" style="zoom:75%;" />

##### Locked time period always used

Sets the last modified display time period as default.

##### Show Chart Preview

Enables or disables the 24 hours small chart in the lower screen area.

<img src="../images/UI-ChartPreview.png" style="zoom:75%;" />

##### Show Collector Status

Shows information messages regarding the collector status below the main graph.

<img src="../images/UI-CollStatus.png" style="zoom:75%;" />

##### Show Sensor Expiry

Displays the remaining time before sensor expiry below the main graph.

<img src="../images/UI-SensorExpiry.png" style="zoom:75%;" />

##### Show Graphical Trend Arrow

Adds an option allowing you to select other arrow styles.

Use the wrench and drop down menu to select them.  
Color arrows include a hue cursor to change color. 

Graphical trend arrows angle depends on the reading difference with the previous value (5 minutes) and not only flat/45/90 degree like the classic arrows.

<img src="../images/UI-GraphicArrow.png" style="zoom:90%;" />

### [Three dots menu](../3dotsmenu)

This menu contains some shortcuts to settings and other unique functions.

<img src="../../images/3dots_menu.png" style="zoom:75%;" />

<img src="../../images/3DM.png" style="zoom:75%;" />

### Widget

If your phone supports widgets, long touch an empty area on your home screen and select widgets.  
Browse the apps until you find xDrip+. 

<img src="../images/Widget1.png" style="zoom:75%;" />

Keep your finger on the widget and drag it to the position you want it to be displayed.

<img src="../images/Widget2.png" style="zoom:75%;" />

You can resize it using the blue dots.

<img src="../images/Widget3.png" style="zoom:75%;" />

And make it the size you like. Then you can customize colors and contents aspect in [display settings](../display).

<img src="../images/Widget4.png" style="zoom:75%;" />

### Screensaver

If your phone supports this feature you can enable xDrip+ as screensaver in Android Settings.

<img src="../images/ScreenSaver1.png" style="zoom:75%;" />

When you put your phone in charge it will display a small graph and the BG value.

<img src="../images/ScreenSaver2.png" style="zoom:75%;" />

</br>

[*Last modified 15/5/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.05.12)
