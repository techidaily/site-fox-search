---
title: Scheduled Events and Their Impact on Automatic Task Execution
date: 2024-09-29T18:22:51.522Z
updated: 2024-10-05T18:30:46.030Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/fix-immediately-reduce-high-cpu-usage-of-your-device-targeted-solutions-for-tackling-excessive-shell-induced-heat/"><u>[Fix] Immediately Reduce High CPU Usage of Your Device – Targeted Solutions for Tackling Excessive Shell-Induced Heat.</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-premium-video-capture-devices-for-windows-os/"><u>[New] In 2024, Premium Video Capture Devices for Windows OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-expert-fb-video-sharing-tactics-for-desktop-and-handheld-devices-for-2024/"><u>[Updated] Expert FB Video Sharing Tactics for Desktop and Handheld Devices for 2024</u></a></li>
<li><a href="https://fox-search.techidaily.com/1-property-details-of-registry-storage-settings/"><u>1. Property Details of Registry Storage Settings</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-content-creation-in-todays-revenue-landscape/"><u>2024 Approved Content Creation in Today’s Revenue Landscape</u></a></li>
<li><a href="https://fox-search.techidaily.com/engaging-photo-carousel-pages-on-the-web/"><u>Engaging Photo Carousel Pages on the Web</u></a></li>
<li><a href="https://fox-search.techidaily.com/exploring-the-spectrum-of-methodical-structured-teaching-mst-models/"><u>Exploring the Spectrum of Methodical Structured Teaching (MST) Models</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebook-follower-verification-techniques-for-professionals-for-2024/"><u>Facebook Follower Verification Techniques for Professionals for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-garmin-virb-ultra-30-an-insider-look-at-an-adventure-staple/"><u>In 2024, Garmin VIRB Ultra 30 An Insider Look at an Adventure Staple</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Oppo Reno 11 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-xiaomi-redmi-k70-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Xiaomi Redmi K70 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://fox-search.techidaily.com/mastering-imsm-file-enrollment-comprehensive-strategies-and-tips/"><u>Mastering IMSM File Enrollment: Comprehensive Strategies and Tips</u></a></li>
</ul></div>

