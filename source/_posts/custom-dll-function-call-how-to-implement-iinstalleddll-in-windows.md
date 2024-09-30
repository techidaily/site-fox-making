---
title: "Custom DLL Function Call: How to Implement IInstalledDll in Windows"
date: 2024-09-26T05:49:57.989Z
updated: 2024-09-30T09:08:48.064Z
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
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Declaration

IInstalledDllFunctionCallCustomAction: ICustomAction

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Overview

This interface facilitates editing custom action for calling function from installed native dll .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Properties

**IFile InstalledDll** \- Gets or sets the installed dll file of the custom action.

**String FunctionName** \- Gets or sets the name of a function to call .

**String ActionData** \- Gets or sets the value of the CustomActionData property. This property can be retrieved as a regular property inside Deferred custom actions and it is available only for DLL, JScript and VBScript custom actions. A common usage scenario is to use the CustomActionData property in Rollback Custom Actions since they are also deferred .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Example

      $advinst = new-object -com AdvancedInstaller
$project = $advinst.CreateProjectS(“architect”)
$dllFile = $project.FilesComponent.AddFileS("appdir\my_app", "D:\test.dll")
$custAct = $project.CustomActionsComponent.NewInstalledNativeDllFunctionCall($dllFile)
$custAct.FunctionName = "ExecuteTest"

    Copy

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
<li><a href="https://facebook-video-recording.techidaily.com/updated-eliminate-imposter-face-effects-in-facebook-discussion/"><u>[Updated] Eliminate Imposter Face Effects in Facebook Discussion</u></a></li>
<li><a href="https://sound-issues.techidaily.com/black-ops-cold-war-repair-your-voice-chat-feature-expert-fixes-and-advice/"><u>Black Ops Cold War: Repair Your Voice Chat Feature - Expert Fixes & Advice</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effortless-conversion-turn-dall-es-webp-art-into-jpeg-png/"><u>Effortless Conversion: Turn DALL-E's WebP Art Into JPEG, PNG</u></a></li>
<li><a href="https://fox-making.techidaily.com/how-to-customize-your-websites-book-titles-with-keywords-and-descriptions-using-flipbuilder/"><u>How to Customize Your Website's Book Titles with Keywords & Descriptions Using FlipBuilder</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-htc-u23-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing HTC U23 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://fox-making.techidaily.com/recovering-your-missing-flipkey-a-comprehensive-guide-on-the-flipbuilder-platform/"><u>Recovering Your Missing FlipKey: A Comprehensive Guide on the FlipBuilder Platform</u></a></li>
<li><a href="https://fox-making.techidaily.com/share-functionality-explained-navigating-through-flipbuilders-sharing-tools/"><u>Share Functionality Explained: Navigating Through FlipBuilder's Sharing Tools</u></a></li>
<li><a href="https://fox-making.techidaily.com/top-locations-to-source-custom-photo-frames-after-editing-with-flipbuilder/"><u>Top Locations to Source Custom Photo Frames After Editing with FlipBuilder</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/understanding-your-place-in-youtube-earnings-for-2024/"><u>Understanding Your Place in YouTube Earnings for 2024</u></a></li>
</ul></div>

