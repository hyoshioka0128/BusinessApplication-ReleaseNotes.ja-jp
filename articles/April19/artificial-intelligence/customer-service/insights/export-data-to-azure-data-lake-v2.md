---
title: さらに分析するために Azure Data Lake v2 にデータをエクスポートする
description: ユーザーは、Dynamics 365 Customer Service Insights から独自の Azure Data Lake v2 ストレージにデータをエクスポートして、詳細に分析したり、他のデータと相関させたりできます。
author: gxy001
ms.date: 03/22/2019
ms.topic: article
ms.service: business-applications
ms.author: xiaoying
ms.reviewer: v-stsau
ms.openlocfilehash: 965ee1aa3db1cfa96b7699c4e6bcb66ad6f10f5a
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224974"
---
# <a name="export-data-to-azure-data-lake-v2-for-further-analysis"></a>さらに分析するために Azure Data Lake v2 にデータをエクスポートする
[!include[customer-service banner](../../../includes/dynamics365-ai-customer-service.md)]


Dynamics 365 Customer Service Insights が標準で提供している機能に加えて、さらに詳細な分析や他のデータとの相関が必要になる場合があります。 このリリースでは、Dynamics 365 Customer Service Insights からユーザー独自の Azure Data Lake v2 ストレージにデータをエクスポートすることができます。 エクスポートされたデータは Common Data Model に基づいており、一貫性のあるスキーマを提供し、AI 生成トピックとビジネス インテリジェンス (BI) 集約データの両方を含みます。
