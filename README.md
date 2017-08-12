# Gapps' Runtime Permissions Fixer

Why you need it: Beginning in Android 6.0 (API level 23), users grant permissions to apps while the app is running, not when they install the app. As far as I know, there is not any way to get runtime permissions before you flash Gapps to your system. [See here](https://developer.android.com/training/permissions/requesting.html).  

So if your android system (for example MIUI) did not give the runtime permissions for Gapps you flashed, you should fix it manually.[ See here](https://github.com/opengapps/opengapps/wiki/Notes-for-Android-6.0). The script we use in this module comes from the same article.
  
For anyone who uses [OpenGapps](https://github.com/opengapps)/[BeansGapps](https://gitlab.com/PureNexus/BeansGapps)/[MagicGApps
](https://github.com/Magisk-Modules-Repo/MagicGApps), and experiences crashes of GMS or problems to sync contacts or calendar.

This Module is a one-shot script, can be removed after install.

## Request
[Magisk](https://github.com/topjohnwu/Magisk)  

## Useage
* Download this repo
* Add all files (but not the repo directory itself) into a zip file
* Copy the zip file to your android device
* Use Magisk Manager to install that zip file
* Done
* After reboot, you can remove the module frome Magisk Manager