---
title: How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills
date: 2024-10-19T22:40:54.857Z
updated: 2024-10-23T04:03:47.937Z
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
<li><a href="https://extra-hints.techidaily.com/best-laughs-in-layout-designer-for-2024/"><u>Best Laughs in Layout Designer for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-honor-magic-6-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Honor Magic 6 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/expert-insight-on-linksys-wrt3200acm-why-it-stands-out-amongst-open-source-router-options/"><u>Expert Insight on Linksys WRT3200ACM: Why It Stands Out Amongst Open Source Router Options</u></a></li>
<li><a href="https://win-answers.techidaily.com/no-more-crashes-discover-how-to-play-pathfinder-wrath-of-the-righteamaximized-for-pc/"><u>No More Crashes! Discover How to Play Pathfinder: Wrath of the Righteamaximized for PC</u></a></li>
<li><a href="https://win-net.techidaily.com/resolving-the-dilemma-steps-to-solve-airdrop-hanging-in-limbo-on-your-apple-devices/"><u>Resolving the Dilemma: Steps to Solve Airdrop Hanging in Limbo on Your Apple Devices</u></a></li>
<li><a href="https://win-net.techidaily.com/scopri-come-accedere-e-visualizzare-i-file-nascosti-in-windows-11-tutorial-dettagliato/"><u>Scopri Come Accedere E Visualizzare I File Nascosti in Windows 11 - Tutorial Dettagliato</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sony-bdp-s6500-review-updated-for-2024/"><u>Sony BDP-S6500 Review - Updated for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-guide-to-the-affordable-z-edge-z3-plus-top-performance-and-easy-use-reviewed/"><u>The Ultimate Guide to the Affordable Z-Edge Z3 Plus - Top Performance and Easy Use Reviewed</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-to-eliminate-unwanted-user-profiles-in-windows-10-systematically/"><u>The Ultimate Walkthrough to Eliminate Unwanted User Profiles in Windows 10 Systematically</u></a></li>
<li><a href="https://win-net.techidaily.com/top-tecnicas-para-optimizar-la-instalacion-de-windows-11-en-un-disco-solid-state/"><u>Top Técnicas Para Optimizar La Instalación De Windows 11 en Un Disco Solid State</u></a></li>
<li><a href="https://win-net.techidaily.com/1728481249043-word/"><u>Word 檔案修補技巧：如何完美恢復有效性</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

