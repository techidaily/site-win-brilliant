---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2024-12-05T18:08:41.852Z
updated: 2024-12-09T09:53:54.037Z
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
<li><a href="https://extra-tips.techidaily.com/new-comprehensive-breakdown-exploring-lgs-widescreen-uhd-display/"><u>[New] Comprehensive Breakdown Exploring LG's Widescreen UHD Display</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-gateway-to-grandeur-embarking-on-a-classic-lit-journey-for-2024/"><u>[New] Gateway to Grandeur Embarking on a Classic Lit Journey for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/activating-microsofts-built-in-antivirus-tips-from-yl-software-experts/"><u>Activating Microsoft's Built-In Antivirus: Tips From YL Software Experts</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/advanced-windows-djing-mastering-the-art-of-wasapi-over-directsoundasio-for-optimal-audio-performance/"><u>Advanced Windows DJing: Mastering the Art of WASAPI Over DirectSound/ASIO for Optimal Audio Performance</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-oppo-k11-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Oppo K11 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/expert-advice-easily-refresh-your-pcs-hardware-support-with-yl-software/"><u>Expert Advice: Easily Refresh Your PC's Hardware Support with YL Software</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/fix-your-windows-issues-with-ease-understanding-and-correcting-error-codes-expert-advice-from-yl-systems/"><u>Fix Your Windows Issues with Ease: Understanding and Correcting Error Codes - Expert Advice From YL Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-playbook-for-podcast-titling-success-and-50plus-name-suggestions/"><u>In 2024, The Ultimate Playbook for Podcast Titling Success & 50+ Name Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-the-functionality-of-secure-boot-after-disabling-in-windows-bios/"><u>Restoring the Functionality of Secure Boot After Disabling in Windows BIOS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-infinix-zero-30-5g-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Infinix Zero 30 5G Device</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-streaming-webcams-comprehensive-tests-and-reviews-by-tech-experts-digital-trends/"><u>Top Rated Streaming Webcams : Comprehensive Tests & Reviews by Tech Experts | Digital Trends</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/troubleshooting-ram-issues-on-windows-machines-with-tips-from-yl-software-experts/"><u>Troubleshooting RAM Issues on Windows Machines with Tips From YL Software Experts</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/unveiling-the-role-how-do-system-properties-serve-within-the-windows-control-panel-insights-from-yl-technologies/"><u>Unveiling the Role: How Do System Properties Serve Within the Windows Control Panel? – Insights From YL Technologies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

