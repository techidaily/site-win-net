---
title: How to Fix EeFineshoreHistoricalFunctionality Problems in EmEditor V12 Text Editor
date: 2024-10-27T18:53:53.207Z
updated: 2024-11-03T16:10:12.135Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/19cc3daca0ae766efaf5a0d940f51eeacf8f6380658cff3e15c9f29d7f7d98eb.jpg
---

## How to Fix EeFineshoreHistoricalFunctionality Problems in EmEditor V12 Text Editor

Viewing 12 posts - 1 through 12 (of 12 total)

* Author  
Posts
* October 13, 2012 at 1:22 am [#10579](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b873808416c17f967acca86a789d0ab1?s=80&d=identicon&r=g)LTT](https://www.emeditor.com/forums/users/LTT/ "View LTT's profile")  
Participant  
For example:  
nFound = document.selection.Find("aaa",  eeFindNext | eeFindSaveHistory);  
 After running this macro, the current word to find doesn’t change to “aaa”.  
October 13, 2012 at 2:35 am [#10580](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello,  
 The issue is that if the Find Bar or Find dialog box is visible, the contents in the Find Bar or Find dialog box has higher priority to determine the search string when F3 is pressed. I will try to synchronize the contents of Find Bar when this macro is run on the next minor version. Meanwhile, please hide the Find Bar.  
 Thanks!  
October 13, 2012 at 6:39 am [#10581](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b873808416c17f967acca86a789d0ab1?s=80&d=identicon&r=g)LTT](https://www.emeditor.com/forums/users/LTT/ "View LTT's profile")  
Participant  
Thank you.  
 \+ other cases:  
 When the Find Bar is visible and “Set Word to Find/Replace” command is triggered…  
 And, how about adding a “Freeze” option (button) on the Find Bar? — So one can keep the contents of Find Bar, unless he changes them manually.  
October 13, 2012 at 10:08 pm [#10582](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello,  
 I will fix the “Set Word to Find/Replace” issue for the next minor version. Thank you!  
October 30, 2012 at 5:17 am [#10616](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b873808416c17f967acca86a789d0ab1?s=80&d=identicon&r=g)LTT](https://www.emeditor.com/forums/users/LTT/ "View LTT's profile")  
Participant  
\+ Yet another case:  
 editor.FindInFiles … eeFindSaveHistory …  
November 5, 2012 at 7:05 pm [#10622](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I will look into the code.  
 Thanks!  
November 12, 2012 at 6:33 pm [#10624](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b873808416c17f967acca86a789d0ab1?s=80&d=identicon&r=g)LTT](https://www.emeditor.com/forums/users/LTT/ "View LTT's profile")  
Participant  
document.selection.Find("strFind", eeFindNext | eeFindSaveHistory | eeFindReplaceQuiet);  
 After this is run, all the options that belong to \[Find/Replace in Files\] now are cleared:  
 Display File Names Only  
 Keep Modified Files Open  
 Look in Subfolders  
 Save Backups  
 Use Output Bar  
 Even the Quiet status persists. Use Find Next/Previous manually, if not found, no message on the status bar.  
November 12, 2012 at 11:45 pm [#10625](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello,  
 I reproduced this issue, and it will be fixed on the next version.  
 Thanks!  
December 11, 2012 at 4:41 pm [#10659](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b873808416c17f967acca86a789d0ab1?s=80&d=identicon&r=g)LTT](https://www.emeditor.com/forums/users/LTT/ "View LTT's profile")  
Participant  
These two issues are not fixed:  
> document.selection.Find("strFind", eeFindNext | eeFindSaveHistory | eeFindReplaceQuiet);  
>  
> Even the Quiet status persists. Use Find Next/Previous manually, if not found, no message on the status bar.  
> editor.FindInFiles … eeFindSaveHistory …  
 And there is no index for “eeFindSaveHistory” in FindInFiles/ReplaceInFiles.  
December 12, 2012 at 5:12 pm [#10660](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello LTT,  
 I will fix the first issue.  
 As for the second issue, eeFindSaveHistory is not supported in Find/Replace in Files.  
 Thanks!  
December 13, 2012 at 6:02 am [#10661](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b873808416c17f967acca86a789d0ab1?s=80&d=identicon&r=g)LTT](https://www.emeditor.com/forums/users/LTT/ "View LTT's profile")  
Participant  
Thanks!  
 (eeFindSaveHistory)  
 So the CHM should be revised:  
[http://www.emeditor.com/help/macro/editor/editor\_findinfiles.htm](https://tools.techidaily.com/emeditor/products/)  
[http://www.emeditor.com/help/macro/editor/editor\_replaceinfiles.htm](https://tools.techidaily.com/emeditor/products/)  
December 13, 2012 at 7:08 pm [#10663](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello LTT,  
 OK. eeFindSaveHistory will be supported on Find/ReplaceInFiles in the next version.  
 Thanks!
* Author  
Posts

Viewing 12 posts - 1 through 12 (of 12 total)

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-finding-the-balance-adding-videos-to-text-on-a-budget/"><u>[New] 2024 Approved Finding the Balance Adding Videos to Text on a Budget</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-in-depth-app-insights-the-az-reporters-cut/"><u>[New] In 2024, In-Depth App Insights - The AZ Reporter's Cut</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-mastering-instagrams-video-upload-constraints-a-detailed-guide/"><u>2024 Approved Mastering Instagram's Video Upload Constraints A Detailed Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/aktivierung-des-energiezustands-in-windows-11-entdecken-sie-die-vier-effektivsten-ansatze/"><u>Aktivierung Des Energiezustands in Windows 11 - Entdecken Sie Die Vier Effektivsten Ansätze</u></a></li>
<li><a href="https://win-net.techidaily.com/clonacion-profesional-del-disco-duro-para-sistemas-bifuncionales-hacia-ssd/"><u>Clonación Profesional Del Disco Duro Para Sistemas Bifuncionales Hacia SSD</u></a></li>
<li><a href="https://win-net.techidaily.com/garantizar-la-continuidad-del-negocio-tecnicas-eficaces-de-copias-de-seguridad-y-reparaciones-en-windows-utilizando-aomei-backupper/"><u>Garantizar La Continuidad Del Negocio: Técnicas Eficaces De Copias De Seguridad Y Reparaciones en Windows Utilizando AOMEI Backupper</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722979130044-get-your-thrustmaster-t150-stealth-plus-gamepad-up-and-running-fast-driver-downloads/"><u>Get Your Thrustmaster T150 Stealth Plus Gamepad Up and Running - Fast Driver Downloads!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-might-cyberthieves-exploit-chatgpt-technology-for-financial-fraud-and-computer-intrusion/"><u>How Might Cyberthieves Exploit ChatGPT Technology for Financial Fraud and Computer Intrusion?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-iphone-15-pro-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and iPhone 15 Pro without Apple Account</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/inside-the-world-of-vivacut-expert-editor-review-2024/"><u>Inside the World of VivaCut Expert Editor Review 2024</u></a></li>
<li><a href="https://win-popular.techidaily.com/resolving-bug-issues-during-text-searches-in-emeditor-7-software-suite/"><u>Resolving Bug Issues During Text Searches in EmEditor 7 Software Suite</u></a></li>
<li><a href="https://win-net.techidaily.com/solving-the-administrative-access-necessary-hiccup-for-winfr-software-a-3-step-guide/"><u>Solving the 'Administrative Access Necessary' Hiccup for WinFR Software: A 3-Step Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/superior-wd-my-cloud-ex2-ultra-datenrettungssoftware-die-beste-wahl-fur-ihr-gerat/"><u>Superior WD My Cloud EX2 Ultra Datenrettungssoftware – Die Beste Wahl Für Ihr Gerät</u></a></li>
<li><a href="https://win-net.techidaily.com/ultimate-guide-erasing-non-essential-files-efficiently/"><u>Ultimate Guide: Erasing Non-Essential Files Efficiently</u></a></li>
<li><a href="https://win-net.techidaily.com/understanding-windows-11-bitlocker-recovery-key-and-finding-your-way-to-it/"><u>Understanding Windows 11 BitLocker Recovery Key and Finding Your Way to It</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

