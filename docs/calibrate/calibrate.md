!!!warning "Calibration"  
    Never blindly trust a glucose sensor: regularly verify the readings with a blood test.  
    A flat line (same number) is **never** a good sign.

### General considerations

Calibration is key to CGM mesurement accuracy. Always use a trusted glucometer and make sure you put yourself in the best conditions to have the most accurate blood reading when calibrating.

Some of the most important prerequisites are:

1. **Stable BG.** Never calibrate when BG is rising or falling rapidly.
2. **In range (important for Libre initial calibration).** Try to perform your calibrations when BG is within normal range (80-180 mg/dl or 5-10 mmol/l).
3. **Don't overcalibrate.** Better few accurate than too many: you will most probably confuse xDrip+. For G4, G5 and G6 use the vendor recommendations.

### Native and xDrip+ algorithms

xDrip+ can provide its own calibrations algorithms for sensors sending raw data.

G6, G7, 1, 1+ native calibration means that xDrip+ will not use its algorithm but will send calibration values to the transmitter and let it handle it with its own proprietary algorithm.

Libre 1, 14 Days, Pro, 2 (EU) and 2+ (EU) sensors only send raw data, and will need either xDrip+ calibration or an external calibration plugin called [out of process algorithm](../../use/OOP/) (short OOP).

Libre 2 patched app will use its own proprietary algorithm (an old version though).

| Sensor                          | xDrip+ calibration              | Native calibration |
| ------------------------------- | ------------------------------- | ------------------ |
| G6 rebatteried                  | Available                       | Available          |
| G6, G7, 1, 1+                   | Not available                   | Mandatory          |
| Libre 1                         | Mandatory                       | OOP1 (obsolete)    |
| Libre 2 EU patched app          | Limited offset (see below)      | By design          |
| Libre 2/2+ EU, Libre 14 days US | [Optional](../../use/OOP/#oop2) | OOP2               |

##### Libre 2 patched app

When using the patched app, you can calibrate but correction is applied as an offset with maximum values between -40 mg/dl to +20 mg/dL [-2,2 mmol/l to +1,1 mmol/l]. Calibrations failing this criteria will be **ignored**.

### xDrip+ calibration settings

!!!warning "xDrip+ calibration only"  
    The information below is relevant to xDrip+ calibration.  
    For G6/G7/1/1+ native mode see [here](https://navid200.github.io/xDrip/docs/Dexcom_page.html).

Before calibrating check your [settings](../advancedcal).

One thing you want to enable is [data tables](../../use/lesscommon/#show-data-tables) in the main menu. This will really help understanding when things go wrong.

### First calibration

If your sensor requires calibrations, after connecting it to xDrip+ and receiving three values you should see this request:

!!!xdripitem "Calibrate Sensor?"  
    &emsp;We have some readings!  
    

    &ensp;Next, we need the first calibration blood test.  
    
    &ensp;Ready to calibrate now?  
    
    &emsp;NO&emsp;&emsp;&emsp;&emsp;<span style="background-color: white; color: black;">&ensp;CALIBRATE&ensp;</span>

Two values initial calibration values are historical from G4. If you want to use that correctly: make two different measurements (two strips), this is a recommended approach. If you usually insert the same value you might want to make it a default [here](../advancedcal/#calibrations).

!!!xDrip "☰&emsp;Initial calibration"  
    &emsp;<u>Enter First BG Value</u>  
    &emsp;<u>Enter Second BG Value</u>  
    
    &emsp;<small>In order to get started, perform one or two finger prick tests and enter the values here!</small>    

If you're using native calibration, the value will be sent to the transmitter for processing.

If you're using xDrip+ calibration, this value will be processed 10 minutes later to make sure to compensate for all physiological and chemical delays of the CGM measurement, **this is why it's extremely important to calibrate at stable BG**.

Let's look graphically at what will happen on the main view:

1. First reading (brought to calibration value)
2. Second reading (brought to calibration value)
3. Not visible yet but it's the third reading. The actual value when you calibrated
4. Next reading in 5 minutes
5. Next reading in 10 minutes and the calibration point (that will be used in 10 minutes)

<img src="../images/CAL03.png" />

If your BG remained stable during this time you should see it go through the calibration point.

<img src="../images/CAL04.png" />

Looking into your calibration data table you will see new entries corresponding to raw BG measurements used to define define the calibration:

1. This is the value you entered (converted if necessary in mg/dl)
2. Same value but in the unit you use with xDrip+ (here in mg/dl but will show also in mmol/l)
3. Raw BG from the sensor
4. Calculated slope and intercept
5. Effective calibration date and time (that is actual + 10 minutes) and corresponding raw BG date and time
6. There are two sets of raw data measurement for one calibration one lower one higher

<img src="../images/CAL05.png" style="zoom:75%;"  />

Your calibration graph it will now be someting like this.  
Depending on the difference between blood samples and the variability of current BG, slope might not be exactly 1.

<img src="../images/CAL06.png" style="zoom:75%;"  />

### Successive calibrations

For safety reasons you will check regularly your real BG value, at least once per day because you can't trust blindly a sensor. Enter these blood tests as [treatments](../../use/mainUI/#treatments).  
In order to have BG values that are not varying too rapidly, you shouldn't calibrate when you have carbs or insulin active at that time.

!!!note "Frequency"  
    Unless expressly required by your sensor do not calibrate systematically when performing a blood test.  
    For Libre sensors, do not necessarily calibrate if difference is less than 15%.

**Don't overcalibrate**, you can perform as many blood checks as you want, enter them as treatments in xDrip+ but add calibrations with extra care.

On your calibration graph you will see active calibration points in blue and old or invalid ones in grey.

<img src="../images/CAL15.png" style="zoom:75%;"  />

If you see, at stable BG, comparing xDrip+ value 10 minutes after your blood test, that the value differs too much, you will add another calibration point.

Since BG trends often are difficult to forecast, you can use a trick:

- Check Use Treatment BG Values is not set to Never Use Them in [Advanced Calibrations](../advancedcal).
- Enter your blood test as a treatment.

<img src="../images/CAL07.png" style="zoom:75%;"  />

- Wait 10 minutes and decide if it would have been a good time to calibrate (stable enough).

<img src="../images/CAL08.png" style="zoom:75%;"  />

- If it was, touch your treatment (the new BG test read and white square dot on the graph) and make it a calibration.

!!!xdripitem "Blood Test Action"  
      
    &emsp;What would you like to do?  
      
      &emsp;NOTHING&emsp;DELETE&emsp;&emsp;&emsp;<span style="background-color: white; color: black;">&ensp;CALIBRATE&ensp;</span>

You now have another calibration point.

<img src="../images/CAL09.png" style="zoom:75%;"  />

### Disable a calibration

It might happen that a calibration point is clearly bad and you want to delete it.

Open the Calibration Data Table and **long touch** the calibration you want to disable.

<img src="../images/CAL10.png" style="zoom:75%;"  />

!!!xdripitem "Disable this calibration?"  
    Flagged calibrations will no longer have an effect.  
      
    &emsp;&emsp;&emsp;NO&emsp;&emsp;&emsp;&emsp;<span style="background-color: white; color: black;">&ensp;YES&ensp;</span>

It will show in red and will not be used for calculation anymore.

<img src="../images/CAL11.png" style="zoom:75%;"  />

### Reset all calibrations

This method only applies to sensors supporting xDrip+ calibration.

**Do not use it for native calibration only sensors (G6 new, G7, 1, 1+ etc.)-**

The fastest way to restart calibration from scratch (Initial Calibration) when it becomes clear that the current ones are wrong, or if you don't have data after calibrating is to reset all calibrations.

From the main menu, Stop Sensor.

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"    
    &ensp;Stop Sensor  

**Do not stop sensor**: only reset all calibrations.

!!!xdripitem "<img src="../../images/BDM.png" style="zoom:75%;" /> Stop Sensor <span class='symbol'></span>"  
      &emsp;Only stop your sensor when you actually plan to remove it, otherwise leave it running!  
       
    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<span style="background-color: white; color: black;">&ensp;DON'T STOP, JUST RESET ALL CALIBRATIONS&ensp;</span>

!!!xdripitem "Are you sure?"  
      &emsp;Do you want to delete and reset the calibrations for this sensor?  
       
     &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;NO &emsp;&emsp;&emsp;<span style="background-color: white; color: black;">&ensp;YES&ensp;</span>

xDrip+ will bring you back to [initial calibration](#first-calibration). Make sure you perform this action at stable BG, when in range.

</br>

[*Last modified 7/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)
