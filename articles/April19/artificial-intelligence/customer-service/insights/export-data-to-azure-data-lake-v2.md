---
title: さらに分析するために Azure Data Lake v2 にデータをエクスポートする
description: ユーザーは、AI for Customer Service Insights から独自の Azure Data Lake v2 ストレージにデータをエクスポートして、詳細に分析したり、他のデータと相関させたりできます。
author: gxy001
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: xiaoying
ms.reviewer: v-stsau
ms.openlocfilehash: eb4d6b07d21c37a95f506c764a7719703ce970a7
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "211097"
---
# <a name="export-data-to-azure-data-lake-v2-for-further-analysis"></a><span data-ttu-id="7e46e-103">さらに分析するために Azure Data Lake v2 にデータをエクスポートする</span><span class="sxs-lookup"><span data-stu-id="7e46e-103">Export data to Azure Data Lake v2 for further analysis</span></span>
[!include[customer-service banner](../../../includes/customer-service.md)]


<span data-ttu-id="7e46e-104">AI for Customer Service Insights が標準で提供している機能に加えて、さらに詳細な分析や他のデータとの相関が必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="7e46e-104">In addition to what AI for Customer Service Insights provides out of the box, you may require further analysis or correlating with other data.</span></span> <span data-ttu-id="7e46e-105">2019 年 4 月リリースでは、AI for Customer Service Insights からユーザー独自の Azure Data Lake v2 ストレージにデータをエクスポートすることができます。</span><span class="sxs-lookup"><span data-stu-id="7e46e-105">With the April '19 release, you can export data from AI for Customer Service Insights to your own Azure Data Lake v2 storage.</span></span> <span data-ttu-id="7e46e-106">エクスポートされたデータは Common Data Model に基づいており、一貫性のあるスキーマを提供し、AI 生成トピックとビジネス インテリジェンス (BI) 集約データの両方を含みます。</span><span class="sxs-lookup"><span data-stu-id="7e46e-106">The exported data is based on the Common Data Model, which provides a consistent schema and contains both AI-generated topics and business intelligence (BI) aggregated data.</span></span>