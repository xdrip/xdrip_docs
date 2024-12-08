Android offers many energy savings options, whilst they are helpful to gain more battery autonomy, they can easily target functions that are mandatory for a CGM system.

All settings described below will be available in your phone Android settings, appearance will greatly vary and depend on the phone vendor customizations.

<img src="../images/AS.png" style="zoom:75%;" />

## Battery Saver

Whenever going below a certain battery level, Android will shut down many services and prevent xDrip+ to function normally.  Make sure you always keep a power bank with you to avoid this situation.

During normal phone use, make sure it is **not** enabled.

<img src="../images/AS-BS.png" style="zoom:75%;" />

## Apps battery savings

Each phone app can be customized in terms of battery savings. Whenever experiencing issues, you should carefully review them. This also applies to OOP, WatchDrip+ (if used) and Bluetooth.

!!!warning "Android upgrades and updates"  
    Updates and upgrades might reset these settings to default, always double-check afterwards.

#### Android 10

<img src="../images/AS-Apps-DO.png" style="zoom:75%;" />

#### Android 11 and above

<img src="../images/AS-Apps.png" style="zoom:75%;" />

xDrip+ should run unrestricted.

<img src="../images/AS-Apps-UR.png" style="zoom:75%;" />

### Bluetooth

You will most probably find Bluetooth in System app (three dots menu).  
Some Android phones don't show the Bluetooth app.

<img src="../images/AS-Apps-SA.png" style="zoom:75%;" />

Bluetooth should run unrestricted if xDrip+ connects directly to a sensor.

## Xiaomi MIUI Optimizations

The MIUI Optimizations can have a massive impact (in a negative sense) on the stability of the system and the reliability of xDrip+.
If you experience an increased number of "missed readings" in MIUI 14 (or possibly earlier MIUI versions), you should try to deactivate the MIUI Optimizations.
This setting can be found in the \<Developer Options\>, which are hidden by default. The following describes how to display the \<Developer Options\> and deactivate the MIUI Optimizations afterwards.

### Enable Developer Options

To show the **\<Developer Options\>**, follow these steps:

1. Open the **\<Settings\>** of your smartphone.
2. Select **\<About phone\>**.
3. Click 7 times on **\<MIUI version\>** (first entry of the list).
4. A message **\<Now you are a developer.\>** is shown.
5. Now the entry **\<Settings\>** \-\> **\<Additional settings\>** \-\> **\<Developer options\>** is visible.

### Disable Xiaomi MIUI Optimizations

To disable the MIUI Optimizations, you have to **Enable Developer Options** first. Then follow these steps:

1. Open the **\<Settings\>** of your smartphone.
2. Select **\<Additional settings\>** \-\> **\<Developer options\>**.
3. **Only for MIUI 14:** On MIUI 14, the **\<Turn on MIUI optimisation\>** option is **NOT** visible by default. To see the missing option, scroll down to **\<AUTO-FILL\>** and tap **\<Reset to default values\>** multiple times. Then the required option will appear.
4. **Disable** the option **\<Turn on MIUI optimisation\>**!
5. Restart your smartphone.

</br>

[*Last modified 6/03/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.02.26)