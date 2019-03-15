---
title: さらに分析するために Azure Data Lake v2 にデータをエクスポートする
description: ユーザーは、Dynamics 365 Customer Service Insights から独自の Azure Data Lake v2 ストレージにデータをエクスポートして、詳細に分析したり、他のデータと相関させたりできます。
author: gxy001
ms.date: 02/21/2019
ms.topic: article
ms.service: business-applications
ms.author: xiaoying
ms.reviewer: v-stsau
ms.openlocfilehash: 15536eeec5bd1e5800cc3e176748ebb1b01745d5
ms.sourcegitcommit: a48a8ad8fbddb30b1d4f738911ddafffb9fb6ba1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/20/2019
ms.locfileid: "404942"
---
# <a name="export-data-to-azure-data-lake-v2-for-further-analysis"></a><span data-ttu-id="24f57-103">さらに分析するために Azure Data Lake v2 にデータをエクスポートする</span><span class="sxs-lookup"><span data-stu-id="24f57-103">Export data to Azure Data Lake v2 for further analysis</span></span>
[!include[customer-service banner](../../../includes/customer-service.md)]


<span data-ttu-id="24f57-104">Dynamics 365 Customer Service Insights が標準で提供している機能に加えて、さらに詳細な分析や他のデータとの相関が必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="24f57-104">In addition to what Dynamics 365 Customer Service Insights provides out of the box, you may require further analysis or correlating with other data.</span></span> <span data-ttu-id="24f57-105">2019 年 4 月リリースでは、Dynamics 365 Customer Service Insights からユーザー独自の Azure Data Lake v2 ストレージにデータをエクスポートすることができます。</span><span class="sxs-lookup"><span data-stu-id="24f57-105">With the April '19 release, you can export data from Dynamics 365 Customer Service Insights to your own Azure Data Lake v2 storage.</span></span> <span data-ttu-id="24f57-106">エクスポートされたデータは Common Data Model に基づいており、一貫性のあるスキーマを提供し、AI 生成トピックとビジネス インテリジェンス (BI) 集約データの両方を含みます。</span><span class="sxs-lookup"><span data-stu-id="24f57-106">The exported data is based on the Common Data Model, which provides a consistent schema and contains both AI-generated topics and business intelligence (BI) aggregated data.</span></span>
