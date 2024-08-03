<img src="../../images/hamburger_menu.png" style="zoom:75%;" />  
<img src="../../images/M-S.png" style="zoom:75%;" />  
<img src="../../images/M-S-HDS.png" style="zoom:75%;" />  
<img src="../images/M-S-HDSlistE.png" style="zoom:75%;" />

!!!warning "Work in progress"  
    In July 2024, Google shutdown the deprecated the [Firebase API](https://firebase.google.com/docs/cloud-messaging/migrate-v1) xDrip+ used for xDrip+ Sync.  
    A workaround solution was implemented in [July 23rd pre-release](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) but outstanding issues make the follower app lose connection after few minutes.  
    If you need to use xDrip+ Sync, the master device must be of a minimum version [July 23rd 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.07.23) but the followers should be of a maximum version [June 28th 2024](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.06.28).

Select this data source if you've setup a device with xDrip+ as master and decided this other device will be the follower.  
A master device is usually the one getting BG from the sensor.  
A follower replicates readings from the master device real time (network latency applies).

There is virtually no limit in the amount of xDrip+ follower devices.

See [here](../../use/syncsetup) how to setup xDrip+ Sync follower. 

</br>

[*Last modified 3/8/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.08.03)
