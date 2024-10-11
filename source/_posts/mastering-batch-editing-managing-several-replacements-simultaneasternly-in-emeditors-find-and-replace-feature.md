---
title: "Mastering Batch Editing: Managing Several Replacements Simultaneasternly in EmEditor's Find and Replace Feature"
date: 2024-10-09T06:26:22.035Z
updated: 2024-10-11T00:38:40.584Z
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
<li><a href="https://youtube-stream.techidaily.com/new-navigating-the-world-of-hashtags-to-boost-your-gaming-video-yields/"><u>[New] Navigating the World of Hashtags to Boost Your Gaming Video Yields</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-action-cam-faceoff-the-best-of-both-worlds-hero5-black-and-hero4-silver/"><u>2024 Approved Action Cam Faceoff The Best of Both Worlds – Hero5 Black & Hero4 Silver</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-laughter-unleashed-a-stepwise-strategy-for-making-impactful-gifs/"><u>2024 Approved Laughter Unleashed A Stepwise Strategy for Making Impactful GIFs</u></a></li>
<li><a href="https://fox-direct.techidaily.com/a-filmmakers-handbook-building-effective-luts-for-2024/"><u>A Filmmaker's Handbook Building Effective LUTs for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722997938550-how-to-fix-league-of-legends-wont-open-2024-tips/"><u>How to Fix League of Legends Won't Open - 2024 Tips</u></a></li>
<li><a href="https://win-net.techidaily.com/how-to-modify-page-colors-in-your-flipbooks-with-flipbuilder-a-comprehensive-guide/"><u>How to Modify Page Colors in Your Flipbooks with FlipBuilder - A Comprehensive Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/how-to-select-and-import-specific-pages-from-your-document-using-flipbuilder/"><u>How to Select and Import Specific Pages From Your Document Using FlipBuilder</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-gamers-dilemma-oculus-htc-and-sonys-vr-dominance/"><u>In 2024, Gamers' Dilemma Oculus, HTC & Sony's VR Dominance</u></a></li>
<li><a href="https://win-net.techidaily.com/incorporating-timestamps-into-text-documents-for-flash-book-creation-on-flipbuilder/"><u>Incorporating Timestamps Into Text Documents for Flash Book Creation on FlipBuilder</u></a></li>
<li><a href="https://win-net.techidaily.com/master-the-art-of-self-made-picture-albums-using-flipbuilders-step-by-step-guide/"><u>Master the Art of Self-Made Picture Albums Using FlipBuilder's Step-by-Step Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/mastering-flipbook-shadows-a-step-by-step-guide-on-precision-alignment/"><u>Mastering FlipBook Shadows: A Step-by-Step Guide on Precision Alignment</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mastering-mobile-how-to-track-and-manage-your-data-usage/"><u>Mastering Mobile: How to Track and Manage Your Data Usage</u></a></li>
<li><a href="https://win-net.techidaily.com/no-charge-image-to-pdf-maker-expert-tool-for-mass-converting-pictures-to-professional-pdf-formats/"><u>No Charge Image to Pdf Maker - Expert Tool for Mass Converting Pictures to Professional PDF Formats</u></a></li>
<li><a href="https://win-net.techidaily.com/optimizing-your-flipbuildercom-e-book-for-mobile-devices-a-comprehensive-guide/"><u>Optimizing Your FlipBuilder.com E-Book for Mobile Devices: A Comprehensive Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/protecting-your-digital-content-ensuring-only-authorized-users-read-your-published-flipbooks-on-flipbuildercom/"><u>Protecting Your Digital Content - Ensuring Only Authorized Users Read Your Published FlipBooks on FlipBuilder.com</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-motorola-moto-g13-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Motorola Moto G13</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unleash-your-gadgets-the-surprisingly-powerful-and-portable-8-in-1-adapter-a-steal-for-tech-enthusiasts/"><u>Unleash Your Gadgets: The Surprisingly Powerful & Portable 8-in-1 Adapter - A Steal for Tech Enthusiasts!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

