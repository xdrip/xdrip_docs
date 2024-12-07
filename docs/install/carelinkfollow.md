!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
        &ensp;Settings  
    &emsp;Hardware Data Source  
    &ensp;&emsp;CareLink Follower

</br>

!!!warning  
    Carelink server are subject to frequent modifications that might break the feature.  
    **Use the [latest pre-release](../download#pre-release) in case of issues.**  
    Consider using [Companion app](../companion) on the master phone and xDrip+ [Sync](../xdripfollower) or Nightscout to share data.  
    The CarePartner app authentication is valid for 1 week, thus even if xDrip+ is unable to connect to CareLink for a few days (for example due to the lack of internet connection), it will be able to renew the login (refresh the token) automatically in the background after it can connect to CareLink again without needing to login again manually using the browser. The user account restriction applies to this authentication process as well:   
    **a dedicated follower account must be used for xDrip+, you cannot use the same follower for other apps or phones.**

</br>

Select the country in which you registered your CareLink user.

!!!xdripitem "CareLink Country"  
    &ensp;Select your CareLink country

Set patient username if using a care partner account with multiple patients.

!!!xdripitem "CareLink Patient Username"  
    &ensp;CareLink patient username (optional)

xDrip+ will open the CareLink autentication web site, enter your credentials to login.  

!!!xdripitem "Login"  
    &ensp;Login with browser

Grace period is an additional waiting time after receiving last reading + 5 minutes.  
Used to avoid server lock if xDrip+ performs too frequent requests.

!!!xdripitem "Grace Period"  
    &ensp;Grace period for data request in seconds

Missed data polling interval is an additional waiting time after received last reading + 5 minutes + grace period.  
Used to avoid server lock if xDrip+ performs too frequent requests.

!!!xdripitem "Missed data poll interval"  
    &ensp;Grace period for data request in seconds

</br>

#### Treatments

You can download treatments and receive notifications.

!!!xdripitem "Finger BGs <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;You can download finger BGs from CareLink  

!!!xdripitem "Boluses <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;You can download boluses from CareLink

!!!xdripitem "Meals <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;You can download meals from CareLink

!!!xdripitem "Notifications <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;You can download notifications from CareLink

</br>

#### Status line

Sensor status and pump status can be enabled in the [Extra status line](../../use/lesscommon/#extra-status-line) option.

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;&ensp;Less Common settings  
    &emsp;&emsp;Extra status line

!!!xdripitem "External Status <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Display status from other apps like AndroidAPS

!!!xdripitem "Pump Status <span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Display pump status information if available

Pump information (status, basal) is <u>only visible</u> in the status line and **cannot be uploaded to Nightscout/Tidepool**.

<img src="../images/M-S-HDS-CF6.png" style="zoom:75%;" />

</br>

If no data is visible and no error message pops-up you might need to [Start sensor](../../use/startsensor/#followers-and-companion-apps).

[*Last modified 7/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)

