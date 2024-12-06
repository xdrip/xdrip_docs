These days almost all phones support NFC scanning. If yours does, you can scan your Libre 1, US 14 days, Libre 2/2+ (EU) and Libre Pro sensor with xDrip+ in addition to the vendor supplied LibreLink. Please note, xDrip+ NFC scan **cannot** start a sensor - only LibreLink - (or the reader) can do this. 

## Supported data sources

In order to access the NFC menu, you need to select one of the Libre data sources.

If you will only use xDrip+ to scan the sensor you should choose LibreAlarm.

!!!note  
    If you enable xDrip+ NFC scan support, you should disable any other app that will try to read NFC devices in order to avoid conflicts. This is especially true for the Libre vendor app.

#### Configure NFC

Configure NFC exactly [like this](../../use/NFC).

## Supported sensors

Only Libre 1 and Pro are natively supported by xDrip+ for NFC readings. In order to scan a Libre 14 days US or a Libre 2 Europe you need an [Out of Process Algorithm](../../use/OOP/) installed on the phone.

| - Libre 1 / Pro - | - 14 days US - | - Libre 2/2+ EU - |
| :---------------: | :------------: | :------------: |
|       `Yes`       |     `OOP2`      |     `OOP2`      |

!!!note "Minimum scanning interval"  
    You should wait at least 60 seconds between two NFC scans.

</br>

Continue to [Start Sensor](../../use/startsensor/#libre), remembering that you will need to scan the sensor to get initial readings.

</br>



</br>

[*Last modified 6/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)
