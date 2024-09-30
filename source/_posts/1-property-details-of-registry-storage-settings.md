---
title: 1. Property Details of Registry Storage Settings
date: 2024-09-29T04:03:15.557Z
updated: 2024-09-30T06:31:58.782Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes 1. Property Details of Registry Storage Settings
thumbnail: https://thmb.techidaily.com/b11b88dbc857a31124bdb8c315da86bb5d3837eab7f55e4985ff315c1fb2d97a.jpg
---

## 1. Property Details of Registry Storage Settings

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
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Search](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [File To Search Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Component Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Registry Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [INI Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [XML Search Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Folder Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Extended Search Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Search Results](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Properties Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Custom Actions](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Table Editor](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Registry Location Properties

### Root

 The Registry Hive Root. Can be one of "Classes Root", "Current User", "Local Machine" or "Users". 

### Key and Name

 The path to the registry location. Use the\[... \] button to browse the registry and select a key and value using the [Registry Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/). Also, you can insert reference to a file, folder or property using [Smart Edit Control](https://tools.techidaily.com/advancedinstaller/products/).

### Type

 Specifies how to interpret the value found in that registry location: as a path to a file, a folder or raw data. 

* The value contains a path to a file
* The search result property will contain the path to the file's folder if the file **is present** on the target machine. The returned value will be **null** if the file's parent folder does not exist.

| Location exist     | Location does not exist |                    |                        |
| ------------------ | ----------------------- | ------------------ | ---------------------- |
| File location      | C:\\A\\B\\My\_File.txt  | File location      | C:\\A\\B\\My\_File.txt |
| Registry contents  | C:\\A\\B\\My\_File.txt  | Registry contents  | C:\\A\\C\\My\_File.txt |
| **Returned Value** | **C:\\A\\B**            | **Returned Value** | **null**               |

* The value contains a path to a directory
* The result search property will contain the path to the folder if it **is present** on the target machine.The returned value will be **null** if the folder of the directory does not exist.

| Location exist     | Location does not exist |                    |          |
| ------------------ | ----------------------- | ------------------ | -------- |
| File location      | C:\\A\\B                | File location      | C:\\A\\B |
| Registry contents  | C:\\A\\B                | Registry contents  | C:\\A\\C |
| **Returned Value** | **C:\\A\\B**            | **Returned Value** | **null** |

* Retrieve the raw value
* The search result property will be equal with the value extracted from the registry and will be null if the registry value **does not exist**

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)When retrieving the raw value of a registry entry you will get these results:

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

* for string entries, the searches property will contain the registry entry's actual value
* for binary entries, the searches property will contain the registry entry's value preceded by the "#x" characters (for example "#xValue")
* for dword entries, the searches property will contain the registry entry's value preceded by the "#" character (for example "#Value")

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Search the 64-bit portion of the registry

 Check this if you want to search in the 64-bit registry section. 

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)In case of [Merge Module](https://tools.techidaily.com/advancedinstaller/products/) projects the following attributes can be made configurable at merge time:

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

* Root
* Key
* Name
* Type

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)For more information about the resources and attributes that can be configured, please see: [Configurable Merge Modules Page](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105876/7443" target="_top" id="2105876">
  <img src="//a.impactradius-go.com/display-ad/7443-2105876" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105876/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-easy-start-the-definitive-guide-to-free-channel-openers/"><u>[New] 2024 Approved Easy Start The Definitive Guide to Free Channel Openers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-best-boutique-online-portals-for-individualized-gift-artistry/"><u>[New] Best Boutique Online Portals for Individualized Gift Artistry</u></a></li>
<li><a href="https://fox-search.techidaily.com/1-free-compact-button-rich-templates-available-now-on-flipbuildercom/"><u>1. Free Compact Button-Rich Templates Available Now on FlipBuilder.com</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-beginners-guide-to-luts-and-downloading-tools/"><u>2024 Approved The Beginner's Guide to LUTs and Downloading Tools</u></a></li>
<li><a href="https://fox-search.techidaily.com/build-tailored-user-manuals-with-advanced-template-tech-discover-how-at-flipbuildercom/"><u>Build Tailored User Manuals with Advanced Template Tech - Discover How at FlipBuilder.com</u></a></li>
<li><a href="https://screen-recording.techidaily.com/discover-top-5-ios-ps2-games-simulators/"><u>Discover Top 5 IOS PS2 Games Simulators</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-add-music-tracks-in-your-flipbook-creation-a-guide-on-sound-integration-with-flipbuilder/"><u>How to Add Music Tracks in Your FlipBook Creation: A Guide on Sound Integration with FlipBuilder</u></a></li>
<li><a href="https://fox-search.techidaily.com/how-to-add-your-brands-logo-as-a-watermark-in-every-page-of-your-digital-brochure-with-flipbuilder/"><u>How to Add Your Brand's Logo as a Watermark in Every Page of Your Digital Brochure with FlipBuilder</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-brush-up-your-skills-and-inspire-creativity-top-10-freeware-for-mac/"><u>In 2024, Brush Up Your Skills & Inspire Creativity - Top 10 Freeware for Mac</u></a></li>
<li><a href="https://fox-search.techidaily.com/mastering-multimedia-conversion-how-to-turn-your-ppts-into-engaging-page-turning-flash-animations-using-flipbuilder/"><u>Mastering Multimedia Conversion: How to Turn Your PPTs Into Engaging Page-Turning Flash Animations Using FlipBuilder</u></a></li>
<li><a href="https://games-able.techidaily.com/mobile-marvel-making-your-iphone-a-gaming-powerhouse/"><u>Mobile Marvel: Making Your iPhone a Gaming Powerhouse</u></a></li>
<li><a href="https://win-able.techidaily.com/no-sound-in-lost-ark-here-are-the-solutions-you-need/"><u>No Sound in Lost Ark? Here Are the Solutions You Need</u></a></li>
<li><a href="https://fox-search.techidaily.com/ready-to-enhance-your-browsing-experience-uninstall-flipbuilder-toolbar-now/"><u>Ready to Enhance Your Browsing Experience? Uninstall FlipBuilder Toolbar Now!</u></a></li>
<li><a href="https://fox-search.techidaily.com/step-by-step-guide-creating-flipbooks-from-pdfs-and-incorporating-watermarks-using-flipbuilder/"><u>Step-by-Step Guide: Creating Flipbooks From PDFs and Incorporating Watermarks Using FlipBuilder</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/toms-tech-insights-comprehensive-reviews-and-buying-guides/"><u>Tom's Tech Insights: Comprehensive Reviews & Buying Guides</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-ai-chatbots-exploring-their-rise-in-popularity/"><u>Understanding AI Chatbots: Exploring Their Rise in Popularity</u></a></li>
<li><a href="https://fox-search.techidaily.com/understanding-the-flipbuilder-share-button-a-comprehensive-guide/"><u>Understanding the FlipBuilder Share Button: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-search.techidaily.com/unlock-the-potential-of-your-data-which-formats-are-compatible-for-conversion-with-flip-office/"><u>Unlock the Potential of Your Data: Which Formats Are Compatible for Conversion with Flip Office?</u></a></li>
</ul></div>

