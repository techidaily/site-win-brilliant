---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2025-02-03T00:55:11.759Z
updated: 2025-02-08T16:57:21.628Z
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-detailed-breakdown-of-camstudio-screencapture-pro-for-2024/"><u>[New] Detailed Breakdown of CamStudio ScreenCapture Pro for 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/does-windows-defender-operate-correctly-insights-from-yl-software-experts/"><u>Does Windows Defender Operate Correctly? Insights From YL Software Experts</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/enabling-twain-functionality-for-scanners-in-windows-steps-and-tips-from-yl-software/"><u>Enabling TWAIN Functionality for Scanners in Windows: Steps and Tips From YL Software</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/enhancing-system-speed-and-performance-in-windows-nine-professional-guidance-by-yl-software-experts/"><u>Enhancing System Speed and Performance in Windows Nine – Professional Guidance by YL Software Experts</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/enhancing-your-laptop-speed-and-power-a-compreh-groph-guide-by-yl-computing-with-yl-software-innovations/"><u>Enhancing Your Laptop Speed and Power: A Compreh Groph Guide by YL Computing with YL Software Innovations</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhancing-your-media-production-skills-with-easy-to-follow-guides-for-windows-8-movie-maker/"><u>Enhancing Your Media Production Skills with Easy-to-Follow Guides for Windows 8 Movie Maker</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/how-to-troubleshoot-display-problems-on-your-windows-pc-expert-tips-from-yl-computing/"><u>How to Troubleshoot Display Problems on Your Windows PC: Expert Tips From YL Computing</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-nokia-c210-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Nokia C210 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-experience-next-level-media-craftsmanship-install-xp-maker/"><u>In 2024, Experience Next-Level Media Craftsmanship Install XP Maker</u></a></li>
<li><a href="https://fox-pages.techidaily.com/mejores-practicas-para-la-gestion-de-backups-y-copias-de-seguridad/"><u>Mejores Prácticas Para La Gestión De Backups Y Copias De Seguridad</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/pcdj-and-dex-3-now-compatible-with-macos-big-sur-enhancements-in-djing-software/"><u>PCDJ and DEX 3 Now Compatible with macOS Big Sur: Enhancements in DJing Software</u></a></li>
<li><a href="https://win11.techidaily.com/registry-edits-for-controlling-installation-processes/"><u>Registry Edits for Controlling Installation Processes</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1723862797098-revolutionize-your-gaming-setup-the-premium-24-curved-display-by-sceptre-now-available-for-just-79/"><u>Revolutionize Your Gaming Setup: The Premium, 24 Curved Display by Sceptre Now Available for Just $79</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-retrieve-content-from-a-shared-windows-space/"><u>Seamlessly Retrieve Content From a Shared Windows Space</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/steps-to-launch-network-and-sharing-settings-in-windows-os-yl-softwares-expert-advice/"><u>Steps to Launch Network & Sharing Settings in Windows OS - YL Software's Expert Advice</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/unbiased-take-on-recordcast-efficacy/"><u>Unbiased Take on RecordCast Efficacy</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/unlocking-kjs-secrets-how-karaoke-cloud-pro-delivers-ultimate-dj-tools/"><u>Unlocking KJ's Secrets: How Karaoke Cloud Pro Delivers Ultimate DJ Tools</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

