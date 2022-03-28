<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-PS.png" style="zoom:75%;" />

xDrip+ Predictive Simulation settings is an experimental, non medically approved feature. Make sure to re-read the [EULA](../../install/install/#understand-what-is-xdrip) before enabling it. Do not use them to take medical decisions.

!!!warning  
    If you use a closed-loop system do not rely on these predictions since they don't take into account basal modulation.

<img src="../images/M-S-PS1.png" style="zoom:75%;" />

Enabling predictions will add the prediction curve on the main graph.

<img src="../images/M-S-PS1a.png" style="zoom:75%;" />

xDrip+ can handle multiple insulin types. See [below](#multiple-insulin-types).

<img src="../images/M-S-PS2.png" style="zoom:75%;" />

### Carb ratio and insulin sensitivity

### Carb absorbtion rate

These parameters are key to diabetes management and should be known.  
They will most probably vary during the day and should be [calculated](https://diyps.org/2014/05/29/determining-your-carbohydrate-absorption-rate-diyps-lessons-learned/) for every meal and also outside meal times.  
Everybody has his own parameters. Don't use other people's parameters.

<img src="../images/M-S-PS3.png" style="zoom:75%;" />

<img src="../images/M-S-PS4.png" style="zoom:75%;" />

Touching one of the two menus above will open the treatment profile editor.

<img src="../images/M-S-PS4a.png" style="zoom:75%;" />

You can define carbs per units of insulin and correction factor, just remember to validate the entry and not jump from one line to another without confirming an entry. Save when finished.

<img src="../images/M-S-PS4b.png" style="zoom:75%;" />

You will create blocks of for different hours during the day.  
To create (split) or delete a block, long touch the upper area of the block.

  <img src="../images/M-S-PS4c.png" style="zoom:75%;" />

Touching the time bar at the top of a block allows you to change it, it also will propagate to the block below.  
Eventually you'll end up having something like this.

<img src="../images/M-S-PS4d.png" style="zoom:75%;" />

If necessary you can perform a global percentage modification of all parameters with the slide at the bottom.  
Remember to save.

<img src="../images/M-S-PS4e.png" style="zoom:75%;" />

### Use trend momentum

Trend momentum can be integrated in predictions (recommended).

<img src="../images/M-S-PS5.png" style="zoom:75%;" />

Including current trend (1) can prevent sharp prediction variations and might be closer to real evolution (2).

<img src="../images/M-S-PS5a.png" style="zoom:75%;" />

Might

<img src="../images/M-S-PS5b.png" style="zoom:75%;" />

### EULA

Review the [EULA](../../install/install/#understand-what-is-xdrip) before using this feature.

<img src="../images/M-S-PS6.png" style="zoom:75%;" />

### Low Level prediction

You can setup more prediction parameters here.

<img src="../images/M-S-PS7.png" style="zoom:75%;" />

Target is used for bolus wizard calculator. This is the desired BG target.

Insulin [duration](https://www.diabettech.com/insulin/why-we-are-regularly-wrong-in-the-duration-of-insulin-action-dia-times-we-use-and-why-it-matters/) depends on your insuline type. Changing the value requires xDrip+ restart (or phone restart).

Liver parameters were introduced to take into account liver glycogen reaction to lows but are not characterizable easily and should be left at default values.

<img src="../images/M-S-PS7a.png" style="zoom:75%;" />

### Multiple insulin types

<img src="../images/M-S-PS2a.png" style="zoom:75%;" />

Select the insulin types you are using.

<img src="../images/M-S-PS2b.png" style="zoom:75%;" />

You can select up to three insulin types and then decide which one is used basal and which for bolus.

<img src="../images/M-S-PS2b2.png" style="zoom:75%;" />

When adding multiple insulin type, using [treatments](../mainUI/#treatments) will ask you to select the one you're using for this treatment.

<img src="../images/M-S-PS2b3.png" style="zoom:75%;" />

You can add basal insulin on the display and integrate it in calculation.  
Not recommended as basal insulin in MDI is only used to keep background BG constant.  
Use [notes](../mainUI/#treatment-notes) to track basal injections.

Multiple insulin types will be displayed in an identical way on the main graph.

<img src="../images/M-S-PS2c.png" style="zoom:75%;" />

<img src="../images/M-S-PS2c2.png" style="zoom:75%;" />

</br>

[*Last modified 28/4/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)