---
title: How to Fix EeFineshoreHistoricalFunctionality Problems in EmEditor V12 Text Editor
date: 2024-10-19T16:02:42.991Z
updated: 2024-10-23T09:12:18.495Z
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-ultimate-approaches-to-clearer-zoomed-video-on-online-platforms/"><u>[New] 2024 Approved Ultimate Approaches to Clearer Zoomed Video on Online Platforms</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/uide-to-10-top-ranked-entrepreneurial-youtube-platforms/"><u>[New] Guide to 10 Top-Ranked Entrepreneurial YouTube Platforms</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-recording-tech-evaluation-blueprint/"><u>[Updated] 2024 Approved Recording Tech Evaluation Blueprint</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-guide-top-10-free-youtube-to-mp3-tools-for-2024/"><u>[Updated] Essential Guide Top 10 Free YouTube-to-MP3 Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-instagrams-sponsorship-jungle-for-affluent-creators/"><u>[Updated] Navigating Instagram's Sponsorship Jungle for Affluent Creators</u></a></li>
<li><a href="https://win-net.techidaily.com/1-windows-1011-startup-failure-how-to-restore-your-system-effectively/"><u>1. Windows 10/11 Startup Failure - How to Restore Your System Effectively</u></a></li>
<li><a href="https://tech-revival.techidaily.com/avoiding-fraudulent-chatbot-software-a-guide-for-navigating-the-ios-app-store/"><u>Avoiding Fraudulent Chatbot Software: A Guide for Navigating the iOS App Store</u></a></li>
<li><a href="https://win-net.techidaily.com/converting-thick-ebs-volumes-to-thinly-provisioned-storage-on-vmware-esxi-essential-steps-and-tips/"><u>Converting Thick EBS Volumes to Thinly Provisioned Storage on VMware ESXi - Essential Steps and Tips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-verdict-on-iphone-15-top-tier-choice-for-professionals-and-enthusiasts-alike-insights-from-zdnet/"><u>Expert Verdict on iPhone 15: Top-Tier Choice for Professionals and Enthusiasts Alike - Insights From ZDNet</u></a></li>
<li><a href="https://win-net.techidaily.com/expert-walkthrough-for-transferring-windows-os-from-hddssd-to-nvme-storage-device/"><u>Expert Walkthrough for Transferring Windows OS From HDD/SSD to NVMe Storage Device</u></a></li>
<li><a href="https://win-net.techidaily.com/free-conversion-of-heic-images-to-jpeg-on-windows-11-using-fonetool-a-comprehensive-guide/"><u>FREE Conversion of HEIC Images to JPEG on Windows 11 Using FoneTool: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-streamlining-virtual-meetings-best-practices-for-teams/"><u>In 2024, Streamlining Virtual Meetings Best Practices for Teams</u></a></li>
<li><a href="https://win-net.techidaily.com/myrecover-word-restore-utility-effortless-auto-saved-documents-retrieval/"><u>MyRecover Word Restore Utility - Effortless Auto-Saved Documents Retrieval</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premiere-pros-guide-to-avoiding-overlit-iphone-hdr-videos-for-2024/"><u>Premiere Pro's Guide to Avoiding Overlit iPhone HDR Videos for 2024</u></a></li>
<li><a href="https://win-net.techidaily.com/top-rated-no-cost-programs-to-seamlessly-sync-your-desktop-folders-in-any-windows-os/"><u>Top Rated No Cost Programs to Seamlessly Sync Your Desktop Folders in Any Windows OS</u></a></li>
<li><a href="https://win-net.techidaily.com/two-effective-methods-for-creating-no-cost-external-backups-in-windows-versions-11-10-8-and/"><u>Two Effective Methods for Creating No-Cost External Backups in Windows (Versions 11, 10, 8 &</u></a></li>
<li><a href="https://win-net.techidaily.com/rabochee-rukovodstvo-kak-bystro-klonirovat-sistemu-windows-1011-na-zagruzochnyj-usb-nakopitel/"><u>Рабочее Руководство: Как Быстро Клонировать Систему Windows 10/11 На Загрузочный USB-Накопитель</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

