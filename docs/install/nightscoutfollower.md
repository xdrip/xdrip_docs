<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistJ.png" style="zoom:75%;" />

### Nightscout

For using xDrip+ with data coming from your [Nightscout](https://nightscout.github.io/) site, you only need to enter your site URL, you can also download compatible treatments from Nightscout (BG, calibrations, treatments).

<img src="../images/M-S-HDS-NSF.png" style="zoom:75%;" />

With a classic DIY Nightscout URL it will look like this: `https://sitename.herokuapp.com`

If you use a hosted service contact the vendor for more information.

<img src="../images/M-S-HDS-NSURL.png" style="zoom:75%;" />

If your Nightscout site is [secured](https://nightscout.github.io/nightscout/security/), you need to add the API_SECRET or a token information.

`https://API_SECRET@sitename.herokuapp.com`

`https://access_token@sitename.herokuapp.com`

</br>

xDrip+ performs limited (24 hours) data backfilling from Nightscout.

### Diabox

You can receive data from [Diabox](https://sirius.thetaphi.de/diabox/) by enabling http broadcast in the app and making xDrip+ a local follower.

!!!warning  
    You cannot use this feature with xDrip+ running a [web service](../../use/interapp/#web-service).

<img src="../images/Diabox1.png" style="zoom:75%;" />

<img src="../images/Diabox2.png" style="zoom:75%;" />

Once done set xDrip+ in Nightscout follower (see above) with the address:

`http://localhost:17580`

<img src="../images/Diabox3.png" style="zoom:75%;" />

</br>

[*Last modified 24/12/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.12.09)
