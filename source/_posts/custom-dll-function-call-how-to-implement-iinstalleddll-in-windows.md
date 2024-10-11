---
title: "Custom DLL Function Call: How to Implement IInstalledDll in Windows"
date: 2024-10-05T22:27:28.566Z
updated: 2024-10-11T00:34:24.091Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Custom DLL Function Call: How to Implement IInstalledDll in Windows"
thumbnail: https://thmb.techidaily.com/412d065764cb0ba50733f600b7a0dabb6c2d4fd117a0cc25cd8642bbb251c9cc.png
---

## Custom DLL Function Call: How to Implement IInstalledDll in Windows

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
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
         * [IAdvancedInstaller](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IAdvinstProject](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IProductDetails](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IFolder](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ILaunchConditionsComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IFilesComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IIniFilesComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IShortcut](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ITempFile](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IXmlFile](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IDirectoryMember](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IRegistryComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IInstallParameters](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IBuildComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ITextFileUpdatesComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ITextUpdateFile](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ITextUpdateAppendOrCreate](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ITextUpdateReplace](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IFileAssociations](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IDefaultProgramFA](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IExtensionFA](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IProgIdFA](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IVerbFA](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IEnvironment](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IEnvironmentVariable](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IProductCode](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IUpgradeCode](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMergeModulesComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMergeModule](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IDigitalSignature](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ICustomActionsComponent](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ICustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ICustomActionSequence](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IAttachedFileCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IAttachedScriptFileCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IDotNetCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IExeWithWorkingDirectoryCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IFileCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IInstalledFileCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IInstalledScriptFileCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IPowershellScriptFile](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IPowershellAttachedScriptFile](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IInstallCertificate](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IUninstallCertificate](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IFileFromPropertyCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IScriptFileFromPropertyCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IAttachedDllFunctionCallCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [IInstalledDllFunctionCallCustomAction](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ITranslationsComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IDriversComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [ISearch](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IServices](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IOrganizationComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IComComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IRemoveFilesComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IRemoveFile](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IUpdatesProject](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IUpdaterComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IPatchProject](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IPropertyComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IProperty](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IPathVariable](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMsixComponent](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMsixDependencies](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMsixDriverDependency](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMsixDriverConstraint](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMsixExternalDependency](https://tools.techidaily.com/advancedinstaller/products/)  
         * [IMsixPackageDependency](https://tools.techidaily.com/advancedinstaller/products/)
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

## IInstalledDllFunctionCallCustomAction

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Declaration

IInstalledDllFunctionCallCustomAction: ICustomAction

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Overview

This interface facilitates editing custom action for calling function from installed native dll .

## Properties

**IFile InstalledDll** \- Gets or sets the installed dll file of the custom action.

**String FunctionName** \- Gets or sets the name of a function to call .

**String ActionData** \- Gets or sets the value of the CustomActionData property. This property can be retrieved as a regular property inside Deferred custom actions and it is available only for DLL, JScript and VBScript custom actions. A common usage scenario is to use the CustomActionData property in Rollback Custom Actions since they are also deferred .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Example

      $advinst = new-object -com AdvancedInstaller
$project = $advinst.CreateProjectS(“architect”)
$dllFile = $project.FilesComponent.AddFileS("appdir\my_app", "D:\test.dll")
$custAct = $project.CustomActionsComponent.NewInstalledNativeDllFunctionCall($dllFile)
$custAct.FunctionName = "ExecuteTest"

    Copy

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## See also

[ICustomActionsComponent](https://tools.techidaily.com/advancedinstaller/products/)

[ICustomAction](https://tools.techidaily.com/advancedinstaller/products/)

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
<li><a href="https://network-issues.techidaily.com/fixed-screen-share-problem-between-laptop-and-tv/"><u>[Fixed] Screen Share Problem Between Laptop & TV</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-webcam-creation-video-making-for-mac-users/"><u>[New] In 2024, Webcam Creation Video Making for Mac Users</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-crafting-universal-streams-for-youtube-and-beyond-networks/"><u>[Updated] Crafting Universal Streams for YouTube & Beyond Networks</u></a></li>
<li><a href="https://fox-making.techidaily.com/effortlessly-crafting-editable-pdf-forms-no-adobe-required/"><u>Effortlessly Crafting Editable PDF Forms: No Adobe Required!</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/expert-tips-on-adding-yt-playlists-to-your-website-content/"><u>Expert Tips on Adding YT Playlists to Your Website Content</u></a></li>
<li><a href="https://fox-making.techidaily.com/exploring-the-power-of-icom-classes-unlocking-new-career-opportunities/"><u>Exploring the Power of ICOM Classes: Unlocking New Career Opportunities</u></a></li>
<li><a href="https://fox-making.techidaily.com/guide-to-generating-effective-filefolder-associations-for-streamlined-installation-processes/"><u>Guide to Generating Effective File/Folder Associations for Streamlined Installation Processes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-6-to-an-older-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 6 to an Older iOS Version? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-apple-iphone-xs-max-by-drfone-ios/"><u>How to Remove and Reset Face ID on Apple iPhone XS Max</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-ace-2v-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Ace 2V to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ignite-interest-with-your-own-solo-podcast-series/"><u>In 2024, Ignite Interest with Your Own Solo Podcast Series</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/instagram-stories-mastering-the-art-of-time-manipulation/"><u>Instagram Stories – Mastering the Art of Time Manipulation</u></a></li>
<li><a href="https://fox-making.techidaily.com/next-level-scripting-unlocking-the-full-potential-of-installer-powershell-apis/"><u>Next-Level Scripting: Unlocking the Full Potential of Installer PowerShell APIs</u></a></li>
<li><a href="https://fox-making.techidaily.com/speedy-techniques-for-instant-whiteness-transforming-online-background-colors-with-ease/"><u>Speedy Techniques for Instant Whiteness: Transforming Online Background Colors with Ease</u></a></li>
<li><a href="https://fox-making.techidaily.com/step-by-step-guide-casting-your-android-screen-onto-a-samsung-smart-tv/"><u>Step-by-Step Guide: Casting Your Android Screen Onto a Samsung Smart TV</u></a></li>
<li><a href="https://fox-making.techidaily.com/the-ultimate-list-of-top-free-photo-editing-tools-on-android/"><u>The Ultimate List of Top Free Photo Editing Tools on Android</u></a></li>
<li><a href="https://fox-making.techidaily.com/top-10-screen-recording-tools-for-windows-11-free-and-premium-options-explored/"><u>Top 10 Screen Recording Tools for Windows 11: Free and Premium Options Explored</u></a></li>
<li><a href="https://fox-making.techidaily.com/top-rated-free-and-premium-background-replacement-apps/"><u>Top-Rated Free and Premium Background Replacement Apps</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/winning-the-battle-against-video-tdr-problems-and-atikmpagsys-on-windows-10-a-comprehensive-guide/"><u>Winning the Battle Against Video TDR Problems and atikmpag.sys on Windows 10: A Comprehensive Guide</u></a></li>
</ul></div>

