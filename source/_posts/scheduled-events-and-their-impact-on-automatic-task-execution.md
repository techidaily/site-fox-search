---
title: Scheduled Events and Their Impact on Automatic Task Execution
date: 2024-10-05T08:12:56.539Z
updated: 2024-10-11T08:04:18.611Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Scheduled Events and Their Impact on Automatic Task Execution
thumbnail: https://thmb.techidaily.com/f386bcd1cdef2e7eae82e10cf44eeb6665615e5a19222b7cb69d0ec540888707.jpg
---

## Scheduled Events and Their Impact on Automatic Task Execution

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Environment Variables](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Scheduled Tasks](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Application Settings Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Account Settings Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Schedule Settings Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Trigger Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Event triggered Scheduled Tasks](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Condition Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Control Panel Applets](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Game Explorer](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Windows Firewall](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Users and Groups](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [COM](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Event triggered Scheduled Tasks

To schedule tasks **On an Event** add your custom query to the **Event query subscription** field.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)This field is [formatted](https://tools.techidaily.com/advancedinstaller/products/), so any conflicting special characters references must be escaped.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Example

<QueryList>
  <Query Id="0" Path="Application">
    <Select Path="Application">*[System[Provider[@Name='Advanced Installer 13.5 License Service']]]</Select>
  </Query>
</QueryList>

Copy

The above example should be included like this:

<QueryList>
  <Query Id="0" Path="Application">
    <Select Path="Application">*[\[]System[\[]Provider[\[]@Name='Advanced Installer 13.5 License Service'[\]][\]][\]]</Select>
  </Query>
</QueryList>

Copy

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-best-in-class-premium-screenshots-and-recorders/"><u>[Updated] Best in Class Premium Screenshots & Recorders</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-best-5-headsets-a-youtube-gamers-guide/"><u>[Updated] In 2024, Best 5 Headsets A YouTube Gamer's Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-premier-destinations-amplifying-youtube-videos/"><u>[Updated] Premier Destinations Amplifying YouTube Videos</u></a></li>
<li><a href="https://fox-search.techidaily.com/customize-virtual-machine-settings-for-optimized-performance/"><u>Customize Virtual Machine Settings for Optimized Performance</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnose-and-repair-why-isnt-my-razer-headset-mic-working-a-5-step-tutorial/"><u>Diagnose and Repair: Why Isn't My Razer Headset Mic Working? A 5-Step Tutorial</u></a></li>
<li><a href="https://fox-search.techidaily.com/easy-and-effective-ways-to-transform-vimeo-content-into-high-quality-mp3-files/"><u>Easy and Effective Ways to Transform Vimeo Content Into High-Quality MP3 Files</u></a></li>
<li><a href="https://fox-search.techidaily.com/effortless-chromebook-video-capture-a-beginners-guide-to-quick-and-easy-recording/"><u>Effortless Chromebook Video Capture: A Beginner's Guide to Quick and Easy Recording</u></a></li>
<li><a href="https://fox-search.techidaily.com/embark-on-your-digital-journey-with-msix-enhanced-product-selection-conversations/"><u>Embark on Your Digital Journey with MSIX-Enhanced Product Selection Conversations</u></a></li>
<li><a href="https://fox-search.techidaily.com/enhancing-productivity-with-the-versatile-notepad-feature/"><u>Enhancing Productivity with the Versatile Notepad Feature</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-7-ways-to-unlock-a-locked-oppo-a79-5g-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Oppo A79 5G Phone</u></a></li>
<li><a href="https://fox-search.techidaily.com/introducing-apowersofts-latest-screen-capture-software-professional-edition-v10/"><u>Introducing Apowersoft's Latest Screen Capture Software: Professional Edition V1.0</u></a></li>
<li><a href="https://fox-search.techidaily.com/key-characteristics-of-premium-service-offerings/"><u>Key Characteristics of Premium Service Offerings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-top-10-ios-gif-apps/"><u>Navigating the Top 10 iOS GIF Apps</u></a></li>
<li><a href="https://fox-search.techidaily.com/quick-and-effective-methods-to-strip-watermarks-off-reels-videos-2021-edition/"><u>Quick and Effective Methods to Strip Watermarks Off Reel's Videos - 2021 Edition</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-comprehensive-users-manual-to-google-photos/"><u>The Comprehensive User's Manual to Google Photos</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-freezes-in-windows-7-updates-expert-advice-edition-tip/"><u>Troubleshooting Freezes in Windows 7 Updates – Expert Advice Edition (Tip)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/virtual-reality-of-genuine-ppc-games/"><u>Virtual Reality of Genuine PPC Games</u></a></li>
</ul></div>

