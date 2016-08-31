---
title: "Create a task sequence for non-operating system deployments with System Center Configuration Manager"
ms.custom: na
ms.date: 2015-12-08
ms.prod: configuration-manager
ms.reviewer: na
ms.suite: na
ms.technology: 
  - configmgr-osd
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 92aaec8a-8751-442a-b64b-62ab05b5bf50
caps.latest.revision: 6
author: Dougeby
translation.priority.ht: 
  - cs-cz
  - de-de
  - en-gb
  - es-es
  - fr-fr
  - hu-hu
  - it-it
  - ja-jp
  - ko-kr
  - nl-nl
  - pl-pl
  - pt-br
  - pt-pt
  - ru-ru
  - sv-se
  - tr-tr
  - zh-cn
  - zh-tw
---
# Create a task sequence for non-operating system deployments with System Center Configuration Manager
Task sequences in System Center Configuration Manager are used to automate a variety of tasks within your environment. These tasks are primarily designed and tested for deploying operating systems.  Configuration Manager has many other features that should be the primary technology that you use for scenarios such as [application installation](http://technet.microsoft.com/library/mt627959\(TechNet.10\).aspx), [software updates installation](http://technet.microsoft.com/library/mt634340\(TechNet.10\).aspx), [setting configuration](http://technet.microsoft.com/library/mt629310\(TechNet.10\).aspx), or custom automation. There are other Microsoft System Center automation technologies, such as [Orchestrator](https://technet.microsoft.com/library/hh237242.aspx) and [Service Management Automation](https://technet.microsoft.com/library/dn469260.aspx) that you should also consider.  
  
 The power of task sequences lies in their flexibility and how you  can use them to configure client settings, distribute software, update drivers, edit user states, and perform other tasks independent of operating system deployment. You can create a custom task sequence to add any number of tasks. While basic  use of custom task sequences for non-operating system deployment is supported, there is no way to test all of the possible configurations and the chance of having problems increases as you develop more complex task sequences.  
  
 The following steps can be used in a non-operating system deployment custom task sequence:  
  
-   [Check Readiness](../../osd/understand/task-sequence-steps.md#BKMK_CheckReadiness)  
  
-   [Connect To Network Folder](../../osd/understand/task-sequence-steps.md#BKMK_ConnectToNetworkFolder)  
  
-   [Download Package Content](../../osd/understand/task-sequence-steps.md#BKMK_DownloadPackageContent)  
  
-   [Install Application](../../osd/understand/task-sequence-steps.md#BKMK_InstallApplication)  
  
-   [Install Package](../../osd/understand/task-sequence-steps.md#BKMK_InstallPackage)  
  
-   [Install Software Updates](../../osd/understand/task-sequence-steps.md#BKMK_InstallSoftwareUpdates)  
  
-   [Restart Computer](../../osd/understand/task-sequence-steps.md#BKMK_RestartComputer)  
  
-   [Run Command Line](../../osd/understand/task-sequence-steps.md#BKMK_RunCommandLine)  
  
-   [Run PowerShell Script](../../osd/understand/task-sequence-steps.md#BKMK_RunPowerShellScript)  
  
-   [Set Dynamic Variables](../../osd/understand/task-sequence-steps.md#BKMK_SetDynamicVariables)  
  
-   [Set Task Sequence Variable](../../osd/understand/task-sequence-steps.md#BKMK_SetTaskSequenceVariable)  
  
## See Also  
 [Create a custom task sequence with System Center Configuration Manager](../../osd/deploy-use/create-a-custom-task-sequence.md)