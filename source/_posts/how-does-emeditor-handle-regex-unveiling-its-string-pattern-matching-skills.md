---
title: How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills
date: 2024-11-24T16:24:20.520Z
updated: 2024-11-30T23:29:21.165Z
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
<li><a href="https://fox-info.techidaily.com/updated-in-2024-cutting-edge-4k-tools-for-optimal-video-quality/"><u>[Updated] In 2024, Cutting-Edge 4K Tools for Optimal Video Quality</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-roadmap-to-youtube-fame-essential-steps-for-successful-content/"><u>[Updated] The Roadmap to YouTube Fame Essential Steps for Successful Content</u></a></li>
<li><a href="https://win-net.techidaily.com/1728464677201-windows/"><u>如何在Windows系统中回答資源回收桶還原手冊：高效指南</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/inners-guide-to-elevating-auditory-experiences-on-youtube/"><u>A Beginner's Guide to Elevating Auditory Experiences on YouTube</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-motorola-moto-g13-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Motorola Moto G13 is off? | Dr.fone</u></a></li>
<li><a href="https://win-top.techidaily.com/decoding-session-identifiers-in-depth-insights-and-key-seo-techniques-for-enhanced-online-visibility/"><u>Decoding Session Identifiers: In-Depth Insights & Key SEO Techniques for Enhanced Online Visibility</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/explore-the-past-reverse-video-on-ios-devices/"><u>Explore the Past Reverse Video on iOS Devices</u></a></li>
<li><a href="https://win-net.techidaily.com/how-to-repair-and-revive-a-non-functional-toshiba-storage-device/"><u>How To Repair and Revive a Non-Functional Toshiba Storage Device</u></a></li>
<li><a href="https://win-net.techidaily.com/verstehen-sie-das-wunder-der-hyper-v-virtualisierung-fur-physische-computer-erleuchtende-tipps-zum-erstellen-von-virtuellen-umgebungen/"><u>Verstehen Sie Das Wunder Der Hyper-V Virtualisierung Für Physische Computer: Erleuchtende Tipps Zum Erstellen Von Virtuellen Umgebungen</u></a></li>
<li><a href="https://win-net.techidaily.com/wiederherstellung-verlorener-bilder-schritt-fur-schritt-anleitung-zur-wiederherstellung-von-geloschten-bildern-auf-verschiedenen-endgeraten/"><u>Wiederherstellung Verlorener Bilder: Schritt-Für-Schritt-Anleitung Zur Wiederherstellung Von Gelöschten Bildern Auf Verschiedenen Endgeräten</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

