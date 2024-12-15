You can update xDrip+ by installing another version on top of the current one without uninstalling it, the same way you originally [installed](../../install/download) it.

You can also use xDrip+ internal update mechanism.

!!!xdrip "<img src="../../images/hamburger_menu.png" style="zoom:75%;" />"  
    &ensp;Settings  
    &emsp;<img src="https://raw.githubusercontent.com/NightscoutFoundation/xDrip/master/app/src/main/res/drawable-xhdpi/ic_briefcase_download_grey600_48dp.png" style="width:5%;" />&ensp;xDrip+ Update Settings

Update settings allows you to choose between various xDrip+ versions update.

!!!warning "DO NOT UNINSTALL xDRIP+"  
    You can upgrade and downgrade xDrip+ just installing a newer or an older version on top of the current one.  
    Uninstalling xDrip+ might lead to complete and unrecoverable data loss if you don't [backup](../../troubleshoot/reinstall/#reinstall-xdrip).

Only xDrip+ official versions can use this feature.  
If you installed a [forked version](../../install/download/#forked-versions), only the author can provide upgrades. 

!!!note  
    Updating xDrip+ is completely transparent and will not require any specific actions on your current sensor.  
    Your settings will be maintained unless a serious modification was made on a specific setting.  
    As a precaution it's better to keep xDrip+ monitored if you selected an alpha or nightly release.

You should enable automatic update check.

!!!xdripitem "Automatic update check <span class='symbol'><img src="../../images/ON.png" style="zoom:75%;" /></span>"  
    &ensp;Get notified of new apk releases  

If you leave it disabled xDrip+ will remind you to update every 60 days.

!!!xdripitem "Hey fam..."  
    &ensp;You have update checks switched off!  
    &ensp;We try to fix bug and add xDrip+ features over time.  
    &ensp;Every 60 days this reminder will appear to ask you to turn update checking on.  

There are four update channels:

- Stable: released versions that proved stability and reliability
- Beta: versions that are candidates to stable release
- Alpha: versions in development

Once Alpha selected, update and you can see a new option:

- Nightly: prototypes for testing

Most tested versions will not include latest features and fixes.

Less tested versions might include bugs but will also include latest features and fixes.

!!!xdripitem "Update channel (beta)"  
    &ensp;Choose Stable, Beta or Alpha release

!!!xdripitem "Update Channel"  
    &ensp;Stable - tried and tested versions  
    &ensp;Beta - new features but not fully tested  
    &ensp;Alpha - versions for early testing  
    &ensp;Nightly - untested raw code - experts only!

Looking in the [official repository](https://github.com/NightscoutFoundation/xDrip/releases), you can identify the latest release by the label Latest.    
You can download the latest release [here](https://xdrip-plus-updates.appspot.com/stable/xdrip-plus-latest.apk).  
All others are labelled Pre-release.

<img src="../images/M-S-US2b.png" style="zoom:75%;" />

Reporting features are not used anymore. If you need support use [discussions](https://github.com/NightscoutFoundation/xDrip/discussions) or [Facebook](https://www.facebook.com/groups/xDripG5).

!!!xdripitem "Automatic crash reporting"

!!!xdripitem "Enable telemetry"

Feedback in not used anymore. Only use it for compliments.

!!!xdripitem "Send feedback message"

### Update

You can update xDrip+ by installing another version on top of the current one without uninstalling it, the same way you originally [installed](../../install/download) it.

You can also use xDrip+ internal update mechanism.

Update available notifications will trigger based on your channel selection.  
You can manually request a check if you disabled automatic update check using the [3 dots menu](../3dotsmenu/#check-for-updated-version).

1. The currently update channel will be displayed
2. Current and newer (available) versions
3. Download now will start the update download, Android will ask for the install authorization when download is complete.
4. You can disable automatic updates. This has the same effect than the automatic update check button above.
5. If you don't use the internal downloader, your device will use the default app for downloading internet files.
6. Exit without doing anything.

<img src="../images/M-S-US5.png" style="zoom:75%;" />

If selecting the internal downloader you will see a progress bar and once complete, the install will start automatically.

<img src="../images/M-S-US6.png" style="zoom:75%;" />

If you didn't select the internal downloader your phone will download the package from [GitHub](https://github.com/NightscoutFoundation/xDrip/releases) and launch the install once complete.

No new permissions should be required.

 <img src="../images/M-S-US6a.png" style="zoom:75%;" />

Once upgraded you can verify the current version in [system status](../../troubleshoot/systemstatus).

### Downgrade

You don't need to uninstall xDrip+ to return to an older version (unless [switching from official to forked version](../../troubleshoot/reinstall/) and the other way round): just install the version you want on top of the current one [like you did at first install](../../install/download/).

</br>

[*Last modified 15/12/2024*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2024.11.26)
