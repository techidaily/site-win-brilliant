---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-10-06T17:21:07.303Z
updated: 2024-10-11T17:06:05.715Z
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
<li><a href="https://screen-video-capture.techidaily.com/new-obs-studio-explained-capturing-ps4-playthroughs/"><u>[New] OBS Studio Explained Capturing PS4 Playthroughs</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-a-deep-dive-into-windows-hd-color-and-hdr-editing-excellence/"><u>[Updated] 2024 Approved A Deep Dive Into Windows HD Color and HDR Editing Excellence</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-discover-the-9-finest-filters-for-clear-video/"><u>[Updated] 2024 Approved Discover the 9 Finest Filters for Clear Video</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/best-free-mac-pdf-editor-software-top-10-recommendations/"><u>Best Free Mac PDF Editor Software: Top 10 Recommendations</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/best-screen-capture-tools-purchase-now/"><u>Best Screen Capture Tools - Purchase Now</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/como-convertir-archivo-mp4-al-formato-mpeg-de-manera-gratuita-con-herramientas-en-linea-movavi/"><u>Cómo Convertir Archivo MP4 Al Formato MPEG De Manera Gratuita Con Herramientas en Línea - Movavi</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722962070756-download-your-matching-intel-wireless-controller-driver-for-win11-10-or-7-today/"><u>Download Your Matching Intel Wireless Controller Driver for Win11, 10 or 7 Today!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-apple-iphone-13-pro-max-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From Apple iPhone 13 Pro Max Lock Screen | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/1723262406618-lenovo-desktop-powerhouse-save-big-on-the-latest-legion-model-featuring-rtx-4080-gpu-for-just-under-3k/"><u>Lenovo Desktop Powerhouse: Save Big on the Latest Legion Model Featuring RTX 4080 GPU for Just Under $3K</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/mp3-mp4/"><u>MP3 转换为 MP4（免费、快速指南） | 无限制播放</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/trasforma-i-tuoi-file-mxf-in-mp4-gratuitamente-su-internet-con-moveavew/"><u>Trasforma I Tuoi File MXF in MP4 Gratuitamente Su Internet Con Moveavew</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-missing-d3dx925dll-error-effective-strategies-and-tips/"><u>Troubleshooting Missing d3dx9_25.dll Error: Effective Strategies and Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027176/19272" target="_top" id="2027176">
  <img src="//a.impactradius-go.com/display-ad/19272-2027176" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027176/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

