---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-11-24T19:23:28.745Z
updated: 2024-11-30T22:16:47.121Z
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-direct-download-of-youtube-videos/"><u>[New] 2024 Approved Direct Download of YouTube Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-avoid-the-fake-out-maintaining-authenticity-in-likes/"><u>[Updated] 2024 Approved Avoid the Fake-Out Maintaining Authenticity in Likes</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-podcastpathfinder-charting-new-courses/"><u>[Updated] 2024 Approved PodcastPathfinder Charting New Courses</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-exploring-new-horizons-a-guide-to-top-6-nft-innovators/"><u>[Updated] Exploring New Horizons A Guide to Top 6 NFT Innovators</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-next-evaluation-diverse-solutions-for-2024/"><u>[Updated] Next Evaluation Diverse Solutions for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-optimal-mobile-photography-and-videography-on-ios-and-android/"><u>[Updated] Optimal Mobile Photography and Videography on iOS & Android</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/complete-step-by-step-tutorial-safeguarding-your-iphone-with-ios-1navigate-protecting-and-recovering-data-on-macpc/"><u>Complete Step-by-Step Tutorial: Safeguarding Your iPhone with iOS 1Navigate | Protecting and Recovering Data on Mac/PC</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/curious-about-why-your-iphone-continuously-snaps-copies-of-images-discover-effective-ways-to-halt-duplication/"><u>Curious About Why Your iPhone Continuously Snaps Copies of Images? Discover Effective Ways to Halt Duplication!</u></a></li>
<li><a href="https://location-social.techidaily.com/does-samsung-galaxy-a15-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Samsung Galaxy A15 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/download-premium-facebook-hd-content-anywhere-for-2024/"><u>Download Premium Facebook HD Content Anywhere for 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/efficiently-mass-deploy-windows-7-across-several-pcs-using-a-single-imaged-setup/"><u>Efficiently Mass-Deploy Windows 7 Across Several PCs Using a Single Imaged Setup</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/guia-definitiva-para-guardar-la-imagen-de-su-pantalla-en-windows-1011-el-software-libre-mas-eficiente-que-existe/"><u>Guía Definitiva Para Guardar La Imagen De Su Pantalla en Windows 10/11: El Software Libre Más Eficiente Que Existe</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-nokia-c12-plus-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Nokia C12 Plus</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/lost-partition-recovery-in-windows-1011-a-4-step-guide-to-restoring-your-data/"><u>Lost Partition Recovery in Windows 10/11: A 4-Step Guide to Restoring Your Data</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/steps-to-recover-removed-tweets-and-videos-on-twitter/"><u>Steps to Recover Removed Tweets and Videos on Twitter</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/steps-to-restore-unintentionally-removed-data-when-relocating-files/"><u>Steps to Restore Unintentionally Removed Data When Relocating Files</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211192922-9780811742160-the-big-book-of-virginia-ghost-stories/"><u>The Big Book of Virginia Ghost Stories | Free Book</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/vrouwtje-snelle-toegang-van-window-11-file-explorer-herstellen/"><u>Vrouwtje Snelle Toegang Van Window 11 File Explorer Herstellen</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/windows-11-0/"><u>Windows 11 バックアップサイズが0バイトの問題を解消した！</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

