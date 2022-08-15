<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../use/images/M-S-SW.png" style="zoom:75%;" />

<img src="../images/M-S-SW-BJ.png" style="zoom:76%;" />

You can buy your BlueJay Watch [here: <img src="../images/M-S-SW-BJ1.png" style="zoom:100%;" />](https://bluejay.website/) 

Two generations of BlueJay are available.  
You need to setup X2 with xDrip+, then you can make it standalone.  
[GTS](https://bluejay.website/shop/product/bluejay-gts-26) can be setup without xDrip+ (only standalone) and also with xDrip+.

!!!info "Sharing BG"  
    BlueJay is only Bluetooth and cannot share BG data without being connected to your phone xDrip+.

BlueJay watches are powerful companions for your G5, G6 and ONE sensors. They both connect directly to the transmitter but you need to be aware of the limitations.

##### G5 and ONE

These transmitters only have one Bluetooth slot.  
If you want to connect BlueJay you need to disconnect the transmitter from any other app or receiver.

##### G6

G6 transmitters have two Bluetooth slots: phone and non-phone.  
You can configure your slots as per the table below. Only two devices can be connected simultaneously to the transmitter, each one using a unique slot.  
By default BlueJay uses the non-phone slot. See [here](#run-collector) how to change this setting.

| Vendor app          | Receiver                | Connected pump                            | BlueJay Watch                             |
| ------------------- | ----------------------- | ----------------------------------------- | ----------------------------------------- |
| Cannot be used      | Cannot be used          | Cannot be used                            | Non-phone slot **xDrip+ uses phone slot** |
| **Uses phone slot** | Cannot be used          | Cannot be used                            | Non-phone slot                            |
| Cannot be used      | **Uses non-phone slot** | Cannot be used                            | Phone slot                                |
| Cannot be used      | Cannot be used          | t:slim, Omnipod 5 **use non-phone slots** | Phone slot                                |
| Cannot be used      | Cannot be used          | CamAPS, DBLG1 **use phone slot**          | Non-phone slot                            |

*Note: xDrip+ uses the phone slot by default, non-phone slot requires engineering mode*

### Pair your watch to xDrip+

1. Make sure the watch is charged before starting.
2. Enable BlueJay and disable watch collector.  
   <img src="../images/M-S-SW-BJb.png" style="zoom:76%;" />
3. If you have a BlueJay GTS continue to 6.  
   If you have a BlueJay X2 it should show a QR code on the screen.  
   <img src="../images/M-S-SW-BJc5.png" style="zoom:40%;" />  
   If you see it continue to 7.
4. Launch BlueJay Panel and Scan.  
   <img src="../images/M-S-SW-BJc.png" style="zoom:76%;" />  
   <img src="../images/M-S-SW-BJc1.png" style="zoom:76%;" />  
   When the watch is detected you should see its Mac address. Select it.  
   <img src="../images/M-S-SW-BJc2.png" style="zoom:66%;" /></br>  
   If xDrip+ doesn't find the watch, try to restart your phone and retry. If you still can't find it: you can enter the watch Mac address manually in BlueJay Advanced Settings -> BlueJay Mac   
   <img src="../images/M-S-SW-BJcb.png" style="zoom:76%;" /> </br>  
   The QR code should now appear on the watch, if you see it: continue to 7.
5. If the QR code didn't show-up on your watch, select QR and retry.  
   <img src="../images/M-S-SW-BJc4.png" style="zoom:76%;" />  
   If you still can't see the QR code try REBOOT then [contact](https://bluejay.website/contactus) the vendor for assistance or seek help [here](https://gitter.im/jamorham/BlueJay).
6. On the GTS follow this menu sequence to display the QR code:  
   Settings Menu -> Admin Menu -> Show QR Code  
   <img src="../images/M-S-SW-BJc6.png" style="zoom:76%;" /> 
7. In xDrip+ scan the watch QR code  
   <img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
   <img src="../../use/images/M-S-AC.png" style="zoom:75%;" />  
   You need to authorize xDrip+ to access the phone camera.  
   Scan the QR code displayed on the watch.  
   <img src="../images/M-S-SW-BJc7.png" style="zoom:50%;" />

Setup the watch as a follower and you should see your BG within minutes.

<img src="../images/M-S-SW-BJc9.png" style="zoom:76%;" /> 

<img src="../images/M-S-SW-BJca.png" style="zoom:50%;" /> 

Check [System Status](../../troubleshoot/systemstatus/) to confirm the watch paired correctly. Swipe to the advanced status tab BlueJay.  

<img src="../images/M-S-SW-BJc8.png" style="zoom:66%;" />

If the xDrip core is not installed you should install it now.

### Install the xDrip Core 

!!!warning "Put the watch in charge whilst installing the core"

In xDrip+ System Status, BlueJay advanced status, tap the red line xDrip Core: Not Installed.

<img src="../images/M-S-SW-BJd1.png" style="zoom:71%;" />

Select OK to update the watch.

<img src="../images/M-S-SW-BJd2.png" style="zoom:79%;" />

Check System Status afterwards, you should see the core installed.

<img src="../images/M-S-SW-BJd3.png" style="zoom:66%;" />

### Run collector

Run collector means you will be using the watch without having necessarily your phone with you.

You must setup the watch using xDrip+ if you use an X2 model.  
For GTS you can do it directly through the watch [menu](https://bluejay.website/gts-menu-top), without using xDrip+.

In order to use the watch with xDrip+ you must have a transmitter directly connected to xDrip+ with BG data currently displaying in xDrip+.

Define which slot will connect to the transmitter. Refer to the table [above](#g6) to setup your slots.

<img src="../images/M-S-SW-BJe1.png" style="zoom:76%;" />

##### Run Phone Collector

Enables/disable the connection of xDrip+ to the transmitter (using the phone slot).

##### BlueJay uses Phone slot

By default BlueJay uses the non-phone slot. You can let it use the phone slot with this option but you should then disable Run Phone Collector above.

<img src="../images/M-S-SW-BJe2.png" style="zoom:76%;" />

Once slots setup you can enable the watch as a standalone collector device.

<img src="../images/M-S-SW-BJe3.png" style="zoom:76%;" />

You will then see your phone xDrip+ is not connected to the transmitter anymore: BlueJay is.  
When your watch is within Bluetooth range, your phone should receive BG from BlueJay.

<img src="../images/M-S-SW-BJe4.png" style="zoom:66%;" />

## BlueJay GTS

GTS doesn't need xDrip+ to be setup but the steps above should also apply if you want to so so.

See the video [here](https://www.youtube.com/watch?v=JM5cw-xVAZk) for a guided tour.

See here [how](https://www.youtube.com/watch?v=6YpjuZe2c_Q) to connect to the transmitter.

</br>

[*Last modified 3/8/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.08.03)