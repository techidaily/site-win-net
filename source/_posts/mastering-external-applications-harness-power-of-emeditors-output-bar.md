---
title: "Mastering External Applications: Harness Power of EmEditor's Output Bar"
date: 2024-11-30T01:38:30.728Z
updated: 2024-11-30T20:55:42.471Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/b940b6b0f5ea7e32cad1821c53c7dd63eece1d15c1851d2a65f8ffeb1e28c4c2.jpg
---

## Mastering External Applications: Harness Power of EmEditor's Output Bar

Tagged: [External Tools](https://tools.techidaily.com/emeditor/products/), [Output Bar](https://tools.techidaily.com/emeditor/products/)

Viewing 3 posts - 1 through 3 (of 3 total)

* Author  
Posts
* July 2, 2014 at 11:10 pm [#18629](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b3a0ed2c9d805d8c56f58fefc57d7709?s=80&d=identicon&r=g)Shavok](https://www.emeditor.com/forums/users/shavok/ "View Shavok's profile")  
Participant  
Hi  
I’m running my Python script using the command prompt (cmd.exe) and discovered I could have the output directly in EmEditor! But each time I run the command I get “Do you want to terminate the current tool job?”  
I read a previous post on this but was uncertain how to proceed – also, the posts are over 2 years old now.  
Thanks!  
July 3, 2014 at 1:02 pm [#18631](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello,  
I think you were looking at the correct message of 2 years old. This “Do you want to terminate the current tool job?” message appears because the previous external tool job has not been finished before you try to start the next external tool job. If you can’t finish the previous job, you can disable this message by adding the following registry key:  
HKEY\_CURRENT\_USER\\Software\\EmSoft\\EmEditor v3\\Common  
PromptTerminateJob  
REG\_DWORD: 0  
Thank you!  
July 4, 2014 at 12:05 am [#18632](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b3a0ed2c9d805d8c56f58fefc57d7709?s=80&d=identicon&r=g)Shavok](https://www.emeditor.com/forums/users/shavok/ "View Shavok's profile")  
Participant  
Thanks! This worked perfectly.  
On closer inspection I see this actually opens up the cmd.exe process. So by introducing this “hack” we actually close the previous cmd.exe then?  
Works quite nicely.
* Author  
Posts

Viewing 3 posts - 1 through 3 (of 3 total)

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
<li><a href="https://twitter-videos.techidaily.com/updated-comprehensively-covering-the-top-tweets-cleanse-apps/"><u>[Updated] Comprehensively Covering the Top Tweets Cleanse Apps</u></a></li>
<li><a href="https://win-net.techidaily.com/mnvme-nvme-ssd/"><u>容量アップのためのM.nvme NVMe SSDクローニング手法【スマートな方法】</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-aid-excellence-using-these-high-tech-digital-tools/"><u>Boost Aid Excellence Using These High-Tech Digital Tools</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-itel-a70-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Itel A70 Back to Operation | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-tactics-to-quiet-down-distractions-during-google-meets/"><u>In 2024, Tactics to Quiet Down Distractions During Google Meets</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy A34 5G? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-14-pro-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue From Apple iPhone 14 Pro</u></a></li>
<li><a href="https://win-net.techidaily.com/soluciones-efectivas-para-reparar-tu-unidad-samsung-magician-no-admitida-en-la-garantia/"><u>Soluciones Efectivas Para Reparar Tu Unidad Samsung Magician No Admitida en La Garantía</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-game-torrents-at-a-glance-navigating-the-best-free-downloading-portals/"><u>Top Game Torrents at a Glance: Navigating the Best Free Downloading Portals</u></a></li>
<li><a href="https://win-net.techidaily.com/troubleshooting-itunes-error-what-to-do-when-it-cant-locate-your-original-file/"><u>Troubleshooting iTunes Error: What to Do When It Can’t Locate Your Original File</u></a></li>
<li><a href="https://win-net.techidaily.com/1728508220358-404/"><u>サイト上のページがないことを意味する404警告:未検出</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

