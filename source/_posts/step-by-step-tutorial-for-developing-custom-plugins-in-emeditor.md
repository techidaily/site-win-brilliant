---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-11-08T00:51:58.185Z
updated: 2024-11-12T19:07:06.716Z
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-decoding-youtubes-5-second-tales/"><u>[New] 2024 Approved Decoding YouTube's 5-Second Tales</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-igtv-to-fb-exposure-strategies-6-essential-tips/"><u>[New] 2024 Approved IGTV to FB Exposure Strategies (6 Essential Tips)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-revamp-srt-to-subc-3-effective-techniques-unpacked/"><u>[New] Revamp SRT to SUBC 3 Effective Techniques Unpacked</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/3-effektive-methoden-zum-erstellen-eines-systemwiederherstellungsdatentragers-unter-windows-11-81-8-und-7-schritt-fur-schritt-anleitung/"><u>3 Effektive Methoden Zum Erstellen Eines Systemwiederherstellungsdatenträgers Unter Windows 11, 8.1, 8 Und 7 – Schritt-Für-Schritt-Anleitung</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/system-restore-points-in-windows-11-5/"><u>揪出失去 System Restore Points in Windows 11的秘技: 5次方法分享</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/bestaanbouw-van-veiligheid-meest-effectieve-mogelijkheden-en-verder-buigen-groot-inleidingshandboek/"><u>Bestaanbouw Van Veiligheid: Meest Effectieve Mogelijkheden en Verder Buigen - Groot Inleidingshandboek</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/boost-your-site-with-cookiebot-enabled-features/"><u>Boost Your Site with Cookiebot-Enabled Features</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/capturing-every-angle-top-choice-pro-360cameras-of-2023/"><u>Capturing Every Angle Top Choice Pro 360°Cameras of 2023</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/el-mejor-respaldo-de-particion-para-windows-compatible-con-las-versiones-11-10-8-y-7/"><u>El Mejor Respaldo De Partición Para Windows: Compatible Con Las Versiones 11, 10, 8 Y 7</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-5-evolution-anticipated-breakthrough-capabilities/"><u>GPT-5 Evolution: Anticipated Breakthrough Capabilities</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-move-your-entire-music-library-from-an-external-hard-drive-to-ios-devices/"><u>How to Move Your Entire Music Library From an External Hard Drive to iOS Devices</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-superior-animation-suites-top-3d-modelers/"><u>In 2024, Superior Animation Suites Top 3D Modelers</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/save-big-with-our-ultimate-guide-to-julys-premier-laptop-bargains-at-zdnet/"><u>Save Big with Our Ultimate Guide to July's Premier Laptop Bargains at ZDNet</u></a></li>
<li><a href="https://technical-tips.techidaily.com/share-your-gaming-highlights-screen-capture-techniques-for-the-nintendo-switch/"><u>Share Your Gaming Highlights: Screen Capture Techniques for the Nintendo Switch</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/stop-auto-updating-your-pc-in-windows-with-easy-tips-and-tricks/"><u>Stop Auto-Updating Your PC in Windows with Easy Tips and Tricks</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/topmost-efficient-file-restoration-options-for-windows-users-an-in-depth-exploration/"><u>Topmost Efficient File Restoration Options for Windows Users: An In-Depth Exploration</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/vanishing-in-the-crowd-how-to-peruse-instagram-stories-on-various-platforms-anonymously/"><u>Vanishing in the Crowd How to Peruse Instagram Stories on Various Platforms Anonymously</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-11-partition-recovery-techniques-the-top-two-methods-you-should-know-about/"><u>Windows 11 Partition Recovery Techniques: The Top Two Methods You Should Know About</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-1110872hdd/"><u>Windows 11/10/8/7での2台の外部HDD同期手順</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

