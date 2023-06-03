These days almost all phones support NFC scanning. If yours does, you can scan your Libre sensor with xdrip+ in addition to the vendor supplied LibreLink. Please note, xDrip+ NFC scan **cannot** start a sensor - only LibreLink - (or the reader) can do this. 

## Supported data sources

In order to access the NFC menu, you need to select one of the Libre data sources.

If you will only use xDrip+ to scan the sensor you should choose LibreAlarm.

!!!note  
    If you enable xDrip+ NFC scan support, you should disable any other app that will try to read NFC devices in order to avoid conflicts. This is especially true for the Libre vendor app.

## Enabling NFC

`Menu` / `Settings` / `NFC Scan Features`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-S.png" style="zoom:75%;" />

<img src="../images/M-S-HDS-NFC.png" style="zoom:75%;" />

Enable `Use NFC Feature`

<img src="../images/M-S-HDS-NFC2.png" style="zoom:75%;" />

In order to automatically open xDrip+ upon NFC sensor detection you should enable this (recommended)

<img src="../images/M-S-HDS-NFC3.png" style="zoom:75%;" />

You can decide how xDrip+ will inform you that the scan completed. When scanning remember that you need to keep the phone in the right NFC antenna spot for some seconds to allow a correct scan.

<img src="../images/M-S-HDS-NFC4.png" style="zoom:75%;" />

Faster scan should remain disabled.

<img src="../images/M-S-HDS-NFC5.png" style="zoom:75%;" />

If you have trouble with your phone NFC, try to enable Any tag method.

<img src="../images/M-S-HDS-NFC5.png" style="zoom:75%;" />

## Supported sensors

Only Libre 1 is natively supported by xDrip+ for NFC readings. In order to scan a Libre 14 days US or a Libre 2 Europe you need an [Out of Process Algorithm](../../use/OOP/) installed on the phone.

| - Libre 1 / Pro - | - 14 days US - | - Libre 2 EU - |
| :---------------: | :------------: | :------------: |
|       `Yes`       |     `OOP2`      |     `OOP2`      |

!!!note "Minimum scanning interval"  
    You should wait at least 60 seconds between two NFC scans.

</br>

Continue to [Start Sensor](../../use/startsensor/#libre), remembering that you will need to scan the sensor to get initial readings.

</br>

[*Last modified 2/2/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.02.02)
