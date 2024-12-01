---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-11-29T22:57:35.162Z
updated: 2024-12-01T04:19:08.636Z
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
<li><a href="https://win-brilliant.techidaily.com/guide-complet-restaurer-les-informations-dun-ordinateur-avec-windows-endommage/"><u>« Guide Complet: Restaurer Les Informations D'un Ordinateur Avec Windows Endommagé »</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-asmr-app-selection-guide-for-phones/"><u>[New] 2024 Approved ASMR App Selection Guide for Phones</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/5oco6bq86kej5rg65zug5qqu5qgi5rai5asx6icm5byv6lw355qe56gs56kf5yig5ymy5y2a5y2x5qmf77yf/"><u>怎麼解決因檔案消失而引起的硬碟分割區危機？</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/expert-tips-for-bulk-file-migration-effortless-techniques-to-relocate-your-documents-to-an-exterior-storage-device/"><u>Expert Tips for Bulk File Migration: Effortless Techniques to Relocate Your Documents to an Exterior Storage Device</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-recover-windows-server-snapshots-on-vmware-and-hyper-v-a-comprehensive-guide/"><u>How to Recover Windows Server Snapshots on VMware and Hyper-V - A Comprehensive Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-mini-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/meet-the-future-with-oneplus-10t-ultra-fast-charging-capability-and-cutting-edge-android-12-system/"><u>Meet the Future with OnePlus 10T - Ultra-Fast Charging Capability and Cutting-Edge Android 12 System</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/merge-moments-seamlessly-from-tiktok-to-facebook-for-2024/"><u>Merge Moments Seamlessly From TikTok, To Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reinventing-tech-windows-leap-from-version-11/"><u>Reinventing Tech: Windows' Leap From Version 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

