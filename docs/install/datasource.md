Until a blood glucose data source is selected, xDrip+ will show the  data source wizard. You can enable or disable it using the [blood drop menu](../../use/mainUI/#blood-drop-menu), then Source wizard button.

<img src="../images/Install08.png" style="zoom:75%;" />

Scroll down until you see your sensor or use case.

## G6, G7, 1, 1+ and Stelo

If you connect xDrip+ directly to your sensor ([G6, G7, 1, 1+ and Stelo](../g6)), you **will not be able** to use the vendor app, upload to Clarity (you can use [Nightscout](https://nightscout.github.io/) or [Tidepool](../../use/cloud/#tidepool)). You might be able to use sharing through [share](../../use/cloud/#dexcom-share-server-upload) servers but it needs to be setup with the vendor apps first.

<img src="../images/DS-DxDrip.png" style="zoom:50%;" />

If you use the vendor apps (G6, G7, 1+), you can connect xDrip+ as a [Share follower](../dexshare) as long as a follower has been setup with the vendor apps.

<img src="../images/DS-DShare.png" style="zoom:50%;" />

When using [BYODA](../byod) (G6 only) if you've enabled Broadcast to xDrip+ you don't need a network connection to have data in xDrip+. Use the 640G/Eversense data source

<img src="../images/DS-BYOD.png" style="zoom:45%;" />

You can add xDrip+ to your current setup and select [Companion app](../companion) to have xDrip+ read BG from the vendor app notifications (G6, G7, 1, 1+, Stelo). Note Stelo gives readings every 15 minutes with the vendor app.

<img src="../images/DS-DComp.png" style="zoom:50%;" />

And this is also possible if you use [CamAPS](../companion), still using the Companion app data source

<img src="../images/DS-GCAPS.png" style="zoom:50%;" />

## Libre

xDrip+ connects directly to Libre 2/2+ EU, you can use Libre 1 and 14 days US with a bridge device. Other Libre 2 and 3 sensors are not directly supported.

You can connect Libre 2/2+ EU to xDrip+, adding [OOP2](../../use/OOP/). You **cannot** use the vendor app for alarms (just NFC scans) and upload data to the vendor servers (use [Nightscout](https://nightscout.github.io/) or [Tidepool](../../use/cloud/#tidepool)). Use the [Libre Bluetooth](../libreBT) data source.

<img src="../images/DS-L2EU.png" style="zoom:50%;" />

Since Libre 1 don't have bluetooth, you need to add a [bridge](../libreBT) device. Use the [Libre Bluetooth](../libreBT) data source.  
Some of these bridges also work with Libre 2/2+ EU. Check your sensor doesn't require an [OOP](../../use/OOP/).

<img src="../images/DS-LBT.png" style="zoom:50%;" />

The [patched app](../libre2patch) can send data to xDrip+, note it's now a very old app and it probably won't work on recent phones.

<img src="../images/DS-L2Patch.png" style="zoom:50%;" />

For non-supported sensors (Libre 2/2+ non-EU and Libre 3/3+) you can also use Diabox or Juggluco, then [broadcast](../libre2patch) data to xDrip+ that will receive data from the [Libre 2 patched](../libre2patch) data source (**not** the patched app itself).

<img src="../images/DS-LOther.png" style="zoom:50%;" />

You can follow a Libre 2/2+ CGM or a Libre 3/3+ with xDrip+ with the [Web follower](../webfollower) data source.

<img src="../images/DS-L3Web.png" style="zoom:50%;" />

## Guardian and Minimed

With a [640G/670G pump](../640_670) you need to get BG data from the pump using a glucometer connected to your phone with an OTG cable.

<img src="../images/DS-M6xx.png" style="zoom:50%;" />

You can add xDrip+ to your current setup and select [Companion app](../companion) to have xDrip+ read BG from the vendor app notifications.

<img src="../images/DS-MComp.png" style="zoom:50%;" />

You can follow sensor data when shared through [Carelink](../carelinkfollow), but this feature might be broken frequently by the vendor.

<img src="../images/DS-MFoll.png" style="zoom:50%;" />

## [Aidex](../aidex)

You can receive data from the vendor app into xDrip+.

You can add xDrip+ to your current setup and select [Companion app](../companion) to have xDrip+ read BG from the vendor app notifications.

## Sibionics

The [patched app](https://t.me/s/kubarev_modz) will allow you to use xDrip+ with the [640G/Eversense](../640_670) data source.

## CareSens Air

You can receive data from the vendor app into xDrip+ with the [CareSens Air](../caresens) (or 640G/Eversense) data source.

<img src="../images/DS-CareSens.png" style="zoom:50%;" />

</br>

## Bluetooth connection to a sensor or a bridge

When connecting xDrip+ directly to a sensor, it will take care of the Bluetooth connection or to the Bluetooth device sending data from your device (called a bridge). 

!!!warning    
    Do **NOT** try to use Android Settings -> Connections -> Bluetooth to connect! 

<img src="../images/Install26.png" style="zoom:100%;" />

If your bridge paired to Android, unpair it before continuing.

<img src="../images/Install27.png" style="zoom:100%;" />

!!!warning "One device at a time"  
    Sensors and bridges can only connect to one smartphone (or tablet) at a time, and only to one app at a time.  
    You should uninstall the vendor app in order to connect xDrip+ to your sensor or bridge.  
    If another device is connect to your sensor or bridge you should turn it off or disable the other app before trying to connect with xDrip+.  
    **You cannot connect to two phones or applications. With an exception for Dex G6/G7/1 and 1+: the second device can only be a receiver/connected pump or a BlueJay watch.**

</br>

You should now see the the data source selection wizard.

<img src="../images/Install08.png" style="zoom:75%;" />

If you don't, touching this button will display the wizard.

<img src="../images/Install12.png" style="zoom:75%;" />

If the button is not visible you can display it using a long touch on the xDrip+ icon and enabling the `Source Wizard Button`.

<img src="../../images/UImenu.png" style="zoom:75%;" />

</br>

## Sensor selection

Unused and obsolete sensors have been removed from this documentation.

### The following sensors are supported directly by xDrip+:

- G4 (with bridge) or G4 Platinum receiver    
  <img src="../images/Install28.png" style="zoom:54%;" />    <img src="../images/Install29.png" style="zoom:50%;" />
- G5  
  <img src="../images/Install28.png" style="zoom:54%;" />    <img src="../images/Install30.png" style="zoom:49%;" />
- [G6, G7, 1 and 1+](../g6)  
  <img src="../images/Install28.png" style="zoom:54%;" />    <img src="../images/Install31.png" style="zoom:50%;" />
- [Libre (with bridge)](../libreBT)  
  <img src="../images/Install32.png" style="zoom:54%;" />    <img src="../images/Install33.png" style="zoom:50%;" />
- Libre with patched SWR50 smartwatch  
  <img src="../images/Install32.png" style="zoom:54%;" />    <img src="../images/Install34.png" style="zoom:51%;" />
- [Libre 2 (only EU)](../libre2)  
  <img src="../images/Install32.png" style="zoom:54%;" />    <img src="../images/Install33.png" style="zoom:50%;" />
- [Medtrum A6/S7](../medtrum)  
  <img src="../images/Install36.png" style="zoom:54%;" />    <img src="../images/Install37.png" style="zoom:53%;" />
- [CareSens Air](../caresens)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install48.png" style="zoom:54%;" />

### The following sensors and features are supported with a companion app:

- [Libre 2 (only EU)](../libre2patch)  
  <img src="../images/Install32.png" style="zoom:51%;" />    <img src="../images/Install35.png" style="zoom:53%;" />
- [Eversense](../eversense)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install41.png" style="zoom:53%;" />
- [640G/670G pumps](../640_670)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install40.png" style="zoom:53%;" />
- [Build your own app (BYODA)](../byod) for G6 sensors  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install40.png" style="zoom:53%;" />
- [Aidex](../aidex)  
  See below GlucoRx/Aidex.
- [Companion app](../companion) for G6, G7, 1, 1+, CamAPS and Eversense  
  See below.

</br>

## Follower mode

- [xDrip+ Sync](../xdripfollower) (requires Google Play Services)
- [Nightscout](../nightscoutfollower)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install38.png" style="zoom:53%;" />
- [Dex Share](../dexshare)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install39.png" style="zoom:53%;" />
- [Libre Web Follower](../webfollower)  
  See below.
- [CareLink Follower](../carelinkfollow)  
  See below.

</br>

## Changing data source

You can select another data source without using the wizard from the settings menu:

!!!xdrip "`Hardware data source`"  
    <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
    &ensp;Settings  
    &emsp;Hardware Data Source

G4 (with bridge) or G4 Platinum receiver  

<img src="../images/M-S-HDSlistA.png" style="zoom:75%;" />

[G5, G6, 1, 1+ and G7](../g6) 

<img src="../images/M-S-HDSlistB.png" style="zoom:75%;" />

[Libre (with bridge)](../libreBT) 

<img src="../images/M-S-HDSlistC.png" style="zoom:75%;" />

[Libre whole house](https://github.com/tzachi-dar/LibreAllHouse)

<img src="../images/M-S-HDSlistD.png" style="zoom:75%;" />

[xDrip+ Sync](../xdripfollower)

<img src="../images/M-S-HDSlistE.png" style="zoom:75%;" />

Libre with patched SWR50 smartwatch 

<img src="../images/M-S-HDSlistF.png" style="zoom:75%;" />

[Libre 2 (only EU), Diabox or Juggluco](../libre2patch)

<img src="../images/M-S-HDSlistG.png" style="zoom:75%;" />

[640G/670G pumps](../640_670), [Eversense](../eversense) and [Build your own app (BYODA)](../byod)

<img src="../images/M-S-HDSlistH.png" style="zoom:75%;" />

[Medtrum A6/S7](../medtrum) 

<img src="../images/M-S-HDSlistI.png" style="zoom:75%;" />

[Nightscout](../nightscoutfollower) 

<img src="../images/M-S-HDSlistJ.png" style="zoom:75%;" />

[Dex Share](../dexshare) 

<img src="../images/M-S-HDSlistK.png" style="zoom:75%;" />

[Companion app](../companion) for G6, G7, One and CamAPS

<img src="../images/M-S-HDSlistN.png" style="zoom:75%;" />

[GlucoRx/Aidex](../aidex)

<img src="../images/M-S-HDSlistP.png" style="zoom:75%;" />

[Web Follower](../webfollower) for Libre 2 CGM and Libre 3

<img src="../images/M-S-HDSlistO.png" style="zoom:75%;" />

[CareLink](../carelinkfollow)

<img src="../images/M-S-HDSlistM.png" style="zoom:75%;" />

##### Disable Collection

If you want to disable xDrip+.

<img src="../images/M-S-HDSlistL.png" style="zoom:75%;" />

</br>

[*Last modified 5/9/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.09.04)
