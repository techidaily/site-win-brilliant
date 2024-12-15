---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-12-13T10:31:18.807Z
updated: 2024-12-14T19:43:05.620Z
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
<li><a href="https://fox-cloud.techidaily.com/new-superb-simple-countdown-apps-for-free-for-2024/"><u>[New] Superb Simple Countdown Apps for Free for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-a-complete-overview-of-polarr-photo-editor-for-2024/"><u>[Updated] A Complete Overview of Polarr Photo Editor for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-change-youtube-playback-speed-to-speed-up-or-slow-down-video/"><u>[Updated] How to Change YouTube Playback Speed to Speed Up or Slow Down Video</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-audio-experts-choice-best-6-microphone-picks-for-online-broadcasting/"><u>[Updated] In 2024, Audio Experts' Choice Best 6 Microphone Picks for Online Broadcasting</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1-easy-steps-to-updating-your-windows-device-drivers-tips-by-yl-computing/"><u>1. Easy Steps to Updating Your Windows Device Drivers - Tips by YL Computing</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-top-tier-aerial-vehicles-sold-here/"><u>2024 Approved Top-Tier Aerial Vehicles Sold Here</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/can-using-a-registry-optimization-tool-benefit-your-pc-performance-find-out-with-yl-softwares-guide/"><u>Can Using a Registry Optimization Tool Benefit Your PC Performance? Find Out with YL Software’s Guide</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/ensuring-proper-hardware-linkage-on-pcs-expert-advice-by-yl-software-specialists/"><u>Ensuring Proper Hardware Linkage on PCs: Expert Advice by YL Software Specialists</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-google-pixel-7a-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Google Pixel 7a Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/maximizing-audio-quality-expert-techniques-to-enhance-your-dj-setup-with-pcdj-watch-our-djntv-guide/"><u>Maximizing Audio Quality: Expert Techniques to Enhance Your DJ Setup with PCDJ – Watch Our #DJNTV Guide!</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/troubleshooting-low-resolution-scans-improve-your-image-output-with-yl-computings-expert-advice/"><u>Troubleshooting Low-Resolution Scans: Improve Your Image Output with YL Computing's Expert Advice</u></a></li>
<li><a href="https://vp-tips.techidaily.com/winxvideo-ai-effizientes-video-und-audio-konvertieren-durch-gpu-technologie-fur-optimale-leistung/"><u>Winxvideo AI - Effizientes Video Und Audio Konvertieren Durch GPU-Technologie Für Optimale Leistung</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

