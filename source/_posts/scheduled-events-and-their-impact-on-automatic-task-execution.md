---
title: Scheduled Events and Their Impact on Automatic Task Execution
date: 2024-09-26T16:43:32.570Z
updated: 2024-09-29T21:51:22.374Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-quick-and-effective-strategies-for-vimeo-capture/"><u>[New] 2024 Approved Quick & Effective Strategies for Vimeo Capture</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-professional-capturer-snappy-windows-snap/"><u>[Updated] Professional Capturer Snappy Windows Snap</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-zero-price-green-screen-aids/"><u>[Updated] Zero-Price Green Screen Aids</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-bypassing-barriers-privately-share-youtube-video-via-google/"><u>2024 Approved Bypassing Barriers Privately Share YouTube Video via Google</u></a></li>
<li><a href="https://fox-search.techidaily.com/get-premium-xxxbunker-adult-videos-converted-to-common-file-types-mp4-mov-avi-on-windows-and-macos/"><u>Get Premium Xxxbunker Adult Videos Converted to Common File Types (MP4, MOV, AVI) on Windows and macOS</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-download-and-change-your-youtube-video-into-mov-file-a-complete-tutorial-for-pcs-and-macbooks/"><u>How to Download and Change Your YouTube Video Into MOV File: A Complete Tutorial for PCs and MacBooks</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-easily-download-your-favorite-shows-a-guide-using-playedto/"><u>How to Easily Download Your Favorite Shows: A Guide Using Played.to</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-fix-video-grabber-not-working-top-replacement-tools/"><u>How to Fix 'Video Grabber Not Working': Top Replacement Tools</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-get-your-favorite-nowness-media-content-cross-platform-guide-for-mac-and-windows-users/"><u>How to Get Your Favorite NOWNESS Media Content: Cross-Platform Guide for Mac & Windows Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-interactive-learning-strategies-in-video-editing/"><u>In 2024, Interactive Learning Strategies in Video Editing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-mastery-in-media-download-from-facebook-platforms/"><u>In 2024, Mastery in Media Download From Facebook Platforms</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Spoofing Life360 How to Do it on Samsung Galaxy F15 5G? | Dr.fone</u></a></li>
</ul></div>

