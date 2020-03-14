---
layout: default
title: Signal Strength FAQs
permalink: /nss_faqs/
---

#### Purchase Issues - Things to try
* Use the same google account from which purchases have been made.
* Try reinstalling app
* Try restarting device
* Check network connection is available.
* From Android Settings -> Apps -> Play store -> Clear cache
* Try on another device
* Have you got the purchase confirmation email from google? 

If the above steps are not giving result email me the order id of your purchase. It will be there in the email you must have received from Google.

#### Widget issues - Things to try
* Widgets freezing - Start and exit app
* Widgets freezing - Try restarting device
* Check if a red flag is appearing on app main screen. Click this red flag and resolve the issues.
* Widget update notifications - Disable by double clicking widget or long pressing App icon -> Notifications -> Disable
* If app has been moved to sdcard please move it back to internal storage. Widgets will not work when app is installed in sdcard.
* Reinstall app
* There may be some utilities like battery savers, memory optimizers, task killers etc which may be interfering with the app. Try after temporarily disabling them.
* Try adjusting launcher grid. If possible keep it at default grid layout which mostly is 4x4
* Try with a different launcher

#### New Android permissions
* All cellular and wifi scan functions need location permission. Location toggle is also to be enabled from the status bar. 
The app does not need location information however cellular/wifi scan info may possibly contain location info from the cell towers and Wifi routers. 
Hence Android has mandated location permissions/location enabling for using these functions.

#### Errors
* Some devices do not fully support the Android reporting standard for dual SIM, LTE etc. Please contribute debug reports from App Navigation Menu • Support • Report Bugs so that all variations can be incorporated

#### 5G
* Will be coming soon

<hr/>

#### Tech Notes :-

#### Signal
* The Cellular and WiFi signal varies in orders of 1000s (The full range is actually more than a million times) which is difficult to appreciate and hence the unit called dBm is used which presents the data in a nice logarithmic manner
* WiFi -95dBm to -35dBm
* GSM -113dBm to -51dBm
* CDMA -100dBm to -75dBm
* EVDO -105dBm to -65dBm
* LTE -140dBm to -44dBm

#### Tech Note - Networks
* 2G - GPRS,EDGE,CDMA,IDEN
* 3G - HSPA,HSUPA,HSDPA,EHRPD,1XRTT,EVDO,UMTS,HSPA+
* 4G - LTE
* LTE and EVDO are pure data channels. Your phone by default shows the signal strength of voice channels like cdma or gsm. Even if you are on a LTE/EVDO network the phone uses these GSM/CDMA channels for voice communication. If you are on a Voice over LTE operator then LTE carries both Voice and Data.

#### Tech Note - Technologies
* GSM - Global System for Mobile Communications
* CDMA - Code Division Multiple Access
* EDGE - Enhanced Data GSM Environment
* HSPA - High Speed Packet Access
* HSUPA - High Speed Uplink Packet Access
* HSDPA - High Speed Downlink Packet Access
* EHRPD - Evolved High Rate Packet Data
* 1xRTT - CDMA Data Mode
* EVDO - Evolution Data Optimized
* UMTS - Universal Mobile Telecommunications System
* HSPA+ - Evolved HSPA
* LTE - Long Term Evolution
* CDMA/EVDO Ec/Io - This is a measure of the quality of your CDMA/EVDO channel. This is more important than the corresponding CDMA/EVDO strength or RSSI channel
* LTE RSRP - Reference Signal Received Power. This is the main measurement in LTE channels and indicates the average strength of the reference signal
* LTE RSRQ - Reference Signal Received Quality. This indicates the quality of the LTE signal
* Note - If you get good strength but poor quality then connection will also be poor. Conversely if you get poor strength but good quality then your connection is likely to still be good

[back](/)
