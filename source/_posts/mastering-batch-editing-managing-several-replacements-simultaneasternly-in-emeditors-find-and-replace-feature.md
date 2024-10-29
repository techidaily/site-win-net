---
title: "Mastering Batch Editing: Managing Several Replacements Simultaneasternly in EmEditor's Find and Replace Feature"
date: 2024-10-21T19:54:59.988Z
updated: 2024-10-28T19:20:30.817Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/84a4620f422e4279d6cc9c20449448701c42416dfe9f4fbdd744755993fb5c2e.png
---

## Mastering Batch Editing: Managing Several Replacements Simultaneasternly in EmEditor's Find and Replace Feature

October 14, 2011 at 8:01 am [#9733](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/f29c043a3cc5c5dac8db4e62939893e9?s=80&d=identicon&r=g)Stefan](https://www.emeditor.com/forums/users/Stefan/ "View Stefan's profile")

Participant

.

 Hi :-)

 Me thinks that is how the regex engine works?

 You search “,d,” on an string like “10,6,3,12”

 The regex will match “,6,”   
 then it continuous at the very next sign from the rest of the string which is now “3,12”.

 As you see your search pattern will not match on “3,12” because there is no “,d,” anymore.

 The trick is to not match the comas itself as you do but only take an look if they are present.  
 That can be fine done by using positive lookbehind and lookahead which EmEditor supports (thanks Yutaka).  
 For more info about that feature see e.g.: <http://www.regular-expressions.info/lookaround.html>

**Example:**  
 search pattern: “oogl”  
 positive lookbehind if there is an “G” right before your search pattern: (?<=G)  
 positive lookahead if there is an “e” just after your search pattern: (?=e)

 So RegEx search for:  
 (?<=G)oogl(?=e)

 Will match:  
 Woogle  
 G**oogl**e  
 Googlo  
 G**oogl**e  
 Foogle

**Example for your issue with commas:**  
 (?<=,)(d)(?=,)  
 01

 HTH? :lol:

 .

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-cut-to-the-chase-newest-method-for-idevice-screen-recordings-2023/"><u>[New] Cut-to-the-Chase Newest Method for iDevice Screen Recordings, 2023</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-vlogging-vs-micro-video-which-outperforms-for-2024-youtubes-shorts-or-tiktoks/"><u>[Updated] Vlogging Vs. Micro-Video Which Outperforms for 2024 YouTubes Shorts or TikToks?</u></a></li>
<li><a href="https://win-net.techidaily.com/win10-ssd/"><u>關於 Win10 啟動SSD速度放慢的原因和解決法 - 明白</u></a></li>
<li><a href="https://win-net.techidaily.com/automatizando-la-sincronizacion-de-carpetas-con-un-nas-en-windows-11-8-o-7/"><u>Automatizando La Sincronización De Carpetas Con Un NAS en Windows 11, 8 O 7</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comprehensive-steps-acquiring-and-installing-your-hp-laserjet-pro-m402n-driver-on-windows-systems/"><u>Comprehensive Steps: Acquiring & Installing Your HP LaserJet Pro M402n Driver on Windows Systems</u></a></li>
<li><a href="https://win-net.techidaily.com/emeditor-v1500-beta-edition-available-now-ultimate-free-text-editing-experience/"><u>EmEditor v15.0.0 Beta Edition Available Now – Ultimate Free Text Editing Experience</u></a></li>
<li><a href="https://win-net.techidaily.com/fehlende-bitlocker-schlusseloptionen-auf-dem-laufwerk-angehen-losung-fur-windows-10/"><u>Fehlende BitLocker Schlüsseloptionen Auf Dem Laufwerk Angehen - Lösung Für Windows 10</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-oppo-reno-9a-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Oppo Reno 9A Through Google Earth?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-iphone-photography-playbook/"><u>In 2024, The Ultimate iPhone Photography Playbook</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/pushing-the-limits-of-overclocking-splave-and-asrocks-z790i-motherboard-set-unprecedented-world-records-together/"><u>Pushing the Limits of Overclocking: Splave and ASRock's Z790I Motherboard Set Unprecedented World Records Together</u></a></li>
<li><a href="https://win-net.techidaily.com/schnell-abgehoben-wie-man-probleme-mit-der-partition-einrichtung-auf-laufwerk-0-in-windows-beseitigt/"><u>Schnell Abgehoben: Wie Man Probleme Mit Der Partition Einrichtung Auf Laufwerk 0 In Windows Beseitigt</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/trouble-with-iphone-13-swipe-up-try-these-11-solutions-by-drfone-ios/"><u>Trouble with iPhone 13 Swipe-Up? Try These 11 Solutions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-no-rest-for-the-wicked-game-crashes-a-comprehensive-guide-for-windows-users/"><u>Troubleshooting 'No Rest for the Wicked' Game Crashes: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://win-net.techidaily.com/outlookimap/"><u>ローカルバックアップ方法：OutlookでIMAPメールを安全に保管するためのガイド</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

