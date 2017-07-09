---
title: "添加应用"
titleSuffix: Intune for Education
description: "了解如何将应用添加到 Intune 教育版。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7a2298d4a1b55d8a1355ca9e828d92c0a561eac8
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-apps-to-intune-for-education"></a>如何将应用添加到 Intune 教育版？

你可以在你的学校设备使用 Intune 教育版上安装应用之前，这些应用程序必须添加到你的 Intune 教育帐户中。

教育版的 Intune 支持的以下类型的应用：
- Web 应用程序，如[联机 Microsoft Word](https://office.live.com/start/Word.aspx)
- 对于教育应用程序，任何 Microsoft 存储[分发通过应用商店的通用应用](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- 桌面应用，如[独立 Microsoft Office](https://products.office.com/products)

添加应用后，你可以[安装的应用](install-apps.md)上的设备的组。

设置适用于组，其中包括的应用的组。 由于组都设置为层次结构，与上面另一个字符串，一个组[由及其所有子组继承分配给组的任何应用](settings-inheritance.md)。

## <a name="add-web-apps"></a>添加 web 应用

A _web 应用_是由用户以独占方式在浏览器访问的应用。 它们可轻松地分配，因为所有你必须将发送到用户都是链接到网站，而不将任何安装文件发送到其设备。

可以将 web 应用程序分配为针对教育使用 Intune 的 Windows 10 设备的开始菜单中的链接。 若要分配应用程序，你必须首先将其添加到 Intune 中的教育版**管理应用**部分。

  ![添加新的 web 应用程序页，该页将提示用户输入下面的过程中所述的信息。](./media/apps-001-add-webapp.png)

1. 在[教育版的 Intune](https://intuneeducation.portal.azure.com)控制台中，选择**应用**。

2. 下**Web 应用**，选择**+ 新的应用程序**，然后输入以下详细信息：
 * **URL** -你想要分配的应用的 URL
 * **应用程序名称**-在设备上的开始菜单中显示应用的名称
 * **图标**-上载 PNG 或 JPG 从您的计算机要用作应用程序图标

3. 选择“保存”。 你的 web 应用现在已准备。

4. 你现在可以[在设备上安装应用](install-apps.md)。

你可以随时编辑应用程序，通过选择**编辑**，可重新打开其详细信息页。

## <a name="add-desktop-apps"></a>添加桌面应用

你可以在安装桌面应用的整个相同的接口**应用**页。 此过程类似于安装的 web 应用，但涉及到 web 应用不需要的 install 文件。

![新的桌面应用程序屏幕。](./media/apps-003-add-desktop-app.png)

1. 在[教育版的 Intune](https://intuneeducation.portal.azure.com)控制台中，选择**应用**。

2. 下**桌面应用**，选择**+ 新的应用程序**。 这将打开**新桌面应用程序**屏幕，然后输入以下详细信息：
 * **应用程序文件**-上载应用程序的 MSI 安装程序
 * **应用程序名称**-应用程序以在设备上显示的名称
 * **说明**— 它是应用程序以帮助你快速识别哪些应用程序的说明
 * **发布服务器**-使用应用发布者，来帮助你快速识别谁开发应用程序的名称
 * **图标**-上载 PNG 或 JPG 从您的计算机要用作应用程序图标

3. 选择**保存并上载文件**。

  ![添加新桌面应用程序屏幕，有关示例应用，evernote 填写所有字段。](./media/apps-004-filled-out-desktop-app.png)

4. 然后，应用将上载到 Intune 教育版。 上载完成后，你可以[在设备上安装应用](install-apps.md)。

> [!NOTE]
> 有时你可能会遇到错误，指出"此应用程序没有安装文件"或"任何应用程序安装文件已添加"。 这意味着，该文件未正确上载。 尝试保存并上载文件后，再次以修复此错误。

## <a name="add-popular-apps"></a>添加常用应用程序

你可以从教育版的 Microsoft 存储还快速安装常用教育应用程序。 我们的目标是能够轻松地查找和安装你最喜欢的应用为你的用户。 我们建议这些应用，因为它们是经常用到教育工作者。 你可以找到这些应用，在 Express 配置中，或在**管理应用**磁贴。

  ![在添加应用程序过程中在 Express 配置选定的常用应用程序。](./media/apps-005-popular-apps.png)

教育门户 Intune 显示前十二个教育 web 应用和排名靠前的 12 个的教育 Microsoft 应用商店的教育应用程序尚未添加下**应用**管理。

> [!TIP]
> 如果你尚未设置你 Microsoft 应用商店教育帐户将应用添加到 Intune 教育版，则可以了解如何执行该操作[此处](acquire-store-apps.md)。

1. 在[教育版的 Intune](https://intuneeducation.portal.azure.com)控制台中，选择**管理应用** > **添加应用** > **快速添加常用应用程序**。 一份**Web 应用**和**Microsoft 应用商店应用**显示。

  ![快速添加常用应用程序屏幕。](./media/apps-006-add-popular-apps.png)

2. 选择你想要添加，然后选择的应用程序**添加应用**。

  ![选择多个常用的应用程序，将添加到门户。](./media/apps-007-select-multiple-popular-apps.png)

3. 你的应用程序将在后台中添加并显示在左侧边栏准备就绪时。

  ![你的应用程序正在添加屏幕。](./media/apps-008-your-popular-apps-are-being-added.png)

## <a name="find-out-more"></a>查看详细信息

- [了解有关管理使用 Intune 的应用的完整体验的详细信息](https://docs.microsoft.com/intune/deploy-use/add-apps)

