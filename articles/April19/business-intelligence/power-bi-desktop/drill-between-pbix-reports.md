---
title: PBIX レポート間のドリル処理
description: レポート作成者は、Power BI サービスに発行されたレポート間のドリルスルー アクションを設定できるようになりました。
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: 7f9025a87e82791412b73fe8f715fc0e1431138c
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210770"
---
# <a name="drill-between-pbix-reports"></a><span data-ttu-id="2b756-103">PBIX レポート間のドリル処理</span><span class="sxs-lookup"><span data-stu-id="2b756-103">Drill between PBIX reports</span></span>
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


<span data-ttu-id="2b756-104">レポート作成者は、Power BI サービスに発行されたレポート間のドリルスルー アクションを設定できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2b756-104">Report authors can now set up drillthrough actions across reports published to the Power BI service.</span></span> <span data-ttu-id="2b756-105">作成者は追加情報や異なる詳細レベルが含まれる複数のレポートを作成し、コンテキストに応じてあるレポートから別のレポートに移動できるようにしたい場合があるため、この機能は重要です。</span><span class="sxs-lookup"><span data-stu-id="2b756-105">This is important because sometimes an author will have multiple reports, with additional information or levels of detail, and would like to contextually transition from one report to another.</span></span> <span data-ttu-id="2b756-106">エンド ユーザーのエクスペリエンスでは、レポート内のソース ビジュアルを選択し、別のレポートにドリルするだけで、ソース ビジュアルと同じコンテキストでフィルター処理されて簡単にコンテキスト ジャンプできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2b756-106">The end users' experience allows easy contextual jumps by simply selecting a source visual in a report and drilling into another report that is now filtered to the same context as the source visual.</span></span> <span data-ttu-id="2b756-107">レポートのスキーマが一致する場合、次のフィルター コンテキストが移動先のレポートに適用されます。</span><span class="sxs-lookup"><span data-stu-id="2b756-107">Provided that the schema of the reports match, the following filter context will get applied to the destination report:</span></span>

-   <span data-ttu-id="2b756-108">ソース ビジュアルに影響するレポート、ページ、およびビジュアル レベルのフィルター</span><span class="sxs-lookup"><span data-stu-id="2b756-108">Report, page, and visual level filters affecting the source visual</span></span>

-   <span data-ttu-id="2b756-109">ソース ビジュアルに影響を与えるクロス フィルタリングとクロス ハイライト</span><span class="sxs-lookup"><span data-stu-id="2b756-109">Cross-filtering and cross-highlighting that impacts the source visual</span></span>

-   <span data-ttu-id="2b756-110">ページ上のスライサーと同期スライサー</span><span class="sxs-lookup"><span data-stu-id="2b756-110">Slicers on the page and sync-slicers</span></span>

-   <span data-ttu-id="2b756-111">URL パラメーター</span><span class="sxs-lookup"><span data-stu-id="2b756-111">URL parameters</span></span>

<span data-ttu-id="2b756-112">この機能は、次の Power BI アイデア要求に応えたものです:</span><span class="sxs-lookup"><span data-stu-id="2b756-112">This feature addresses the following Power BI Ideas requests</span></span>

-   [<span data-ttu-id="2b756-113">レポートにドリルする</span><span class="sxs-lookup"><span data-stu-id="2b756-113">Drill to a report</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/13715889-drill-to-a-report-page)

-   [<span data-ttu-id="2b756-114">レポートのドリルスルー機能</span><span class="sxs-lookup"><span data-stu-id="2b756-114">Drillthrough functionality for reports</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/20533858-drill-through-functionality-in-power-bi-reports)

-   [<span data-ttu-id="2b756-115">クロス レポートのドリル</span><span class="sxs-lookup"><span data-stu-id="2b756-115">Cross-report drill</span></span>](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/33751942-drill-through-between-different-reports)
