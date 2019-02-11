---
title: 独自の Data Lake 内のエンティティ格納
description: エンティティ格納内のトランザクション データとマスター データは、独自の ADLS Gen2 Data Lake で利用できます。
author: MilindaV2
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: MilindaV2
ms.openlocfilehash: c11d0d0f0d4a8be91bc3a300864c0eeb70816e84
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210615"
---
<!--from editor: What does BYOD stand for? Also, COGS? Does ADL mean Azure Data Lake?-->


#  <a name="entity-store-in-your-own-business-data-lake"></a><span data-ttu-id="afdbd-103">独自の Business Data Lake 内のエンティティ格納</span><span class="sxs-lookup"><span data-stu-id="afdbd-103">Entity store in your own Business Data Lake</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="afdbd-104">Dynamics 365 for Finance and Operations に組み込まれている分析ワークスペースは、以下のような理由で、お客様から高く評価されています。</span><span class="sxs-lookup"><span data-stu-id="afdbd-104">Customers appreciate the analytical workspaces that are built in to Dynamics 365 for Finance and Operations due to:</span></span>

- <span data-ttu-id="afdbd-105">**Finance and Operations のコンテキストでの埋め込み**: セキュリティ フィルターとデータ フィルターはユーザーのコンテキストに基づいています。</span><span class="sxs-lookup"><span data-stu-id="afdbd-105">**Embedding with Finance and Operations context**: Security and data filters are based on the user’s context.</span></span> <span data-ttu-id="afdbd-106">ユーザーはドリルスルーしてアクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-106">Users can drill through to take action.</span></span>

- <span data-ttu-id="afdbd-107">**予測可能な価格**: Finance and Operations のライセンスを入手すると、お客様はエクスペリエンスを利用できます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-107">**Predictable pricing**: Customers get the experience when they license Finance and Operations.</span></span>

<span data-ttu-id="afdbd-108">ただし、一般に、KPI や計算を追加することによって埋め込みレポートを拡張したり、独自のデータとマージすることが、頻繁に必要になります。</span><span class="sxs-lookup"><span data-stu-id="afdbd-108">However, a common requirement is to extend embedded reports often by adding KPIs, calculations, or to merge with their own data.</span></span> <span data-ttu-id="afdbd-109">埋め込みレポートを変更するとコストは高くなります (つまり、開発者の関与が必要です)。</span><span class="sxs-lookup"><span data-stu-id="afdbd-109">The cost of modifying embedded reports are high (in other words, developer involvement is required).</span></span> <span data-ttu-id="afdbd-110">そのため、お客様は BYOD も使用して、レポート用に独自のデータベースにデータをエクスポートし、多くの場合、レポートを複製して変更します。</span><span class="sxs-lookup"><span data-stu-id="afdbd-110">Therefore, customers also use BYOD and export data into their own databases for reports—often duplicating the same report with a few changes.</span></span> <span data-ttu-id="afdbd-111">データ管理では引き続き SQL データベース (BYOD など) へのデータのエクスポートがサポートされますが、データのエクスポートと例外の管理に関連する管理上のオーバーヘッドを削減したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="afdbd-111">While Data Management will continue to support exporting data into SQL databases (such as BYOD), we want to reduce the administrative overhead associated with exporting data and managing exceptions.</span></span>

<span data-ttu-id="afdbd-112">苦労を減らして、エクスペリエンスを単純化するため、Business Data Lake (ADL Gen2) インフラストラクチャを Power BI データフローと共に利用しています。</span><span class="sxs-lookup"><span data-stu-id="afdbd-112">To reduce pain and to simplify the experience, we're leveraging the Business Data Lake (ADL Gen2) infrastructure along with Power BI dataflows.</span></span> <span data-ttu-id="afdbd-113">この機能は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="afdbd-113">The feature is as follows:</span></span>

<span data-ttu-id="afdbd-114">お客様は、独自の Data Lake (Azure Data Lake Storage Gen2) を持ち込み、Finance and Operations 内で構成することができます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-114">Customers can bring their own Data Lake (Azure Data Lake Storage Gen2) and configure within Finance and Operations.</span></span> <span data-ttu-id="afdbd-115">Data Lake は、SQL データベースより費用対効果の高いオプションです。</span><span class="sxs-lookup"><span data-stu-id="afdbd-115">Data Lake is a cost-effective option compared to SQL databases.</span></span>

<span data-ttu-id="afdbd-116">エンティティ格納内のトランザクション データとマスター データは、お客様の Data Lake に公開されます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-116">Transactional and master data in the Entity store will be published to customer’s Data Lake.</span></span> <span data-ttu-id="afdbd-117">リアルタイム ベースで最新のデータが保持されます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-117">Microsoft will keep the data fresh on a real-time basis.</span></span> <span data-ttu-id="afdbd-118">最初の重点は Data Lake 内で集計の測定と集計の分析コードを有効にすることですが、機能の改善として Data Lake で通常のデータ エンティティをステージングできるようにする予定です。</span><span class="sxs-lookup"><span data-stu-id="afdbd-118">While the initial focus is to enable aggregate measurements and aggregate dimensions in the Data Lake, we will enable staging regular data entities in the Data Lake as feature improvements.</span></span>

<span data-ttu-id="afdbd-119">お客様は、自分自身の PowerBI.com サブスクリプションを持ち込み、Finance and Operations 内で構成することもできます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-119">Customers can also bring their own PowerBI.com subscription and configure within Finance and Operations.</span></span> <span data-ttu-id="afdbd-120">この機能は、システムで既に使用できます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-120">This feature is already available in the system.</span></span> <span data-ttu-id="afdbd-121">お客様がこの情報を提供すると、分析ワークスペースに含まれる Power BI レポートも、お客様独自の PowerBI.com サブスクリプションに公開されます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-121">When the customer provides this information, Power BI reports contained in analytical workspaces will also be published into the customer's own PowerBI.com subscription.</span></span> <span data-ttu-id="afdbd-122">PowerBI.com のパワー ユーザーや消費者は、レポートやダッシュボードを使用するだけでなく拡張することもできます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-122">Power users and consumers of PowerBI.com can use as well as extend reports and dashboards.</span></span> <span data-ttu-id="afdbd-123">また、Power Q&A やモバイル ダッシュボードの使用など、PowerBI.com で利用可能なすべての機能も使用できます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-123">They can also use the full features available in PowerBI.com, including use of Power Q&A and mobile dashboards.</span></span>

<span data-ttu-id="afdbd-124">この機能により、運用レポートの作成に伴う現在の苦労が解消されるだけでなく、戦略的な利点ももたらされます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-124">While this feature will eliminate current pains associated with developing operational reports, it also accrues to strategic benefits:</span></span>

- <span data-ttu-id="afdbd-125">エンティティ格納で使用できるトランザクション データとマスター データに、Data Lake 経由でアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="afdbd-125">Transactional and master data available in the Entity store will be accessible via a Data Lake.</span></span> <span data-ttu-id="afdbd-126">同じトランザクション データを BYOD にエクスポートする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="afdbd-126">No need to export the same transactional data into BYOD.</span></span> <span data-ttu-id="afdbd-127">データ フローを介した PowerBI.com との既製の統合により、簡単なデータ マッシュアップが可能になります。</span><span class="sxs-lookup"><span data-stu-id="afdbd-127">Ready-made integration with PowerBI.com via data flows will enable easy data mash-ups.</span></span>

- <span data-ttu-id="afdbd-128">お客様は、データをオンプレミスのデータ ウェアハウスにダウンロードしなくても、自分のデータ Data Lake に取り込んで、マッシュアップ シナリオを簡単に実現できます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-128">Customers can bring their own data into the Data Lake and achieve mash-up scenarios easily without having to download the data onto on-premises data warehouses.</span></span> <span data-ttu-id="afdbd-129">データを Data Lake に格納するコストは、SQL データベースに格納するよりはるかに低くなります。</span><span class="sxs-lookup"><span data-stu-id="afdbd-129">The cost of storing data in a Data Lake is much lower than storing it in a SQL database.</span></span>

- <span data-ttu-id="afdbd-130">Dynamics ドメイン内の複数のアプリケーションを対象とする分析アプリを構築できます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-130">Enable building analytic apps across applications within the Dynamics domain.</span></span> <span data-ttu-id="afdbd-131">たとえば、お客様は Customer Engagement アプリケーションと Finance and Operations の間でデータを組み合わせることができます。</span><span class="sxs-lookup"><span data-stu-id="afdbd-131">For example, customers will be able to combine data between Customer Engagement applications and Finance and Operations.</span></span>

- <span data-ttu-id="afdbd-132">お客様の COGS の削減 (BYOD の使用の削減)。</span><span class="sxs-lookup"><span data-stu-id="afdbd-132">Reduction in COGS for customers (reduce usage of BYOD).</span></span>
