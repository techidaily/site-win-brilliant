---
title: "Mastering File Navigation in EmEditor with Regular Expressions: Including/Excluding Matches"
date: 2025-02-06T00:42:28.750Z
updated: 2025-02-09T07:49:19.080Z
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
<li><a href="https://article-helps.techidaily.com/new-essential-list-of-minuscule-uavs-2021/"><u>[New] Essential List of Minuscule UAVs 2021</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-basic-strategy-revamping-fishy-windowspeak/"><u>[Updated] 2024 Approved Basic Strategy Revamping Fishy Windowspeak</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-best-image-safekeepers-online-for-2024/"><u>[Updated] Best Image Safekeepers Online for 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1726222098139-wtv-wmv-movavi/"><u>「ワンクリックで無料オンラインWTV WMV Movaviへの変換ガイド」</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/como-diminuir-o-tamanho-dos-seus-arquivos-mov-online-e-gratuitamente-top-7-dicas/"><u>Como Diminuir O Tamanho Dos Seus Arquivos MOV Online E Gratuitamente - Top 7 Dicas</u></a></li>
<li><a href="https://tech-haven.techidaily.com/expertly-crafted-list-the-ultimate-six-benefits-for-procuring-an-apple-watch-featured-by-a-wearable-specialist-at-zdnet/"><u>Expertly Crafted List: The Ultimate Six Benefits for Procuring an Apple Watch, Featured by a Wearable Specialist at ZDNet</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guia-rapida-para-convertir-videos-wmv-en-musica-aiff-gratuita-a-traves-de-software-en-linea/"><u>Guía Rápida Para Convertir Videos WMV en Música AIFF Gratuita a Través De Software en Línea</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-handle-illegal-game-entry-error-messages-successfully/"><u>How to Handle 'Illegal Game Entry' Error Messages Successfully</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-music-on-realme-by-fonelab-android-recover-music/"><u>How to restore wiped music on Realme</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-to-pay-for-apple-tvplus-on-iphone-12-mini-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID to Pay for Apple TV+ on iPhone 12 mini</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-8-things-to-consider-before-buying-next-lens-for-4k-camera/"><u>In 2024, 8 Things to Consider Before Buying Next Lens for 4K Camera</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/mastering-overtime-highlights-a-step-by-step-tutorial-for-saving-overwatchs-best-plays/"><u>Mastering Overtime Highlights: A Step-by-Step Tutorial for Saving Overwatch's Best Plays</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/transformer-un-fichier-audio-m4b-en-format-mp4-gratuit-sur-internet-avec-movavi/"><u>Transformer Un Fichier Audio M4B en Format MP4 Gratuit - Sur Internet Avec Movavi</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/vob/"><u>VOBファイルを完全無料でオンライン変換 - 動画魔童</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

