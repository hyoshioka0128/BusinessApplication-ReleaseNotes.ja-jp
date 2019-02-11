---
title: 拡張可能なキャンペーンとセグメント (Dynamics 365 for Marketing)
description: API を使用して外部サービスや Flow などの Microsoft のツールと Dynamics 365 for Marketing を統合する
author: jain-shailesh
ms.author: shjain
ms.reviewer: kamaybac
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: 6e416471c271218f8d0eb559ed85221c9cb15c9a
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210443"
---
# <a name="extensibility-for-campaigns-and-segments"></a><span data-ttu-id="85fd5-103">キャンペーンとセグメントの拡張性</span><span class="sxs-lookup"><span data-stu-id="85fd5-103">Extensibility for campaigns and segments</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]


<span data-ttu-id="85fd5-104">このリリースでは、顧客体験行やセグメントに対して豊富な API セットが提供されています。</span><span class="sxs-lookup"><span data-stu-id="85fd5-104">This release provides a rich set of APIs for customer journeys and segments.</span></span> <span data-ttu-id="85fd5-105">これらの API では、外部サービス統合のための重要な統合ポイントが提供されており、Flow などの Microsoft ツールと簡単に接続できます。</span><span class="sxs-lookup"><span data-stu-id="85fd5-105">These APIs provide key integration points for external services integration and can easily connect with Microsoft tools like Flow.</span></span>

<span data-ttu-id="85fd5-106">たとえば、顧客体験をプログラムで構築し、必要に応じてそのプロパティを変更したり、既存のセグメントに基づいて新しいセグメントを構築したりできます。</span><span class="sxs-lookup"><span data-stu-id="85fd5-106">For example, you can build a customer journey programmatically and modify its properties as needed—or build a new segment based on any existing segment.</span></span> <span data-ttu-id="85fd5-107">また、体験の開始、停止、編集など、エンティティのライフサイクルを制御することもできます。</span><span class="sxs-lookup"><span data-stu-id="85fd5-107">You can also control entity lifecycles, such as starting, stopping, or editing a journey.</span></span>

<span data-ttu-id="85fd5-108">お客様とパートナーは、これらの機能を使用して Marketing アプリを拡張し、セルフサービスや軽量の使用シナリオ (反復プロセスの自動化など) に対応したり、複雑なシナリオ (外部システムからのトリガーなど) を実現したりできます。</span><span class="sxs-lookup"><span data-stu-id="85fd5-108">Customers and partners can use these abilities to extend the marketing app, address self-service and lightweight usage scenarios (such as automating repetitive processes), and enable complex scenarios (such as triggering from external systems).</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="85fd5-109">![Marketing の開発者ガイド](media/extensibility-campaigns-segments-1.png "Marketing の開発者ガイド")
<!-- Picture 1 --></span><span class="sxs-lookup"><span data-stu-id="85fd5-109">![Developer Guide for Marketing](media/extensibility-campaigns-segments-1.png "Developer Guide for Marketing")
<!-- Picture 1 --></span></span>
