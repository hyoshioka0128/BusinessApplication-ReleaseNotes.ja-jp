---
title: Common Data Model (CDM)
description: Common Data Model (CDM)
author: theresapalmer
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
ms.reviewer: deonhe
ms.openlocfilehash: 7484d9f7a4742b7d979d9a0642ab84949a014fe7
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210747"
---
# <a name="common-data-model-cdm"></a><span data-ttu-id="8d04e-103">Common Data Model (CDM)</span><span class="sxs-lookup"><span data-stu-id="8d04e-103">Common Data Model (CDM)</span></span>
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]


<span data-ttu-id="8d04e-104">現在の Common Data Model (CDM) では、モジュール式で拡張可能なビジネス エンティティ (取引先企業、リード、営業案件など) と、観察データの概念 (リンクのクリックや電子メールのオープンなど) が提供されています。</span><span class="sxs-lookup"><span data-stu-id="8d04e-104">Today’s Common Data Model (CDM) provides modular and extensible business entities (account, lead, opportunity, and so on) as well as observational data concepts (such as Link clicks and Email opens).</span></span> <span data-ttu-id="8d04e-105">それにより、よく知られたスキーマ内のデータと、データ サイロ、アプリケーション、展開をまたがって一貫性を持つセマンティックが統合されます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-105">It unifies data in a well-known schema with semantic consistency across data silos, applications, and deployments.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="8d04e-106">![CDM によりプロデューサーとコンシューマーがデータ レイク内で相互作用できる](media/common-data-model-cdm-1.png "CDM によりプロデューサーとコンシューマーがデータ レイク内で相互作用できる")</span><span class="sxs-lookup"><span data-stu-id="8d04e-106">![CDM allows producers and consumers to interoperate within the data lake](media/common-data-model-cdm-1.png "CDM allows producers and consumers to interoperate within the data lake")</span></span>

<span data-ttu-id="8d04e-107">CDM の形式でデータを実装、生成、消費する製品、プラットフォーム、サービスの範囲は、Microsoft の内外で拡大し続けています。</span><span class="sxs-lookup"><span data-stu-id="8d04e-107">The span of products, platforms, and services that implement, produce, and consume data in CDM form continues to grow, inside and outside Microsoft.</span></span>

## <a name="additional-capabilities-and-features-as-part-of-the-open-data-initiative"></a><span data-ttu-id="8d04e-108">Open Data Initiative の一環としての追加機能</span><span class="sxs-lookup"><span data-stu-id="8d04e-108">Additional capabilities and features as part of the Open Data Initiative</span></span>

<span data-ttu-id="8d04e-109">Open Data Initiative の一環として、創設パートナー間の "1 つのデータ モデル" により、基盤となるデータとメタデータに直接アクセスすることで、インテリジェンスと知識の作成シナリオのための顧客所有の共有データ レイクがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-109">As part of the Open Data Initiative, “one data model” across the founding partners supports a customer-owned shared data lake for intelligence and knowledge creation scenarios with direct access to the underlying data and metadata.</span></span> <span data-ttu-id="8d04e-110">創設パートナー (および追加パートナー) は、データと明確に定義されたセマンティック メタデータをそのデータ レイクに格納し、そこから取得します。</span><span class="sxs-lookup"><span data-stu-id="8d04e-110">The founding partners (and additional ones) will land their data with well-defined semantic metadata in that data lake and pull from it.</span></span> <span data-ttu-id="8d04e-111">これは Azure Data Lake Storage (ADLS) Gen2 の最初のバージョンの "CDM フォルダー" に似ていますが、複数の Azure データ サービスとパートナー (Informatica など) がそれに向けて構築することで、大きな進化が必要です。</span><span class="sxs-lookup"><span data-stu-id="8d04e-111">This resembles the first version of “CDM folders” in Azure Data Lake Storage (ADLS) Gen2 but requires significant evolution, with multiple Azure data services and partners (for example, Informatica) building toward it.</span></span>

<span data-ttu-id="8d04e-112">既存のトランザクション プラットフォーム (CDS など) 上には膨大な量の既存の顧客データとアプリケーションが存在しており、それらを同じ "1 つのデータ モデル" に収束させることは簡単な問題ではありません。</span><span class="sxs-lookup"><span data-stu-id="8d04e-112">With the huge volume of existing customer data and applications on the existing transactional platforms (such as CDS), it is not a tractable problem to converge those onto the same “one data model.”</span></span> <span data-ttu-id="8d04e-113">データがレイクにシームレスかつ自動的に格納されることを保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d04e-113">We need to ensure we make landing the data in the lake seamless and automatic.</span></span> <span data-ttu-id="8d04e-114">同様に、共有データ レイクから分析情報を取得し、それらの分析情報をプラットフォームに戻すことも、簡単でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8d04e-114">Similarly, it must be easy to gain insights from the shared data lake and bring those insights back into the platforms.</span></span> <span data-ttu-id="8d04e-115">これにより、Adobe および SAP のデータ資産を当社の AI およびインテリジェンス オファリングに含めるための取り組みも拡張されます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-115">This also extends the effort to include data assets from Adobe and SAP in our AI and intelligence offerings.</span></span>

## <a name="updated-developer-and-consumer-documentation"></a><span data-ttu-id="8d04e-116">開発者および消費者向けドキュメントの更新</span><span class="sxs-lookup"><span data-stu-id="8d04e-116">Updated developer and consumer documentation</span></span>

<span data-ttu-id="8d04e-117">Common Data Model は範囲と機能が進化し続けているため、消費者と開発者の両方に対する公開ドキュメントの重要性が増しています。</span><span class="sxs-lookup"><span data-stu-id="8d04e-117">The Common Data Model continues to evolve in scope and capabilities, which increases the importance of the public documentation for both consumers and developers.</span></span> <span data-ttu-id="8d04e-118">公開ドキュメント セットに対する追加のクイック スタートやベスト プラクティスなどのリリースにより、CDM に関心のある人ならだれでもその力を最大限に活用する方法を学ぶことができる場所が提供されます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-118">The release of additional quick starts, best practices, and more to the public documentation set provides a destination where anyone interested in CDM can learn how best to leverage its power.</span></span>

## <a name="cdm-schema-documents"></a><span data-ttu-id="8d04e-119">CDM スキーマ ドキュメント</span><span class="sxs-lookup"><span data-stu-id="8d04e-119">CDM schema documents</span></span>

<span data-ttu-id="8d04e-120">CDM スキーマの定義は、エコシステムからのニーズに基づいて改善され続けています。</span><span class="sxs-lookup"><span data-stu-id="8d04e-120">The CDM schema definition has continued to improve based on needs from the ecosystem.</span></span> <span data-ttu-id="8d04e-121">たとえば、名前空間処理のサポートの追加により、パートナーは自分のソリューションに固有の概念として識別およびバージョン管理できるスキーマを CDM 形式で開発およびリリースできます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-121">Examples include adding support for namespacing, allowing partners to develop and release schema in CDM form that can be identified and versioned as concepts specific to their solution.</span></span> <span data-ttu-id="8d04e-122">また、CDM スキーマ ドキュメントの正式なバージョン管理体系もリリースされました。</span><span class="sxs-lookup"><span data-stu-id="8d04e-122">We’ve also released an official versioning scheme for the CDM schema documents.</span></span> <span data-ttu-id="8d04e-123">この体系により、プロデューサーとコンシューマーは、サポートしているバージョンを確実に報告および識別できます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-123">This scheme ensures that producers and consumers can report and identify the versions they support.</span></span>

## <a name="sdk-and-tooling"></a><span data-ttu-id="8d04e-124">SDK とツール</span><span class="sxs-lookup"><span data-stu-id="8d04e-124">SDK and tooling</span></span>

<span data-ttu-id="8d04e-125">CDM 形式のデータを作成および利用できるよう、CDM 形式のコンテンツを探索、読み取り、変更、作成するための SDK とツールがリリースされました。</span><span class="sxs-lookup"><span data-stu-id="8d04e-125">In order to create and leverage the data in CDM shape, we’ve released an SDK and tooling to explore, read, modify, and create content in CDM form.</span></span> <span data-ttu-id="8d04e-126">これらのツールにより、開発者はさまざまなプラットフォームやサービスでイニシアチブにアクセスしやすくなります。</span><span class="sxs-lookup"><span data-stu-id="8d04e-126">These tools make the initiative approachable to developers across a wide range of platforms and services.</span></span> <span data-ttu-id="8d04e-127">これらのツールにより、増え続けている CDM 形式対応のサービスやエクスペリエンスの集合にデータが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8d04e-127">These tools open their data to the growing set of services and experiences that understand data in CDM form.</span></span>

## <a name="new-entity-definitions"></a><span data-ttu-id="8d04e-128">新しいエンティティの定義</span><span class="sxs-lookup"><span data-stu-id="8d04e-128">New entity definitions</span></span>

<span data-ttu-id="8d04e-129">CDM は、コア Dynamics 365 ソリューションからリリースされる新しい業界アクセラレーターと概念によって拡大を続けています。</span><span class="sxs-lookup"><span data-stu-id="8d04e-129">CDM continues to expand with the release of new industry accelerators and concepts from core Dynamics 365 solutions.</span></span> <span data-ttu-id="8d04e-130">たとえば、教育業界や非営利産業からのアクセラレーターのリリース、および医療アクセラレーターの更新により、CDM モデルに 100 を超える新しいエンティティがもたらされました。</span><span class="sxs-lookup"><span data-stu-id="8d04e-130">For example, the release of accelerators from the education and non-profit industries, as well as updates to the healthcare accelerator, have brought more than 100 new entities to the CDM model.</span></span> <span data-ttu-id="8d04e-131">さらに、Dynamics 365 for Finance and Operations、Marketing、Talent などからのエンティティ定義により、CDM とあらゆる規模の顧客やパートナーとの関連が強化され続けています。</span><span class="sxs-lookup"><span data-stu-id="8d04e-131">Additionally, entity definitions from Dynamics 365 for Finance and Operations, Marketing, Talent, and more continue to make CDM relevant to customers and partners of all sizes.</span></span>
