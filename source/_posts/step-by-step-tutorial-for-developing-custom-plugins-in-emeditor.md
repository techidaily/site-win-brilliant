---
title: Step-by-Step Tutorial for Developing Custom Plugins in EmEditor
date: 2025-03-05T19:48:01.708Z
updated: 2025-03-07T21:08:56.505Z
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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-mastering-bio-link-addition-on-tiktok/"><u>[New] In 2024, Mastering Bio Link Addition on TikTok</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-decoding-the-intelligent-shooting-methods-of-auto-3-and-4-hdr-for-2024/"><u>[Updated] Decoding the Intelligent Shooting Methods of Auto, 3 & 4 HDR for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-how-to-secure-free-fcp-software-for-2024/"><u>[Updated] How to Secure Free FCP Software for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-achieving-the-pinnacle-of-color-accuracy-in-11-crucial-edits/"><u>[Updated] In 2024, Achieving the Pinnacle of Color Accuracy in 11 Crucial Edits</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/44cm5osp5asw44gq57ch5y2y77yb44ov44kh44kk44or44gm5rai44gi44gf44gc44go44gn44kc44cb44gp44gg44ke44gj44gm44oh44o844k44ks5pwr44gi44kl77yf44cn/"><u>「意外な簡単！ファイルが消えたあとでも、どうやってデータを救える？」</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/come-migrare-dal-tuo-hard-disk-al-ssd-senza-la-necessita-di-ripristinare-il-desktop/"><u>Come Migrare Dal Tuo Hard Disk Al SSD Senza La Necessità Di Ripristinare Il Desktop?</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/enregistrer-des-photos-sur-iphone-a-laide-dun-hdd-extern-au-sous-windows-11-ou-10-guide-complet/"><u>Enregistrer Des Photos Sur iPhone À L'aide D'un HDD Extern Au Sous Windows 11 Ou 10 - Guide Complet</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-infinix-smart-8-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Infinix Smart 8 Pro Phones with/without a PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/keep-your-work-consistently-updated-with-easy-onedrive-automatic-refresh-tips-for-windows-users/"><u>Keep Your Work Consistently Updated with Easy OneDrive Automatic Refresh Tips for Windows Users</u></a></li>
<li><a href="https://driver-error.techidaily.com/qualcomm-atheros-bluetooth-not-working-heres-how-to-solve-it-in-windows-10/"><u>Qualcomm Atheros Bluetooth Not Working? Here's How to Solve It in Windows 10</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/reviving-lost-photoshop-projects-a-step-by-step-guide/"><u>Reviving Lost Photoshop Projects: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win11-clearview-resolving-fuzzy-displays/"><u>Win11 ClearView: Resolving Fuzzy Displays</u></a></li>
</ul></div>

