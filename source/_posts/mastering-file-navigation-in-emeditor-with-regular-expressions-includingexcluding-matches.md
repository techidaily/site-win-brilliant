---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-10-27T18:25:16.509Z
updated: 2024-10-28T18:42:14.261Z
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
<li><a href="https://youtube-video-recordings.techidaily.com/new-demystifying-youtube-shorts-for-total-beginners/"><u>[New] Demystifying YouTube Shorts for Total Beginners</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1-windows-11vssvcexe6/"><u>1. Windows 11でVSSVC.exeが多くのスペースを消費する場合、これを解決するための6つの簡単な手順</u></a></li>
<li><a href="https://win-docs.techidaily.com/1728466865433-usb/"><u>如何使用最佳免费软件从USB重建操作系统图像</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728495484648-windows-1011/"><u>学习如何轻松地在Windows 10/11中备份和复制三种方法的用户设置文件</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/comandi-facile-e-gratis-da-usare-in-cmd-per-ripristinare-i-file-dallhard-disk/"><u>Comandi Facile E Gratis Da Usare in CMD per Ripristinare I File Dall'Hard Disk</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/comment-fabriquer-un-support-amovible-a-demarrage-avec-windows-server-2008-r2-a-partir-dun-fichier-iso-guide-complet/"><u>Comment Fabriquer Un Support Amovible À Démarrage Avec Windows Server 2008 R2 À Partir D'un Fichier ISO : Guide Complet</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/comment-recuperer-un-fichier-psd-non-enregistre-ou-perdu-dans-photoshop/"><u>Comment Récupérer Un Fichier PSD Non Enregistré Ou Perdu Dans Photoshop</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-camon-20-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Camon 20.</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/easy-methods-for-uploading-and-syncing-your-cd-tracks-to-icloud-via-an-ios-device-or-laptop/"><u>Easy Methods for Uploading and Syncing Your CD Tracks to iCloud via an iOS Device or Laptop</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-infinix-smart-8-plus-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Infinix Smart 8 Plus FRP Locks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-precise-codex-of-conduct-in-the-digital-realm/"><u>In 2024, Precise Codex of Conduct in the Digital Realm</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-step-by-step-instructions-for-extracting-mp3-from-video/"><u>In 2024, Step-By-Step Instructions for Extracting MP3 From Video</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-xiaomi-mix-fold-3-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Xiaomi Mix Fold 3 Location | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-the-directx-glitch-in-anno-1800-a-comprehensive-guide/"><u>Overcoming the DirectX Glitch in Anno 1800 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/solving-the-home-button-unresponsive-problem-upgrading-your-iphoneipad/"><u>Solving the 'Home Button Unresponsive' Problem: Upgrading Your iPhone/iPad</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/speedy-methods-moving-audio-files-from-iphoneipad-onto-usb-drive/"><u>Speedy Methods: Moving Audio Files From iPhone/iPad Onto USB Drive</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-8-drawing-apps-for-ipados/"><u>Top 8 Drawing Apps for iPadOS</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728465273145-windows-11-3/"><u>Windows 11向けローカルユーザーアカウント設定手順: 3コツのガイド</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

