---
title: "Azure ワークロード監視用の新しいメトリック"
description: "Power BI Embedded のリソース消費を監視し、構成可能なしきい値を超えたときにアクションをトリガーするために、4 つの新しいメトリックが追加されました。"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 082d21ac-805e-4007-8810-f1838369569c
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: 2aa697aa3c550a3dab9d23dec13b1746f583f3a7
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---
#  <a name="new-metrics-for-azure-workload-monitoring"></a><span data-ttu-id="48eaf-103">Azure ワークロード監視用の新しいメトリック</span><span class="sxs-lookup"><span data-stu-id="48eaf-103">New metrics for Azure workload monitoring</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="48eaf-104">Power BI のページ付けされたレポートとデータ フローで新しいワークロードを使用できるようになったため、Power BI Embedded のリソースとワークロードの消費を監視して、構成可能なしきい値を超えたときにアクションをトリガーする、3 つの新しいメトリックが追加されます。</span><span class="sxs-lookup"><span data-stu-id="48eaf-104">As new workloads now available in Power BI- Paginated reports and Data flows, three new metrics will be added to monitor Power BI Embedded resource and workload consumption and trigger actions when configurable thresholds are exceeded.</span></span> <span data-ttu-id="48eaf-105">新しいメトリックは、リソースでの各ワークロードを反映します。</span><span class="sxs-lookup"><span data-stu-id="48eaf-105">The new metrics will reflect each of the workloads in the resource.</span></span> <span data-ttu-id="48eaf-106">新しいメトリックは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="48eaf-106">The new metrics are:</span></span>

<span data-ttu-id="48eaf-107">•   CPU 消費量 •   メモリ消費量 •   メモリ コミット消費量 (メモリのページングを含む)</span><span class="sxs-lookup"><span data-stu-id="48eaf-107">•   CPU Consumption •   Memory Consumption •   Memory Commit Consumption (Incl. memory paging)</span></span>

<span data-ttu-id="48eaf-108">開発者は、Azure を使用してしきい値を定義し、アラートを使用して特定のアクションをトリガーできます (たとえば、特定のモニターが定義済みしきい値を超えたらリソースを自動スケールアップするなど)。</span><span class="sxs-lookup"><span data-stu-id="48eaf-108">Developers can use Azure to define thresholds to trigger specific actions using alerts, such as automatic scale-up of the resource whenever a specific monitor crosses a defined threshold.</span></span>

