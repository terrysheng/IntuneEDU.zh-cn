---
title: "设置是什么？"
titleSuffix: Intune for Education
description: "了解如何管理教育策略通过 Intune 设置。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: c7308ab88970c335a0c43d20f4558a54c9143fd9
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017



---

# <a name="what-are-settings"></a>设置是什么？

_设置_是你用于定义你的用户可以如何使用其设备。 这可以修改给用户尝试执行操作，或通过只需停止中执行某项在设备上的用户设备的响应方式。 教育版设置 Intune 允许你管理学校设备上的功能。

设置应用于组中。 由于组都设置为层次结构，与上面另一个字符串，一个组任何[由及其所有子组继承设置应用于组](settings-inheritance.md)。 这使得更轻松地将设置应用到大的用户、 应用和设备组。

## <a name="manage-settings"></a>管理设置

有三种方法来管理教育版的 Intune 中的设置：

* __Express 配置__： 选择最常使用的学校设置可在[Express 配置](how-do-i-manage-settings.md#manage-settings-with-express-configuration)以便学生可以安全和工作效率的教室中使用的设备。

* __组__： 所有设置进行都管理的每个单独的组。 这是相比与 Express 配置中可用的设置的扩展的列表。 找出什么[设置可供您此处](available-settings.md)。

* __租户设置__： 租户设置会影响所有用户和管理，你拥有的设备。 这些设置可使只能由使用某些管理员管理[适合对你的租户的访问级别](what-are-tenants.md)。

设置可以设置和分配给用户和设备的整个组。 分配给组中的用户设置将使用的用户，无论它们使用的何种设备只讨论。 无论谁登录到设备在设备上，将应用设置分配给组中的设备。

## <a name="find-out-more"></a>查看详细信息

- [了解有关如何保护应用和数据与在 Intune 中完整的管理体验的详细信息](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)

