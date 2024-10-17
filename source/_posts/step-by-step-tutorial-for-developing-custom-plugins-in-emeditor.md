---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-10-15T17:50:15.793Z
updated: 2024-10-17T16:17:18.221Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/a69a15798572265a2574284260281ddf651b6e2edc67c914e7a3a40f4a1feb7f.png
---

## Step-by-Step Tutorial for Developing Custom Plugins in EmEditor

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* March 1, 2008 at 2:38 pm [#5521](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/3597879799f03e6f1ad5d2ca5a32d334?s=80&d=identicon&r=g)Passiday](https://www.emeditor.com/forums/users/Passiday/ "View Passiday's profile")  
Participant  
Hello,  
 Is there any tutorial “How to cook your own plugin for EmEditor”? Being C# developer, I find it hard to grasp the programming of plugins in C by looking on the sources of existing samples available here for download. I’d be happy to see some sort of “basic plugin example” that would be good start, and then learn how it can be extended and also understand what are the limitations in interoperability between EmEditor and the plugin – what kind of features are acutally possible, and what not.  
 As I have previously said, I’d like to get a plugin that would be a floating window with embedded browser, that could be loaded with local or external URL. The JavaScript in the loaded HTML could have access to the EmEditor DOM, and vice-versa – the EmEditor macros could have access to the loaded window’s DOM. To my opinion, that would be like sacred grale – DHTML interface to build visually-enhanced mini-applications to enhance the functionality of basic EmEditor.  
March 2, 2008 at 1:33 am [#5523](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Passiday wrote:  
> Hello,  
>  
> Is there any tutorial “How to cook your own plugin for EmEditor”? Being C# developer, I find it hard to grasp the programming of plugins in C by looking on the sources of existing samples available here for download. I’d be happy to see some sort of “basic plugin example” that would be good start, and then learn how it can be extended and also understand what are the limitations in interoperability between EmEditor and the plugin – what kind of features are acutally possible, and what not.  
>  
> As I have previously said, I’d like to get a plugin that would be a floating window with embedded browser, that could be loaded with local or external URL. The JavaScript in the loaded HTML could have access to the EmEditor DOM, and vice-versa – the EmEditor macros could have access to the loaded window’s DOM. To my opinion, that would be like sacred grale – DHTML interface to build visually-enhanced mini-applications to enhance the functionality of basic EmEditor.  
 Unfortunately, there is no “basic plugin example”, but there are a number of source code available at [http://www.emeditor.com/modules/mydownloads/viewcat.php?cid=6](https://tools.techidaily.com/emeditor/products/) and some are very basic, especially “Word Count plug-in” might be a first one to look at. However, unfortunately, EmEditor DOM is not exposed for other applications, partly because EmEditor wants to be light-weighted.  
March 3, 2008 at 9:16 am [#5531](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/3597879799f03e6f1ad5d2ca5a32d334?s=80&d=identicon&r=g)Passiday](https://www.emeditor.com/forums/users/Passiday/ "View Passiday's profile")  
Participant  
> EmEditor DOM is not exposed for other applications  
 I am not very competent in Windows C application programming, so my question might appear stupid… I was under impression that everything (well, almost) that user can do with EmEditor interface – is possible via macros. The plugins allow to add things like extra windows and extra controls on the existing window (like expand-collapse buttons of the outline plugin). The plugins seem to have ver integrated way of communication with base EmEditor. I am very surprised to hear that there could not be a plugin that sends a “mini macro command” to base EmEditor for execution, and gets a value in return. But what do I know, maybe that requires extensive reprogramming and extra memory load. I’d say that exposing the DOM would allow to stop doing duplicate work with supporting similar range of functions for macros and plugins.  
March 3, 2008 at 5:40 pm [#5538](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Passiday wrote:  
>  
>> EmEditor DOM is not exposed for other applications  
>  
> I am not very competent in Windows C application programming, so my question might appear stupid… I was under impression that everything (well, almost) that user can do with EmEditor interface – is possible via macros. The plugins allow to add things like extra windows and extra controls on the existing window (like expand-collapse buttons of the outline plugin). The plugins seem to have ver integrated way of communication with base EmEditor. I am very surprised to hear that there could not be a plugin that sends a “mini macro command” to base EmEditor for execution, and gets a value in return. But what do I know, maybe that requires extensive reprogramming and extra memory load. I’d say that exposing the DOM would allow to stop doing duplicate work with supporting similar range of functions for macros and plugins.  
 Thanks for inputs! I was not accurate in my previous reply. Actually a plug-in can be used as a communication layter between EmEditor DOM and outside applications if someone writes that plug-in. At any events, it is not very easy. I hope I clarified my points.
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-advanced-color-grading-techniques-with-luts-for-after-effects-users/"><u>[New] 2024 Approved Advanced Color Grading Techniques with LUTs for After Effects Users</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-expert-techniques-for-professionalizing-mobile-based-youtube-thumbnails/"><u>[New] In 2024, Expert Techniques for Professionalizing Mobile-Based YouTube Thumbnails</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-capture-android-the-ultimate-recorder-at-no-cost/"><u>[Updated] 2024 Approved Capture Android The Ultimate Recorder at No Cost</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/5lplush6ac85ocn44gu6auy44ge5pa55rov77ya5pya5paw44gn5ymk6zmk44gv44km44gf44oh44o844k44ks5ywd44gr5oi744gz5oml5byv44gn/"><u>信頼性の高い方法：最新で削除されたデータを元に戻す手引き</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-gpt/"><u>选择专业Windows GPT赛博克隆解决方案 – 提高系统安全性和效率</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/6yen5paw5a2457pluss6loh5rqq5zue5ps25qg2566h55cg77ya5aac5l2v6ycg6l2j5rc45lmf5yiq6zmk/"><u>重新學習資源回收桶管理：如何逆轉永久刪除</u></a></li>
<li><a href="https://vp-tips.techidaily.com/accelerating-videos-an-easy-start-with-snapchat/"><u>Accelerating Videos An Easy Start with Snapchat</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/easy-guide-pausing-auto-play-on-your-apple-music-streams/"><u>Easy Guide: Pausing Auto-Play on Your Apple Music Streams</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728491329377-excel-4/"><u>Excel 表格失去的真相：深入了解 4 种恢复技巧</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guida-semplice-e-completa-per-eseguire-il-backup-delle-email-di-outlook-su-disco-con-facilita/"><u>Guida Semplice E Completa per Eseguire Il Backup Delle Email Di Outlook Su Disco Con Facilità</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-easily-forward-or-copy-messages-from-your-yahoo-mail-top-3-methods-revealed/"><u>How to Easily Forward or Copy Messages From Your Yahoo Mail: Top 3 Methods Revealed</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-from-apple-iphone-13-mini-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock From Apple iPhone 13 mini?</u></a></li>
<li><a href="https://facebook.techidaily.com/social-giants-iron-fisted-approach-to-combatting-false-claims/"><u>Social Giant's Iron-Fisted Approach to Combatting False Claims</u></a></li>
<li><a href="https://win-info.techidaily.com/titres-seo-syncnez-votre-base-de-donnees-utilisant-robocopy-guide-pratique-et-facile/"><u>Titres SEO : Syncnez Votre Base De Données Utilisant Robocopy - Guide Pratique Et Facile</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/unable-to-locate-the-webpage-understanding-404-errors/"><u>Unable to Locate the Webpage: Understanding 404 Errors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/visualizing-chronoscopic-imagery-in-media/"><u>Visualizing Chronoscopic Imagery in Media</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728487966531-windows-xp/"><u>フリーソフトでWindows XPバックアップ:スムーズなデータ保護のコツ</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

