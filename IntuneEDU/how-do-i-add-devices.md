---
title: "添加设备"
titleSuffix: Intune for Education
description: "了解如何为教育版的 Intune 设置 Windows 10 设备。"
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7b5343d996868ceaf18a58812a4db14d626d2969
ms.contentlocale: zh-cn
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-devices-to-intune-for-education"></a>如何将设备添加到 Intune 教育版？

已使用你的信息来设置 Intune 教育版后 — 例如学生记录、 应用和设备的设置-你需要将设备连接到 Intune 教育版。 你可以执行此新的 Windows 10 设备的安装程序体验的一部分。


> [!NOTE]
> 你的设备需要访问 Internet，并且你的帐户必须具有足够 Intune 教育版设备许可证可用于完成安装程序。 你可以了解详细信息中我们[许可证文档](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)。

## <a name="add-devices-to-intune-for-education"></a>将设备添加到 Intune 教育版

你将需要将执行以下操作来将 Windows 10 设备纳入管理由 Intune 教育版：

1. 在新的 Windows 10 设备上打开并开始标准的 Windows 安装程序。 在访问**谁拥有此电脑？**屏幕上，选择**我的工作或学校拥有它**。

  !["谁拥有此电脑？"的屏幕截图 在 Windows 安装程序的屏幕](./media/devices-001-who-owns-this-pc.png)

2. 上**选择如何将连接**屏幕上，选择**加入 Azure AD**。

  ![Windows 安装程序在"选择如何连接"屏幕的屏幕快照](./media/devices-002-how-you-connect-pc.png)

3. 输入教育版管理的 Intune 帐户详细信息或**其他有权限注册用户**和选择**下一步**。

你的设备将[使用 Azure AD 进行身份验证](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access)以及在将安装程序完成后接收分配的应用和设置。

若要注册设备的另一种方法是通过[免费__设置学校电脑__应用](how-should-i-enroll-devices.md)地快速设置使用 USB 密钥的电脑。 

## <a name="find-out-more"></a>查看详细信息
- [查找更多有关**设置学校电脑**应用](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)
- [了解有关将设备添加到 Intune 的完整体验的详细信息](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)

