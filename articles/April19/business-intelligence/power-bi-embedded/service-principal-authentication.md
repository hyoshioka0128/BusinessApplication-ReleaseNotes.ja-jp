---
title: サービス プリンシパル認証
description: Power BI Embedded を使用してアプリケーションの展開、セキュリティ、およびアプリケーション ライフサイクル管理を強化するために、サービス プリンシパルのサポートが計画されました
author: NimrodShalit
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: nishalit
ms.openlocfilehash: f5f07ed16e45015328a9a026d2abb0de5e717436
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210593"
---
# <a name="service-principal-authentication"></a><span data-ttu-id="bcc5e-103">サービス プリンシパル認証</span><span class="sxs-lookup"><span data-stu-id="bcc5e-103">Service principal authentication</span></span> 
[!include[business-intelligence banner](../../includes/business-intelligence.md)]



<span data-ttu-id="bcc5e-104">Power BI Embedded を使用してアプリケーションの展開、セキュリティ、およびアプリケーション ライフサイクル管理を強化するために、サービス プリンシパルのサポートが計画されました。</span><span class="sxs-lookup"><span data-stu-id="bcc5e-104">To enhance deployment, security, and application lifecycle management of applications using Power BI Embedded, support for service principal is planned.</span></span> <span data-ttu-id="bcc5e-105">この推奨の認証アプローチを使用すると、アプリケーションはユーザー コンテキストを必要とせずに認証を行い、Power BI API を使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="bcc5e-105">This recommended authentication approach allows applications to authenticate without a user context and use Power BI APIs.</span></span> <span data-ttu-id="bcc5e-106">Power BI API でサービス プリンシパルを使用するには、Azure Active Directory Web アプリケーションで Power BI 管理者による認証を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="bcc5e-106">To use service principal in Power BI API, an Azure Active Directory web application needs authorization by a Power BI admin.</span></span>
