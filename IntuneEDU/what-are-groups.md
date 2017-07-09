---
title: "组有哪些？"
titleSuffix: Intune for Education
description: "了解如何管理使用 Intune 教育版的设备组。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 925fee7b2807a340d2b4d0e1e9aa4ca069875f84
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017


---

# <a name="what-are-groups"></a>组有哪些？

你使用_组_来管理用户、 应用和教育版在 Intune 中的设备。 可以对用户或设备在一起而无需单独管理每个设备进行分组。 这样可以轻松地将应用和设置分配给大量的用户和设备。

在创建组时，请考虑将如何应用设置和应用到用户和设备。 例如，你可能需要阻止应用使用位置服务的所有设备。 这的替代方法是如何特定组可能需要某些操作，如提供学生采用[AP 计算机科学](https://www.tealsk12.org)应用以编辑其代码。

设置应用于组中。 由于组都设置为层次结构，与上面另一个字符串，一个组[的及其所有子组将继承任何设置应用于组](settings-inheritance.md)。 这使得更轻松地将设置应用到大的用户、 应用和设备组。

教育版的 Intune 将自动创建__所有设备__和__所有用户__创建你的租户时进行分组。 这些默认组表示更广泛类别的用户和设备中你的学校或学区和[无法移动](what-are-groups.md#why-cant-i-move-certain-groups)。


## <a name="managing-groups-and-subgroups"></a>管理组和子组

你可以通过导航到创建组**组**，然后选择**创建组**顶部的组列表。 你可以通过创建进一步组织组*子组*下任何组中，除__所有设备__或__所有用户__。

  ![创建子组页面上的子组创建的两个位置，-顶部的组名称和侧栏-以红色圆圈](./media/groups-007-create-subgroup.png)

1. 在[教育控制台 Intune](https://intuneeducation.portal.azure.com)，选择**管理用户和设备组**。
2. 选择其下面你想要创建子组的组。
3. 单击**创建子组**，然后输入**组名称**。

## <a name="making-changes-to-groups"></a>对组进行更改

已创建了组之后，就可能需要编辑其成员身份-例如，如果设备需要转给于您所在地区的另一个学校。

  ![编辑组中的设备](./media/groups-008-edit-group-membership.png)

1. 选择你想要编辑其成员的组。
2. 选择**设备**选项卡。
3. 选择**编辑设备**按钮，然后选择**添加设备**以从列表中添加多个设备或**X**旁边设备，以删除它。

如果你需要重命名组，选择的组，则需要重命名，则**重命名**按钮可编辑名称。

## <a name="move-a-group"></a>将组移动

你可以在你的组结构内, 移动组或**层次结构**。

  ![将移动以红色圆圈的分组按钮](./media/groups-010-move-groups.png)

1.  在[教育门户 Intune](https://intuneeducation.portal.azure.com)，选择**管理组**。
2. 选择需要移动的组。
3.  单击**移动组**菜单列表中或通过选择**移动组**按钮。
4.  选择你想要通过搜索组名称或通过选择层次结构中移动组的组位置。
5.  选择**确定**以保存所做的更改。

## <a name="why-cant-i-move-certain-groups"></a>为什么无法移动特定组？

教育版的 Intune 提供了一套不能移动、 的默认组**所有用户**和**所有设备**，当你[创建租户](what-are-tenants.md)。 **所有教师**和**所有学生**是之后学校数据同步具有 student 与老师数据导入 Intune 教育版创建的默认组。

极少数情况下，这可能导致其中你可以结束与两个组下子组的问题。

  ![将显示在多个组的错误消息的子组](./media/groups-012-subgroup-is-under-two-groups-warning.png)

如果发生这种情况，你将需要选择一个组将上面此子组。

## <a name="delete-a-group"></a>删除组

当您删除组时，教育版的 Intune 中删除是该组的成员的任何设备上应用和设置的集合。 删除组不会删除这些用户或设备从管理。

  ![删除组以红色圆圈的按钮](./media/groups-011-delete-groups.png)

1.  在[教育门户 Intune](https://intuneeducation.portal.azure.com)，选择**管理组**。
2. 选择你想要删除的组
3.  单击**删除组**在任务列表。

## <a name="find-out-more"></a>查看详细信息

- [了解有关管理体验在 Intune 中的完整组的详细信息](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

