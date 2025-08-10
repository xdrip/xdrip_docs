!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="../images/CrystalBall.png" style="width:5%;" />&ensp;Predictive Simulations

xDrip+ Predictive Simulation settings is an experimental, non medically approved feature. Make sure to re-read the [EULA](../../install/install/#understand-what-is-xdrip) before enabling it. Do not use them to take medical decisions.

!!!warning  
    If you use a closed-loop system do not rely on these predictions since they don't take into account basal modulation.

!!!xdripitem "Predictive simulations"  
    &ensp;Display mathematical simulations based on profile data and carbs/insulin logs

Enabling predictions will add the light purple prediction curve on the main graph. This curve is showing you how your BG should theoretically evolve using current insulin and carbs entered in xDrip+. More details on display [here](../display/#treatments-and-predictions-curves).

<img src="../images/M-S-PS1a.png" style="zoom:75%;" />

xDrip+ can handle multiple insulin types. See [below](#multiple-insulin-types).

!!!xdripitem "Multiple Insulin Types"  
    &ensp;Options for working with multiple insulin types

### Carb ratio and insulin sensitivity

!!!note "Automatic import"  
    If you use [accepting treatments](../interapp/#receiving-from-nsclient) from AAPS or NSClient, these parameters and the basal profile will automatically import at profile switch.

### Carb absorbtion rate

These parameters are key to diabetes management and should be known.  
They will most probably vary during the day and should be calculated for every meal and also outside meal times.  
Everybody has his own parameters. Don't use other people's parameters.

Carb ratio is the amount of carbohydrates that will be covered by 1 unit of insulin.

For example 10 means each 10g of carbohydrates will require 1 unit of insulin.

!!!xdripitem "Carb Ratio"  
    &ensp;Grams of carbohydrates 1 Unit covers

Insulin sensitivity is the resulting blood glucose drop for one unit of insulin, with no carbohydrates in the blood stream.

For example 50 (or 2.8) means 1 unit drops BG of 50 mg/dl (or 2.8 mmol/l).

!!!xdripitem "Insulin Sensitivity"  
    &ensp;Glucose drop for 1 Unit

Carbohydrates absorption rate is the speed at which your body will assimilate carbohydrates. See [here](https://diyps.org/2014/05/29/determining-your-carbohydrate-absorption-rate-diyps-lessons-learned/) how to calculate that parameter.

!!!xdripitem "Carb absorption rate"  
    &ensp;Linear model carbs absorbed by hour

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

### Basal Profile Editor

!!!info "This feature is under development."  
    Current basal profile is automatically imported from NSClient when [Accept Treatments](../interapp/#receiving-from-nsclient) is enabled.

!!!xdripitem "Basal Profile Editor"  
    &ensp;Graphical editor for pump basal profiles

You can display and edit your basal profile.

1. Select the profile you want to modify or view
2. Export (not functional yet)
3. Save locally

<img src="../images/M-S-PS4f2.png" style="zoom:78%;" />

To edit your basal profile:

1.  Touch the basal hour bar you want to modify, it will turn orange
2. Change the step if necessary
3. Use the positive numbered box or the upwards arrow to increase
4. Use the negative numbered box or the downwards arrow to decrease
5. Use set, or double tap the bar to set the new value

<img src="../images/M-S-PS4f3.png" style="zoom:78%;" />

### Use trend momentum

Trend momentum is independent from predictions, it is just a mathematical extrapolation (i.e. if BG continues to evolve with his trend, not considering insulin and carbs, where will it go?) of your current BG trend (up/down/flat). It can be used for [Forecasted Low alarms](../alarms/#forecasted-low).

Trend momentum can be integrated in predictions (recommended).

!!!xdripitem "Use trend momentum"  
    &ensp;Calculate including glucose trend

Including current trend (1) can prevent sharp prediction variations and might be closer to real evolution (2).

<img src="../images/M-S-PS5a.png" style="zoom:75%;" />

<img src="../images/M-S-PS5b.png" style="zoom:75%;" />

Might

<img src="../images/M-S-PS5c.png" style="zoom:75%;" />

### EULA

Review the [EULA](../../install/install/#understand-what-is-xdrip) before using this feature.

!!!xdripitem "End User License Agreement"  
    &ensp;Not for medical use - research only

### Low Level prediction

You can setup more prediction parameters here.

!!!xdripitem "Low level prediction values"  
    &ensp;Deep settings for algorithms

Target is used for bolus wizard calculator. This is the desired BG target.

Insulin [duration](https://www.diabettech.com/insulin/why-we-are-regularly-wrong-in-the-duration-of-insulin-action-dia-times-we-use-and-why-it-matters/) depends on your insuline type. Changing the value requires xDrip+ restart (or phone restart).

Target glucose value is the value used to calculate suggested corrections.

!!!xdripitem "Target glucose value"  
    &ensp;99 / 5.5

Insulin duration is a parameter you should discuss with your endocrinologist. When using closed loop systems, this value will be much more. Still, remember that xDrip+ predictions find their best use with multiple daily injections, not with pumps.

!!!xdripitem "Insulin duration in hours"  
    &ensp;3

Liver parameters were introduced to take into account liver glycogen reaction to lows but are not characterizable easily and should be left at default values.

!!!xdripitem "Default liver sensitivity ratio"  
    &ensp;2

!!!xdripitem "Default liver maximum impact (0 to 1)"  
    &ensp;0.8

### Multiple insulin types

!!!xdripitem "Multiple insulin types"

Select the insulin types you are using.

You can select up to three insulin types and then decide which one is used basal and which for bolus.

!!!xdripitem "Treatment profile editor"  
    Enable at least one, max three profiles.  
    &ensp;☐&emsp;FIASP (ultra-fast acting)  
    &ensp;☐&emsp;Afrezza (ultra-fast acting)  
    &ensp;☐&emsp;Apidra (ultra-fast acting)  
    &ensp;☐&emsp;Novorapid (fast acting)  
    &ensp;☐&emsp;Humalog (fast acting)  
    &ensp;☐&emsp;Lispro (fast acting)  
    &ensp;☐&emsp;Actrapid (short acting)  
    &ensp;☐&emsp;Insulatard (NPH)  
    &ensp;☐&emsp;Toujeo (long acting)  
    &ensp;☐&emsp;Lantus (long acting)  
    &ensp;☐&emsp;Levemir (long acting)  
    &ensp;☐&emsp;Basaglar (long acting)  
    &ensp;☐&emsp;Tresiba (ultra-long acting) 

In the lower part of the dialog, select which insulin will be used for basal (long acting) and bolus (fast acting):

!!!xdripitem "Choose basal insulin profile"

!!!xdripitem "Choose bolus insulin profile. Also used for pump and pen..."

Once done, save your choices.

!!!xdripitem "<span style="background-color: grey; color: white;"> &ensp;CANCEL&ensp;</span> &emsp;<span style="background-color: grey; color: white;"> &ensp;RESET&ensp;</span>  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<span style="background-color: grey; color: white;"> &ensp;SAVE&ensp;</span>  &emsp;</span>" 

When adding multiple insulin type, using [treatments](../mainUI/#treatments) will ask you to select the one you're using for this treatment.

<img src="../images/M-S-PS2b3.png" style="zoom:75%;" />

You can add basal insulin on the display and integrate it in calculation.  
Not recommended as basal insulin in MDI is only used to keep background BG constant.  
Use [notes](../mainUI/#treatment-notes) to track basal injections.

Multiple insulin types will be displayed in an identical way on the main graph.

!!!xdripitem "Use Basal Activity"  
    &ensp;Plot basal activity on graph and incorporate in predictive model.

<img src="../images/M-S-PS2c2.png" style="zoom:75%;" />

</br>

[*Last modified 15/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)