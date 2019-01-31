---
title: 計算されたエンティティ
description: 計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。
author: adiregev
manager: AnnBe
ms.date: 11/07/2018
ms.assetid: ''
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: adiregev
audience: ''
ms.openlocfilehash: 1cdde742870006f7f55e9656668ed46d903a4779
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200122"
---
# <a name="computed-entities-public-preview"></a><span data-ttu-id="81972-103">計算されたエンティティ (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="81972-103">Computed entities (Public Preview)</span></span>  

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="81972-104">データフロー エンティティは、Azure Data Lake Storage Gen2 内の Common Data Model に準拠したフォルダー (CDM フォルダー) に格納されます。</span><span class="sxs-lookup"><span data-stu-id="81972-104">Dataflow entities are stored in Common Data Model-compliant folders (CDM folders) in Azure Data Lake Storage Gen2.</span></span> <span data-ttu-id="81972-105">エンティティが CDM フォルダーに読み込まれた後、エンティティを変換、変更、補強し、大規模なデータを集約することで、新しい分析情報を生成できます。</span><span class="sxs-lookup"><span data-stu-id="81972-105">After your entities have been loaded to CDM folders, you can generate new insights by transforming, modifying, and enriching entities, and aggregating large-scale data.</span></span> <span data-ttu-id="81972-106">これらの新しく作成されたエンティティは、CDM フォルダーにも格納されます。</span><span class="sxs-lookup"><span data-stu-id="81972-106">These newly created entities are also stored in CDM folders.</span></span> <span data-ttu-id="81972-107">Power Query の M 式のスタティック分析により、エンティティ間の依存関係が自動的に識別され、常に最適な順序でエンティティが更新されるので、手動オーケストレーションの必要はありません。</span><span class="sxs-lookup"><span data-stu-id="81972-107">Static analysis of Power Query M expressions makes it possible to identify dependencies between entities automatically, so they’ll always be updated in the optimal order, with no need for manual orchestration.</span></span> 

<span data-ttu-id="81972-108">計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。</span><span class="sxs-lookup"><span data-stu-id="81972-108">Support for computed entities allows third parties to build Power BI apps leveraging dataflows with richer insights and AI capabilities.</span></span> <span data-ttu-id="81972-109">たとえば、Dynamics 365 for Sales の顧客アカウント エンティティを、サービスに対する Dynamics 365 のオープン サービス チケットからの情報、および Office 365 の関連する顧客会議情報で補強できます 。</span><span class="sxs-lookup"><span data-stu-id="81972-109">For example, you could enrich a customer account entity from Dynamics 365 for Sales with information from open service tickets in Dynamics 365 for Service, and relevant customer meeting information from Office 365.</span></span>
<span data-ttu-id="81972-110">計算されたエンティティを最新の情報に更新するには、Power BI Premium が必要です。</span><span class="sxs-lookup"><span data-stu-id="81972-110">Refreshing computed entities requires Power BI Premium.</span></span> 


## <a name="resources"></a><span data-ttu-id="81972-111">リソース</span><span class="sxs-lookup"><span data-stu-id="81972-111">Resources</span></span>
[<span data-ttu-id="81972-112">Power BI Premium での計算されたエンティティの使用</span><span class="sxs-lookup"><span data-stu-id="81972-112">Using computed entities on Power BI Premium</span></span>](https://docs.microsoft.com/en-us/power-bi/service-dataflows-computed-entities-premium)
