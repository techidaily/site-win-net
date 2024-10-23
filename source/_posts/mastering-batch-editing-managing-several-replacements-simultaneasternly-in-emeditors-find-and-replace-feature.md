---
title: "Mastering Batch Editing: Managing Several Replacements Simultaneasternly in EmEditor's Find and Replace Feature"
date: 2024-10-16T01:55:54.890Z
updated: 2024-10-23T09:53:00.630Z
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-streamline-your-workflow-macos-screencast-tutorial/"><u>[New] 2024 Approved Streamline Your Workflow MacOS Screencast Tutorial</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-indoor-android-games-you-can-play-without-a-network/"><u>[New] Indoor Android Games You Can Play Without a Network</u></a></li>
<li><a href="https://fox-http.techidaily.com/bring-out-the-splendor-in-your-iphone-reflections/"><u>Bring Out the Splendor in Your iPhone Reflections</u></a></li>
<li><a href="https://win-net.techidaily.com/discover-top-free-software-downloads-compatible-with-windows-11/"><u>Discover Top Free Software Downloads Compatible with Windows 11</u></a></li>
<li><a href="https://win-net.techidaily.com/effortlessly-retrieving-lost-photographs-from-your-computer-a-guide/"><u>Effortlessly Retrieving Lost Photographs From Your Computer: A Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/free-techniques-for-retrieving-accidentally-erased-data-from-your-flash-drive/"><u>Free Techniques for Retrieving Accidentally Erased Data From Your Flash Drive</u></a></li>
<li><a href="https://win-net.techidaily.com/guia-paso-a-paso-transferir-archivos-de-programas-entre-unidades-de-almacenamiento-en-windows-11/"><u>Guía Paso a Paso: Transferir Archivos De Programas Entre Unidades De Almacenamiento en Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Infinix Hot 40? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-12-mini-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On Apple iPhone 12 mini</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-the-recruitment-game-how-influential-business-leaders-unlock-attraction-of-premier-tech-talent-expert-tips-on-zdnet/"><u>Mastering the Recruitment Game: How Influential Business Leaders Unlock Attraction of Premier Tech Talent – Expert Tips on ZDNET</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-new-neural-networks-which-tech-takes-preference/"><u>Navigating New Neural Networks: Which Tech Takes Preference?</u></a></li>
<li><a href="https://win-net.techidaily.com/recovering-windows-10-primary-partition-after-accidental-deletion/"><u>Recovering Windows 10 Primary Partition After Accidental Deletion</u></a></li>
<li><a href="https://win-net.techidaily.com/resolving-cannot-install-windows-10-version-21h2-step-by-step-troubleshooting-tips/"><u>Resolving 'Cannot Install Windows 10 Version 21H2': Step-by-Step Troubleshooting Tips</u></a></li>
<li><a href="https://win-net.techidaily.com/resolving-windows-11s-corrupt-c-drive-issues-identifying-causes-and-implementing-repairs/"><u>Resolving Windows 11'S Corrupt C Drive Issues: Identifying Causes and Implementing Repairs</u></a></li>
<li><a href="https://win-net.techidaily.com/simple-methods-to-transfer-your-gmail-messages-onto-your-pc-or-mac-a-comprehensive-guide/"><u>Simple Methods to Transfer Your Gmail Messages Onto Your PC or Mac: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-iphone-call-reception-issues-effectively/"><u>Troubleshooting iPhone Call Reception Issues Effectively</u></a></li>
<li><a href="https://games-able.techidaily.com/unravel-the-mystery-of-disappearing-wordle-streaks/"><u>Unravel the Mystery of Disappearing Wordle Streaks</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

