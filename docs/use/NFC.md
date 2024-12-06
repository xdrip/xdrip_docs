This menu will only appear if a [Libre hardware data source](../../install/datasource/#libre) is selected.

!!!xdrip "`NFC Scan Features`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_nfc_grey600_48dp.png" style="width:5%;" />&ensp;NFC Scan features

If your phone has an **ISO 15693 compatible NFC chip**, you can use the xDrip+ NFC feature with Libre 1/14 days/Pro and 2/2+ (EU).

Remember to first enable the NFC feature in Android settings.

!!!xdripitem "Use NFC Feature&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; →`ON`"  
    &ensp;Options for scanning NFC based sensor with the phone headset.

**Enable** `Use NFC Feature`

!!!xdripitem "Scan when not in xDrip+&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;🗹"  
    &ensp;NFC scanning will also work from your app launcher screen.

In order to automatically open xDrip+ upon NFC sensor detection you should **enable** `Scan when not in xDrip+` (recommended). If several apps can scan NFC devices, you will be asked to select the one to use each scan.

!!!xdripitem "Vibrate to indicate scanning status&ensp;&emsp;&emsp;&emsp;🗹" 

!!!xdripitem "Beep when scanning within xDrip+ app&emsp;&emsp;🗹" 

You can decide how xDrip+ will inform you that the scan completed.  Vibration and sound are helpful during (long) NFC scans, you should **enable** both.

When scanning remember that you need to keep the phone in the NFC antenna spot for some seconds to allow a correct scan. Consult your phone manufacturer documentation to find where it is located.

!!!xdripitem "Use faster multi-block reading method&emsp;&emsp;☐" 

`Faster scan` should remain **disabled** to start. You can try to enable it once successful in scanning sensors.

!!!xdripitem "Use any-tag optimized reading method&emsp;&emsp;🗹" 

If you have trouble with your phone NFC, try to **enable** `Any tag` method.

## Smooth libre 3 data when using xxx method

!!!note  
    Smoothing will apply to any external data source app using the `Libre2 (patched app)` data source.

The original implementation included a 25 minutes smoothing algorithm to remove noise and make DIY close looping safer with Libre sensors. You can change the smoothing period to 10, 15 or 25 minutes.

!!!xdripitem "Smooth Libre 3 data when using xxx method"  
    &ensp;Number of minutes to take in consideration when using librex data

Smoothing adds a delay in xDrip+ BG from raw data. The delay is about half the smoothing period. Set the delay accordingly to the sensor behavior for your safety. If you don't use a DIY closed loop system with xDrip+ providing glucose values, set it to 10 minutes.

<img src="../../install/images/M-S-HDS-NFC8.png" style="zoom:75%;" />

</br>

[*Last modified 6/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)