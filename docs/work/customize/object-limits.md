---
title: Work tracking object limits | VSTS 
description: Limits placed on the number of objects that can be specified for the Inheritance and Hosted XML process models for Visual Studio Team Services (VSTS)
ms.technology: vs-devops-wit
ms.prod: vs-devops-alm
ms.assetid: E5FABB7C-ECA8-4FA5-9488-4AD78C60869A  
ms.manager: douge
ms.author: kaelli
ms.date: 06/02/2017
---

# Work tracking object limits 

<b>VSTS</b> 

When customizing the work item types (WITs) defined in the Inheritance or Hosted XML process models, be aware of the limits placed on objects defined in this topic. To learn about process models, see [Customize your work tracking experience](customize-work.md).

## Inheritance and Hosted XML process models

Below you find maximum number of object in the Inheritance and Hosted XML process models.

|Object | Inheritance |Hosted XML | 
|-------|------------:|----------:|
| Work item types defined for a process | 64  | 64 |
| Fields defined for an account | 4096  | 4096 |
| Fields defined for a process | 2048  | 2048 |
| Fields defined for a work item type | 64  | 256 |
| Pick lists defined for an account or collection | 512  | - |
| Pick list items defined for a list | 128  | - |
| Pick list item character length | 256  | - |
| Workflow states defined for a work item type | 32  | 16 |
| Rules defined for a work item type | 1024  | 1024 |
| Portfolio backlog levels defined for a process| 5  | 5 |
| Categories defined for a process | - | 32 | 
| Global lists defined for a process | - | 64  |
| List items defined within a global list | - | 512 | 

For additional restrictions and conformance requirements of the Hosted XML process model, see [Customize a process when using Hosted XML](import-process/customize-process.md).

>[!NOTE]  
>For the Hosted XML process model, you can define an approximate total of 10K items for all global lists specified across all WITs. 
 
## Work items
- A long text field can contain 1M characters.
- You can't assign more than 100 tags to a work item.
- You can't add more than 1,000 links to a work item.
- You can't add more than 100 attachments to a work item.
- You can't add an attachment size larger than 60MB to a work item.

## Related notes

- [Customize a process when using Hosted XML](import-process/customize-process.md)
- [Create an Inheritance process](process/manage-process.md)
- [Customize your work tracking experience](customize-work.md)