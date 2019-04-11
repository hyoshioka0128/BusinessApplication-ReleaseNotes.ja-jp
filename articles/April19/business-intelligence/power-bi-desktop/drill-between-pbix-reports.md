---
title: 別のレポートへのドリルスルー
description: レポート作成者は、Power BI サービスに発行されたレポート間のドリルスルー アクションを設定できるようになりました。
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: c4cc3b054fe9beb0d8bca5d8752915347ec42e65
ms.sourcegitcommit: e9ae36f4f7ff145fcdc3d3ebfb2080fc33083f69
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2019
ms.locfileid: "849604"
---
# <a name="drill-through-to-another-report"></a><span data-ttu-id="1cc83-103">別のレポートへのドリルスルー</span><span class="sxs-lookup"><span data-stu-id="1cc83-103">Drill through to another report</span></span>
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


<span data-ttu-id="1cc83-104">レポート作成者は、Power BI サービスに発行されたレポート間のドリルスルー アクションを設定できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1cc83-104">Report authors can now set up drillthrough actions across reports published to the Power BI service.</span></span> <span data-ttu-id="1cc83-105">作成者は追加情報や異なる詳細レベルが含まれる複数のレポートを作成し、コンテキストに応じてあるレポートから別のレポートに移動できるようにしたい場合があるため、この機能は重要です。</span><span class="sxs-lookup"><span data-stu-id="1cc83-105">This is important because sometimes an author will have multiple reports, with additional information or levels of detail, and would like to contextually transition from one report to another.</span></span> <span data-ttu-id="1cc83-106">エンド ユーザーのエクスペリエンスでは、レポート内のソース ビジュアルを選択し、別のレポートにドリルするだけで、ソース ビジュアルと同じコンテキストでフィルター処理されて簡単にコンテキスト ジャンプできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1cc83-106">The end users' experience allows easy contextual jumps by simply selecting a source visual in a report and drilling into another report that is now filtered to the same context as the source visual.</span></span> <span data-ttu-id="1cc83-107">レポートのスキーマが一致する場合、次のフィルター コンテキストが移動先のレポートに適用されます。</span><span class="sxs-lookup"><span data-stu-id="1cc83-107">Provided that the schema of the reports match, the following filter context will get applied to the destination report:</span></span>

-   <span data-ttu-id="1cc83-108">ソース ビジュアルに影響するレポート、ページ、およびビジュアル レベルのフィルター</span><span class="sxs-lookup"><span data-stu-id="1cc83-108">Report, page, and visual level filters affecting the source visual</span></span>

-   <span data-ttu-id="1cc83-109">ソース ビジュアルに影響を与えるクロス フィルタリングとクロス ハイライト</span><span class="sxs-lookup"><span data-stu-id="1cc83-109">Cross-filtering and cross-highlighting that impacts the source visual</span></span>

-   <span data-ttu-id="1cc83-110">ページ上のスライサーと同期スライサー</span><span class="sxs-lookup"><span data-stu-id="1cc83-110">Slicers on the page and sync-slicers</span></span>

-   <span data-ttu-id="1cc83-111">URL パラメーター</span><span class="sxs-lookup"><span data-stu-id="1cc83-111">URL parameters</span></span>

<span data-ttu-id="1cc83-112">この機能は、次の Power BI アイデア要求に応えたものです:</span><span class="sxs-lookup"><span data-stu-id="1cc83-112">This feature addresses the following Power BI Ideas requests</span></span>

-   [<span data-ttu-id="1cc83-113">レポートにドリルする</span><span class="sxs-lookup"><span data-stu-id="1cc83-113">Drill to a report</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/13715889-drill-to-a-report-page)

-   [<span data-ttu-id="1cc83-114">レポートのドリルスルー機能</span><span class="sxs-lookup"><span data-stu-id="1cc83-114">Drillthrough functionality for reports</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/20533858-drill-through-functionality-in-power-bi-reports)

-   [<span data-ttu-id="1cc83-115">クロス レポートのドリル</span><span class="sxs-lookup"><span data-stu-id="1cc83-115">Cross-report drill</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/33751942-drill-through-between-different-reports)

[!include[feedback](../includes/desktop-feedback.md)]