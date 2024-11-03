---
title: How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills
date: 2024-11-02T19:54:00.256Z
updated: 2024-11-03T21:48:12.298Z
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-eyecapture-screen-logger-x/"><u>[New] 2024 Approved EyeCapture Screen Logger X</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-elite-digital-image-grabbers/"><u>[Updated] Elite Digital Image Grabbers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-ultimate-compilation-best-tools-for-vimeo-files/"><u>[Updated] In 2024, Ultimate Compilation Best Tools for Vimeo Files</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-unlocking-potential-through-virtualization/"><u>[Updated] In 2024, Unlocking Potential Through Virtualization</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-is-it-possible-to-see-all-chatted-content-of-others-for-2024/"><u>[Updated] Is It Possible to See All Chatted Content of Others for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mastering-zero-cost-online-seminars-youtube-edition/"><u>[Updated] Mastering Zero-Cost Online Seminars YouTube Edition</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-value-capture-affordable-cam-options/"><u>[Updated] Value Capture Affordable Cam Options</u></a></li>
<li><a href="https://win-net.techidaily.com/msvcp110dll-5/"><u>重現MSVCP110.dll：失去后的具体指南 - 5个有效的歸還方式</u></a></li>
<li><a href="https://win-net.techidaily.com/centralizzato-strategie-di-backup-con-aomei-guida-per-il-recupero-dei-dati/"><u>Centralizzato: Strategie Di Backup Con AOMEI - Guida per Il Recupero Dei Dati</u></a></li>
<li><a href="https://win-net.techidaily.com/comment-liberer-lecran-damorcage-avec-ces-8-techniques-speciales-sur-windows-et-mac/"><u>Comment Libérer L'Écran D'Amorçage Avec Ces 8 Techniques Spéciales Sur Windows Et Mac</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effortless-troubleshooting-repair-your-razer-microphone-with-simple-solutions/"><u>Effortless Troubleshooting: Repair Your Razer Microphone with Simple Solutions</u></a></li>
<li><a href="https://win-net.techidaily.com/entendiendo-el-acuerdo-de-licencia-con-las-herramientas-de-gestion-de-datos-aomei/"><u>Entendiendo El Acuerdo De Licencia Con Las Herramientas De Gestión De Datos AOMEI</u></a></li>
<li><a href="https://win-net.techidaily.com/fehlerbehebung-akronis-datenspeicherkopie-funktioniert-nicht-korrekt-hilfe-finden-sie-hier/"><u>Fehlerbehebung: Akronis-Datenspeicherkopie Funktioniert Nicht Korrekt - Hilfe Finden Sie Hier!</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-nubia-red-magic-9-proplus-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Nubia Red Magic 9 Pro+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win-net.techidaily.com/mastering-batch-editing-managing-several-replacements-simultaneasternly-in-emeditors-find-and-replace-feature/"><u>Mastering Batch Editing: Managing Several Replacements Simultaneasternly in EmEditor's Find and Replace Feature</u></a></li>
<li><a href="https://win-net.techidaily.com/resolve-wd-my-cloud-not-connecting-on-windows-11-follow-these-12-fixes/"><u>Resolve WD My Cloud Not Connecting on Windows 11 - Follow These 12 Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://win-net.techidaily.com/ultimate-guide-to-kioxia-clone-top-tier-security-and-zero-costs/"><u>Ultimate Guide to KIOXIA Clone: Top-Tier Security and Zero Costs</u></a></li>
<li><a href="https://win-net.techidaily.com/error-code-0x80070002/"><u>ファイルが探索できない状態(Error Code 0X80070002):対処手順と解決策</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

