## Use only one device

If you have a receiver it's now time to decide which device you will want to use to start and stop your sensors. Use only one and make sure the other device is either turned off or stored in a shielding bag (or a microwave oven turned OFF). When starting a sensor, do not let the other device interact before warm-up is complete.

</br>

At this point make sure you have a sensor inserted (already started or a new one not started yet) with the transmitter attached. You will not be able to connect to the transmitter if it is not attached to the sensor.

</br>

## Check connection

Reference documentation is [here](https://navid200.github.io/xDrip).

`Menu` / `System Status`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-SS.png" style="zoom:75%;" />

Once on this page (that does not refresh real time) swipe leftwards to display `G5/G6 Status`

<img src="../images/M-SS-CG61.png" style="zoom:90%;" />

<img src="../images/M-SS-CSDex.png" style="zoom:75%;" />

xDrip+ will first try try to find the transmitter. Keep it close to the phone and leave the app on this page.

<img src="../images/M-SS-CG62.png" style="zoom:90%;" />

Connection status showing Authenticated means the device has been found, it doesn't mean it's connected now as the transmitter is only active for a few seconds every 5 minutes.

xDrip+ will try to connect to the transmitter, and for this it will wait for activity from it.  
At this point you will see the scan starting time and the equivalent of time passed since you tried to connect. If the transmitter connects, scanning time shouldn't be more than 5 minutes but initial pairing might take up to 20 minutes.

!!!note  
    The sensor will communicate every 5 minutes, the rest of the time it will be sleeping.  
    Last connected should **not** be more than 5 minutes. If it doesn't connect check your [G5](../../install/g5/#verify-your-settings) or [G6](../../install/g6/#verify-your-settings) settings.

<img src="../images/M-SS-CSG56a.png" style="zoom:75%;" />

For Android versions 10 and above, you will have to allow the pairing request for a new transmitter.

<img src="../images/M-SS-CSG56h.png" style="zoom:75%;" />

Once connected to the transmitter you will see data coming in. Last connected should remain a value less than 5 minutes ago and the brain state deep sleeping is normal. 

<img src="../images/M-SS-CSG56b.png" style="zoom:75%;" />

When running, a typical advanced status will look like this, with last connected value always less than 5 minutes.

<img src="../images/M-SS-CSG56c.png" style="zoom:75%;" />

**Do not consider all error messages contents when your transmitter is not correctly connected.**

You might have connection issues when you can see either one or more of these information:

- Bluetooth link is disconnected
- Last connected a long time ago
- Phone trying to connect
- Items queued

In this last case you want to review your [G5](../../install/G5)/[G6](../../install/G6) parameters and [delete queued items](../connection/#command-queue).

<img src="../images/M-SS-CSG56d.png" style="zoom:75%;" />

Note that preemptive restarts should be disabled for Firefly transmitters. Older transmitters starting by 80 or 81 will support it but make sure to know the impact on the measurement before enabling it.

<img src="../images/M-SS-CSG56e.png" style="zoom:75%;" />

When connected you can get battery information from the transmitter: touch the battery last queried line.  
Battery level is retrieved automatically twice a day. [Monitor](https://navid200.github.io/xDrip/docs/Battery-condition.html) your battery regularly.  
Only voltage B is important for G6, resistance (if visible) has no useful meaning.

<img src="../images/M-SS-CSG56f.png" style="zoom:75%;" />

Newer firmware will require you to update xDrip+, if the latest pre-release still shows the message, please [report](https://github.com/NightscoutFoundation/xDrip/discussions) the version.

<img src="../images/M-SS-CSG56g.png" style="zoom:75%;" />

Authentication errors might be a sign you missed the initial pairing request. You can force it changing the transmitter ID, confirm with `Ok`, then put the correct ID and confirm with `Ok`. A pairing request should appear in the next 5 minutes.

Once found it will try to connect to it. If xDrip+ doesn't find it, check again the transmitter code, make sure no other device is connected or trying to connect to the transmitter.

<img src="../images/M-SS-CG63.png" style="zoom:81%;" />

<img src="../images/M-SS-CG64.png" style="zoom:74%;" />

</br>

## Command queue

Commands are processed by the transmitter one by one when received. Interactions occur every 5 minutes so it might take some time before they get processed. If you still see them pending after 20 minutes you might want to [check connection](#check-connection) and then delete them manually.

<img src="../images/M-SS-CG6Q.png" style="zoom:55%;" />

Do not attempt to send start or stop commands if the queue is not empty.

From the main view, touch the syringe (treatments) icon.

<img src="../../images/Treatments.png" style="zoom:75%;" />

Long touch the microphone icon. 

<img src="../../images/T-Voice.png" style="zoom:75%;" />

Write `clear transmitter queue` then `OK`.

<img src="../../images/T-V-Clear.png" style="zoom:75%;" />

</br>

## Hard reset transmitter

You can reset the internal day counter of your G5 or G6 transmitter. **Only rebatteried transmitters** allow this option.  
Hard reset is necessary only if you use your transmitter in **native mode** after it's expired.

With recent xDrip+ versions **you don't need to be in engineering mode** to perform this operation.  
Make sure you have a good connection and nothing in the queue before resetting the transmitter.

!!!info  
    Hard resetting will not improve a transmitter low battery condition.

Touch the syringe icon on the main graph.

<img src="../../use/images/UI-Treat.png" style="zoom:75%;" />

Long touch the microphone icon. 

<img src="../../images/T-Voice.png" style="zoom:75%;" />

Write `hard reset transmitter` then `OK`.

<img src="../images/M-SS-CSG56i.png" style="zoom:75%;" />

Be patient, il will take up to 20 minutes.

</br>

## Firefly transmitters

!!!note  
    Anubis transmitters can be considered as old G6 transmitters.

Modern G6 transmitters have a very different firmware than the original ones.

You can recognize an **old G6 transmitter** by the fact it's rebatteried.  
Its firmware is version 1.6.5.25 or below.

Old transmitters will allow you to:

- Replace the battery and [reset the transmitter days counter](#hard-reset-transmitter)
- Receive [raw data](../../use/display/#raw-data) from your sensor
- Use the [xDrip+ calibration algorithm](../../calibrate/101/#xdrip-calibration-algorithm)
- [Restart](../../use/g56debug/#restart-sensor) the sensor using xDrip+

**For new transmitters**:

- You cannot replace the battery or reset the transmitter days
- They do not send raw data
- In order to restart the sensor you need to physically extract the transmitter from the sensor

</br>

[*Last modified 25/3/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.03.23)