---
title: Sailfish OS for Nexus 4 updated to version 2.1.3.7 for 2018
date: 2018-05-21T20:13:31+02:00
lastmod: 2018-05-21T22:13:31+02:00
draft: false
categories:
  - Nexus4
  - technology
  - tutorial
  - Custom-rom
tags:
  - Nexus4
  - technology
  - tutorial
  - Custom-rom
slug: sailfish-os-nexus-4-2018-updated
comments: true
description: Sailfish OS port for Nexus 4 (mako) updated version 2.1.3.7 for 2018. Download links, installation and review (updated).
# menu: main
# weight: -210
---

# Sailfish OS for Nexus 4 updated to version 2.1.3.7 for 2018

Recently, I was browsing the internet, hoping to find some news about the long-untouched Sailfish OS port for the Nexus 4. According to the [merproject site](https://wiki.merproject.org/wiki/Adaptations/libhybris/Install_SailfishOS_for_mako) the latest Sailfish port for the Nexus 4 is still the gamma 8 version, which corresponds to Sailfish OS 2.0.5.6 (file list [here](http://images.devaamo.fi/sfe/mako/)).

**However**, today I was browsing the [4pda.ru forum about the Sailfish OS port for the Nexus 4](https://4pda.ru/forum/index.php?showtopic=559889&st=780) where someone posted a link to the sailfish os mako release version 2.1.3.7 based on CM-13 .

[Here is the download link for both the Cyanogenmod 13 SNAPSHOT and Sailfish OS mako version 2.1.3.7](https://yadi.sk/d/huAt-End3S4H7x).

So let’s take a look how this stuff works.

# Installation

I am using the [latest TWRP recovery for Nexus 4](https://eu.dl.twrp.me/mako/).

The installations instructions are totally the same as [in my last post about Sailfish OS on the Nexus 4](../sailfish-os-on-nexus-4/).

Here is a quick run-down:

- Backup first (duh)
- Flash the latest TWRP recovery 
- Make a full wipe in the recovery (go to Advanced Wipe and check everything)
- Transfer both .zip files to the phone
- Install the cm-13-xx.zip 
- Install sailfishos-xx.zip
- Reboot

**Oh yeah, I am not responsible if you brick your device. Also, you lose all your data in the process of installation.**

# Review Sailfish OS 2.1.3.7 on Nexus 4

Now, let’s take a look how this Sailfish version works.

And unfortunately, there is directly one really big flaw: The camera doesn’t work! I haven’t found out the reason for that yet, but I will keep this blog page updated for more news.

Bluetooth seems to work just fine (in contrary to [my previous post](../sailfish-os-on-nexus-4/)). 

However, the Jolla AppStore still doesn’t really work (it refuses to download the stock apps), but apparently it is possible to add open repositories (which don’t require authentication), and obtain apps from there. Last but not least you could always install the .rpm’s manually.

# Screenshots Sailfish OS 2.1.3.7 on Nexus 4

Here are some screenshots:

![Sailfish 2.1 on Nexus 4, welcome screen](/images/blog/sailfish21scr1.jpg)

*Sailfish 2.1 on Nexus 4, welcome screen*

![Sailfish 2.1 on Nexus 4, device information](/images/blog/sailfish21scr2.jpg)

*Sailfish 2.1 on Nexus 4, device information*

![Sailfish 2.1 on Nexus 4, camera issue](/images/blog/sailfish21scr3.jpg)

*Sailfish 2.1 on Nexus 4, camera issue*

# Conclusion

It is nice that porters are still at work. But the camera, which is not working, is, until now, a deal breaker.
For the future maybe I will dive deeper into the actual porting process, perhaps build it myself.

For now, I will keep this page updated to any new developments regarding the state of Sailfish OS for the Nexus 4 in 2018.