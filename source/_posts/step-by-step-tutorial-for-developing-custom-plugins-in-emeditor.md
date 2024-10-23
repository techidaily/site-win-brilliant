---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-10-19T04:00:53.159Z
updated: 2024-10-23T05:22:44.389Z
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
<li><a href="https://fox-links.techidaily.com/new-effortless-text-insertion-on-visuals-explained-for-2024/"><u>[New] Effortless Text Insertion on Visuals Explained for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/he-best-of-yt-a-deep-dive-into-music-dance-clips-23-for-2024/"><u>[New] The Best of YT A Deep Dive Into Music Dance Clips, '23 for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-pixelated-panoramas-instaslideshow/"><u>[Updated] 2024 Approved Pixelated Panoramas InstaSlideShow</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/11-windows52024/"><u>11 Windows用ベストフリーファイル回復ツール5本【2024新雑誌】</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-complete-introduction-to-snapchats-new-feature/"><u>In 2024, A Complete Introduction to Snapchat's New Feature</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-honor-90-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Honor 90 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/pictorial-mosaic-construction-with-digital-photography/"><u>Pictorial Mosaic Construction with Digital Photography</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/problembehandlung-fur-windows-server-sicherungsaktion-unzureichender-platz-auf-datentrager-behoben/"><u>Problembehandlung Für Windows Server Sicherungsaktion - Unzureichender Platz Auf Datenträger Behoben</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-meizu-21-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Meizu 21 Pro</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/resolving-the-windows-server-2016-startup-cycle-issues-post-update-top-5-methods/"><u>Resolving the Windows Server 2016 Startup Cycle Issues Post-Update: Top 5 Methods</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windowshp0xc000021a/"><u>Windowsパフォーマンス障害：HPの場合、エラー0xC000021Aが表す問題</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

