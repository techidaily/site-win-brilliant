---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-10-22T17:21:41.313Z
updated: 2024-10-29T07:32:59.266Z
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
<li><a href="https://screen-capture.techidaily.com/new-capturing-your-workspace-a-step-by-step-screenrec-guide/"><u>[New] Capturing Your Workspace A Step-by-Step ScreenRec Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-audio-interfaces-unveiled-the-podcasters-must-have-list/"><u>[New] Top Audio Interfaces Unveiled The Podcaster's Must-Have List</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-pinnacle-speech-to-text-applications/"><u>[Updated] 2024 Approved Pinnacle Speech-to-Text Applications</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-capturing-moments-in-time-creating-dynamic-photo-videos-with-pixiz/"><u>[Updated] Capturing Moments in Time Creating Dynamic Photo Videos with Pixiz</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-efficient-subtitling-strategies-for-facebook-media-posts-for-2024/"><u>[Updated] Efficient Subtitling Strategies for Facebook Media Posts for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-optimal-energy-kits-for-gopro-hero5-genuine-and-third-party-brands-for-2024/"><u>[Updated] Optimal Energy Kits for GoPro Hero5 – Genuine and Third-Party Brands for 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/5lplush6ac85ocn44gu6auy44ge5pa55rov77ya5pya5paw44gn5ymk6zmk44gv44km44gf44oh44o844k44ks5ywd44gr5oi744gz5oml5byv44gn/"><u>信頼性の高い方法：最新で削除されたデータを元に戻す手引き</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-gpt/"><u>选择专业Windows GPT赛博克隆解决方案 – 提高系统安全性和效率</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/6yen5paw5a2457pluss6loh5rqq5zue5ps25qg2566h55cg77ya5aac5l2v6ycg6l2j5rc45lmf5yiq6zmk/"><u>重新學習資源回收桶管理：如何逆轉永久刪除</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728491329377-excel-4/"><u>Excel 表格失去的真相：深入了解 4 种恢复技巧</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guida-semplice-e-completa-per-eseguire-il-backup-delle-email-di-outlook-su-disco-con-facilita/"><u>Guida Semplice E Completa per Eseguire Il Backup Delle Email Di Outlook Su Disco Con Facilità</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-easily-forward-or-copy-messages-from-your-yahoo-mail-top-3-methods-revealed/"><u>How to Easily Forward or Copy Messages From Your Yahoo Mail: Top 3 Methods Revealed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-samsung-galaxy-s24-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Samsung Galaxy S24 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-or-update-your-raid-controller-intels-latest-driver-support-for-windows-111087-systems/"><u>Install or Update Your RAID Controller: Intel's Latest Driver Support for Windows 11/10/8/7 Systems</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/iphone-to-iphone-the-complete-guide-on-data-transfer-without-using-an-apple-id/"><u>IPhone to iPhone: The Complete Guide on Data Transfer Without Using an Apple ID</u></a></li>
<li><a href="https://technical-tips.techidaily.com/removing-your-repost-from-tiktok-simple-steps-inside/"><u>Removing Your Repost From TikTok: Simple Steps Inside</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/unable-to-locate-the-webpage-understanding-404-errors/"><u>Unable to Locate the Webpage: Understanding 404 Errors</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-realme-gt-5-pro-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Realme GT 5 Pro Users</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728487966531-windows-xp/"><u>フリーソフトでWindows XPバックアップ:スムーズなデータ保護のコツ</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

