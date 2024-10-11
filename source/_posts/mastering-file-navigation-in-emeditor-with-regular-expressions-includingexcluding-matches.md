---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2024-10-09T17:34:26.117Z
updated: 2024-10-11T17:13:39.186Z
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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-enhance-phantom-flying-top-11-add-on-gear/"><u>[New] In 2024, Enhance Phantom Flying Top 11 Add-On Gear</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-quick-reference-guide-to-mastering-mobizens-screen-recording-tech/"><u>[Updated] 2024 Approved Quick Reference Guide to Mastering Mobizen's Screen Recording Tech</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-size-your-content-smartly-video-tips-for-instagram-excellence/"><u>[Updated] In 2024, Size Your Content Smartly Video Tips for Instagram Excellence</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-ultra-brief-on-achieving-clear-background-effects/"><u>[Updated] Ultra-Brief on Achieving Clear Background Effects</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1-convertidor-de-archivos-gratuito-en-linea-para-cambiar-wav-a-mp3-con-movavi/"><u>1. Convertidor De Archivos Gratuito en Línea Para Cambiar WAV a MP3 Con Movavi</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1-mastering-the-art-of-creating-stunning-collages-with-your-iphone-top-2-techniques-revealed/"><u>1. Mastering the Art of Creating Stunning Collages with Your iPhone: Top 2 Techniques Revealed!</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-seamless-content-propagation-beyond-youtube-and-facebook/"><u>In 2024, Seamless Content Propagation Beyond YouTube and Facebook</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/jpeg-zu-jpg-konvertieren-kostenlose-online-losungen-von-movavi-schnelle-und-einfache-bearbeitung/"><u>JPEG-Zu-JPG Konvertieren: Kostenlose Online-Lösungen Von Movavi – Schnelle Und Einfache Bearbeitung</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/mastering-mac-screen-capture-an-ultimate-tutorial-the-movavi-way/"><u>Mastering Mac Screen Capture: An Ultimate Tutorial - The Movavi Way</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/mpeg-ai-formati-di-file-m4am4b-migrazione-senza-costi-con-movavi-converter/"><u>MPEG Ai Formati Di File M4A/M4B: Migrazione Senza Costi Con Movavi Converter!</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/os-13-melhores-sites-gratuitos-para-assistir-animes-online-e-streaming-ilimitado-no-ano-de/"><u>Os 13 Melhores Sites Gratuitos Para Assistir Animes Online E Streaming Ilimitado No Ano De</u></a></li>
<li><a href="https://media-tips.techidaily.com/1723620227859-transform-your-dat-videos-into-mp4-in-a-flash-discover-the-three-best-converter-applications/"><u>Transform Your DAT Videos Into MP4 in a Flash - Discover the Three Best Converter Applications</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

