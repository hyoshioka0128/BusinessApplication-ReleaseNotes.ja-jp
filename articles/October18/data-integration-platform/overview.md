---
title: "データ統合プラットフォーム"
description: "データ統合プラットフォーム"
author: shellyhaverkamp
manager: AnnBe
ms.date: 9/7/2018
ms.assetid: c1ee3db5-6f37-47cd-a0c1-b995e7ad844d
ms.topic: overview
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: c45edf358d80b5831b80db4b1c423f39dcd79b63
ms.openlocfilehash: 6ca2d3391f48462fae54fd1065a6cd4814703dd1
ms.contentlocale: ja-jp
ms.lasthandoff: 09/07/2018

---



#  <a name="overview-of-data-integration-platform-october-18-release"></a><span data-ttu-id="0c33f-103">データ統合プラットフォーム 2018 年 10 月リリースの概要</span><span class="sxs-lookup"><span data-stu-id="0c33f-103">Overview of Data Integration Platform October '18 release</span></span>

<span data-ttu-id="0c33f-104">(リリース ノートで説明されている機能は、まだリリースされていない場合があります。)</span><span class="sxs-lookup"><span data-stu-id="0c33f-104">(These release notes describe functionality that may not have been released yet.</span></span> <span data-ttu-id="0c33f-105">提供タイムラインおよび予定されている機能は、変更される可能性、または出荷されない可能性があります ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。</span><span class="sxs-lookup"><span data-stu-id="0c33f-105">Delivery timelines and projected functionality may change or may not ship (see [Microsoft policy](https://go.microsoft.com/fwlink/p/?linkid=2007332).)</span></span> 

<span data-ttu-id="0c33f-106">データ統合は、外部データを Common Data Service (CDS) に取り込み、そのデータを Common Data Model (CDM) フォームに保存することを可能にする、コネクタとゲートウェイを提供します。</span><span class="sxs-lookup"><span data-stu-id="0c33f-106">Data Integration provides the connectors and gateways that make it possible to bring any external data into the Common Data Service (CDS) and store the data in Common Data Model (CDM) form.</span></span> <span data-ttu-id="0c33f-107">これらのコネクタとゲートウェイにより、組織は簡単にデータを 1 か所に統合してビジネス アプリケーションや分析に利用できます。</span><span class="sxs-lookup"><span data-stu-id="0c33f-107">These connectors and gateways make it easier for organizations to integrate their data in a single place for business applications and analytics.</span></span> <span data-ttu-id="0c33f-108">データ統合は Microsoft Power Query に基づいています。Power Query は、数百万人が Power BI と Excel で毎日使っているのと同じテクノロジです。</span><span class="sxs-lookup"><span data-stu-id="0c33f-108">Data Integration is based on Microsoft Power Query, the same technology that millions of people use daily in Power BI and Excel.</span></span>

<span data-ttu-id="0c33f-109">![データ統合プラットフォームの概要](media/data-integration-1.png "データ統合プラットフォームの概要")</span><span class="sxs-lookup"><span data-stu-id="0c33f-109">![Data Integration Platform overview](media/data-integration-1.png "Data Integration platform")</span></span>

<span data-ttu-id="0c33f-110">データ統合により、次のような数百ものビジネス クリティカルなデータ ソースへの直接接続が可能になります。</span><span class="sxs-lookup"><span data-stu-id="0c33f-110">Data Integration provides direct connectivity to hundreds of business-critical data sources, including:</span></span>

-   <span data-ttu-id="0c33f-111">オンプレミス データ ゲートウェイ経由のハイブリッド接続。</span><span class="sxs-lookup"><span data-stu-id="0c33f-111">Hybrid connectivity via the on-premises data gateway.</span></span>
-   <span data-ttu-id="0c33f-112">Power BI、PowerApps、Logic Apps、Microsoft Flow、Azure Analysis Services、Office 365 (Excel の Power Query) への統合。</span><span class="sxs-lookup"><span data-stu-id="0c33f-112">Integration into Power BI, PowerApps, Logic Apps, Microsoft Flow, Azure Analysis Services, and Office 365 (Power Query in Excel).</span></span>

<span data-ttu-id="0c33f-113">このプラットフォーム機能に対する改善によって、Microsoft やサード パーティのアプリケーションとサービスへの接続が拡充されます。</span><span class="sxs-lookup"><span data-stu-id="0c33f-113">Improvements to this platform functionality enable richer connectivity to Microsoft and third-party applications and services.</span></span> <span data-ttu-id="0c33f-114">このリリースでは、次の領域で重要なイノベーションが行われています。</span><span class="sxs-lookup"><span data-stu-id="0c33f-114">The release delivers key innovations in the following areas:</span></span>

-   [<span data-ttu-id="0c33f-115">Power Query およびデータ統合プラットフォームによるエンタープライズ データのよりシンプルかつスマートな変換と統合</span><span class="sxs-lookup"><span data-stu-id="0c33f-115">Simpler, smarter transformation and integration of enterprise data with Power Query and Data Integration Platform</span></span>](1-power-query.md)
-   [<span data-ttu-id="0c33f-116">Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化</span><span class="sxs-lookup"><span data-stu-id="0c33f-116">Easier sharing, unification, and enrichment of data with Common Data Model entities</span></span>](2-cdm.md)
-   [<span data-ttu-id="0c33f-117">強化され、より統合されたコネクターと開発者エコシステム</span><span class="sxs-lookup"><span data-stu-id="0c33f-117">Richer and more unified connector and developer ecosystem</span></span>](3-connector-ecosystem.md)
-   [<span data-ttu-id="0c33f-118">データ統合の強化された管理者機能</span><span class="sxs-lookup"><span data-stu-id="0c33f-118">Enhanced administrator capabilities for Data Integration</span></span>](4-data-integration-admin.md)
-   [<span data-ttu-id="0c33f-119">オンプレミス データ ゲートウェイを使用したエンタープライズ レベルのハイブリッド接続</span><span class="sxs-lookup"><span data-stu-id="0c33f-119">Enterprise-grade hybrid connectivity using the on-premises data gateway</span></span>](5-data-gateway.md)

<span data-ttu-id="0c33f-120">(リリース ノートで説明されている機能は、まだリリースされていない場合があります。)</span><span class="sxs-lookup"><span data-stu-id="0c33f-120">(These release notes describe functionality that may not have been released yet.</span></span> <span data-ttu-id="0c33f-121">提供タイムラインおよび予定されている機能は、変更される可能性、または出荷されない可能性があります ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。</span><span class="sxs-lookup"><span data-stu-id="0c33f-121">Delivery timelines and projected functionality may change or may not ship (see [Microsoft policy](https://go.microsoft.com/fwlink/p/?linkid=2007332).)</span></span> 

