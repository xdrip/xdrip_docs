Out of process algorithms are external apps which function is to perform dataprocessing that is not directly provided by xDrip+.

They are only used for Libre sensors and bridges now.

There are two different families of Out Of Process Algorithms (OOP):

### OOP1

<img src="../images/OOP_1.png" style="zoom:75%;" />

!!!warning  "Old Android ONLY"  
    Maximum supported Android version is 9.  
    Few Android 10 and above phones have been reported to be functioning with OOP1.

OOP1 provides readings similar to the vendor reader without calibrating. It can also decode the Libre 2 EU data. You need a [compatible bridge](../../install/libreBT/#libre-and-bridge) if using any. OOP1 also applies to NFC scan results.

!!!warning "No calibration possible"  
    Calibrations will be ignored when using OOP1.  
    This is a safety feature as xDrip+ cannot perform sanity checks on data provided by OOP1.

Two versions are available: [Libre 1 and Libre 2 EU](https://drive.google.com/open?id=13ERWcSVSFMLy9rhpbv5rArFrnDuAzriM) or [Libre 14 Days US](https://drive.google.com/open?id=172whZZYTyE_ZEuN0T-zhdMKhucy6jP-a).

Out Of process Algorithm must be [enabled](../misc/#out-of-process-algorithm) when using OOP1.

### OOP2

<img src="../images/OOP_2.png" style="zoom:75%;" />

OOP2 provides decoding for the Libre 2 EU sensor, either for direct connection or using a [compatible bridge](../../install/libreBT/#libre-and-bridge).

!!!info "Calibration is optional"  
    You can calibrate if using OOP2.

The original version is available [here](https://drive.google.com/uc?id=1aeWvBiFCidOhreCMoW1S0ARa5HvNNf2m&export=download) but it is **recommended to use the [latest OOP2 release](https://drive.google.com/file/d/1cRfUDzFRnLUnsn6gKaC2cibZrIY1oIb-/view?usp=sharing)**.

!!!warning  
    Out Of process Algorithm must be [disabled](../misc/#out-of-process-algorithm) when using OOP2.

### Auto-detection

Some xDrip+ versions will detect the presence or necessity of the out of process algorithm.

Make sure you enable it only for OOP1 and not for OOP2.

<img src="../images/OOP_AD.png" style="zoom:75%;" />

### Settings

Use service corresponds to switching ON or OFF the OOP app. If you want to use it it must be enabled.

<img src="../images/OOP_UI1.png" style="zoom:75%;" />

Foreground service is an addition that makes it less probably the app will be put to sleep by the phone.  
Enable it if you have data loss.

<img src="../images/OOP_UI2.png" style="zoom:75%;" />

You can select the period at which OOP will make sure it's available.  
When having data loss you can reduce the interval. The less the interval, the more battery use it will require.

<img src="../images/OOP_UI3.png" style="zoom:75%;" />

</br>

[*Last modified 28/3/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)
