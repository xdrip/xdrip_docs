If your phone has an NFC reader you can use it to scan your Libre sensor. Compatible phones will allow you to install LibreLink (if you can find it in your region Google Play store). There were doubts on some smartphones "breaking" the sensor but recent models should be safe. If your phone is not compatible with the vendor app, you should try the feature on a sensor close to expiration date.

<img src="../images/M-S-HDS-NFC1.png" style="zoom:87%;" />

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

The options below should remain disabled.

<img src="../images/M-S-HDS-NFC5.png" style="zoom:75%;" />

## Supported sensors

Only Libre 1 is natively supported by xDrip+ for NFC readings. In order to scan a Libre 14 days US or a Libre 2 Europe you need an Out of Process Algorithm installed on the phone.

| - Libre 1 - | - 14 days US - | - Libre 2 EU - |
| :---------: | :------------: | :------------: |
|    `Yes`    |     `OOP`      |     `OOP`      |

</br>

[*Last modified 28/4/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)
