# Libre Web Follower

## System setup

When using this data source you need to make sure your system, is configured correctly with the vendor apps.

#### The master app (connected to the Libre sensor) should upload data in the vendor [server](https://www.libreview.com/).  

Log out and in to the server to verify you are using the right credentials.

Make sure you have data in the server.

#### The vendor [follower](https://play.google.com/store/search?q=librelinkup&c=apps) app should receive share data.  

Try to delete and resend an invitation to the vendor follower app (using the vendor master app).

Try to uninstall and reinstall the vendor follower app.

- Use preferably the set of credentials from the invitation to log in.
- If it doesn't work use the master app (server) credentials and resend the invitation.

</br>

## xDrip+ setup

Once the system is running on the vendor apps, you can troubleshoot xDrip+.

1. Make sure the data source is [Web follower](../../install/webfollower/).
2. Use the credentials from the follower you invited with the vendor master app.
3. If it doesn't work, you can try to use the server credentials to troubleshoot but be cautious to reduce the risks of an account lock.

</br>

## Vendor servers updates

Server updates might break the mechanism. Once xDrip+ has been fixed, you might need to reset it following this sequence:

!!!xdrip "`Web Follower`"  
    <img src="../../images/hamburger_menu.png" style="zoom:60%;" />  
    &ensp;Settings  
    &emsp;Hardware Data Source  
    &ensp;&emsp;Web Follower

Edit the `Configuration script`

!!!xdripitem "Configuration Script"  
    &ensp;This is the community helper address or keyword

Add a space after `beonlabs`, select `Ok`

<img src="../images/M-S-HDS-WF-Scr.png" style="zoom:75%;" />

Edit again the `Configuration script`, **remove the space** after `beonlabs`, and select `Ok`.

Wait up to a minute for data to display again.

</br>

If the issue persist, install the vendor follower app on the same phone and check it can receive data with the same credentials.

</br>

[*Last modified 18/6/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.06.15)
