# ITSelfService
A static local site that can be used locally at CAE Training Centers as a self-service IT station

## Setup Guide

### 1) Equipment required:
- PC (non-CAE W10/11 image)
- touchscreen display

### 2) Download [the latest release](https://github.com/Daniel-lamin/ITSelfService/releases/)
Once downloaded extract .zip to C:\temp\

### 3) Configure Windows in Kiosk user mode
Navigate to Settings → Accounts → Other Users → Kiosk

![image](https://github.com/Daniel-lamin/ITSelfService/assets/94974969/f13fc0ca-d890-44d3-97a8-f01fca1c3c3e)

### 4) Use the below settings to configure kiosk mode

![image](https://github.com/Daniel-lamin/ITSelfService/assets/94974969/138163c6-7e32-4d46-88bf-c382ba2d596e)

The website address should be **C:\temp\ITSelfService-x.x.x\ITSelfService-x.x.x\ITSelfService.html** (Where x.x.x is the latest release version number.)

### 5) Ensure that the screensaver is disabled and power/sleep settings are configured to not hibernate/sleep

### 6) Set the account to autologon

There are two ways to do this:

You can download [SysInternals](https://learn.microsoft.com/en-us/sysinternals/) and configure Autologon.exe with the below settings:
Username: kioskUser0 
Password: [blank]

Alternatively you can [modify the registry directly](https://learn.microsoft.com/en-us/troubleshoot/windows-server/user-profiles-and-logon/turn-on-automatic-logon) using the same credentials.

### 7) Once this is done, reboot the device - You've now successfully configured an ITSelfService Kiosk for your site. Thanks for following and good luck solving all of those new tickets 😁

Please note this guide is for a non-CAE imaged PC -> It is possible to configure on a CAE imaged device but there are extra steps. Please [get in touch](mailto:daniel.fitzgerald@cae.com) if you require further assistance.




