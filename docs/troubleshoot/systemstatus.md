System status provides internal information on xDrip+ collector state (either from a sensor or as a follower) as well as sharing, followers and smartwatch connected directly.

### Classic Status Page

This page shows information about currently installed version, and previously installed version.  
For a new installation the downgradable version will show as 1603091400 by default.

<img src="../../images/M-SS-Ver.png" style="zoom:75%;" />

Version information allows you to quickly [find the matching release or pre-release](https://github.com/NightscoutFoundation/xDrip/releases). Before the version date you'll see the build version.

Any version name that shows additional information, like debug, dev, a smartwatch name, carelink, is a [private release](../../install/download/#private-versions) of xDrip+ and might not contain all the latest functions of the released app (but probably some extra).

On this page you'll find the data source type (the one you selected to receive your BG values) and the sensor start date (as entered as sensor start date and time, or automatically detected, depending on the sensor type).

<img src="../images/M-SS-CS1.png" style="zoom:75%;" />

In the case of a physical sensor, after the data source type, you'll see the name of the actual Bluetooth device connected to xDrip+. Keep in mind this page doesn't update automatically: you need to touch the rounded arrows to refresh it.

<img src="../images/M-SS-CS2.png" style="zoom:75%;" />

Most data sources will have an advanced status tab. Swipe your finger on the screen towards the left to display it.

#### Restart collector - Forget device

<img src="../images/M-SS-CSRCFD.png" style="zoom:75%;" />

Restart collector will restart xDrip+ internal collector mechanism. The effect depends on the data source.

Forget device will only have effect when xDrip+ is connected through Bluetooth to a device.  
The device will be disconnected and you will need to scan Bluetooth from the main menu to recover the connection.

### Advanced status page

General information:  
Buggy Samsung is not an error, but just the fact xDrip+ is [correcting](https://github.com/NightscoutFoundation/xDrip/issues/435) a non-compliance of Samsung devices.

<img src="../images/M-SS-CSBSsg.png" style="zoom:75%;" />

Slowest wake-up gives an information on when xDrip+ received data against the expected time. Seconds are acceptable but minutes might be the sign of a connectivity issue.

<img src="../images/M-SS-CSWU.png" style="zoom:75%;" />

#### G5 and G6 

Connection status showing Authenticated means the device has been found, it doesn't mean it's connected now as the transmitter is only active for a few seconds every 5 minutes.

<img src="../images/M-SS-CSDex.png" style="zoom:75%;" />

When you first start a G5 or G6 sensor, xDrip+ will try to connect to the transmitter, and for this it will wait for activity from it.  
At this point you will see the scan starting time and the equivalent of time passed since you tried to connect. If the transmitter connects, scanning time shouldn't be more than 5 minutes but initial pairing might take up to 20 minutes.

<img src="../images/M-SS-CSG56a.png" style="zoom:75%;" />

Once connected to the transmitter you will see data coming in. Last connected should remain a value less than 5 minutes ago and the brain state deep sleeping is normal. 

<img src="../images/M-SS-CSG56b.png" style="zoom:75%;" />

Once running, a typical advanced status will look like this, with last connected value always less than 5 minutes.

<img src="../images/M-SS-CSG56c.png" style="zoom:75%;" />

**Do not consider all error messages contents when your transmitter is not correctly connected.**

You might have connection issues when you can see either one or more of these information:

- Bluetooth link is disconnected
- Last connected a long time ago
- Phone trying to connect
- Items queued

In this case you want to review your [G5](../../install/G5)/[G6](../../install/G6) parameters and delete queued items.

<img src="../images/M-SS-CSG56d.png" style="zoom:75%;" />

Note that preemptive restarts should be disabled for Firefly transmitters. Older transmitters starting by 80 or 81 will support it but make sure to know the impact on the measurement before enabling it.

<img src="../images/M-SS-CSG56e.png" style="zoom:75%;" />

When connected you can get battery information from the transmitter: touch the battery last queried line.  
Battery level is retrieved automatically twice a day. [Monitor](https://navid200.github.io/xDrip/docs/Battery-condition.html) your battery regularly.  
Only voltage B is important for G6, resistance (if visible) has no useful meaning.

<img src="../images/M-SS-CSG56f.png" style="zoom:75%;" />

Newer firmware will require you to update xDrip+, if the latest pre-release still shows the message, please [report](https://github.com/NightscoutFoundation/xDrip/discussions) the version.

<img src="../images/M-SS-CSG56g.png" style="zoom:75%;" />

#### Libre Bluetooth

All devices report as LimiTTer until connected, only Libre 2 direct connection and some older bridges (Transmitter_T for example) will remain indicated as LimiTTer (and obviously [LimiTTer](https://github.com/JoernL/LimiTTer)s).

<img src="../images/M-SS-CSL2.png" style="zoom:75%;" />

Swipe the screen towards the left to display the BT Device page.

Phone service state gives the last time data was received from the bridge, it should be equal or less than 5 minutes.  
Next wake up will count down to the next expected data to be received, then restart at 5 minutes.

Bluetooth should always be connected. If it isn't, check your [Bluetooth settings](../../install/libreBT/#bridge-settings) and [Restart collector](#restart-collector-forget-device). If device still isn't visible try to [Scan Bluetooth](../../install/libreBT/#connect-bluetooth-bridge) to find it.

<img src="../images/M-SS-BTLBa.png" style="zoom:75%;" />

You will also see various information on the bridge like Mac address, hardware and firmware version. Note that battery level is not available on Blucon bridges and 100% will only mean that it's still usable. 

<img src="../images/M-SS-BTLBb.png" style="zoom:75%;" />

It is strongly recommended to upgrade your device firmware to the latest available version.

**Bluetooth pairing should be disabled, if you changed this by mistake: touch the line to return to this state:**

<img src="../images/M-SS-BTLBc.png" style="zoom:75%;" />

No sensor found errors are usually due to bad positioning of the bridge over the sensor. Some bridges do not have any tolerance in respect with distance and angle to the sensor antenna area. It might also be due to an internal bridge issue, firmware issue, ...  
Since this is a persistent message, check the time indicated is recent. If it is permamently 5 minutes ago, the sensor is not seen.

<img src="../images/M-SS-BTLBd.png" style="zoom:75%;" />

#### xDrip+ Sync Follower

xDrip+ follower is really simple to setup. If you have issues with it, most of the time it's either a network connection issue or Google Play services issues.

<img src="../images/M-SS-xF.png" style="zoom:75%;" />

Followers will add-up in the list when identified, if you remove a follower it might take some time before it's actually removed from the list.

For initial setup problems check [here](../../install/xdripfollower/).

#### Nightscout Follower

<img src="../images/M-SS-NF.png" style="zoom:75%;" />