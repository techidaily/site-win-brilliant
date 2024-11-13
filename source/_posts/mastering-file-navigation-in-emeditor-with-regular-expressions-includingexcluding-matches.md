---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-11-09T18:11:11.727Z
updated: 2024-11-12T20:55:55.336Z
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-essential-list-8-leading-tools-for-video-translation-mastery/"><u>[New] 2024 Approved Essential List 8 Leading Tools for Video Translation Mastery</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-slide-swivel-and-shift-the-instagram-way-to-rotating-images-with-finesse/"><u>[New] 2024 Approved Slide, Swivel and Shift The Instagram Way to Rotating Images with Finesse</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-secrets-to-massive-channel-subscription-growth/"><u>[Updated] 2024 Approved Secrets to Massive Channel Subscription Growth</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/excel/"><u>【自由教學】快速找回丟失的 Excel 文件方法</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-xiaomi-14-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Xiaomi 14</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/best-aomei-onekey-recovery-versions-full-side-by-side-analysis/"><u>Best AOMEI OneKey Recovery Versions - Full Side-by-Side Analysis</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/complete-step-by-step-tutorial-safeguarding-your-iphone-with-ios-1navigate-protecting-and-recovering-data-on-macpc/"><u>Complete Step-by-Step Tutorial: Safeguarding Your iPhone with iOS 1Navigate | Protecting and Recovering Data on Mac/PC</u></a></li>
<li><a href="https://screen-capture.techidaily.com/elevate-your-live-recordings-on-facebook-with-4-methods-for-2024/"><u>Elevate Your Live Recordings on Facebook with 4 Methods for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/free-hp-deskjet-3050a-windows-printing-software-upgrade-available-now/"><u>Free HP Deskjet 3050A Windows Printing Software Upgrade Available Now</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-movie-marathon-discover-the-world-of-entertainment-with-crackle/"><u>Free Movie Marathon: Discover the World of Entertainment with Crackle</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guida-definitiva-allintegrazione-di-gmail-con-outlook-2016-un-tutorial-approfondito/"><u>Guida Definitiva All'integrazione Di Gmail Con Outlook 2016: Un Tutorial Approfondito</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/hikvision-ssdhdd/"><u>Hikvision SSDへ素早くHDDを移行する究極のガイド</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-safely-back-up-your-data-on-a-hard-drive-before-reformatting-with-windows-11-8-or-7/"><u>How to Safely Back Up Your Data on a Hard Drive Before Reformatting with Windows 11, 8 or 7</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-realme-12plus-5g-frp-bypass-by-drfone-android/"><u>In 2024, About Realme 12+ 5G FRP Bypass</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/mastering-incremental-file-copies-using-the-robocopy-utility/"><u>Mastering Incremental File Copies Using the Robocopy Utility</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/steps-to-recover-removed-tweets-and-videos-on-twitter/"><u>Steps to Recover Removed Tweets and Videos on Twitter</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-affordable-tablets-comprehensive-reviews-by-tech-experts-zdnet/"><u>Top Affordable Tablets : Comprehensive Reviews by Tech Experts | ZDNet</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-htc-u23-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive HTC U23 Screen | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/vrouwtje-snelle-toegang-van-window-11-file-explorer-herstellen/"><u>Vrouwtje Snelle Toegang Van Window 11 File Explorer Herstellen</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

