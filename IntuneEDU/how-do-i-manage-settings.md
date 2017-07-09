---
title: "如何管理设置？"
titleSuffix: Intune for Education
description: "请按照以下步骤来管理通过 Intune 对教育策略的设置。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope:
- IntuneEDU
.md#ms.tgt_pltfrm: 
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: a8a9619476315459d49dc128e14c3bc0f2f7794e
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017



---

# <a name="how-do-i-manage-settings"></a>如何管理设置？

你可以管理大量的用户、 应用和使用 Intune 的设备的设置。 它是如何将更改如何设备可以响应用户操作。

设置应用到一组设备时，它们访问该组中的设备时，会受到影响的用户。 如果设置应用于一组用户，

设备设置适用于他们的组中的所有设备。 设置**未配置**允许用户在其设备本身上定义其设置。

## <a name="manage-settings-for-groups"></a>管理组的设置

使用以下步骤来管理教育版的 Intune 中的设置的完整列表：
1. 在[教育版的 Intune](https://intuneeducation.portal.azure.com)控制台中的，在左侧导航菜单中，选择**组**。
2. 选择你想要管理其设置的组。 完整列表，请参阅[可用设置](what-are-settings.md)。
3. 单击**设置**页后，可以查看可用设置的完整列表顶部。
4. 展开类别，并修改所选组的单个设置。
5. 单击**保存**保存该组的更改。 设置自动发送到该组中的设备中。

## <a name="manage-settings-with-express-configuration"></a>管理使用 Express 的配置设置

快速配置轻松让你可以快速启动，但还可以帮助您对你的设备进行快速更改。

  ![快速配置设置修补程序](./media/express-config-006-choose-settings.png)

1. 在[教育版的 Intune](https://intuneeducation.portal.azure.com)控制台中，选择**启动 Express 配置**。 查看**欢迎**页上，选择**开始**。
2. 查看**获取学校信息**页。 如果你已添加学校信息，请选择**下一步**。
3. 选择你想要管理，然后选择其设置的组**下一步**。
4. 检查应用的列表，然后选择**下一步**。
5. 上**设置**页上，展开可用设置的类别：
  * [基本设备设置](available-settings.md#basic-device-settings)
  * [Microsoft Edge 设置](available-settings.md#microsoft-edge-settings)
  * [设备更新设置](available-settings.md#device-update-settings)
  * [无线设置](available-settings.md#wireless-settings)
  * [应用程序设置](available-settings.md#app-settings)
  * [登录设置](available-settings.md#sign-in-settings)

  展开某个类别并切换以修改设置，然后选择该控件**下一步**。

6. 检查你的选择，然后选择**完成**若要保存所做的更改它们在更新所选组中的设备。

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>永远都不可以会不协同工作的设置

它有可能不兼容的设置要应用于同一个组。 这些不一致时导致错误，用户或设备为其设置具有不同设置在多个位置。 用户或设备处于多个组的成员的结果发生这种情况。

例如，Esperanza 为属于*第六个年级*组和也是名为组成员*地球科学*。 如果你配置主页设置，并将分配给*第六个年级*，和你配置一个不同的主页设置，并将其分配给*地球科学*，她现在具有两个冲突的主页设置分配给其用户。 那样会导致不一致的设置分配，从而导致错误。 你可以发现哪些设备和用户具有设置错误使用[设置错误报表](what-are-reports.md)。

## <a name="find-out-more"></a>查看详细信息

- [了解有关 Intune 中的完整的策略管理体验的详细信息](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)

