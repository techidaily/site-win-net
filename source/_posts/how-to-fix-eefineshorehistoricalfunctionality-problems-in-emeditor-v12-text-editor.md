---
title: How to Fix EeFineshoreHistoricalFunctionality Problems in EmEditor V12 Text Editor
date: 2024-11-18T17:12:01.577Z
updated: 2024-11-22T17:55:20.607Z
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
<li><a href="https://youtube-tips.techidaily.com/-symphony-in-silence-mastering-audio-with-precision-for-2024/"><u>[New] A Symphony in Silence Mastering Audio with Precision for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-crafting-impactful-video-campaigns-for-startups/"><u>[Updated] Crafting Impactful Video Campaigns for Startups</u></a></li>
<li><a href="https://win-net.techidaily.com/hddssdwindows-1111pc/"><u>安全にHDDをSSDに交換:Windows 11／11ノートPC用最適化方法【専門家入門】</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/effortless-conversion-from-wmv-to-mp3-files-on-pc-and-mac/"><u>Effortless Conversion From WMV to MP3 Files on PC & Mac</u></a></li>
<li><a href="https://win-net.techidaily.com/expert-steps-to-repair-and-recover-gopro-video-content-successfully/"><u>Expert Steps to Repair and Recover GoPro Video Content Successfully</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guard-against-deception-the-hidden-dangers-of-googles-bard-update/"><u>Guard Against Deception: The Hidden Dangers of Google’s Bard Update</u></a></li>
<li><a href="https://win-net.techidaily.com/hddssd-windows-1110/"><u>HDDを素早くSSDに移行する簡単方法: Windows 11/10ユーザー向けチュートリアル</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Huawei P60? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-10t-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme 10T 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://win-net.techidaily.com/perfektes-airdrop-mit-windows-11-zu-iphoneipad-professionelle-losungen-fur-ein-reibungsloses-dateitransfer/"><u>Perfektes AirDrop Mit Windows 11 Zu iPhone/iPad - Professionelle Lösungen Für Ein Reibungsloses Dateitransfer</u></a></li>
<li><a href="https://win-net.techidaily.com/successfully-resolved-chkdsk-disk-errors-including-corrected-capitalization-glitches/"><u>Successfully Resolved CHKDSK Disk Errors Including Corrected Capitalization Glitches</u></a></li>
<li><a href="https://win-net.techidaily.com/top-solutions-for-successfully-completing-an-ipad-transfer-when-upgrading-to-a-new-model/"><u>Top Solutions For Successfully Completing An iPad Transfer When Upgrading to a New Model</u></a></li>
<li><a href="https://win-blog.techidaily.com/yakuza-3-hd-remake-freezing-issues-solved-optimized-gameplay-on-windows/"><u>Yakuza 3 HD Remake Freezing Issues Solved: Optimized Gameplay on Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

