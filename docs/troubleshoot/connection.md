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

xDrip+ will first try try to find the transmitter. Keep it close to the phone and leave the app on this page.

<img src="../images/M-SS-CG62.png" style="zoom:90%;" />

Once found it will try to connect to it. If xDrip+ doesn't find it, check again the transmitter code, make sure no other device is connected or trying to connect to the transmitter.

<img src="../images/M-SS-CG63.png" style="zoom:81%;" />

!!!note  
    The sensor will comunicate every 5 minutes, the rest of the time it will be sleeping.  
    Last connected should **not** be more than 5 minutes. If it doesn't connect check your [G5](../../install/g5/#verify-your-settings) or [G6](../../install/g6/#verify-your-settings) settings.

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

Proceed [here](../../use/startsensor/#g4-with-bridge-g5-and-g6) to start your sensor.

</br>

[*Last modified 20/6/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.06.20b)