---
title: How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills
date: 2024-10-25T19:30:15.211Z
updated: 2024-10-28T19:05:36.813Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/3f251edfe87940db023c8b9c0c8cf809bbc15f1b02387807fe3914c9b67e4de7.jpg
---

## How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills

Viewing 8 posts - 1 through 8 (of 8 total)

* Author  
Posts
* September 5, 2010 at 5:02 am [#8922](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/eb16ee29fcd506f98fc630a3029fd690?s=80&d=identicon&r=g)hydra](https://www.emeditor.com/forums/users/hydra/ "View hydra's profile")  
Member  
i have a string that contains 3 characters that vary, it looks like this: board=XYZ  
 note: sometimes X=Y, or Y=Z (they can be either a letter or a number). thus, sometimes the string will read like this: board=K66.  
 what i want to do, is to find every instance where the variable pattern looks like “XYY” and switch the order to be “YYX”. can emeditor do this using the regular expression function? or can it only be done via script/macro?  
September 5, 2010 at 5:28 am [#8923](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello hydra,  
 In the Replace dialog box, you can use replace  
 \=(w)(ww)  
 with  
 \=21  
 and check Use Regular Expressions.  
 Please let me know if you have further questions.  
 Thank you!  
September 5, 2010 at 5:51 am [#8924](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/eb16ee29fcd506f98fc630a3029fd690?s=80&d=identicon&r=g)hydra](https://www.emeditor.com/forums/users/hydra/ "View hydra's profile")  
Member  
hi yutaka,  
 thx for the quick reply, however it doesnt do what i need it to do. allow me to explain:  
 1\. when the pattern “board=XYY” is found, i need it to be changed to “board=YYX”. your above suggestion does this. so far so good.  
 2\. BUT, when the pattern XXY is found, i want it to do nothing! your above suggestion changes all instances of XXY into XYX. this is something i must avoid.  
 is there any expression that can do both #1 while avoiding #2?  
September 5, 2010 at 6:00 am [#8925](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/eb16ee29fcd506f98fc630a3029fd690?s=80&d=identicon&r=g)hydra](https://www.emeditor.com/forums/users/hydra/ "View hydra's profile")  
Member  
if the regular expression function cant do this, can u write a simple script/macro that does this for me?  
September 5, 2010 at 6:49 am [#8926](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ec03db8a2a7b8dea60b1c9f8f11901d9?s=80&d=identicon&r=g)Jibz](https://www.emeditor.com/forums/users/Jibz/ "View Jibz's profile")  
Member  
Try searching for  
=(w)((w)3)  
 and replace with  
=21  
September 5, 2010 at 7:02 am [#8927](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/eb16ee29fcd506f98fc630a3029fd690?s=80&d=identicon&r=g)hydra](https://www.emeditor.com/forums/users/hydra/ "View hydra's profile")  
Member  
jibz,  
 such an elegant solution! thank u so much!  
September 5, 2010 at 6:54 pm [#8928](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
That’s an excellent solution. Thnaks jibz!  
September 6, 2010 at 5:20 am [#8929](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ec03db8a2a7b8dea60b1c9f8f11901d9?s=80&d=identicon&r=g)Jibz](https://www.emeditor.com/forums/users/Jibz/ "View Jibz's profile")  
Member  
Glad to hear it worked :-).
* Author  
Posts

Viewing 8 posts - 1 through 8 (of 8 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-above-and-beyond-uavs-for-gopro-recording-excellence/"><u>[Updated] 2024 Approved Above and Beyond UAVs for GoPro Recording Excellence</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-social-media-synergy-connecting-twitch-streams-with-fb/"><u>2024 Approved Social Media Synergy Connecting Twitch Streams with FB</u></a></li>
<li><a href="https://win-net.techidaily.com/erstellen-eines-wiederherstellungspfades-fur-windows-710-auf-einem-usb-datentrager-schritt-fur-schritt-anleitung/"><u>Erstellen Eines Wiederherstellungspfades Für Windows 7/10 Auf Einem USB-Datenträger - Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://extra-information.techidaily.com/hooking-audience-early-with-smart-intros/"><u>Hooking Audience Early with Smart Intros</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exploring-gospel-music-how-to-download-and-modify-your-ringtone/"><u>In 2024, Exploring Gospel Music How to Download & Modify Your Ringtone</u></a></li>
<li><a href="https://article-helps.techidaily.com/innovative-use-of-movie-maker-for-digital-storytelling-for-2024/"><u>Innovative Use of Movie Maker for Digital Storytelling for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/manual-gps-deception-techniques-to-falsify-cellular-device-positioning-data/"><u>Manual GPS Deception: Techniques to Falsify Cellular Device Positioning Data</u></a></li>
<li><a href="https://win-net.techidaily.com/ricostruire-il-tuo-profilo-wechat-su-iphone-dopo-leliminazione-della-cronologia-dei-messaggi/"><u>Ricostruire Il Tuo Profilo WeChat Su iPhone Dopo L'eliminazione Della Cronologia Dei Messaggi</u></a></li>
<li><a href="https://win-net.techidaily.com/step-by-step-guide-building-a-bootable-windows-7-live-usb-without-using-an-iso-file/"><u>Step-by-Step Guide: Building a Bootable Windows 7 Live USB Without Using an ISO File</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-15-apps-to-hack-wifi-password-on-samsung-galaxy-a15-5g-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://win-net.techidaily.com/troubleshoot-windows-to-go-drive-issues-with-these-5-steps/"><u>Troubleshoot Windows To Go Drive Issues with These 5 Steps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-video-tagging-software-for-mac-a-comprehensive-review/"><u>Updated Best Video Tagging Software for Mac A Comprehensive Review</u></a></li>
<li><a href="https://win-net.techidaily.com/website-error-alert-page-unavailable-http-404/"><u>Website Error Alert: Page Unavailable (HTTP 404)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

