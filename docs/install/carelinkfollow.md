<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistM.png" style="zoom:76%;" />

</br>

!!!warning  
    Carelink server are subject to frequent modifications that might break the feature.  
    Consider using [Companion app](../companion) on the master phone and xDrip+ [Sync](../xdripfollower) or Nightscout to share data.  
    The CarePartner app authentication is valid for 1 week, thus even if xDrip+ is unable to connect to CareLink for a few days (for example due to the lack of internet connection), it will be able to renew the login (refresh the token) automatically in the background after it can connect to CareLink again without needing to login again manually using the browser. The user account restriction applies to this authentication process as well: **a different dedicated follower account must be used for every app, otherwise the authentication token (login) will be revoked.**

</br>

**Check [requirements](https://github.com/benceszasz/xDripCareLinkFollower#requirements).**

</br>

Select your country, eventually a patient name (optional) and click Login to perform login in a browser.  
*Note: set patient username if using a care partner account with multiple patients.*

<img src="../images/M-S-HDS-CF1.png" style="zoom:71%;" />

Grace period is an additional waiting time after receiving last reading + 5 minutes.

<img src="../images/M-S-HDS-CF2.png" style="zoom:75%;" />

Missed data polling interval is an additional waiting time after received last reading + 5 minutes + grace period.

<img src="../images/M-S-HDS-CF3.png" style="zoom:75%;" />

</br>

#### Treatments

You can download treatments and receive notifications.

<img src="../images/M-S-HDS-CF4.png" style="zoom:75%;" />

</br>

#### Status line

<img src="../images/M-S-HDS-CF6.png" style="zoom:75%;" />

Sensor status and pump status are available in [Extra status line](../../use/lesscommon/#extra-status-line) option.

<img src="../images/M-S-HDS-CF5.png" style="zoom:75%;" />

</br>

If no data is visible and no error message pops-up you might need to [Start sensor](../../use/startsensor/#followers-and-companion-apps).

[*Last modified 1/4/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.03.27)

