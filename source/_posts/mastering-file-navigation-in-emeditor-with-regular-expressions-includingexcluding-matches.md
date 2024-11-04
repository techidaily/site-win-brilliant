---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-10-31T16:46:34.111Z
updated: 2024-11-04T00:36:45.318Z
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-essential-gear-for-video-blogging-top-rated-camera-lenses-revealed/"><u>[New] 2024 Approved Essential Gear for Video Blogging Top-Rated Camera Lenses Revealed</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-drive-more-traffic-effective-strategies-for-youtube-outros/"><u>[New] Drive More Traffic Effective Strategies for YouTube Outros</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-ideal-timekeepers-top-10-androidios-apps-for-your-big-day/"><u>[New] In 2024, Ideal Timekeepers Top 10 Android/iOS Apps for Your Big Day</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-visioncast-feedback-interface/"><u>[New] VisionCast Feedback Interface</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-digital-detailing-at-your-command/"><u>[Updated] Digital Detailing at Your Command</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/csv3/"><u>「CSVデータ失われるのを防ぐ無料ツールトップ3」</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/aktuelle-fehlerbehebungen-entfernung-von-youtube-inhalten-fur-die-jahre-2021-bis-2024/"><u>Aktuelle Fehlerbehebungen: Entfernung Von YouTube-Inhalten Für Die Jahre 2021 Bis 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/comprehensive-guide-solving-the-ios-18-16-update-installation-issues-and-ensuring-data-safety/"><u>Comprehensive Guide: Solving the iOS 18-16 Update Installation Issues & Ensuring Data Safety</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/hp-laptop-effiziente-image-wiederaufnahme-mit-myrecover-die-ultimative-losung-fur-verlorene-fotos/"><u>HP Laptop: Effiziente Image-Wiederaufnahme Mit MyRecover – Die Ultimative Lösung Für Verlorene Fotos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-high-definition-zoom-features/"><u>In 2024, Navigating High-Definition Zoom Features</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unleash-your-inner-gamer-best-free-voice-change-tool-for-valorant/"><u>In 2024, Unleash Your Inner Gamer Best Free Voice Change Tool for Valorant</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-new-features-a-guide-to-using-live-activities-in-ios-16/"><u>Mastering the New Features: A Guide to Using Live Activities in iOS 16</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/professionelle-windows-11-clone-tools-lizenzfrei-und-ohne-bootschwierigkeiten/"><u>Professionelle Windows 11 Clone-Tools - Lizenzfrei Und Ohne Bootschwierigkeiten</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-battle-of-innovation-deciding-between-apple-watch-ultra-and-apple-watch-series-8-expert-reviews-and-comparison-chart/"><u>The Battle of Innovation: Deciding Between Apple Watch Ultra & Apple Watch Series #8 | Expert Reviews & Comparison Chart</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/ultimate-guide-free-windows-usb-recovery-tools-and-applications/"><u>Ultimate Guide: FREE Window's USB Recovery Tools and Applications</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/understanding-the-hyper-v-os-load-failure-solutions-for-missing-operating-system-issues/"><u>Understanding the 'Hyper-V OS Load Failure': Solutions for Missing Operating System Issues</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/vanuit-ongelukkig-gegaan-hoe-uw-reconstructieverzoek-naar-voorraad-is-aangeklapt/"><u>Vanuit Ongelukkig Gegaan... Hoe Uw Reconstructieverzoek Naar Voorraad Is Aangeklapt!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896555/19272" target="_top" id="1896555">
  <img src="//a.impactradius-go.com/display-ad/19272-1896555" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896555/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

