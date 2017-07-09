---
title: "设置继承是什么？"
titleSuffix: Intune for Education
description: "了解如何管理使用教育版的 Intune 设备组的设置。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 388e4f4468c3184d4dd941c74f8524a6302694f3
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017


---

# <a name="what-is-settings-inheritance"></a>设置继承是什么？

设置应用于组中。 由于组都设置为由及其所有子组继承层次结构，与上面的另一个，任何设置应用于组的一个组。 这使得更轻松地将设置应用到大的用户、 应用和设备组。

  ![树中的组和子组。](./media/groups-002-inheritance.png)

这意味着，对于使用其下的子组的任何组，子组将自动继承到它上面组所做的任何更改。 这称为_继承_。

## <a name="can-i-configure-subgroups-differently-after-inheriting-settings-from-another-group"></a>是否可以配置子组以不同的方式从另一个组中继承设置后？

子组可以单独进行配置，即使它们从其上方的组中继承设置。 可以通过只需配置的设置，你需要然后将其保存来覆盖继承的设置。

## <a name="can-i-ever-end-up-with-settings-that-do-not-work-together"></a>可以我曾经最终不协同工作的设置呢？

在多个设置具有应用于同一个组，则会通过 Intune 教育版单独分析每个设置。 强制用户采取措施以使其设备符合你设置某些设置将始终优先于其他设置。

请考虑子组，*第十二个年级 AP 计算机科学*，到组*第十二个年级*。 你知道 AP 计算机科学类将需要下载不需要安全扫描、 某些 JavaScript 文件，但你想要确保的整个评分结果不会尝试执行相同操作。 如果你不重写设置继承，限制性更强*第十二个年级*设置将应用到中的用户*第十二个年级 AP 计算机科学*。

## <a name="find-out-more"></a>查看详细信息

  - [在 Intune 中找的出有关完整的组的详细信息体验](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

