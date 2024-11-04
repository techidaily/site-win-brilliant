---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-10-29T20:55:15.070Z
updated: 2024-11-04T01:19:19.717Z
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
<li><a href="https://vp-tips.techidaily.com/updated-exclusive-insights-the-highest-rated-vr-games-for-2024/"><u>[Updated] Exclusive Insights The Highest-Rated VR Games for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-precision-leaders-best-7-shooting-adventures/"><u>[Updated] In 2024, Precision Leaders Best 7 Shooting Adventures</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1-system/"><u>1 System</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728496490061-aomei-backupper/"><u>配置データのエクスポート・インポート - AOMEI Backupperガイド</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728487674371-aomei-fonebackup-ios/"><u>使用 AOMEI FoneBackup 轻松移动数据保存技巧：iOS设备的完整指导</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/t-roundup-of-platforms-for-video-intro-acquisition-for-2024/"><u>Expert Roundup of Platforms for Video Intro Acquisition for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-get-back-your-vanished-iphone-photos-a-guide-for-devices-6s-7-8-x-and-11/"><u>How to Get Back Your Vanished iPhone Photos: A Guide for Devices 6S, 7, 8, X & 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Xiaomi 13T? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722976029844-linksys-ae2500-easy-driver-download-boost-your-wi-fi-experience-instantly/"><u>Linksys AE2500 Easy Driver Download - Boost Your Wi-Fi Experience Instantly!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/meta-unveils-512gb-quest-3-offer-the-premier-virtual-reality-deal-of-the-moment-says-zdnet/"><u>Meta Unveils 512GB Quest 3 Offer – The Premier Virtual Reality Deal of the Moment, Says ZDNet</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-reviews-expert-insights-on-the-latest-gadgets-and-computer-components/"><u>Tom's Tech Reviews: Expert Insights on the Latest Gadgets and Computer Components</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/transfert-dun-systeme-hdd-a-ssd-avec-commentcloner-pour-windows-7810/"><u>Transfert D'un Système HDD À SSD Avec CommentCloner Pour Windows 7/8/10</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/ultimate-guide-efficiently-moving-data-onto-an-external-hdd-on-windows-10/"><u>Ultimate Guide: Efficiently Moving Data Onto an External HDD on Windows 10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

