# Start sensor

xDrip+ is not able to start a Libre sensor, neither is it to stop one (actually you can't stop this sensor: if it doesn't fail it will run it's useful lifetime and stop by itself after 14 days and 12 hours).

In order to start your sensor you need to use the vendor reader or app, some other third party apps like Glimp-S and eDropletNFC can start the Libre sensor.

xDrip+ sensor start is only used to track lifetime and make sure calibrations are updated. This operation is necessary and recommended each time you replace your sensor.

</br>

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-StaS.png" style="zoom:75%;" />

Confirm `START SENSOR`

<img src="../images/M-StaSC.png" style="zoom:75%;" />

If you inserted the sensor today (i.e. not started or recently started), answer `YES, TODAY`

<img src="../images/M-StaSToday.png" style="zoom:75%;" />

If you answered today select the hour you physically started the sensor dragging the blue pointer to the correct time. With 12 hours display, tap `am` or`pm`. With 24 hours display drop the correct hour either on the inner or outer ring for the correct hour. Tap `OK`.

<img src="../images/M-StaSHour.png" style="zoom:75%;" />

Drag the minutes blue pointer to the correct time and tap `OK`.

<img src="../images/M-StaSMin.png" style="zoom:75%;" />

The newly started sensor will continue its warm-up if started from less than one hour.

!!!warning  
    **Even if xDrip+ will attempt reading a sensor during its warm-up phase, values can range from unreliable to inconsistent and should not be used.**

<img src="../images/LibreWarmup.png" style="zoom:70%;" />

If you're using an already started sensor you will have a calibration request within 15 minutes. If you see a purple arrow you might have made a mistake in the date and time the sensor was started as BG data is available but won't display during the 1 hour warm-up.

<img src="../images/PurpleArrow.png" style="zoom:70%;" />

</br>

xDrip+ will now wait for readings and update the progress. Stay on this screen. Every reading is done 5 minutes apart so it should take less than 20 minutes.

<img src="../images/M-SS-InitialR.png" style="zoom:65%;" />

If the data source shows LimiTTer and you're not using an actual [LimiTTer](https://github.com/JoernL/LimiTTer), your bridge device is not connected correctly.

<img src="../images/M-SS-LimiTTer.png" style="zoom:70%;" />

The indication ***No data received yet*** will change to ***Need 3 recent readings***. If no data is received, [check your parameters](../../install/libreBT/#bridge-settings).

<img src="../images/M-SS-InitialR2.png" style="zoom:72%;" />

When enough readings are received, the calibration request will display.

If your BG is within normal range (recommended in the lower normal range for a new sensor) and has been stable for the last 10 minutes, with no carbs not insulin active, you can calibrate.

If your BG is quickly varying or not within normal range, it is not recommended to calibrate now. 

<img src="../images/M-SS-Calibrate.png" style="zoom:70%;" />

Two readings are required from legacy G4 receiver, you can use only one if you're sure it's valid. Just put twice the same value.

You BG should start displaying on the main graph.

