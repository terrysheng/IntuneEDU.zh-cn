---
title: "Express 配置是什么？"
titleSuffix: Intune for Education
description: "使用 Express 配置来快速设置你教育版的 Intune 中的组。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 796782e6c0cf9fa975bd9c8f3a94314bb00d8d89
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017


---

# <a name="what-is-express-configuration"></a>Express 配置是什么？

明确配置是当你首次登录到 Intune 教育版，你看到的磁贴之一。

  ![Express 配置磁贴，显示启动 Express 配置-单击此处以选择应用程序和组的设置。](./media/express-config-001-launch-tile.png)

快速配置可帮助您快速为用户和设备提供使用应用程序和所需的设置。 它不一定要限制为仅使用一次;每当你想要对你管理任何组进行更改，你可以使用它。 我们选择某些应用程序和默认设置，我们认为你将找到有用。 你可以更改这些选择，以满足你的需求。

## <a name="choose-a-group"></a>选择一个组

首先，将通过选择要配置的组。

  ![选择组屏幕，要求用户以选择一个组。](./media/express-config-004-choose-group.png)

A_组_在 Intune 中的教育是设备或用户的组织，可方便地了解谁或你配置在控制台中的集合。 这可能是设备 (如_第六个年级计算机车_) 或用户 (如_第四个年级学生_或_生物学教师_)。 教育版的 Intune 基于您提供的学校信息的组的附带预设。 我们提供了有关中可用的组的详细信息我们[组文章](what-are-groups.md)。

我们建议你先将分配设置，你知道**所有用户**都需要如密码要求，或阻止 Microsoft Edge 中的弹出窗口。

选择要设置，然后选择的组**下一步**以继续。

## <a name="choose-apps"></a>选择应用

现在，你将选择应用程序，以便将分配给该组。

  ![应用程序分配屏幕。 分配的情况下按不同的类型，对于教育应用程序包括 web 应用程序和 Microsoft 应用商店进行组织应用。](./media/express-config-005-choose-apps.png)

有几种类型的应用程序可以在设备上安装的：

* [Web 应用](how-to-add-apps.md#add-web-apps)
* [桌面应用程序](how-to-add-apps.md#add-desktop-apps)
* [教育应用程序的 Microsoft 存储](acquire-store-apps.md)

教育版的 Intune 还显示[常用应用程序从教育版的 Microsoft 应用商店](how-to-add-apps.md#add-popular-apps)从跨所有 Intune 教育版用户。

选择应用程序，以便将分配给该组，然后选择**下一步**以继续。

## <a name="choose-settings"></a>选择设置

接下来，你将选择你想要应用到的设备或用户组中的设置。

  ![选择设置屏幕中。 设置已组织成的折叠列表，包括部门等设备共享、 基本设备设置、 应用程序设置、 浏览器设置的详细信息。](./media/express-config-006-choose-settings.png)

明确配置显示了你可能想要获取你准备就绪的组的设置。 我们选择这些设置，以使你快速开始使用其设备的用户更轻松。 你无需进行任何修改，如果你想要使用我们建议，或者你可以自定义这些设置以满足特定需求。

你可以随时以适合你需要进行，任何更改更改选择 Express 配置和自定义你甚至可更进一步使用完整的设置[的可用设置列表作为 Intune 教育版的一部分](available-settings.md)。

## <a name="finish-up"></a>完成

进行选择后，你有机会查看应用和你选择的设置。 然后，您可以选择**完成**按钮或返回到任何步骤以修改这些设置。

  ![查看你选择的屏幕。 它显示了应用程序和 Express 配置过程中选择的设置。](./media/express-config-007-save-changes.png)

选择后**完成**，你可以**配置多个组**也是**全部完成**。

  ![在完成屏幕中。 它显示配置多个组和已完成的选项。 所有完成的选项提供过程，包括添加到 Intune 教育版的设备，通过将它们联接到 Azure Active Directory 中的下一步的简短的说明。](./media/express-config-008-all-done.png)

完成后，你将进入教育仪表板的 Intune 可以继续管理你的设备、 用户和应用程序。 你可以回到 Express 配置随时从仪表板或导航菜单添加、 删除或修改应用程序和任何组的设置。

## <a name="next-steps"></a>后续步骤

已设置了你的应用和设置所需的组后，你便准备好开始针对教育通过 Intune 使用的设备。

## <a name="find-out-more"></a>查看详细信息
- [了解有关 Intune 中的完整的管理体验中可用的设置的详细信息](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)

