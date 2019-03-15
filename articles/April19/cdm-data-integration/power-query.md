---
title: Power Query
description: Power Query
author: msftman
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: deonhe
ms.openlocfilehash: 16e399f3df7bb8bf3ebeb9ffcf4f9eacfd9ff75a
ms.sourcegitcommit: ca9feb07bc4f4050b7621ba462eb0d3ad5cd8359
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/13/2019
ms.locfileid: "390067"
---
<!--Are the names in the screenshot from an approved fictitious names list?-->


# <a name="power-query-becomes-smarter-and-more-powerful"></a><span data-ttu-id="8fb82-103">Power Query がよりスマートかつパワフルに</span><span class="sxs-lookup"><span data-stu-id="8fb82-103">Power Query becomes smarter and more powerful</span></span>
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]


<span data-ttu-id="8fb82-104">セルフサービスのデータ準備分野における主な傾向の 1 つは、*スマート データ準備*です。</span><span class="sxs-lookup"><span data-stu-id="8fb82-104">One of the major trends within the self-service data preparation space is *smart data preparation*.</span></span> <span data-ttu-id="8fb82-105">データ アナリストは AI の力を活用して、自動 (組み込みのレコメンデーションなど) であっても、ユーザーの操作 (AI/ML 関数への呼び出しなど) によるものであっても、AI アルゴリズムへのアクセスを一般化し、データを補完して強化します。</span><span class="sxs-lookup"><span data-stu-id="8fb82-105">It brings the power of AI into the hands of the data analyst, democratizing access to AI algorithms to enrich and enhance data, whether that is automatic (such as built-in recommendations) or by means of user interaction (such as calling in to AI/ML functions).</span></span>

<span data-ttu-id="8fb82-106">過去 6 か月から 12 か月の間に、Power Query のコア エクスペリエンスに次のようなスマート データ準備機能が多数追加されました。</span><span class="sxs-lookup"><span data-stu-id="8fb82-106">Over the last 6-12 months, Power Query added a lot of smart data preparation capabilities to its core experiences, including:</span></span>

- <span data-ttu-id="8fb82-107">**例によるデータ抽出機能**: ユーザーが既存のテーブル列や HTML ページからデータを抽出できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8fb82-107">**By example data extraction capabilities**: Allows users to extract data from existing table columns or from HTML pages.</span></span> <span data-ttu-id="8fb82-108">これは、ユーザーに一連のサンプルの出力値を指定させ、Power Query にユーザーの意図を推測させた後に AI アルゴリズムを適用することで残りの値を抽出することをベースとしています。</span><span class="sxs-lookup"><span data-stu-id="8fb82-108">This is based on letting users specify a set of sample output values, having Power Query infer the users' intent, and then extracting the remaining values by applying AI algorithms.</span></span>  
- <span data-ttu-id="8fb82-109">**あいまい統合**: 完全一致ではなく、あいまい一致アルゴリズムを使用して複数のテーブルからデータを簡単に結合できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8fb82-109">**Fuzzy merge**: Allows users to easily combine data from multiple tables using fuzzy matching algorithms instead of strict matching.</span></span> 
- <span data-ttu-id="8fb82-110">**データ プロファイリング**: ユーザーが Power Query Editor のデータ プレビュー内でエラー値、空の値、異常値を簡単に特定できるようサポートします。</span><span class="sxs-lookup"><span data-stu-id="8fb82-110">**Data profiling**: Helps users easily identify error, empty, and outlier values within their Power Query Editor data previews.</span></span> 
- <span data-ttu-id="8fb82-111">**Power Query Online の組み込みのブラウジングおよび呼び出しエクスペリエンス**: Azure Machine Learning モデルと Azure Cognitive Services の機能を Power BI データフローの通常のデータ準備ステップとして使用します。</span><span class="sxs-lookup"><span data-stu-id="8fb82-111">**Built-in browsing and invocation experiences in Power Query Online**: Uses Azure Machine Learning models and Azure Cognitive Services functions as regular data preparation steps in Power BI dataflows.</span></span> <span data-ttu-id="8fb82-112">これにより Azure クラウド プラットフォームに Cognitive Services のすぐに使える機能を組み込み、組織のデータ サイエンティストが作成した Azure Machine Learning モデルをデータ アナリストと共有して使用できます。</span><span class="sxs-lookup"><span data-stu-id="8fb82-112">This brings together the out-of-the-box Cognitive Services capabilities built in to the Azure cloud platform, as well as the ability to consume Azure Machine Learning models created by an organization’s data scientists, and shared with data analysts for consumption.</span></span>  

   <span data-ttu-id="8fb82-113">![データ プロファイリングのイメージ](media/data-profiling.png "データ プロファイリングのイメージ")</span><span class="sxs-lookup"><span data-stu-id="8fb82-113">![Data profiling image](media/data-profiling.png "Data profiling image")</span></span>

<span data-ttu-id="8fb82-114">今後数か月において、Microsoft ではこれをベースに Power Query のスマート データ準備機能を強化し、データ アナリストが少ない労力でより多くの分析情報をデータから得られるようにします。</span><span class="sxs-lookup"><span data-stu-id="8fb82-114">In the upcoming months, we will continue building on this foundation to make Power Query’s smart data preparation capabilities even more powerful, helping data analysts achieve more from their data with even less effort.</span></span>

## <a name="high-enterprise-value-connectors-become-generally-available-for-power-bi-customers"></a><span data-ttu-id="8fb82-115">Power BI ユーザーへのエンタープライズ グレードの高レベルなコネクタの一般提供を開始</span><span class="sxs-lookup"><span data-stu-id="8fb82-115">High enterprise value connectors become generally available for Power BI customers</span></span>

<span data-ttu-id="8fb82-116">2019 年の 4 月までに、パブリック プレビューとして最近公開された Power BI のエンタープライズ グレードのコネクタの多くの機能の一般提供が開始されます。その中には次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8fb82-116">By April '19, many of the recently shipped Public Preview capabilities for enterprise-grade connectors in Power BI will become generally available, including:</span></span>

- <span data-ttu-id="8fb82-117">Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP BW シングル サインオン (Kerberos)</span><span class="sxs-lookup"><span data-stu-id="8fb82-117">SAP BW single sign-on (Kerberos) in Power BI service (via on-premises data gateway)</span></span>
- <span data-ttu-id="8fb82-118">Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP HANA シングル サインオン (SAML)</span><span class="sxs-lookup"><span data-stu-id="8fb82-118">SAP HANA single sign-on (SAML) in Power BI service (via on-premises data gateway)</span></span>
- <span data-ttu-id="8fb82-119">PDF コネクタ</span><span class="sxs-lookup"><span data-stu-id="8fb82-119">PDF connector</span></span>
- <span data-ttu-id="8fb82-120">Essbase コネクタ</span><span class="sxs-lookup"><span data-stu-id="8fb82-120">Essbase connector</span></span>
- <span data-ttu-id="8fb82-121">IBM DB2 DirectQuery</span><span class="sxs-lookup"><span data-stu-id="8fb82-121">IBM DB2 DirectQuery</span></span>

<span data-ttu-id="8fb82-122">さらに、次のコネクタがパブリック プレビューに入ります。</span><span class="sxs-lookup"><span data-stu-id="8fb82-122">In addition, the following connector will go into Public Preview:</span></span>

- <span data-ttu-id="8fb82-123">AtScale コネクタ</span><span class="sxs-lookup"><span data-stu-id="8fb82-123">AtScale connector</span></span>

<span data-ttu-id="8fb82-124">さらに、Power BI ではエンタープライズ ユーザーのフィードバックに基づいて、SAP HANA と SAP BW コネクタの上に、レポートのユーザーが SAP HANA/BW の変数値を PowerBI.com のレポート消費エクスペリエンス内で修正できる新機能をパブリック プレビューとして公開します。</span><span class="sxs-lookup"><span data-stu-id="8fb82-124">Additionally, Power BI is enabling a new Public Preview capability on top of the SAP HANA and BW connectors based on enterprise customer feedback, allowing report consumers to modify SAP HANA/BW variable values within the PowerBI.com report consumption experiences.</span></span>

## <a name="power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities"></a><span data-ttu-id="8fb82-125">Power Query Online にデータ接続とデータ準備に関わるいくつかの新機能を追加</span><span class="sxs-lookup"><span data-stu-id="8fb82-125">Power Query Online adds several new data connectivity and preparation capabilities</span></span>

<span data-ttu-id="8fb82-126">Power Query は Windows/デスクトップに埋め込み可能なコンポーネント (現在 Power BI Desktop、デスクトップ版 Excel、SQL Server Data Tools と統合) としてのほか、Azure にホストされた Web ベースのサービス (現在 Power BI データフロー、Common Data Service for Apps、Microsoft Flow と統合) として利用できます。</span><span class="sxs-lookup"><span data-stu-id="8fb82-126">Power Query is available as a Windows/Desktop embeddable component (currently integrated with Power BI Desktop, Excel Desktop, and SQL Server Data Tools) as well as a web-based, Azure-hosted service (currently integrated with Power BI dataflows, Common Data Service for Apps, and Microsoft Flow).</span></span>

<span data-ttu-id="8fb82-127">今後 6 か月間で、次のデータ コネクタを Power Query Online に追加します。</span><span class="sxs-lookup"><span data-stu-id="8fb82-127">Over the next six months, we'll add the following data connectors to Power Query Online:</span></span>  

- <span data-ttu-id="8fb82-128">Amazon Redshift</span><span class="sxs-lookup"><span data-stu-id="8fb82-128">Amazon Redshift</span></span>
- <span data-ttu-id="8fb82-129">Impala</span><span class="sxs-lookup"><span data-stu-id="8fb82-129">Impala</span></span>
- <span data-ttu-id="8fb82-130">Apache Spark</span><span class="sxs-lookup"><span data-stu-id="8fb82-130">Apache Spark</span></span>
- <span data-ttu-id="8fb82-131">HDInsight Spark</span><span class="sxs-lookup"><span data-stu-id="8fb82-131">HDInsight Spark</span></span>
- <span data-ttu-id="8fb82-132">HDInsight Hive 対話型クエリ</span><span class="sxs-lookup"><span data-stu-id="8fb82-132">HDInsight Hive Interactive Query</span></span>
- <span data-ttu-id="8fb82-133">Vertica</span><span class="sxs-lookup"><span data-stu-id="8fb82-133">Vertica</span></span>
- <span data-ttu-id="8fb82-134">Google BigQuery</span><span class="sxs-lookup"><span data-stu-id="8fb82-134">Google BigQuery</span></span>
- <span data-ttu-id="8fb82-135">Teradata</span><span class="sxs-lookup"><span data-stu-id="8fb82-135">Teradata</span></span>
- <span data-ttu-id="8fb82-136">Informix</span><span class="sxs-lookup"><span data-stu-id="8fb82-136">Informix</span></span>
- <span data-ttu-id="8fb82-137">Sybase</span><span class="sxs-lookup"><span data-stu-id="8fb82-137">Sybase</span></span>
- <span data-ttu-id="8fb82-138">MySQL</span><span class="sxs-lookup"><span data-stu-id="8fb82-138">MySQL</span></span>
- <span data-ttu-id="8fb82-139">PostgreSQL</span><span class="sxs-lookup"><span data-stu-id="8fb82-139">PostgreSQL</span></span>

## <a name="increased-support-for-developers-on-the-power-query-platform"></a><span data-ttu-id="8fb82-140">開発者に対する Power Query プラットフォームに関わるサポートを改善</span><span class="sxs-lookup"><span data-stu-id="8fb82-140">Increased support for developers on the Power Query platform</span></span>

<span data-ttu-id="8fb82-141">認定コネクタの一般提供開始と Power BI のカスタム コネクタ開発により、コネクタの開発に使用する同じツールを Power Query プラットフォームで世界中の開発者が利用できるようにしました。</span><span class="sxs-lookup"><span data-stu-id="8fb82-141">With the general availability of certified connectors and custom connector development for Power BI, the Power Query platform has made the same tools that we use to develop connectors available to developers around the world.</span></span>

<span data-ttu-id="8fb82-142">Microsoft では今後 6 か月の間にこのオファーを継続的に開発者に展開し、だれでもデータを Power Query プラットフォームに接続できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8fb82-142">Over the next six months, we will continue to expand our offerings to developers and the ability for anyone to connect their data to the Power Query platform.</span></span> 

<span data-ttu-id="8fb82-143">開発者は Microsoft のプロセスに従うのではなく、自身の証明書で署名されたコネクタを提供する方法をサポートするよう Microsoft に依頼してきました。</span><span class="sxs-lookup"><span data-stu-id="8fb82-143">Developers have asked us to support a way to deliver connectors that have been signed with their certificate, rather than going through Microsoft’s process.</span></span> <span data-ttu-id="8fb82-144">Microsoft では開発者やユーザーがサード パーティによって署名されたコネクタを使用できるようにする方法を導入します。</span><span class="sxs-lookup"><span data-stu-id="8fb82-144">We will be introducing a method to enable developers and users to use connectors signed by third parties.</span></span>
