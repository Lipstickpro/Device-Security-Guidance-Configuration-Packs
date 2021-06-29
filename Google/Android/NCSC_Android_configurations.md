## NCSC Android configurations ##
|MDM settings||
|---|---|
||
|General Settings||
|Enable application auditing in personal space. |Disabled|
|Wipe if device isn’t synced within a set time period. |Disabled|
|Allow users to wipe their devices from Find My Device.|Disabled|
||
|Work Profile||
|Work Profile in Android for Work supported devices running Google Apps Device Policy|Enforce|
|Apply password settings only for the Work Profile. (supported from Android 7.0+, for older devices, password applies to the entire device)|Disabled |
||
|Apps and Data Sharing||
|Allow controlling installed applications. |Enabled|
|Allow application verification to be turned off. |Disabled|
|Allow USB file transfer. (company owned only) |Disabled*|
|Allow non-Play Store apps from unknown sources installation. |Disabled|
|Allow developer options to be turned on. |Disabled|
|Allow location sharing with apps. |Disabled*|
|Allow screen capture. |Disabled*|
|Allow content sharing from Work Profile to personal space. (Work Profile only) |Disabled*|
|Allow copy and paste between Work Profile and personal space. (Work Profile only) |Disabled*|
|Allow outgoing Beam. |Disabled*|
|Set the default option for runtime permission requests from apps.|Prompt User*|
||
|Users and Accounts||
|Allow user addition. (company owned only) |Disabled|
|Allow user removal. (company owned only) |Disabled|
|Allow account addition and removal. |Disabled*|
|Allow Google Accounts addition. (Only allowed if the Accounts section above is enabled)|Disabled|
||
|Networks||
|Allow network settings modification. |Enabled  |
|Allow Bluetooth configuration.|Disabled|
|Allow VPN access configuration. |Enabled|
|Allow tethering and portable hotspot setup. |Disabled|
|Allow mobile network settings modification. |Enabled|
|Allow cell broadcast settings modifications.|Enabled|
||
|Device Features ||
|Allow external SD card. |Enabled**|
|Allow trusted credentials modification. |Enabled|
|Allow microphone. |Enabled|
|Allow speaker. |Enabled|
|Enable remote management of administrator restriction PIN. |Disabled|
|Allow users to do factory reset |Disabled|
|Enter up to 10 admins who can sign in to a device after factory reset. |Null|
|Allow user to edit the date and time. |Disabled|
|Allow user to connect to data services when roaming. |Enabled|
|Allow user to reboot device in safe mode.|Disabled|
||
|Lock Screen Sharing ||
|Allow lock screen features and enable unlisted lock screen features (e.g. facial recognition).|Disabled*|
|Allow notification details. |Disabled |
|Allow notifications.|Enabled|
|Allow trust agents. |Enabled|
|Allow camera. |Disabled*|
|Allow fingerprint unlock.|Enabled  |
||
|* Should be assesed against business need and risk ||
|** Either secured by Android 10 or not applicable for Android 10||
||