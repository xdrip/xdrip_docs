### Blucon

You cannot upgrade these devices firmware.  
In order to know the actual firmware version, you need to install the [vendor app](https://www.ambrosiasys.com/our-products/blucon/) and you'll find it in About...

<img src="../images/BluKon_FW.png" style="zoom:75%;" />

All firmware versions will support Libre 1, for Libre 14 days US and Libre 2 you'll need a recent device with minimum firmware version 4.2, and an Out Of Process Algorithm.

### MiaoMiao

Recommended firmware is:

| Device     | Firmware |
| ---------- | -------- |
| MiaoMiao   | 39       |
| MiaoMiao 2 | 7        |
| MiaoMiao 3 | latest   |

In order to upgrade your firmware, you first need to [Forget Device](../systemstatus/#restart-collector-forget-device) from xDrip+ System Status.

For MiaoMiao1 and 2 you can use the vendor APK to upgrade. Follow [these instructions](https://miaomiaoreader.medium.com/how-to-make-libre-us-14-days-sensors-work-with-miaomiao2-on-xdrip-35b431a40940) **from 1 to 4 only. Ignore the rest.**

Another solution that can also be used for MiaoMiao and MiaoMiao 2 and **must** be used for MiaoMiao 3 is to install the [vendor app](http://tomato.cool/) that will automatically upgrade your miaomiao firmware.

Once updated, uninstall the app, reset the device and [Scan Bluetooth](../../install/libreBT/#connect-bluetooth-bridge) in xDrip+ to reconnect.

### Droplet

Follow the instruction [here](https://droplet.rocks/en/blog/manual/firmware-update-instruction).

### Bubble

All firmware are compatible with xDrip+. Always keep the device updated to the latest version.

In order to upgrade your firmware, you first need to [Forget Device](../systemstatus/#restart-collector-forget-device) from xDrip+ System Status.

Download and install the upgrade utility [here](https://github.com/bubbledevteam/BubbleFW_FlashTool/releases).

Once updated, uninstall the app, reset the device and [Scan Bluetooth](../../install/libreBT/#connect-bluetooth-bridge) in xDrip+ to reconnect.

</br>

[*Last modified 28/4/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.03.27)
