---
title: "Custom DLL Function Call: How to Implement IInstalledDll in Windows"
date: 2024-09-29T20:32:32.411Z
updated: 2024-10-05T21:22:04.835Z
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
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Declaration

IInstalledDllFunctionCallCustomAction: ICustomAction

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Overview

This interface facilitates editing custom action for calling function from installed native dll .

## Properties

**IFile InstalledDll** \- Gets or sets the installed dll file of the custom action.

**String FunctionName** \- Gets or sets the name of a function to call .

**String ActionData** \- Gets or sets the value of the CustomActionData property. This property can be retrieved as a regular property inside Deferred custom actions and it is available only for DLL, JScript and VBScript custom actions. A common usage scenario is to use the CustomActionData property in Rollback Custom Actions since they are also deferred .

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Example

      $advinst = new-object -com AdvancedInstaller
$project = $advinst.CreateProjectS(“architect”)
$dllFile = $project.FilesComponent.AddFileS("appdir\my_app", "D:\test.dll")
$custAct = $project.CustomActionsComponent.NewInstalledNativeDllFunctionCall($dllFile)
$custAct.FunctionName = "ExecuteTest"

    Copy

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-uncluttered-window-logger-w10-version/"><u>[New] Uncluttered Window Logger W10 Version</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/capturing-the-action-top-four-ways-to-record-on-xbox-one-for-2024/"><u>Capturing the Action Top Four Ways to Record on Xbox One for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/complete-guide-to-resolving-game-crash-issues-in-samurai-warriors-5-for-pc-users/"><u>Complete Guide to Resolving Game-Crash Issues in Samurai Warriors 5 for PC Users</u></a></li>
<li><a href="https://fox-making.techidaily.com/download-apowersofts-latest-update-the-new-version-40-of-streaming-audio-recorder/"><u>Download Apowersoft's Latest Update: The New Version 4.0 of Streaming Audio Recorder</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-roleplay-experience-6-ways-to-leverage-chatgpt-for-dynamic-dandd-sessions/"><u>Elevate Your Roleplay Experience: 6 Ways to Leverage ChatGPT for Dynamic D&D Sessions</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-13-mini-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 13 mini to other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/microsoft-bluetooth-driver-download-and-update-win-101187/"><u>Microsoft Bluetooth Driver Download & Update - Win 10/11/8/7</u></a></li>
<li><a href="https://fox-making.techidaily.com/optimized-browser-extension-for-dominating-holeio-best-for-windows-and-macs/"><u>Optimized Browser Extension for Dominating Hole.io - Best for Windows and Macs</u></a></li>
<li><a href="https://fox-making.techidaily.com/permanent-deletion-guide-erasing-footage-off-your-ios-device-effortlessly/"><u>Permanent Deletion Guide: Erasing Footage Off Your iOS Device Effortlessly</u></a></li>
<li><a href="https://fox-making.techidaily.com/the-role-of-data-accuracy-in-business-success-defining-data-integrity-and-key-methods-for-assurance/"><u>The Role of Data Accuracy in Business Success: Defining Data Integrity & Key Methods for Assurance</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-pc-audio-issues-fixing-low-sound-output-in-windows-11/"><u>Troubleshooting PC Audio Issues: Fixing Low Sound Output in Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/ultimate-guide-top-15-solutions-for-fixing-issues-on-any-iphone-model/"><u>Ultimate Guide: Top 15 Solutions for Fixing Issues on Any iPhone Model</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-strategies-for-smoother-loads-in-cod-warzone-eradicating-lags-and-upping-fps/"><u>Ultimate Strategies For Smoother Loads in COD: Warzone - Eradicating Lags and Upping Fps</u></a></li>
</ul></div>

