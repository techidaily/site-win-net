---
title: How to Fix EeFineshoreHistoricalFunctionality Problems in EmEditor V12 Text Editor
date: 2024-11-24T00:44:14.227Z
updated: 2024-12-01T03:33:01.441Z
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
<li><a href="https://instagram-clips.techidaily.com/new-unlocking-insta-success-when-to-share-your-content/"><u>[New] Unlocking Insta Success When to Share Your Content</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1726029500873-mp4-windows-1011/"><u>「MP4フォーマット動画を Windows 10/11で最も効果的にコンパクトにする方法 特集」</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-an-in-depth-look-at-wirecast-and-what-it-offers/"><u>2024 Approved An In-Depth Look at WireCast and What It Offers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/32-premium-free-tools-for-data-backup-a-detailed-ranking-and-review-guide/"><u>32 Premium Free Tools for Data Backup: A Detailed Ranking and Review Guide</u></a></li>
<li><a href="https://win-net.techidaily.com/7-usando-queste-tecniche-top/"><u>7 Usando Queste Tecniche Top!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-obstacle-dealing-with-device-error-22-on-windows-11/"><u>Bypassing the Obstacle: Dealing with Device Error 22 on Windows 11</u></a></li>
<li><a href="https://win-net.techidaily.com/come-risolvere-il-problema-di-backup-e-avvio-del-server-windows-server-2012-r2-che-non-appare-nella-schermata-iniziale/"><u>Come Risolvere Il Problema Di Backup E Avvio Del Server Windows Server 2012 R2 Che Non Appare Nella Schermata Iniziale</u></a></li>
<li><a href="https://win-net.techidaily.com/como-migrar-y-actualizar-el-almacenamiento-con-discos-hddssd-en-windows-10-8-o-7/"><u>Cómo Migrar Y Actualizar El Almacenamiento Con Discos HDD/SSD en Windows 10, 8 O 7</u></a></li>
<li><a href="https://win-net.techidaily.com/estrategia-paso-a-paso-para-rescatar-informacion-de-un-disco-ssd-bloqueado/"><u>Estrategia Paso a Paso Para Rescatar Información De Un Disco SSD Bloqueado</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-error-0x0000004e-in-win11/"><u>Guide to Rectify Error 0X0000004E in Win11</u></a></li>
<li><a href="https://win-net.techidaily.com/how-to-retrieve-missing-documents-from-google-drive/"><u>How To Retrieve Missing Documents From Google Drive</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-blurry-photos-top-tools-reviewed/"><u>In 2024, Blurry Photos Top Tools Reviewed</u></a></li>
<li><a href="https://win-net.techidaily.com/playstation-34-hdd/"><u>PlayStation 3/4 HDD バックアップマスタークラス！詳しいステップ方法を学ぶ</u></a></li>
<li><a href="https://common-error.techidaily.com/silence-is-golden-mastering-the-art-of-fixing-a-noisy-playstation-vehicle/"><u>Silence Is Golden: Mastering the Art of Fixing a Noisy PlayStation Vehicle</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-new-tvs-and-monitors-at-ifa-2023/"><u>The Best New TVs and Monitors at IFA 2023</u></a></li>
<li><a href="https://win-net.techidaily.com/toplogicie-gratuite-le-meilleure-application-de-synchronisation-des-fichiers-pour-windows-11/"><u>Toplogicie Gratuite: Le Meilleure Application De Synchronisation Des Fichiers Pour Windows 11</u></a></li>
<li><a href="https://win-net.techidaily.com/iuodleocoeocpoodqplusw9ouw8jplusobjomdnuwvvuwndog54plusplus6kgm44oq44o844k444on44oz44gr44gk44gr44kl44k144od44o844oi56pluse5zuyig/"><u>ファイル形式が非対応: 現行バージョンにおけるサポート範囲</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

