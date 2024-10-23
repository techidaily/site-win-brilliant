---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-10-18T02:42:22.847Z
updated: 2024-10-22T23:25:24.124Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/d141dd05ed10b1bd39fa40502c6b028dc88f2f05d25c3ac4b8799745512b0ec6.jpg
---

## Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches

Viewing 6 posts - 1 through 6 (of 6 total)

* Author  
Posts
* December 18, 2014 at 10:40 pm [#19719](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e6af1a9ed47c1b77500e6d7cfd4cddef?s=80&d=identicon&r=g)Rien van Ham](https://www.emeditor.com/forums/users/rien-van-ham/ "View Rien van Ham's profile")  
Participant  
Hello Yutaka,  
Sorry, that was an error when I retyped the regex.  
It has to be:  
 ^((?!<Landcode value=”NL”/>).)\*$  
Thanks in advance!  
December 19, 2014 at 9:02 am [#19722](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello Rien van Ham,  
Thanks for letting me know.  
 With the correct regex, was your issue solved?  
December 21, 2014 at 12:10 am [#19728](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e6af1a9ed47c1b77500e6d7cfd4cddef?s=80&d=identicon&r=g)Rien van Ham](https://www.emeditor.com/forums/users/rien-van-ham/ "View Rien van Ham's profile")  
Participant  
Hello Yutaka,  
No, I’m sorry, the same error is popping up.  
December 21, 2014 at 9:57 am [#19729](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello,  
If you have not already checked, In the Customize dialog box – Search tab, please set:  
**Additional Lines to Search for Regular Expressions** text box to 0  
clear the **Regular Expressions “.” Can Match New Line Characters** check box.  
Also, if possible, please re-write regular expressions as simple as possible.  
Thanks,  
December 23, 2014 at 11:44 pm [#19745](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e6af1a9ed47c1b77500e6d7cfd4cddef?s=80&d=identicon&r=g)Rien van Ham](https://www.emeditor.com/forums/users/rien-van-ham/ "View Rien van Ham's profile")  
Participant  
Hello Yutaka,  
I’m sorry to tell you but isn’t that a very strange solution?  
 1: The regex is NOT complex. The only difference is that is does a lookahead to see if the value does NOT excists in the current line.  
 2: The regex is fully Perl-compatible  
 3: Other editors will do the same work without any complaining.  
Thanks!  
December 24, 2014 at 9:27 am [#19746](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Hello,  
Since this error happens inside the regular expression engine (Boost regex++), I can’t control what happens inside the regex engine.  
What number did you set to the **Additional Lines to Search for Regular Expressions** text box, and did you set or clear the **Regular Expressions “.” Can Match New Line Characters** check box?  
There might be a different reason so would you send me a sample file (after zipped) to [tech@emurasoft.com](https://tools.techidaily.com/emeditor/products/) along with the Registry file (exported at HKEY\_CURRENT\_USER\\Software\\EmSoft, please zip the file)? I will try to reproduce the issue here.  
Thank you,
* Author  
Posts

Viewing 6 posts - 1 through 6 (of 6 total)

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-complete-guide-to-youtube-ad-free-viewing-chrome-and-safari/"><u>[New] In 2024, The Complete Guide to YouTube Ad-Free Viewing (Chrome & Safari)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-perfecting-profiles-how-to-embed-linktree-on-tiktok-seamlessly/"><u>[New] Perfecting Profiles How to Embed Linktree on TikTok Seamlessly</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-first-steps-in-digital-content-top-10-easy-to-make-youtube-projects/"><u>[Updated] 2024 Approved First Steps in Digital Content Top 10 Easy-to-Make YouTube Projects</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pro-webcams-8-your-go-to-for-flawless-livestreams/"><u>[Updated] Pro Webcams 8 Your Go-To for Flawless Livestreams</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728487345441-youtube5/"><u>如何在YouTube上恢复已删除的视频：5个技巧与指南</u></a></li>
<li><a href="https://solve-info.techidaily.com/boost-traffic-with-cookiebot-the-ultimate-seo-and-marketing-solution-for-modern-websites/"><u>Boost Traffic With Cookiebot: The Ultimate SEO and Marketing Solution for Modern Websites</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/complete-guide-restoring-files-from-an-iomega-usb-drive/"><u>Complete Guide: Restoring Files From an iOmega USB Drive</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/descubra-porque-sua-cacamba-de-reciclagem-parece-vazia-quando-na-verdade-nao-e/"><u>Descubra Porquê Sua Caçamba De Reciclagem Parece Vazia Quando Na Verdade Não É</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/discover-the-ultimate-selection-of-8-leading-photo-retouching-tools-for-vintage-images-on-your-smartphone/"><u>Discover the Ultimate Selection of 8 Leading Photo Retouching Tools for Vintage Images on Your Smartphone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/dual-mode-replica-synology-tra-due-network-attached-storage-device-with-two-built-in-nas-units/"><u>Dual-Mode Replica Synology Tra Due Network Attached Storage Device with Two Built-In NAS Units</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-poco-m6-pro-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Poco M6 Pro 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/lenovo-ideapad-onekey-rescue/"><u>Lenovo IdeaPad OneKey Rescue: 使用方法と復元プロセスのガイド</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/podanie-skrupulatowe-zapasy-raid-eby-dyski-kluczowe-szyfrowaly-byly-ostatnio-niebezpieczne-dane/"><u>Podanie Skrupulatowe Zapasy RAID Eby Dyski Kluczowe Szyfrowaly Były Ostatnio Niebezpieczne Dane</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728462262354-sd/"><u>SD卡数据恢复技巧：如何成功不花钱</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/step-by-step-solution-addressing-and-repairing-boot-time-windows-script-host-errors/"><u>Step-by-Step Solution: Addressing and Repairing Boot-Time Windows Script Host Errors</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144273/7443" target="_top" id="2144273">
  <img src="//a.impactradius-go.com/display-ad/7443-2144273" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144273/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

