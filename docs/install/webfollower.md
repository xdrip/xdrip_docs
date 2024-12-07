!!!warning "Subject to disruption"  
    As the vendor didn't publish an API, server and protocol updates will break this data source.  
    You will need to wait until the community recovers another access method...

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;Hardware Data Source  
    &ensp;&emsp;Web Follower

</br>

### Prerequisites

1. Install the LibreLink or Libre 3 app, authenticate or create an account (mandatory) and have it display real time readings from the sensor
2. Invite a follower  
   <img src="../images/M-S-HDS-WF3.png" style="zoom:76%;" />
3. In the invitation email touch the Play Store link to install the [follower app](https://play.google.com/store/apps/details?id=org.nativescript.LibreLinkUp)  
   Create another account for the follower app.

!!!warning  "Account lock risk"  
    Do **not** use your main account credentials!

Make sure you have readings.   
You can then uninstall the follower app. You might need to reinstall it to authenticate your follower if data stops displaying in xDrip+.

### Configure xDrip+ web follower

!!!xdripitem "Web Follower Settings"  
    &ensp;Configuration options for web follower data source

Do not change the configuration script name. It is `beonlabs`

!!!xdripitem "Configuration Script"  
    &ensp;This is the community helper address or keyword

Enter the credentials you used on the follower app.

!!!xdripitem "Service logon user name"  
    &ensp;This is your registered user name or email address with the service

!!!xdripitem "Service logon password"  
    &ensp;This is your registered password with the service

Do not enable a proxy server unless you know why you want to do it.

!!!xdripitem "Use proxy server (advanced) <span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  

</br>

If no data is visible and no error message pops-up you might need to [Start sensor](../../use/startsensor/#followers-and-companion-apps).

Check the [troubleshooting](../../troubleshoot/webfollow) page if necessary.

</br>

[*Last modified 7/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)
