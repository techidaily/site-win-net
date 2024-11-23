---
title: How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills
date: 2024-11-22T01:55:55.893Z
updated: 2024-11-22T23:30:09.078Z
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
<li><a href="https://fox-friendly.techidaily.com/new-best-webp-converter-how-to-convert-webp-to-jpg/"><u>[New] Best WebP Converter How to Convert WebP to JPG</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-logo-mastery-for-podcasts-elevate-your-visual-impact/"><u>[New] Logo Mastery for Podcasts Elevate Your Visual Impact</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-discovering-if-muted-on-snapstreak/"><u>[Updated] 2024 Approved Discovering If Muted on Snapstreak</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-story-arcs-in-cinemas-pantheon/"><u>[Updated] Iconic Story Arcs in Cinema’s Pantheon</u></a></li>
<li><a href="https://win-net.techidaily.com/1-effortless-file-recovery-solutions-for-auto-deleted-data-on-your-pc/"><u>1. Effortless File Recovery: Solutions for Auto-Deleted Data on Your PC</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-masterclass-in-tv-streaming-the-ultimate-guide/"><u>2024 Approved Masterclass in TV Streaming The Ultimate Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/determining-ideal-icloud-storage-capacity-for-effective-data-backups/"><u>Determining Ideal iCloud Storage Capacity for Effective Data Backups</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-itel-p55-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Itel P55 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-proven-strategies-for-creating-superb-igtv-videos-on-smartphonesdlsrs/"><u>In 2024, Proven Strategies for Creating Superb IGTV Videos on Smartphones/DLSRs</u></a></li>
<li><a href="https://win-net.techidaily.com/modi-per-risolvere-il-problema-di-restauro-dei-file-in-lightroom-tre-tecniche-efficaci/"><u>Modi Per Risolvere Il Problema Di Restauro Dei File in Lightroom: Tre Tecniche Efficaci</u></a></li>
<li><a href="https://discover-blog.techidaily.com/next-level-graphics-boost-gameplay-fluidity-and-performance-using-advanced-ai-frame-rate-optimization/"><u>Next-Level Graphics: Boost Gameplay Fluidity and Performance Using Advanced AI Frame Rate Optimization</u></a></li>
<li><a href="https://win-net.techidaily.com/perifernal-inputoutput-error-triggers-unprocessed-request/"><u>Perifernal Input/Output Error Triggers Unprocessed Request</u></a></li>
<li><a href="https://win-net.techidaily.com/schritt-fur-schritt-anleitung-zum-sicheren-datentransfer-zwischen-zwei-computern/"><u>Schritt-Für-Schritt Anleitung Zum Sicheren Datentransfer Zwischen Zwei Computern</u></a></li>
<li><a href="https://win-net.techidaily.com/step-by-step-instructions-for-crafting-a-sony-vaio-system-repair-disc-with-windows-7/"><u>Step-by-Step Instructions for Crafting a Sony Vaio System Repair Disc with Windows 7</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-guide-for-elevating-videos-from-basic-sdr-to-breathtaking-hdr-splendor/"><u>Ultimate Guide for Elevating Videos From Basic SDR to Breathtaking HDR Splendor</u></a></li>
<li><a href="https://win-net.techidaily.com/whatsappicloud/"><u>WhatsAppデータのiCloud確認と表示：ステップバイステップ・チュートリアル</u></a></li>
<li><a href="https://win-net.techidaily.com/xcopy-vs-robocopy-a-comprehensive-feature-and-alternative-solution-comparison/"><u>Xcopy Vs. Robocopy: A Comprehensive Feature and Alternative Solution Comparison</u></a></li>
<li><a href="https://win-net.techidaily.com/1728486521765-windows-11/"><u>どうやってWindows 11システム画像バックアップを回復する?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

