### Native Algorithm

If you use xDrip+ with a G6, G7, 1, 1+ or Stelo native algorithm, see [here](https://navid200.github.io/xDrip/docs/Dexcom_page.html).

### xDrip+ Algorithm

Enable [data tables](../../use/lesscommon/#show-data-tables) for more information.

#### No data after initial calibration

<img src="../images/CAL16.png" style="zoom:75%;"  />

If you checked you have connectivity with sensor/bridge and no data shows up after initial calibration, it might be because you're calibrating too high and the intercept calculated is above safety limit. [Reset](../calibrate/#reset-all-calibrations) all calibrations and retry at stable BG when in the lower range.

#### No data after adding a new calibration

<img src="../images/CAL18.png" style="zoom:75%;"  />

You probably drove calibrations out of safety limits. Check Calibration Data Table and eventually [disable](../calibrate/#disable-a-calibration) the offending calibration.

A sensor requiring a large positive intercept might not be safe. If you believe your sensor is still reliable [Reset](../calibrate/#reset-all-calibrations) all calibrations and retry at stable BG when in the lower range.

#### New calibration is ignored

<img src="../images/CAL19.png" style="zoom:75%;"  />

Check Calibration Data Table and you will most probably see your calibrations ended displayed in red as they are disabled for safety reasons.

Most probably your sensor isn't reliable anymore. If you believe it is, [Reset](../calibrate/#reset-all-calibrations) all calibrations and retry at stable BG when in the lower range.

#### Intercept or slope above safety limit

!!!warning "Safety"  
    Limits preventing you to calibrate are thought for your own safety.  
    **You cannot rely on a system that is not able to detect hypoglycemia.**

Open your Calibration Data Table and check last calibration.

<img src="../images/CAL17.png" style="zoom:75%;"  />

!!!warning "Maximum authorized intercept is 40"  
    An intercept above 40 mg/dl will prevent BG display for safety reason.

Slope limits depend on your sensor:

| Sensor                        | Minimum slope | Maximum slope |
| ----------------------------- | ------------- | ------------- |
| G5 or G6 non-native algorithm | 0.7           | 1.6           |
| Libre (raw data source)       | 0.5           | 1.6           |
| Libre 2 patched app           | 1 (fixed)     | 1 (fixed)     |

Since slope and intercept safety limits will prevent xDrip+ from having a too high intercept, calibrations leading to this situation will be ignored.

In the example below you see the orange line is the one that matches the best calibrations, still, xDrip+ will use the red one for safety as its intercept is safe. You can see the plugin intercept value reflecting what would better match calibrations.

<img src="../images/CAL20.png" style="zoom:75%;"  />

</br>

[*Last modified 7/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)