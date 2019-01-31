---
title: Power BI サービス
description: Power BI は、あらゆる規模の組織がデータを活用してビジネスを変革するのを支援しています。
author: HaydnR
manager: ArunUlag
ms.date: 7/22/2018
ms.assetid: 4af9556c-2ed1-4737-b601-d330a2d6df88
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: haydnr
audience: ''
ms.openlocfilehash: 49ef3af21be65a76b9a3ac9776b7d32715731011
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199235"
---
# <a name="power-bi-service"></a><span data-ttu-id="11649-103">Power BI サービス</span><span class="sxs-lookup"><span data-stu-id="11649-103">Power BI service</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="11649-104">2018 年 10 月リリースで提供される新機能は、主に 2 つの領域に分類できます。ビッグデータの処理とエンタープライズ BI です。</span><span class="sxs-lookup"><span data-stu-id="11649-104">The October '18 release brings new capabilities in two primary areas: Working with big data and enterprise BI.</span></span>

### <a name="working-with-big-data"></a><span data-ttu-id="11649-105">ビッグデータの操作</span><span class="sxs-lookup"><span data-stu-id="11649-105">Working with big data</span></span>

-   <span data-ttu-id="11649-106">**Common Data Model の利用開始** – Power BI では、Microsoft によって公開された Common Data Model がサポートされます。これは、標準でありながらも拡張可能な、ビジネス アプリケーション用のデータ スキーマ コレクション (エンティティ、属性、リレーションシップ) です。</span><span class="sxs-lookup"><span data-stu-id="11649-106">**Starting with the Common Data Model** – Power BI supports the Common Data Model, published by Microsoft, that provides a standard yet extensible collection of data schemas (entities, attributes and relationships) for business applications.</span></span> <span data-ttu-id="11649-107">ユーザーは、標準スキーマを使用することもできますし、独自のニーズに基づいてスキーマをカスタマイズすることもできます。これにより、他のデータ ソース (Microsoft やサードパーティのソース) によってデータをエンリッチする作業を簡略化し、分析を迅速化することができます。</span><span class="sxs-lookup"><span data-stu-id="11649-107">Users can take advantage of a standard schema – or customize it based on their unique needs – to simplify how they enrich their data with other data sources, from Microsoft and third parties, to accelerate analysis.</span></span>

-   <span data-ttu-id="11649-108">**ビッグデータに対応したセルフサービスのデータ準備** – Microsoft では、ビッグデータからの分析情報取得を支援する新機能によって、Power BI でのセルフサービス データ準備を拡張しています。</span><span class="sxs-lookup"><span data-stu-id="11649-108">**Self-service data prep for big data** – We’re expanding self-service data prep in Power BI with new capabilities to help business analysts extract insights from big data.</span></span> <span data-ttu-id="11649-109">ビジネス アナリストは、Power BI Desktop や Excel の数百万人ものユーザーが使い慣れている、Power Query のエクスペリエンスを使用して、データの取り込み、変換、統合を行い、Power BI でデータをエンリッチすることができます。サポートされるデータ ソース (オンプレミスおよびクラウドベース) は幅広く、継続的に拡大されています (Dynamics 365、Salesforce、Azure SQL Data Warehouse、Excel、SharePoint など)。</span><span class="sxs-lookup"><span data-stu-id="11649-109">Using the Power Query experience already familiar to millions of Power BI Desktop and Excel users, business analysts can ingest, transform, integrate, and enrich big data with Power BI – including data from a large and growing set of supported on-premises and cloud-based data sources, such as Dynamics 365, Salesforce, Azure SQL Data Warehouse, Excel, and SharePoint.</span></span> <span data-ttu-id="11649-110">ユーザーは、データを既知のエンティティに直接マップしたり、既存のエンティティを変更して拡張したり、ユーザー定義エンティティを作成することができます。またそれらの作業はすべて、Power BI 内で行うことができます。</span><span class="sxs-lookup"><span data-stu-id="11649-110">Users can directly map data to known entities, modify and extend existing entities, or create custom entities all within Power BI.</span></span>
 
-   <span data-ttu-id="11649-111">**Azure を使用した高度な分析と AI** - Power BI と Azure Data Lake Storage との間でのデータ アクセスを統合することで、ロール間でのコラボレーションを強化しています。</span><span class="sxs-lookup"><span data-stu-id="11649-111">**Advanced analytics and AI with Azure** – We’re fueling collaboration across roles by unifying access to data between Power BI and Azure Data Lake Storage.</span></span> <span data-ttu-id="11649-112">ビジネス アナリストは、Power BI のセルフサービス機能を使用して、Azure Data Lake Storage に格納されたデータをシームレスに操作することができます。また、データ エンジニア、データ サイエンティスト、およびその他のユーザーは、補助となる Azure Data Services (Azure Data Factory、Azure Databricks、Azure Machine Learning など) の高度な分析機能や AI を使用して、分析情報へのアクセスを拡張できます。</span><span class="sxs-lookup"><span data-stu-id="11649-112">Business analysts can seamlessly operate on data stored in Azure Data Lake Storage with the self-service capabilities in Power BI, while data engineers, data scientists, and other users can extend access to insights with advanced analytics and AI from complementary Azure data services like Azure Data Factory, Azure Databricks, and Azure Machine Learning.</span></span> <span data-ttu-id="11649-113">たとえば、データ エンジニアは、データの追加、エンリッチ、オーケストレーションを行うことができますし、データ サイエンティストは、機械学習モデルを作成することができます。またビジネス アナリストは、他のユーザーの成果物や、Azure Data Lake Storage のデータを利用しながら、Power BI のセルフサービス ツールを使用して、分析情報を幅広く構築し、共有することができます。</span><span class="sxs-lookup"><span data-stu-id="11649-113">For example, data engineers can add, enrich, and orchestrate data; data scientists can build machine learning models; and business analysts can benefit from the work of others and the data available in Azure Data Lake Storage while continuing to use the self-service tools in Power BI to build and share insights broadly.</span></span>

### <a name="enterprise-bi"></a><span data-ttu-id="11649-114">エンタープライズ BI</span><span class="sxs-lookup"><span data-stu-id="11649-114">Enterprise BI</span></span>

-   <span data-ttu-id="11649-115">**Enterprise reporting** – 今回のリリースでは、人気と信頼性を兼ね備えた SQL Server Reporting Services テクノロジーを、Power BI で使用できるようになりました。これにより、統合性とセキュリティに優れたエンタープライズ規模のレポート プラットフォームを、あらゆるユーザーやデバイス向けに提供できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="11649-115">**Enterprise reporting** – Popular and proven SQL Server Reporting Services technology is now part of Power BI, creating a unified, secure, enterprisewide reporting platform accessible to any user across devices.</span></span> <span data-ttu-id="11649-116">また、ピクセル パーフェクトなページ付けされたレポートを、Power BI の既存の対話型レポートと一緒に使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="11649-116">Pixel-perfect paginated reports can now be included alongside Power BI’s existing interactive reports.</span></span>
  
-   <span data-ttu-id="11649-117">**展開先の拡充** – 展開の柔軟度が改善され、Power BI を展開できる地域が追加されたため、データをユーザーの近くに配置して、パフォーマンスを最適化すると共に、データの所在地要件に準拠することができます。</span><span class="sxs-lookup"><span data-stu-id="11649-117">**Multiple geographies** – New flexibility to deploy Power BI in specific global regions enables organizations to keep data close to users for optimal performance and to meet data residency requirements.</span></span>

-   <span data-ttu-id="11649-118">**エンタープライズ規模の BI モデル** – Microsoft では、SQL Server Analysis Services の全機能を Power BI に統合すると共に、セマンティック BI モデルに対応した拡張性の高いプラットフォームによって、サービスを拡張しています。</span><span class="sxs-lookup"><span data-stu-id="11649-118">**Enterprise-scale BI models** – We’re integrating the full power of SQL Server Analysis Services into Power BI, expanding the service with a highly scalable platform for semantic BI models.</span></span> <span data-ttu-id="11649-119">お客様は、独自のコンプライアンス要件に準拠しながら、高速性と可用性に優れた、管理しやすいレポートをユーザーに提供できます。</span><span class="sxs-lookup"><span data-stu-id="11649-119">Organizations can provide users with reports that are fast, highly available, and easy to manage, while aligning with their unique compliance requirements.</span></span> <span data-ttu-id="11649-120">また Power BI では、増分更新や集約機能を使用することで、大量のデータに対するクエリを実行しながらも、迅速でインタラクティブなユーザー エクスペリエンスを維持することができます。</span><span class="sxs-lookup"><span data-stu-id="11649-120">And with incremental refresh and aggregation capabilities, Power BI can query large amounts of data, while still enabling quick, interactive user experiences.</span></span>

-   <span data-ttu-id="11649-121">**アプリケーション ライフサイクル管理 (ALM)** – エンタープライズ グレードのライフサイクル管理に対応した新機能のほか、XMLA プロトコルを通じたデータセット用の API も完全サポートされたため、お客様はさまざまなサードパーティ BI ツールを Power BI に接続して、統合型のエンタープライズ セマンティック モデル リポジトリを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="11649-121">**Application lifecycle management (ALM)** – New capabilities for enterprise-grade lifecycle management, as well as full API support for datasets through the XMLA protocol to help customers connect a variety of third-party BI tools to Power BI to create a unified enterprise semantic model repository.</span></span>
