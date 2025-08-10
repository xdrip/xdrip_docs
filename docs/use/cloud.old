!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_cloud_upload_grey600_48dp.png" style="width:5%;" />&ensp;Cloud Upload

Cloud upload allows you to upload your BG to various cloud services or databases.  
This can be used to share data with non-xDrip+ devices and for reporting. 

### Nightscout Sync (REST-API)

!!!xdripitem "Nightscout Sync (REST-API)"  
    &ensp;The REST-API is the standard way to connect to Nightscout  

[Nightscout](https://nightscout.github.io/) is the universal method to share your BG numbers, create reports and much more...

After you created your Nightscout site, enable Sync to upload data from xDrip+.

!!!xdripitem "Enable<span class='symbol'><img src="../../images/ON.png" style="zoom:75%;" /></span>"  
    &ensp;The REST-API is the standard way to connect to Nightscout  

If you want to use Nightscout to share your BG, make sure this is enabled if you're using a cellular phone with a SIM and a data plan. Else it will only upload when connected to a Wi-Fi network, which is fine if you use Nightscout to collect data for reports.

!!!xdripitem "Use mobile data<span class='symbol'><img src="../../images/ON.png" style="zoom:75%;" /></span>"  
    &ensp;Upload even when using mobile data  

If you use filters or calibration plugins, you can select this to send to Nightscout the data as displayed by xDrip+ instead of uncalibrated/unfiltered data.

!!!xdripitem "Send display glucose<span class='symbol'><img src="../../images/OFF.png" style="zoom:75%;" /></span>"  
    &ensp;Use noise smoothing and plugins etc. (if enabled) for broadcasted value 

The base URL is composed by your API_SECRET (or a token) and the URL of your site.  
The example provided in the dialog was for an Azure based Nightscout.

!!!xdripitem "Base URL"  
    &ensp;https://password.hostname/api/v1  

The URL format should be like this:

**`https://your-API_SECRET@your-site.domain.fqd/api/v1/`**

You'll find the API_SECRET in your Nightscout [variables](https://nightscout.github.io/nightscout/setup_variables/#nightscout-configuration).

Alternatively you can use an admin [token](https://nightscout.github.io/nightscout/security/#create-authentication-tokens-for-users) to authenticate, it would then look like this:

**`https://xdrip-12ab34cd5678ef90@your-site.domain.fqd/api/v1/`**

Contact the vendor if you use a hosted service.

!!!info "Multiple sites"  
    In the case you have more than one Nightscout site, xDrip+ can upload to multiple **space separated** Nightscout URLs.  
    ***Only BG values will upload to the secondary URL(s), not treatments***

In the case you have several devices uploading to Nightscout (not recommended) you might want to also download treatments from Nightscout to see the information that was uploaded by others.

!!!xdripitem "Download treatments<span class='symbol'><img src="../../images/ON.png" style="zoom:75%;" /></span>"  
    &ensp;Also try to download treatments from Nightscout  

!!!warning "Automatic Calibration"  
    This is the same [Automatic Calibration](../../calibrate/advancedcal#use-treatment-bg-values) setup in calibrations. Use with care.

!!!xdripitem "Automatic Calibration<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Calibrate using new blood glucose reading if the conditions appear right to do so without asking confirmation (experimental)  

</br>

!!!xdripitem "Extra Options"

If your Nightscout is available only on a local server (on a private IP), don't try to upload data to Nightscout when you're not home. Ignore for cloud based Nightscout.

!!!xdripitem "Skip LAN uploads<span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;For local servers with 192.168.x.x addresses, skip uploads when there is no local network connectivity 

You can upload your bridge or sensor battery level (if supported).

!!!xdripitem "Upload bridge battery<span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Send your bridge battery level to Nightscout. Uncheck if your battery sensor is broken

!!!xdripitem "Upload OB1 Dex transmitter battery<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Send Dexcom transmitter battery statistics to Nightscout. Includes all the data shown on the Collector Status screen

Your can upload locally entered [treatments](../mainUI/#treatments) to Nightscout [Care Portal](https://nightscout.github.io/nightscout/setup_variables/#careportal-careportal).

!!!xdripitem "Upload treatments<span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Send treatment data to Nightscout. Uncheck if your careportal is broken

You can setup an alert when upload fails, and add more information to the BG data uploaded.

!!!xdripitem "Alert on failures<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Display and sound a notification if Nightscout upload is failing

!!!xdripitem "Append source info to device name<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;For Dex, send collector type (e.g. OB1) and reading backfill status (for native) to Nightscout

##### Backfill data to Nightscout

If you recently created a Nightscout site and want to upload your historical data from xDrip+ database, you can use back-fill.

!!!xdripitem "Back-fill data"  
    &ensp;Send treatment data to Nightscout. Uncheck if your careportal is broken

Select the first day of the period you want to upload (until today) and touch **DO IT!**  
Depending on the amount of data and network speed, upload can take a very long time (hours).

!!!xdrip "<img src="../../images/BDM.png" style="zoom:75%;" />Nightscout Backfill"  
    Choose the date for the oldest record to send to Nightscout, use with care!  
      

    <div style="background-color: gray; color: white; text-align: center;">  &emsp;FEBRUARY 12, 2022 11:29PM&emsp;</div>  


    <span style="background-color: gray; color: white; text-align: center;">  &emsp;DO IT!&emsp;</span>&emsp;CANCEL

### MongoDB

!!!warning  
    This method has been deprecated for Nightscout.

You can directly upload BG and device status in a Mongo database.

!!!xdripitem "MongoDB"  
    &ensp;Direct database upload, not recommended for Nightscout

MongoDB upload has been deprecated since mLab was acquired by MongoDB and many migrated to Atlas: **you cannot use a DNS seed URI `mongodb+srv`**.  
Use this feature only if you run your own [Mongo](https://github.com/mongodb/mongo) database, default port is 27017.

The [connection string URI](https://www.mongodb.com/docs/manual/reference/connection-string/#connection-string-uri-format) structure is:

```
mongodb://databaseusername:databasepassword@your.mongo.url/databasename
```

In order to keep the database compatible with Nightscout, do not change Collection name or Device status collection name from default (if you do change them you'll also have to modify the corresponding variables in Nightscout `MONGODB_COLLECTION` and `MONGO_DEVICESTATUS_COLLECTION`).

!!!info  
    Uploaded data might not show in the Nightscout web page but only in Nightscout reports.

### InfluxDB

You can also upload to an [InfluxDB](https://www.influxdata.com/products/influxdb-overview/) and use Grafana to present your data.

!!!xdripitem "InfluxDB"  
    &ensp;If using a private InfluxDB database, this should be enabled

Mind your InfluxDB URI will be expressed like:

`https://host_address:port` for example for a local server: `https://192.168.0.56:8086`

### Dex Share

!!!warning "Your username cannot be a phone number"  
    You should create a [dependent account](https://www.dexcom.com/faqs/how-do-i-create-a-dependent-account) to have a text only username.  
    Once created the new dependent account, make sure you're logged with this account in your Dexcom apps and recreate all followers.

Once you have an active follower, created by the Dexcom apps, you can use xDrip+ to upload to Dexcom Share.

!!!xdripitem "Dex Share"  
    &ensp;Upload data to Dex share servers

!!!info  
    You can upload your BG to Dexcom Share, **not to Dexcom Clarity**.

!!!xdripitem "Upload BG values as Dexcom Share<span class='symbol'><img src="../../images/EN.png" style="zoom:75%;" /></span>"  
    &ensp;Enable this to upload to Dexcom's servers

If you use an USA account enable this, **for any other country leave it disabled**. 

!!!xdripitem "Dexcom USA based account<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    &ensp;Enable = Your account and follower apps are from the USA

Enter the credentials you use to log into Clarity.

!!!xdripitem "Dexcom Account Login"


!!!xdripitem "Dexcom Account Password"

### Tidepool

!!!xdripitem "Tidepool"  
    &ensp;Upload data to the Tidepool service

If you have a [Tidepool](https://www.tidepool.org/) account, you can upload automatically your data and share with your endocrinologist.  
If xDrip+ can display [basal information from an external status](../use/display/#basal-information), it will also be uploaded to Tidepool.

!!!xdripitem "Sync to Tidepool<span class='symbol'><img src="../../images/ON.png" style="zoom:75%;" /></span>"

Add your email address and password (those you used to [register](https://app.tidepool.org/signup/personal)).

!!!xdripitem "Login User Name"  
    Your Tidepool login user name, normally your email address

!!!xdripitem "Login Password"  
    Your Tidepool login password

Once done, test the connection.

!!!xdripitem "Test Tidepool Login"

Tidepool doesn't need real time data, select the period data will upload, using the cursor. Default is 15 minutes.

!!!xdripitem "Data Age Mins (15)"

Do **NOT** use test servers (keep unselected).

!!!xdripitem "Use integration (test) servers<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"

You can select to upload at specific conditions to save battery and data costs.

!!!xdripitem "Only when charging<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    Upload data only when charging

!!!xdripitem "Only on Wifi<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    Upload data only when connected to an unmetered network like Wifi

If you also upload data manually from your pump, you might want to disable xDrip+ treatments upload to avoid duplicates.

!!!xdripitem "Don't upload treatments<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    Upload only CGM data to avoid duplicates with manual pump upload

If upload fails, enable the new authentication protocol.

!!!xdripitem "Use new Auth<span class='symbol'><img src="../../images/DIS.png" style="zoom:75%;" /></span>"  
    2023 openid authentication method

</br>

[*Last modified 17/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.12.17)
