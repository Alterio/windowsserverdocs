---
title: Wbadmin
description: "Windows Commands"
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 4b0b3f32-d21f-4861-84bb-b2eadbf1e7b8
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Wbadmin

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Enables you to back up and restore your operating system, volumes, files, folders, and applications from a command prompt.  
To configure a regularly scheduled backup, you must be a member of the **Administrators** group. To perform all other tasks with this command, you must be a member of the **Backup Operators** or the **Administrators** group, or you must have been delegated the appropriate permissions.  
You must run **wbadmin** from an elevated command prompt. (To open an elevated command prompt, right-click **Command Prompt**, and then click **Run as administrator**.)  
## Subcommands  
|Subcommand|Description|  
|--------------|---------------|  
|[Wbadmin enable backup](Wbadmin-enable-backup.md)|Configures and enables a regularly scheduled backup.|  
|[Wbadmin disable backup](Wbadmin-disable-backup.md)|Disables your daily backups.|  
|[Wbadmin start backup](Wbadmin-start-backup.md)|Runs a one-time backup. If used with no parameters, uses the settings from the daily backup schedule.|  
|[Wbadmin stop job](Wbadmin-stop-job.md)|Stops the currently running backup or recovery operation.|  
|[Wbadmin get versions](Wbadmin-get-versions.md)|Lists details of backups recoverable from the local computer or, if another location is specified, from another computer.|  
|[Wbadmin get items](Wbadmin-get-items.md)|Lists the items included in a backup.|  
|[Wbadmin start recovery](Wbadmin-start-recovery.md)|Runs a recovery of the volumes, applications, files, or folders specified.|  
|[Wbadmin get status](Wbadmin-get-status.md)|Shows the status of the currently running backup or recovery operation.|  
|[Wbadmin get disks](Wbadmin-get-disks.md)|Lists disks that are currently online.|  
|[Wbadmin start systemstaterecovery](Wbadmin-start-systemstaterecovery.md)|Runs a system state recovery.|  
|[Wbadmin start systemstatebackup](Wbadmin-start-systemstatebackup.md)|Runs a system state backup.|  
|[Wbadmin delete systemstatebackup](Wbadmin-delete-systemstatebackup.md)|Deletes one or more system state backups.|  
|[Wbadmin start sysrecovery](Wbadmin-start-sysrecovery.md)|Runs a recovery of the full system (at least all the volumes that contain the operating system's state). This subcommand  is only available if you are using the Windows Recovery Environment.|  
|[Wbadmin restore catalog](Wbadmin-restore-catalog.md)|Recovers a backup catalog from a specified storage location in the case where the backup catalog on the local computer has been corrupted.|  
|[Wbadmin delete catalog](Wbadmin-delete-catalog.md)|Deletes the backup catalog on the local computer. Use this subcommand only if the backup catalog on this computer is corrupted and you have no backups stored at another location that you can use to restore the catalog.|  
## Additional references  
-   [Backup and Recovery](http://go.microsoft.com/fwlink/?LinkID=195054)  
-   [Windows Server Backup Cmdlets in Windows PowerShell](http://technet.microsoft.com/library/jj902428.aspx)  