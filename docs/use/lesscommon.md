!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;&ensp;Less Common settings

More xDrip+ settings are available in less common settings.  
If you can't find the setting you're looking for, keep in mind you can use the search lens from the main [settings](../settings) menu.

### Extra Status Line

Top left of your main graph you can see the standard status line.  
This menu allows you to add extra information in this area.

!!!xdripitem "Extra Status Line"  
    &ensp;Options for the extra line

You need to enable the extra status line to add extra information.

!!!xdripitem "Extra Status Line <span class='symbol'><img src="../../images/OFF.png" style="zoom:75%;" /></span>"  
    &ensp;Additional text status

You can make selected statistics to be calculated on the last 24 hours. By default they're starting at midnight.

!!!xdripitem "Sliding Window <span class='symbol'><img src="../../images/OFF.png" style="zoom:75%;" /></span>"  
    &ensp;Use last 24 hours instead of time since midnight for statistics

There is a long list of available extra information you can display.  
Only select those you really need to see every 5 minutes.

!!!xdripitem "Average <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Today's average value 

!!!xdripitem "A1c DCCT <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;A1c estimation in DCCT format (%) 

!!!xdripitem "A1c IFCC <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;A1c estimation in IFCC format (mmol/mol)

!!!xdripitem "In percentage <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Percentage of values in range

!!!xdripitem "High percentage <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Percentage of values above range

!!!xdripitem "Low percentage <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Percentage of values below range

!!!xdripitem "Standard deviation <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show standard deviation of values

!!!xdripitem "Total carbohydrate <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show treatment carbohydrate total

!!!xdripitem "Total insulin <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show treatment insulin total

!!!xdripitem "External status <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Display status from other apps like AAPS

!!!xdripitem "Pump status <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Display pump status information if available

!!!xdripitem "Carb/Insulin ratio <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show treatment Carb/Insulin ratio

!!!xdripitem "Packet capture percentage <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show percentage of sensor readings received 

!!!xdripitem "Realtime packet capture percentage <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Percentage of sensor readings received in realtime (non-backfilled). G5 native mode only.

!!!xdripitem "Accuracy evaluation <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show accuracy evaluation from last 3 days

!!!xdripitem "Time <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;The current time

!!!xdripitem "Calibration data (long) <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show slope and intercept in long form

!!!xdripitem "Calibration data (short) <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show slope and intercept in short form

!!!xdripitem "Calibration plugin <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show slope and glucose data from the active plugin

You can also add this extra information on your [widget](../mainUI/#widget).

!!!xdripitem "Show on widget <span class='symbol'><img src="../../images/OFF.png" style="zoom:75%;" /></span>"  
    &ensp;Also show the extra status line on the widget

### [Advanced Calibration](../../calibrate/advancedcal)

See the dedicated section.

!!!xdripitem "Advanced calibration"  
    &ensp;Extra options relating to calibrations

### [Bluetooth Settings](../bluetooth)

See the dedicated section.

!!!xdripitem "Bluetooth settings"  
    &ensp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_bluetooth_settings_grey600_48dp.png" style="width:5%;" />&ensp;Advanced Bluetooth settings

### blueReader Settings

Settings for the [pioneer](https://www.startnext.com/en/bluereader/wall) Libre bridge device from Sandra.

!!!xdripitem "blueReader settings"  
    &ensp;Advanced blueReader settings

### Advanced Settings for Libre 2

Show additional information for Libre 2 sensors

!!!xdripitem "Advanced settings for Libre 2"

Display raw values on the [main graph](../display/#graph-settings)

!!!xdripitem "Show raw values in graph <span class='symbol'><img src="../../images/OFF.png" style="zoom:75%;" /></span>"  
    &ensp;Switch on to show the raw values on the graph

<img src="../images/M-S-DS6f3.png" style="zoom:75%;" />

Show more information in status

!!!xdripitem "Show sensor infos in status <span class='symbol'><img src="../../images/OFF.png" style="zoom:75%;" /></span>"  
    &ensp;Switch to on to show additional sensor information in status for Libre 2 sensors

### Aggressive Service Restarts

Enabling this provokes a [collector restart](../../troubleshoot/systemstatus/#restart-collector-forget-device) when detecting missing data. This can be useful if you have connection problems.

!!!xdripitem "Aggressive service restarts <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Repeatedly restart the collection service at any hint of missing data. Enable only if you are getting data loss.

### Interpret Raw Values

Display data when not available on the Dexcom receiver.

!!!xdripitem "Interpret raw values <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;If using share, xDrip+ will display values when they are normally hidden on the receiver

### Extra Logging Settings

!!!xdripitem "Extra Logging Settings" 

These options are not used anymore.

!!!xdripitem "Enable remote logging <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>" 

!!!xdripitem "Store logs for troubleshooting <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  

Adding extra tags is useful for debugging as it will add specific traces in the log.

!!!xdripitem "Extra tags for logging"  

You need to know what you want to debug and set the correct level. Make sure to put valid tags to avoid xDrip+ crashing.

<img src="../images/M-S-LCS9c.png" style="zoom:75%;" />

### Show Data tables

This feature is extremely useful if you calibrate using the xDrip+ algorithm (non native).  
It will add two entries in the drawer menu for visualization of calibration and data tables.

!!!xdripitem "Show Data tables <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Show calibration and BG datatables in the app drawer

*Note: Calibration graph will not show in native mode.*

### Display Bridge Battery

You can display your Bluetooth bridge battery level on the main view. This also applies to Libre Bluetooth bridges.  
In follower mode it will most probably display the master phone battery level rather than the bride itself.

!!!xdripitem "Display Bridge Battery <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Choose to display the bridge battery level

<img src="../images/M-S-LCS11a.png" style="zoom:75%;" />

### Disable Battery Warning

Disable battery warnings for bridges

!!!xdripitem "Disable Battery Warning <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Disable the warning for low transmitter battery state on the home screen (only relevant to DIY receivers)

### Database automatic maintenance

Save Database Daily will actually export the database file every day before doing cleanup. This will use a large amount of your device memory and is not recommended.

!!!xdripitem "Save Database Daily <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Allows the daily intent service to save the database before purging

#### Glucose retention

Glucose retention will automatically delete data older than the number of days selected.  
Zero means don't delete anything (recommended). You can use 90 days if you use a cloud backup like Nightscout, so that you will still have all statistics available in xDrip+.

!!!xdripitem "Glucose retention"  
    &ensp;Erase data older than this many days. 0 = don't erase anything.

### [Other Miscellaneous Options](../misc)

See the dedicated section.

!!!xdripitem "Other misc. options"

### Sensor Location

Not used anymore.

!!!xdripitem "Store sensor location to help algorithm impro. <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"

</br>

[*Last modified 15/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)
