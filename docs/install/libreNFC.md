These days almost all phones support NFC scanning. If yours does, you can scan your Libre 1, US 14 days, Libre 2 (EU) and Libre Pro sensor with xDrip+ in addition to the vendor supplied LibreLink. Please note, xDrip+ NFC scan **cannot** start a sensor - only LibreLink - (or the reader) can do this. 

## Supported data sources

In order to access the NFC menu, you need to select one of the Libre data sources.

If you will only use xDrip+ to scan the sensor you should choose LibreAlarm.

!!!note  
    If you enable xDrip+ NFC scan support, you should disable any other app that will try to read NFC devices in order to avoid conflicts. This is especially true for the Libre vendor app.

## Enabling NFC

!!!xdrip "`NFC Scan Features`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;NFC Scan Features  

!!!xdripitem "Use NFC Feature&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Options for scanning NFC based sensor with the phone headset.

**Enable** `Use NFC Feature`

!!!xdripitem "Scan when not in xDrip+&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;NFC scanning will also work from your app launcher screen.

In order to automatically open xDrip+ upon NFC sensor detection you should **enable** `Scan when not in xDrip+` (recommended). If several apps can scan NFC devices, you will be asked to select the one to use each scan.

!!!xdripitem "Vibrate to indicate scanning status&ensp;&emsp;&emsp;&emsp;🗹" 

!!!xdripitem "Beep when scanning within xDrip+ app&emsp;&emsp;🗹" 

You can decide how xDrip+ will inform you that the scan completed.  Vibration and sound are helpful during (long) NFC scans, you should **enable** both.

When scanning remember that you need to keep the phone in the right NFC antenna spot for some seconds to allow a correct scan.

!!!xdripitem "Use faster multi-block reading method&emsp;&emsp;☐" 

`Faster scan` should remain **disabled** to start. You can try to enable it once successful in scanning sensors.

!!!xdripitem "Use any-tag optimized reading method&emsp;&emsp;🗹" 

If you have trouble with your phone NFC, try to **enable** `Any tag` method.

## Supported sensors

Only Libre 1 and Pro are natively supported by xDrip+ for NFC readings. In order to scan a Libre 14 days US or a Libre 2 Europe you need an [Out of Process Algorithm](../../use/OOP/) installed on the phone.

| - Libre 1 / Pro - | - 14 days US - | - Libre 2 EU - |
| :---------------: | :------------: | :------------: |
|       `Yes`       |     `OOP2`      |     `OOP2`      |

!!!note "Minimum scanning interval"  
    You should wait at least 60 seconds between two NFC scans.

</br>

Continue to [Start Sensor](../../use/startsensor/#libre), remembering that you will need to scan the sensor to get initial readings.

</br>

[*Last modified 3/8/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.08.02)
