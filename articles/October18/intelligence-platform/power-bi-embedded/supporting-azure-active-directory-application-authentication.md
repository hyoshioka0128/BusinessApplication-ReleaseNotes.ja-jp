---
title: "Azure Active Directory アプリケーション認証のサポート"
description: "Azure Active Directory アプリケーション認証のサポート"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 4346342cb55725fb42d473f1f89085c5d48658bc
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---
# <a name="azure-active-directory-application-authentication-public-preview"></a><span data-ttu-id="28117-103">Azure Active Directory アプリケーション認証 (パブリック プレビュー) </span><span class="sxs-lookup"><span data-stu-id="28117-103">Azure Active Directory application authentication (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




<span data-ttu-id="28117-104">Power BI Embedded にアプリケーション認証が追加されます。</span><span class="sxs-lookup"><span data-stu-id="28117-104">We are adding application authentication to Power BI Embedded.</span></span> <span data-ttu-id="28117-105">これにより、Power BI Embedded アプリケーションの展開、セキュリティ、およびアプリケーション ライフサイクル管理が強化されます。</span><span class="sxs-lookup"><span data-stu-id="28117-105">This will enhance the deployment, security, and application lifecycle management Power BI Embedded applications.</span></span> <span data-ttu-id="28117-106">現在、Power BI Embedded アプリケーションを作成するには、マスター ユーザー アカウントを作成し、そのアカウントの資格情報を保存した後、それらをアプリケーション コード内で使用して、Power BI への非対話型サインインを実行できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="28117-106">Currently, building a Power BI Embedded application requires the creation of a master user account, storing the credentials for that account, and then using them in the application code for performing non-interactive sign-in to Power BI.</span></span> <span data-ttu-id="28117-107">Azure Active Directory では、ユーザー コンテキストを使用せず、アプリケーション自身の ID を使用するアプリケーション認証が特別にサポートされています。</span><span class="sxs-lookup"><span data-stu-id="28117-107">Azure Active Directory has special support for applications authenticating using their own identity without a user context.</span></span> <span data-ttu-id="28117-108">アプリケーションのみの認証に対応して設計されたこのサポートは、制御性とセキュリティに優れ、制限事項も少ないため、推奨のアプローチとなっています。</span><span class="sxs-lookup"><span data-stu-id="28117-108">This support, designed for app-only authentication, allows higher control and security, has fewer limitations, and is the recommended approach.</span></span> 

