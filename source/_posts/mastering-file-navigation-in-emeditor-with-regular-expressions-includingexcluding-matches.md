---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-10-15T17:48:51.210Z
updated: 2024-10-17T17:21:21.049Z
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-conquerors-of-the-past-the-prime-7-battle-simulations/"><u>[New] In 2024, Conquerors of the Past The Prime 7 Battle Simulations</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-blueprint-for-mastering-picsart/"><u>[New] The Ultimate Blueprint for Mastering PicsArt</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-prime-pickups-for-novice-gopro-owners/"><u>[Updated] Prime Pickups for Novice GoPro Owners</u></a></li>
<li><a href="https://techtrends.techidaily.com/10-effective-methods-for-converting-dvd-video-files-into-mp4-format-on-windows-macos-and-linux/"><u>10 Effective Methods for Converting DVD Video Files Into MP4 Format on Windows, MacOS & Linux</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/como-clonar-un-sistema-operativo-en-una-ssd-de-samsung-sin-necesidad-de-reinstalacion/"><u>Cómo Clonar Un Sistema Operativo en Una SSD De Samsung Sin Necesidad De Reinstalación</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-code-0x887a0006-a-step-by-step-guide-to-troubleshooting-and-resolution/"><u>Error Code 0X887A0006: A Step-by-Step Guide to Troubleshooting and Resolution</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/error-the-resource-youre-looking-for-doesnt-exist/"><u>Error: The Resource You're Looking For Doesn't Exist</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/experten-guide-zum-kopieren-des-c-laufwerks-zu-einer-ssdhhd-in-wenigen-schritten-anwenderfreundliche-anleitung-fur-windows-111087/"><u>Experten-Guide Zum Kopieren Des C-Laufwerks Zu Einer SSD/HHD in Wenigen Schritten – Anwenderfreundliche Anleitung Für Windows 11/10/8/7</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-vivo-x-fold-2-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Vivo X Fold 2 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://article-files.techidaily.com/look-up-tables-enhancing-visual-storytelling/"><u>Look-Up Tables Enhancing Visual Storytelling</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/praktik-restorasi-data-drive-c-step-by-step-for-windows-operating-systems-7-8-10-11/"><u>Praktik Restorasi Data Drive C Step by Step for Windows Operating Systems (7, 8, 10, 11)</u></a></li>
<li><a href="https://fox-access.techidaily.com/supercharge-your-video-subtitling-explore-leading-internet-tools-today-for-2024/"><u>Supercharge Your Video Subtitling Explore Leading Internet Tools Today for 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/tecnica-detallada-para-replicar-el-sistema-operativo-windows-8-y-81-al-otro-disco-duro/"><u>Técnica Detallada Para Replicar El Sistema Operativo Windows 8 Y 8.1 Al Otro Disco Duro</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/understanding-the-aomei-software-usage-agreement-comprehensive-guide-and-conditions/"><u>Understanding the AOMEI Software Usage Agreement: Comprehensive Guide and Conditions</u></a></li>
<li><a href="https://fox-blue.techidaily.com/vr-readiness-your-space-and-tech-essentials/"><u>VR Readiness Your Space and Tech Essentials</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/wie-kann-ich-ungewiesene-festplattenpartitionen-wiederherstellen-myrecovery-guide/"><u>Wie Kann Ich Ungewiesene Festplattenpartitionen Wiederherstellen - MyRecovery Guide</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-11-vs-windows-10-vs-windows-7-which-version-should-you-upgrade-to/"><u>Windows 11 Vs. Windows 10 Vs. Windows 7 - Which Version Should You Upgrade To?</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728476729081-outlook/"><u>もう止まらない！Outlookの自動応答が正常に機能しない理由とそれを修正する方法</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

