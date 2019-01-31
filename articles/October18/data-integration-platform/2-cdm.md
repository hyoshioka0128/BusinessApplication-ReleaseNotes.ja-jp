---
title: Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化
description: Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 60626a9d-c022-4a1f-8d3a-0533deba9b45
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: tpalmer
audience: Admin
ms.openlocfilehash: d4d414025d8270df6128791c3ff9954dcda1bffc
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199939"
---
# <a name="easier-sharing-unification-and-enrichment-of-data-with-common-data-model-entities"></a><span data-ttu-id="4ba5b-103">Common Data Model エンティティを使用した、より簡単なデータの共有、統合、強化</span><span class="sxs-lookup"><span data-stu-id="4ba5b-103">Easier sharing, unification, and enrichment of data with Common Data Model entities</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="4ba5b-104">標準エンティティのオープンソース **Common Data Model** の定義が強化されました。セールス、サービス、マーケティング、運営、財務、人材、およびコマースの各業務機能、また顧客のコア エンティティ プロファイル全体で、**ビジネス プロセス、アプリケーション、プロファイル エンリッチメントを統合**でき、観測的なデータ エンリッチメントと分析がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-104">The open-source **Common Data Model** definition of standard entities has been enhanced for the **integration of business processes, applications, and profile enrichment** across sales, services, marketing, operations, finance, talent, and commerce business functions, as well as core entity profiles for customers to support observational data enrichment and analysis.</span></span>

<span data-ttu-id="4ba5b-105">Common Data Model (CDM) は、アプリケーションや展開全体で構造およびセマンティック面での一貫性を保ちながら、よく知られた形式でデータ統合を可能にします。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-105">The Common Data Model (CDM) enables unification of data in a well-known form with structural and semantic consistency across applications and deployments.</span></span> <span data-ttu-id="4ba5b-106">データを Common Data Model 形式で保存することで、 **多数の幅広いソリューションが効率的に機能する**ようになっています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-106">There is a **large and growing collection of solutions that work together efficiently** when data is stored in the Common Data Model form.</span></span> <span data-ttu-id="4ba5b-107">このようなデータと分析情報の共有により、新しい業務プロセスや分析ソリューションをすばやく導入し、複雑さを排除しながら事業運営を全方位から視野に入れることができます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-107">This sharing of data and insights means you can quickly implement new business processes, analytical solutions, and gain a true 360-degree view into your business operations without complexity.</span></span>

<span data-ttu-id="4ba5b-108">2018 年 3 月の初期リリース以来、公開されている Common Data Model [GitHub リポジトリ](https://github.com/Microsoft/CDM)は、数百もの適切に定義された、モジュラー型で拡張可能なビジネス エンティティへと[大幅に増加](#a-more-expressive-richer-common-data-model)しており、これには戦略的パートナーとの密接なコラボレーションのもとで他の業種をサポートするための大幅な拡張も含まれます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-108">Since the initial release in March 2018, the public Common Data Model [GitHub repository](https://github.com/Microsoft/CDM) has [grown substantially](#a-more-expressive-richer-common-data-model) to several hundred well-defined, modular, and extensible business entities, including major extensions to support additional vertical industries in close collaboration with strategic partners.</span></span> <span data-ttu-id="4ba5b-109">改善された[ドキュメンテーションとプレゼンテーションのコンテンツ](#common-data-model-and-data-integration-community-content)により、顧客とパートナーは Common Data Model についてよりよく理解し、使いこなすことができます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-109">Improved [documentation and presentation content](#common-data-model-and-data-integration-community-content) allows customers and partners to better understand and use the Common Data Model.</span></span> <span data-ttu-id="4ba5b-110">Power Query によるコーディングなし (またはわずかなコーディング) のデータ統合、変換、およびエンリッチメント エクスペリエンスにより、CDM の[サポートと実装](#built-in-support-for-the-common-data-model)が引き続き可能です。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-110">The no-code/low-code data integration, transformation, and enrichment experiences with Power Query continue to [support and implement](#built-in-support-for-the-common-data-model) the CDM.</span></span>

##  <a name="a-more-expressive-richer-common-data-model"></a><span data-ttu-id="4ba5b-111">より表現豊かで豊富な Common Data Model</span><span class="sxs-lookup"><span data-stu-id="4ba5b-111">A more expressive, richer Common Data Model</span></span>

<span data-ttu-id="4ba5b-112">![プラットフォームと CDM の概要](media/a-more-expressive-richer-common-data-model-1.png "プラットフォームと CDM の概要")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="4ba5b-112">![Overview of the platform and CDM](media/a-more-expressive-richer-common-data-model-1.png "Overview of the platform and CDM")
<!-- picture --></span></span>

<span data-ttu-id="4ba5b-113">Microsoft は **ISV のエコシステムと協力**して、Common Data Model のリーチと柔軟性を向上させるための業界の拡張機能を作成して、組織の業務プロセスをデジタルに変革するよう支援しています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-113">Microsoft has been **collaborating with an ecosystem of ISVs** who help organizations digitally transform their business processes by creating industry extensions to increase reach and flexibility of the Common Data Model.</span></span> <span data-ttu-id="4ba5b-114">これらの拡張機能は、エコシステムの専門知識をベースにして業界の一部を対象としていますが、時間とともに拡大する予定です。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-114">These extensions represent a portion of the industry based on the expertise of the ecosystem and are expected to grow over time.</span></span> 

<span data-ttu-id="4ba5b-115">次にいくつかの例を挙げます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-115">The following are some examples.</span></span>

<a name="industry"></a>
### <a name="industry-extensions-for-strategic-verticals"></a><span data-ttu-id="4ba5b-116">戦略的な業種向けの業界拡張機能</span><span class="sxs-lookup"><span data-stu-id="4ba5b-116">Industry extensions for strategic verticals</span></span>

<span data-ttu-id="4ba5b-117">特定の業種を専門とするパートナーとの協力を通して、Common Data Model は、ヘルスケア、小売、財務分析、教育といった分野で、業界エンティティ パックにより拡張されています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-117">In collaboration with partners specializing in certain verticals, the Common Data Model is being extended with industry entity packs for areas such as Healthcare, Retail, Financial Analytics, Education, and others.</span></span> <span data-ttu-id="4ba5b-118">これらのエンティティ パックは、ビジネス アプリケーション プラットフォーム全体に渡る、より大規模な業界ソリューション オファリングの一部としてリリースされています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-118">These entity packs are being released as part of a larger industry solution offering spanning the Business Application platform.</span></span>

<span data-ttu-id="4ba5b-119">そのようなパートナーに **CUNA Mutual Group** があります。その AdvantEdge Analytics ソリューションは、信用組合がメンバーへのサービスを向上するのに役立っています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-119">One such partner is **CUNA Mutual Group**, whose AdvantEdge Analytics solution helps credit unions better serve their members.</span></span> <span data-ttu-id="4ba5b-120">Common Data Model と標準データ コネクタの拡張機能により、信用組合が使用する基幹業務向けアプリのデータを統合することができます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-120">Their extensions for the Common Data Model and standard data connectors help integrate data from line of business apps used by credit unions.</span></span> 

<a name="dynamics"></a>
### <a name="key-scenarios-from-popular-dynamics-offerings"></a><span data-ttu-id="4ba5b-121">人気のある Dynamics オファリングにおける主要なシナリオ</span><span class="sxs-lookup"><span data-stu-id="4ba5b-121">Key scenarios from popular Dynamics offerings</span></span>
<span data-ttu-id="4ba5b-122">人気のある Dynamics オファリングにおける主要なシナリオを対象として、他の CDM エンティティの定義が追加されています。これには、Finance、Operations、Marketing のシナリオも含まれます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-122">Additional CDM entity definitions covering key scenarios from popular Dynamics offerings are being added, including scenarios from Finance, Operations, Marketing, and more.</span></span> <span data-ttu-id="4ba5b-123">更新された Dynamics アプリケーションとともに、顧客は独自のシナリオでこれらの標準エンティティを活用できます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-123">Along with updated Dynamics applications, customers will be able to leverage these standard entities in their own scenarios.</span></span> 

##  <a name="common-data-model-community-content"></a><span data-ttu-id="4ba5b-124">Common Data Model のコミュニティ コンテンツ</span><span class="sxs-lookup"><span data-stu-id="4ba5b-124">Common Data Model community content</span></span>

<span data-ttu-id="4ba5b-125">Common Data Model とデータ統合のコンテンツは CDM GitHub のリポジトリを補完し、ガイダンス、詳細記事、ベスト プラクティスを提供します。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-125">A Common Data Model and Data Integration content complements the CDM GitHub repository to provide guidance, deep-drive articles, and best practices.</span></span>

<a name="explorer"></a>
### <a name="common-data-model-entity-explorer"></a><span data-ttu-id="4ba5b-126">Common Data Model のエンティティ エクスプローラー</span><span class="sxs-lookup"><span data-stu-id="4ba5b-126">Common Data Model entity explorer</span></span>

<span data-ttu-id="4ba5b-127">このインタラクティブかつグラフィカルなエンティティ エクスプローラーは、顧客とパートナーが、ビジネス アプリケーションとアナリティカル ソリューションの開発において既存の Common Data Model エンティティをより良く理解して活用するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-127">This interactive and graphical entity explorer allows customers and partners to better understand and leverage existing Common Data Model entities for business applications and analytical solution development.</span></span> <span data-ttu-id="4ba5b-128">詳細なエンティティと属性メタデータの説明により、このモデルの豊富なセマンティックに対する分析情報をもたらします。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-128">Detailed entity and attribute metadata descriptions provide insight into the rich semantics of the model.</span></span>

<a name="docs"></a>
### <a name="improved-documentation-and-presentation-content"></a><span data-ttu-id="4ba5b-129">ドキュメンテーションとプレゼンテーションのコンテンツの向上</span><span class="sxs-lookup"><span data-stu-id="4ba5b-129">Improved documentation and presentation content</span></span>
<span data-ttu-id="4ba5b-130">顧客およびパートナー向けのドキュメンテーションとプレゼンテーションのコンテンツが充実したことにより、Common Data Model に何が含まれるのか、プラットフォーム内でどのように有効活用できるのか、また CDM ベスト プラクティスに従ってどのようにカスタマイズできるのかをより良く理解できるようになります。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-130">Improved documentation and presentation content for customers and partners to better understanding what’s included in the Common Data Model, how best to use it within the platform, and how to customize it in a way that follows the CDM best practices.</span></span>

<span data-ttu-id="4ba5b-131">また、アプリケーション、データ モデル、データ統合、およびテンプレートの開発者コミュニティをサポートするために、ディスカッション フォーラムも立ち上げられています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-131">Discussion forums are also being set up to support a community for application, data model, and data integration template developers.</span></span>

<span data-ttu-id="4ba5b-132">加えて、パートナーは、CDM における潜在的な[業種向けの機能拡張](#industry-extensions-for-strategic-verticals)において**戦略的パートナーになるための方法**について明確なガイダンスを見つけることができ、CDS プラットフォームにより多くのアプリケーションをもたらして、ISV およびアプリ開発者のエコシステムをさらに強化することができます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-132">In addition, partners will be able to find clear guidance on **how to become a strategic partner** for potential CDM [enhancements for industry verticals](#industry-extensions-for-strategic-verticals), to bring more applications to the CDS platforms and further enhance the ecosystem of ISVs and app developers.</span></span> 

-   <span data-ttu-id="4ba5b-133">これらのソリューションや具体的なユースケースにより、どのように顧客とパートナーが共同でより簡単にソリューションの使用と構築を (CDM と CDS プラットフォームの上で) 成功させることができるのか、またそれによって、追加のアプリや統合による充実したエコシステムがどのように形成されるかに関する説明。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-133">Descriptions of how these solutions and specific use cases enable joint customers and partners to be more successful in using and building solutions (on top of CDM and CDS platforms) much more easily, and how this creates a thriving ecosystem of additional apps and integrations.</span></span>

-   <span data-ttu-id="4ba5b-134">これらの CDM 拡張機能を活用する AppSource のパッケージ化されたターンキー ソリューションの詳細と入手方法。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-134">How to learn more about packaged turn-key solutions in AppSource that leverage these CDM enhancements, and how to acquire them.</span></span>

-   <span data-ttu-id="4ba5b-135">これら戦略パートナーの共同声明および共同顧客の生の経験。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-135">Joint announcements of these strategic partners, and testimonials of our joint customers.</span></span>

<span data-ttu-id="4ba5b-136">レコードと SaaS サービスのシステムを CDS に接続する**データ統合テンプレートとソリューションの構築**に興味があるコンサルタントは、標準コネクタ、Data Connector SDK、およびデータを Common Data Model エンティティに変換するためのガイダンスとベスト プラクティスによるサポートが得られます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-136">Consultants interested in **building data integration templates and solutions** to connect systems of record and SaaS services to CDS are supported with standard connectors, the Data Connector SDK, and guidance and best practices on how to transform data to Common Data Model entities.</span></span>


##  <a name="built-in-automatic-support-for-the-common-data-model"></a><span data-ttu-id="4ba5b-137">Common Data Model の組み込み型自動サポート</span><span class="sxs-lookup"><span data-stu-id="4ba5b-137">Built-in automatic support for the Common Data Model</span></span> 

<span data-ttu-id="4ba5b-138">Power Query のデータ統合エクスペリエンス、データ統合テンプレート、アプリ用 CDS、および Power BI データフローは、Common Data Model を実装しています。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-138">Power Query data integration experiences, data integration templates, CDS for Apps, and Power BI dataflows implement the Common Data Model.</span></span> <span data-ttu-id="4ba5b-139">Common Data Model およびそれがサポートする製品スイートとエクスペリエンスの重要な特徴は拡張性です。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-139">A critical part of the Common Data Model and the suite of products and experiences it supports is its extensibility.</span></span> 

<span data-ttu-id="4ba5b-140">**データ統合テンプレート**は、一般的な基幹業務アプリケーションや SaaS サービスから、有名な Common Data Model エンティティの形式にデータを統合するのを加速します。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-140">**Data Integration Templates** accelerate integrating data into well-known Common Data Model entity shapes from common line-of-business applications and SaaS services.</span></span> <span data-ttu-id="4ba5b-141">たとえば、Salesforce テンプレートは、顧客がデータを CDS および Power BI データフローに統合して、それによってセールスの機会やパイプラインに関する分析情報を取得するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-141">For example, the Salesforce template helps customers integrate their data into CDS and Power BI dataflows and thereby gain insights into their opportunities and sales pipeline.</span></span> <span data-ttu-id="4ba5b-142">また、テンプレートの[追加の機能](4-data-integration-admin.md#templates)では、エンド カスタマーのためにこの機能が拡張される予定です。</span><span class="sxs-lookup"><span data-stu-id="4ba5b-142">[Additional features](4-data-integration-admin.md#templates) for templates will expand this capability to end customers as well.</span></span>
