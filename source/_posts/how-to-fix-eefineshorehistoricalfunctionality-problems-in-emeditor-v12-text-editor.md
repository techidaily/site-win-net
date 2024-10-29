---
title: How to Fix EeFineshoreHistoricalFunctionality Problems in EmEditor V12 Text Editor
date: 2024-10-24T01:18:45.051Z
updated: 2024-10-29T05:54:54.592Z
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-hidden-highlight-harvester/"><u>[New] 2024 Approved Hidden Highlight Harvester</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-best-4-choices-unhackable-video-meetings-for-small-firms/"><u>[New] Best 4 Choices Unhackable Video Meetings for Small Firms</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-contrast-and-composition-theory-in-design/"><u>[Updated] In 2024, Contrast and Composition Theory in Design</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-itel-a60s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Itel A60s | Dr.fone</u></a></li>
<li><a href="https://win-net.techidaily.com/guia-de-respaldo-y-recuperacion-del-almacenamiento-para-sistemas-dinamicos-funcionamiento-con-disc-dynamique/"><u>Guía De Respaldo Y Recuperación Del Almacenamiento Para Sistemas Dinámicos: Funcionamiento Con Disc Dynamique</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-stolen-iphone-13-pro-in-different-conditionsin-drfone-by-drfone-ios/"><u>How To Unlock Stolen iPhone 13 Pro In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://win-net.techidaily.com/la-tua-guida-completa-i-top-5-programmi-di-clonazione-per-windows-11/"><u>La Tua Guida Completa: I Top 5 Programmi Di Clonazione per Windows 11</u></a></li>
<li><a href="https://win-net.techidaily.com/migrating-data-efficiently-from-windows-windows-7-to-windows-windows-10-expert-network-transfer-strategies/"><u>Migrating Data Efficiently From Windows ^[Windows 7] to Windows ^[Windows 10]: Expert Network Transfer Strategies</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-microsoft-wireless-mouse-5000-drivers-get-them-instantly/"><u>Quick Download: Microsoft Wireless Mouse 5000 Drivers - Get Them Instantly!</u></a></li>
<li><a href="https://win-net.techidaily.com/resetting-your-laptop-to-original-state-guides-for-windows-1187-systems/"><u>Resetting Your Laptop to Original State: Guides for Windows 11/8/7 Systems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

