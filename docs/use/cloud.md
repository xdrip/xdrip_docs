<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../images/M-S-CU.png" style="zoom:75%;" />

Cloud upload allows you to upload your BG to various cloud services or databases.

### Nightscout Sync (REST-API)

<img src="../images/M-S-CU-NS.png" style="zoom:75%;" />

[Nightscout](https://nightscout.github.io/) is the universal method to share your BG numbers and much more...

Enable it to upload from xDrip+ to your site. Upload is supported for xDrip+ Sync followers, and sensors direct connection. 

<img src="../images/M-S-CU-NSa.png" style="zoom:75%;" />

Make sure this is enabled if you're using a cellular phone with a SIM and a data plan, else it will only upload when connected to a Wi-Fi network.

<img src="../images/M-S-CU-NSb.png" style="zoom:75%;" />

If you use filters or calibration plugins, you can select this to send to Nightscout the data as displayed by xDrip+ instead of uncalibrated/unfiltered data.

<img src="../images/M-S-CU-NSc.png" style="zoom:75%;" />

The base URL is composed by your API_SECRET (or TOKEN) and the URL of your site.  
The example provided in the dialog was for an Azure based Nightscout.  
The URL format should be like this:

`https://API_SECRET@sitename.domain.com/api/v1/`

Contact the vendor if you use NS10BE or T1Pal.

If you use a classic DIY Nightscout, it will be like:

**`https://API_SECRET@sitename.herokuapp.com/api/v1/`**

and you'll find the API_SECRET variable in [Heroku](https://nightscout.github.io/nightscout/new_user/#editing-config-vars-in-heroku).

<img src="../images/M-S-CU-NSe.png" style="zoom:75%;" />

In the case you have several devices uploading to Nightscout (not recommended) you might want to also download treatments from Nightscout to see the information that was uploaded by the others.

<img src="../images/M-S-CU-NSf.png" style="zoom:75%;" />

!!!warning "Automatic Calibration"  
    This is the same Automatic Calibration setup in calibrations. Use with care.

<img src="../images/M-S-CU-NSh.png" style="zoom:75%;" />

<img src="../images/M-S-CU-NSi.png" style="zoom:75%;" />

If your Nightscout is only on a local server, don't try to upload data to Nightscout when you're not home.

<img src="../images/M-S-CU-NSj.png" style="zoom:75%;" />

You can upload your bridge or sensor battery level (if supported).

<img src="../images/M-S-CU-NSk.png" style="zoom:75%;" />

Your can upload locally entered [treatments](../mainUI/#treatments) to Nightscout [Care Portal](https://nightscout.github.io/nightscout/setup_variables/#careportal-careportal).

<img src="../images/M-S-CU-NSl.png" style="zoom:75%;" />

You can setup an alert when upload fails, and add more information to the BG data uploaded.

<img src="../images/M-S-CU-NSm.png" style="zoom:75%;" />

If you recently created a Nightscout site and want to upload your historical data from xDrip+ database, you can use back-fill.

<img src="../images/M-S-CU-NSn.png" style="zoom:75%;" />

Select the first day of the period you want to upload (until today) and touch DO IT!  
Depending on the amount of data and network speed, upload can take a very long time (hours).

<img src="../images/M-S-CU-NSn2.png" style="zoom:75%;" />

### MongoDB

<img src="../images/M-S-CU-MD.png" style="zoom:75%;" />

MongoDB upload has been deprecated since mLab was acquired by MongoDB. Use this feature only if you run your own [Mongo](https://github.com/mongodb/mongo) database.

<img src="../images/M-S-CU-MDa.png" style="zoom:75%;" />

### InfluxDB

You can also upload to an InfluxDB and use Grafana to present your data.

<img src="../images/M-S-CU-ID.png" style="zoom:75%;" />

Mind your InfluxDB URI will be expressed like:

`https://host_address:port` for example for a local server: `https://192.168.0.56:8086`

<img src="../images/M-S-CU-ID2.png" style="zoom:75%;" />

### Dexcom Share Server Upload

<img src="../images/M-S-CU-DX.png" style="zoom:75%;" />

You can upload your BG to Dexcom share, not to Clarity.

<img src="../images/M-S-CU-DXa.png" style="zoom:75%;" />

If you use an USA account enable this, for any country outside of the US leave it disabled. 

<img src="../images/M-S-CU-DXb.png" style="zoom:75%;" />

Enter the credentials you use to log into Clarity.

<img src="../images/M-S-CU-DXc.png" style="zoom:75%;" />

If you don't own a physical receiver you can use `sm00000000`

<img src="../images/M-S-CU-DXd.png" style="zoom:75%;" />

You can manage your Dexcom followers from this menu:

<img src="../images/M-S-CU-DXe.png" style="zoom:75%;" />

<img src="../images/M-S-CU-DXf.png" style="zoom:75%;" />

<img src="../images/M-S-CU-DXg.png" style="zoom:75%;" />

### Tidepool

<img src="../images/M-S-CU-TP.png" style="zoom:75%;" />

