---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-11-18T05:33:49.761Z
updated: 2024-11-22T17:20:04.150Z
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-essential-guide-top-10-free-youtube-to-mp3-tools/"><u>[New] 2024 Approved Essential Guide Top 10 Free YouTube-to-MP3 Tools</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-cure-for-disconnected-channels-in-obs/"><u>[New] In 2024, Cure for Disconnected Channels in OBS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-perfecting-the-art-of-transmitting-videos-via-discords-channels/"><u>[Updated] 2024 Approved Perfecting the Art of Transmitting Videos via Discord's Channels</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pixelperfect-image-transformations/"><u>[Updated] PixelPerfect Image Transformations</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-11-10-8-7-nas/"><u>導演：在 Windows 系列平台(11, 10, 8, 7)中成功建立自動到 NAS 的硬碟資料备份方法</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/converting-physical-drives-to-virtual-machines-made-easy-using-disk2vhd-a-comprehensive-tutorial/"><u>Converting Physical Drives to Virtual Machines Made Easy Using Disk2VHD - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/decouvrez-comment-corriger-un-erreur-de-lecture-de-disque-persistante-dans-nimporte-quelle-version-de-windows-y-compris-le-1087xp/"><u>Découvrez Comment Corriger Un Erreur De Lecture De Disque Persistante Dans N'importe Quelle Version De Windows, Y Compris Le 10/8/7/XP</u></a></li>
<li><a href="https://win-tricks.techidaily.com/eliminate-intrusive-advertisements-effectively-using-our-proven-anti-adware-solution-from-malwarefox/"><u>Eliminate Intrusive Advertisements Effectively Using Our Proven Anti-Adware Solution From MalwareFox!</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-evaluation-the-pros-and-cons-of-the-latest-ring-video-doorbell-plus-model/"><u>Expert Evaluation: The Pros & Cons of the Latest Ring Video Doorbell Plus Model</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guia-facil-y-completa-para-realizar-una-respaldo-de-iphone-en-windows-10-o-11/"><u>Guía Fácil Y Completa Para Realizar Una Respaldo De iPhone en Windows 10 O 11</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guide-complet-comment-recuperer-facilement-une-partition-egaree-sur-windows-10-ou-11-en-quatre-simples-etapes/"><u>Guide Complet: Comment Récupérer Facilement Une Partition Égarée Sur Windows 10 Ou 11 en Quatre Simples Etapes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-xr-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone XR When You Forget the Passcode?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-nubia-z50-ultra-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Nubia Z50 Ultra to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/los-topes-recomendados-para-desbloquear-bitlocker-en-diversos-versiones-de-windows/"><u>Los Topes Recomendados Para Desbloquear BitLocker en Diversos Versiones De Windows</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/overcoming-connectivity-issues-with-toshiba-external-drives-a-comprehensive-fix-guide/"><u>Overcoming Connectivity Issues with Toshiba External Drives - A Comprehensive Fix Guide</u></a></li>
<li><a href="https://techidaily.com/remove-the-lock-of-honor-by-drfone-android-unlock-android-unlock/"><u>Remove the lock of Honor</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/troubleshooting-guide-how-to-restore-missing-quick-access-icons-on-your-desktop-6-steps/"><u>Troubleshooting Guide: How To Restore Missing Quick Access Icons On Your Desktop (6 Steps)</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/wd-mara-pasaparata-garavalyada-kaya-abha-taka-kasa-oiparashana-ka-pana-jaugdhana-ma-sakashhama-ha/"><u>WD मेरा पासपोर्ट गैरवॉल्यूड: क्या अभी तक किसी ऑपरेशन को पुनः जोड़ने में सक्षम है?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

