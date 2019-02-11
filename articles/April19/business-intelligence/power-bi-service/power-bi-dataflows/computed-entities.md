---
title: 計算されたエンティティ
description: 計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます
author: adiregev
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: antonfrMSFT
ms.reviewer: mihart
ms.openlocfilehash: 180194f56086c3d1eab00f406686a99348b8fd8a
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210713"
---
# <a name="computed-entities"></a><span data-ttu-id="ed886-103">計算されたエンティティ</span><span class="sxs-lookup"><span data-stu-id="ed886-103">Computed entities</span></span>
[!include[business-intelligence banner](../../../includes/business-intelligence.md)]


<span data-ttu-id="ed886-104">データフロー エンティティは、Azure Data Lake Storage Gen2 内の Common Data Model に準拠したフォルダー (CDM フォルダー) に格納されます。</span><span class="sxs-lookup"><span data-stu-id="ed886-104">Dataflow entities are stored in Common Data Model-compliant folders (CDM folders) in Azure Data Lake Storage Gen2.</span></span> <span data-ttu-id="ed886-105">エンティティが CDM フォルダーに読み込まれた後、エンティティを変換、変更、補強し、大規模なデータを集約することで、新しい分析情報を生成できます。</span><span class="sxs-lookup"><span data-stu-id="ed886-105">After your entities have been loaded to CDM folders, you can generate new insights by transforming, modifying, and enriching entities, and aggregating large-scale data.</span></span> <span data-ttu-id="ed886-106">これらの新しく作成されたエンティティは、CDM フォルダーにも格納されます。</span><span class="sxs-lookup"><span data-stu-id="ed886-106">These newly created entities are also stored in CDM folders.</span></span> <span data-ttu-id="ed886-107">Power Query の M 式のスタティック分析により、エンティティ間の依存関係が自動的に識別され、常に最適な順序でエンティティが更新されるので、手動オーケストレーションの必要はありません。</span><span class="sxs-lookup"><span data-stu-id="ed886-107">Static analysis of Power Query M expressions makes it possible to identify dependencies between entities automatically, so they’ll always be updated in the optimal order, with no need for manual orchestration.</span></span> 

<span data-ttu-id="ed886-108">計算されたエンティティのサポートにより、サード パーティは豊富な分析情報と AI 機能を備えたデータフローを利用して Power BI アプリを開発することができます。</span><span class="sxs-lookup"><span data-stu-id="ed886-108">Support for computed entities allows third parties to build Power BI apps leveraging dataflows with richer insights and AI capabilities.</span></span> <span data-ttu-id="ed886-109">たとえば、Dynamics 365 for Sales の顧客アカウント エンティティを、Dynamics 365 for Service のオープン サービス チケットからの情報、および Office 365 の関連する顧客会議情報で補強できます 。</span><span class="sxs-lookup"><span data-stu-id="ed886-109">For example, you could enrich a customer account entity from Dynamics 365 for Sales with information from open service tickets in Dynamics 365 for Service, and relevant customer meeting information from Office 365.</span></span>

<span data-ttu-id="ed886-110">計算されたエンティティを最新の情報に更新するには、Power BI Premium が必要です。</span><span class="sxs-lookup"><span data-stu-id="ed886-110">Refreshing computed entities requires Power BI Premium.</span></span> 
