---
title: Signal Strength FAQs
permalink: /nss_faqs/
---
#### Dual SIM Signal
* Android can only read Signal Strength from the SIM selected for Voice Calls. So in SIM settings change to SIM1/SIM2 for voice calls for reading the signal in the app. Also Do Not keep Prefered SIM settings to "Ask" in Dual SIM phones else nothing will be reported.

#### Signal not updating
* There is a known issue of signal refresh with some phones and not a limitation of the app. Some phones/ROMs particularly a few Samsung stock ROMs dont seem to be supporting cellular signal strength update. Feedback by email would be appreciated

#### Cell towers not visible
* If your phone does not implement the Android standard correctly then the Cell tower info is not displayed

#### LTE errors
* LTE is being implemented in subtle variations by various OEMs and Carriers away from the Android reporting standard and hence some devices will not show the information correctly. Please contribute debug reports from App Navigation Menu • Support • Report Bugs so that all variations can be incorporated

#### Adfree Version
* The app is completely free except for Adfree which can be unlocked through the Play Store. Try the free version first before you unlock.
* If you want to reinstall the app only choose that account from which you bought the unlock option. Then you can reinstall and adfree will be available. This is really relevant when you have multiple accounts in your phone.

#### Tech Note - Signal
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
