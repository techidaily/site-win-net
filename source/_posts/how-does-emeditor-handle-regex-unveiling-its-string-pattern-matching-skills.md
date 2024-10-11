---
title: How Does EmEditor Handle Regex? Unveiling Its String Pattern Matching Skills
date: 2024-10-03T21:44:15.171Z
updated: 2024-10-11T10:24:34.887Z
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-essential-guide-to-the-top-5-windows-snipper-tools/"><u>[New] 2024 Approved Essential Guide to The Top 5 Windows Snipper Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-how-to-convert-youtube-to-mp3-without-compromising-security-3-tips/"><u>[Updated] 2024 Approved How to Convert YouTube to MP3 Without Compromising Security - 3 Tips</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-thorough-examination-hero4-black-performance/"><u>[Updated] In 2024, Thorough Examination Hero4 Black Performance</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-unraveling-the-value-of-stability-in-photoshop-shake-reduction/"><u>[Updated] In 2024, Unraveling the Value of Stability in Photoshop Shake Reduction</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unveil-facebook-friends-8-seamless-downloads/"><u>[Updated] In 2024, Unveil Facebook Friends 8 Seamless Downloads</u></a></li>
<li><a href="https://techtrends.techidaily.com/experience-better-targeting-and-personalization-with-our-advanced-cookiebot-solutions/"><u>Experience Better Targeting and Personalization with Our Advanced Cookiebot Solutions</u></a></li>
<li><a href="https://win-net.techidaily.com/mastering-windows-11-vms-a-comprehensive-walkthrough-for-flawless-performance-tips-by-zdnet-experts/"><u>Mastering Windows 11 VMs: A Comprehensive Walkthrough for Flawless Performance - Tips by ZDNet Experts</u></a></li>
<li><a href="https://win-net.techidaily.com/microsoft-announces-plans-for-a-revamped-windows-update-calendar-insights-from-zdnet/"><u>Microsoft Announces Plans for a Revamped Windows Update Calendar - Insights From ZDNet</u></a></li>
<li><a href="https://win-net.techidaily.com/microsofts-major-challenge-addressing-windows-11-issues-before-the-clock-runs-out-insights-from-zdnet/"><u>Microsoft's Major Challenge: Addressing Windows 11 Issues Before the Clock Runs Out - Insights From ZDNet</u></a></li>
<li><a href="https://win-net.techidaily.com/microsofts-response-key-privacy-and-security-enhancements-post-tough-feedback-technewszdnet/"><u>Microsoft's Response: Key Privacy & Security Enhancements Post-Tough Feedback | TechNewsZDNet</u></a></li>
<li><a href="https://win-net.techidaily.com/navigate-your-deskless-files-with-windows-ai-powered-recall-feature-exclusive-guide/"><u>Navigate Your Deskless Files with Windows' AI-Powered Recall Feature – Exclusive Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/professional-windows-and-mac-video-restoration-tool/"><u>Professional Windows & MAC Video Restoration Tool</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-intersection-of-gaming-and-machine-learning-magic/"><u>The Intersection of Gaming and Machine Learning Magic</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

