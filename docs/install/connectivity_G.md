## Use only one device

If you have a receiver or normally use the vendor app, it's now time to decide which device you will want to use to start and stop your sensors. Use only one and make sure the other devices are either turned off or stored in a shielding bag (or a microwave oven turned OFF). When starting a sensor, do not let the receiver interact before warm-up is complete and you have readings in xDrip+.

</br>

At this point make sure you have a sensor inserted (already started or a new one not started yet) with the transmitter attached. You will not be able to connect to the transmitter if it is not attached to the sensor.

</br>

## Check connection

Reference documentation [here](https://navid200.github.io/xDrip/docs/Proper-connectivity.html).

`Menu` / `System Status`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-SS.png" style="zoom:75%;" />

Once on this page (that does not refresh real time) swipe leftwards to display `G5/G6 Status`

<img src="../images/M-SS-CG61.png" style="zoom:75%;" />

xDrip+ will first try try to find the transmitter. Keep it close to the phone and leave the app on this page.

<img src="../images/M-SS-CG62.png" style="zoom:75%;" />

Once found it will try to connect to it. If xDrip+ doesn't find it, check again the transmitter code.

<img src="../images/M-SS-CG63.png" style="zoom:70%;" />

!!!note  
    The sensor will comunicate every 5 minutes, the rest of the time it will be sleeping.  
    Last connected should **not** be more than 5 minutes. If it doesn't connect check your [settings](../g6).

<img src="../images/M-SS-CG64.png" style="zoom:65%;" />

</br>

## Command queue

Commands are processed by the transmitter one by one when received. Interactions occur every 5 minutes so it might take some time before they get processed. If you still see them pending after 20 minutes you might want to check connectivity and then delete them manually.

<img src="../images/M-SS-CG6Q.png" style="zoom:60%;" />

Do not attempt to send start or stop commands if the queue is not empty.

From the main view, touch the syringe (treatments) icon.

<img src="../../images/Treatments.png" style="zoom:75%;" />

Long touch the microphone icon. 

<img src="../../images/T-Voice.png" style="zoom:75%;" />

Write `clear transmitter queue` then `OK`.

<img src="../../images/T-V-Clear.png" style="zoom:75%;" />

</br>

Proceed [here](../../sensor/G5G6sensor) to start your sensor.
