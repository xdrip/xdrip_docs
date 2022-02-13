For using xDrip+ with data coming from your Nightscout site, you only need to enter your site URL, you can also download compatible treatments from Nightscout (BG, calibrations, treatments).

<img src="../images/M-S-HDS-NSfollow.png" style="zoom:75%;" />

With a classic DIY Nightscout URL it will look like this: `https://nightscout_url.herokuapp.com`

If you use a hosted service contact the vendor for more information.

<img src="../images/M-S-HDS-NSURL.png" style="zoom:75%;" />

If your Nightscout site is [secured](https://nightscout.github.io/nightscout/security/), you need to add the API_SECRET or a token information.

`https://API_SECRET@nightscout_url.herokuapp.com`

`https://access_token@nightscout_url.herokuapp.com`

</br>

xDrip+ performs limited (24 hours) data backfilling from Nightscout.
