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

In the case you have more than one Nightscout site, xDrip+ can upload to multiple **space separated** Nightscout URLs.

!!!warning "Automatic Calibration"  
    This is the same [Automatic Calibration](../../calibrate/advancedcal) setup in calibrations. Use with care.

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

!!!warning  
    This method has been deprecated.

You can directly upload BG and device status in a Mongo Database.

<img src="../images/M-S-CU-MD.png" style="zoom:75%;" />

MongoDB upload has been deprecated since mLab was acquired by MongoDB and many migrated to Atlas: you **cannot** use a DNS seed URI `mongodb+srv`.  
Use this feature only if you run your own [Mongo](https://github.com/mongodb/mongo) database, default port is 27017.

The [connection string URI](https://www.mongodb.com/docs/manual/reference/connection-string/#connection-string-uri-format) structure is:

```
mongodb://databaseusername:databasepassword@your.mongo.url/databasename
```

In order to keep the database compatible with Nightscout, do not change Collection name or Device status collection name from default (if you do change them you'll also have to modify the corresponding variables in Nightscout `MONGODB_COLLECTION` and `MONGO_DEVICESTATUS_COLLECTION`).

!!!info  
    Uploaded data might not show in the Nightscout web page but only in Nightscout reports.

<img src="../images/M-S-CU-MDa.png" style="zoom:75%;" />

### InfluxDB

You can also upload to an InfluxDB and use Grafana to present your data.

<img src="../images/M-S-CU-ID.png" style="zoom:75%;" />

Mind your InfluxDB URI will be expressed like:

`https://host_address:port` for example for a local server: `https://192.168.0.56:8086`

<img src="../images/M-S-CU-ID2.png" style="zoom:75%;" />

### Dexcom Share Server Upload

Once you have an active follower, created by the Dexcom apps, you can use xDrip+ to manage your followers.

<img src="../images/M-S-CU-DX.png" style="zoom:75%;" />

!!!info  
    You can upload your BG to Dexcom share, not to Clarity.

<img src="../images/M-S-CU-DXa.png" style="zoom:75%;" />

If you use an USA account enable this, for any country outside of the US leave it disabled. 

<img src="../images/M-S-CU-DXb.png" style="zoom:75%;" />

Enter the credentials you use to log into Clarity.

<img src="../images/M-S-CU-DXc.png" style="zoom:75%;" />

If you don't own a physical receiver you can use `sm00000000`

<img src="../images/M-S-CU-DXd.png" style="zoom:75%;" />

Invite followers and fill all the information.

<img src="../images/M-S-CU-DXe.png" style="zoom:75%;" />

<img src="../images/M-S-CU-DXf.png" style="zoom:75%;" />

<img src="../images/M-S-CU-DXg.png" style="zoom:75%;" />

You will receive the invitation email, accept it and you'll have a new follower.

You can also delete followers from the list.

### Tidepool

<img src="../images/M-S-CU-TP.png" style="zoom:75%;" />

If you have a [Tidepool](https://www.tidepool.org/) account, you can upload automatically your data and share with your endocrinologist.  
If xDrip+ can display [basal information from an external status](../use/display/#basal-information), it will also be uploaded to Tidepool.

<img src="../images/M-S-CU-TPa.png" style="zoom:75%;" />

Add your email address and password (those you used to [register](https://app.tidepool.org/signup/personal)).  
Once done, test the connection.

<img src="../images/M-S-CU-TPb.png" style="zoom:75%;" />

Tidepool doesn't need real time data, select the amount of data to upload.

<img src="../images/M-S-CU-TPc.png" style="zoom:75%;" />

Do **not** use test servers (keep unselected).

<img src="../images/M-S-CU-TPd.png" style="zoom:75%;" />

You can select to upload at specific conditions to save battery and data costs.

<img src="../images/M-S-CU-TPe.png" style="zoom:75%;" />

If you also upload data manually from your pump, you might want to disable xDrip+ treatments upload to avoid duplicates.

<img src="../images/M-S-CU-TPf.png" style="zoom:75%;" />

</br>

[*Last modified 1/4/2023*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2023.03.28b)
