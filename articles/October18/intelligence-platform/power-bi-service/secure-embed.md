---
title: 埋め込みコードのセキュリティ保護
description: 内部ポータルに安全に埋め込みます。
author: AdamDWilson
manager: AnnBe
ms.date: 10/23/2018
ms.assetid: 1508b82e-6be4-47f9-a827-3659f79aa7a1
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: adamw
audience: Admin
ms.openlocfilehash: 4a8d32cf5a54e3b9f7adb1b5414d59b4a1701cd1
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199377"
---
# <a name="secure-embed-codes"></a><span data-ttu-id="0cbbe-103">埋め込みコードのセキュリティ保護</span><span class="sxs-lookup"><span data-stu-id="0cbbe-103">Secure embed codes</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="0cbbe-104">Power BI サービスのレポートの [ファイル] メニューで使用できる新しい [埋め込み] オプションがリリースされます。これにより、ユーザーは、クラウド ベースでも SharePoint 2019 のようにオンプレミスでホストされていても、内部の Web ポータルにレポートを簡単かつ安全に埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="0cbbe-104">We will release a new Embed option available on the File menu for reports in the Power BI service, enabling users to easily and securely  embed reports in internal web portals, whether cloud-based or hosted on-premises, such as SharePoint 2019.</span></span> <span data-ttu-id="0cbbe-105">この方法で埋め込まれたレポートでは、行レベルのセキュリティ (RLS) によるすべての項目のアクセス許可とデータ セキュリティが適用されます。</span><span class="sxs-lookup"><span data-stu-id="0cbbe-105">Reports embedded in this way respect all item permissions and data security through row-level security (RLS).</span></span> <span data-ttu-id="0cbbe-106">この機能は、埋め込みの手段として URL または IFrame を受け入れるポータルにコードを使用しないで埋め込めるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="0cbbe-106">The feature is designed to allow no-code embedding into any portal that accepts a URL or IFrame as a means of embedding.</span></span>

<span data-ttu-id="0cbbe-107">新しい [埋め込み] オプションを使用してレポートを表示するには、レポートを使用するユーザーが Pro ライセンスを持っているか、またはレポートが EM や P などの Premium 容量のワークスペースに存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0cbbe-107">To view a report using the new Embed option, the user consuming the report must have a Pro license or the report must be in a workspace that is in a Premium capacity, such as EM or P.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="0cbbe-108">![安全な埋め込みの例](media/secure-embed.png "安全な埋め込みの例")</span><span class="sxs-lookup"><span data-stu-id="0cbbe-108">![Secure embed example](media/secure-embed.png "Secure embed example")</span></span>
