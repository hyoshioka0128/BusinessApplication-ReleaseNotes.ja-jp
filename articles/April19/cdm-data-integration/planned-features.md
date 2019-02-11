---
title: Common Data Model とデータ統合の新機能と予定されている機能 (2019 年 4 月)
description: Common Data Model とデータ統合の新機能の概要
author: theresapalmer
ms.date: 01/21/2019
ms.assetid: 5f0ee2c1-29a8-4aa1-abd9-a0f4ab7018ad
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
ms.reviewer: deonhe
ms.openlocfilehash: 148cf2349ab60389022211e13b3ffc22be6e58b7
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210792"
---
# <a name="whats-new-and-planned-for-common-data-model-and-data-integration"></a><span data-ttu-id="8cc0a-103">Common Data Model とデータ統合の新機能と予定されている機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-103">What’s new and planned for Common Data Model and Data Integration</span></span>

<span data-ttu-id="8cc0a-104">このトピックでは、2019 年 4 月から 2019 年 9 月の間にリリースが計画されている機能の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-104">This topic lists features that are planned to release between April and September 2019.</span></span> <span data-ttu-id="8cc0a-105">一部の機能のプレビューは 2019 年 2 月に開始されます。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-105">Previews for some features will start in February 2019.</span></span>  

<span data-ttu-id="8cc0a-106">リリース ノートで説明されている機能は、まだリリースされていない場合があります。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-106">These release notes describe functionality that may not have been released yet.</span></span> <span data-ttu-id="8cc0a-107">提供タイムラインおよび予定されている機能は、変更される可能性、または出荷されない可能性があります ([Microsoft ポリシー](https://go.microsoft.com/fwlink/p/?linkid=2007332)を参照)。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-107">Delivery timelines and projected functionality may change or may not ship (see [Microsoft policy](https://go.microsoft.com/fwlink/p/?linkid=2007332)).</span></span>

<span data-ttu-id="8cc0a-108">**日付**列で月が使用されている場合、機能はその月に配信されます。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-108">When a month is used in the **Date** column, the feature will be delivered sometime within that month.</span></span> <span data-ttu-id="8cc0a-109">配布日は、その月の最初の日だけでなく、その月の任意の日にすることができます。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-109">The delivery date can be any day within that month, not just on the first day of the month.</span></span>

<span data-ttu-id="8cc0a-110">Dynamics 365 ビジネス アプリケーションを利用できる地域の一覧については、[ご利用いただける国と地域に関するガイド](https://aka.ms/dynamics_365_international_availability_deck)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-110">For a list of the regions where Dynamics 365 business applications are available, see the [International availability guide](https://aka.ms/dynamics_365_international_availability_deck).</span></span>

<span data-ttu-id="8cc0a-111">2019 年 4 月リリースには、Power Query、コネクタ プラットフォーム、拡張性、Common Data Model (CDM)、二重書き込み (Common Data Service for Apps へのリンク)、CDS データ インテグレーター、データ エクスポート サービス、データ統合テンプレート、ゲートウェイの分野において、4 つのテーマがあります。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-111">The April '19 release has four themes for these areas: Power Query, Connector Platform and Extensibility, Common Data Model (CDM), Dual Write (Link to Common Data Service for Apps), CDS Data Integrator, Data Export Service, Data Integration Templates, and Gateway.</span></span>

## <a name="power-query-desktop"></a><span data-ttu-id="8cc0a-112">Power Query デスクトップ</span><span class="sxs-lookup"><span data-stu-id="8cc0a-112">Power Query Desktop</span></span>

| <span data-ttu-id="8cc0a-113">分野</span><span class="sxs-lookup"><span data-stu-id="8cc0a-113">Area</span></span>                                           | <span data-ttu-id="8cc0a-114">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-114">Feature</span></span>                                                               | <span data-ttu-id="8cc0a-115">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-115">Release type</span></span>         | <span data-ttu-id="8cc0a-116">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-116">Date</span></span> |
|------------------------------------------------|-----------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-117">改善された新しいコネクタ</span><span class="sxs-lookup"><span data-stu-id="8cc0a-117">New and enhanced connectors</span></span>](./power-query.md#high-enterprise-value-connectors-become-generally-available-for-power-bi-customers)                    | <span data-ttu-id="8cc0a-118">Microsoft では PDF、AtScale、Essbase、IBM DB2 DirectQuery 用のコネクタに取り組んでいます。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-118">We're working on connectors for PDF, AtScale, Essbase, and IBM DB2 DirectQuery.</span></span> <br/>| <span data-ttu-id="8cc0a-119">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-119">General Availability</span></span> <br/> | <br/><span data-ttu-id="8cc0a-120">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-120">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-121">改善された新しいデータ準備機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-121">New and enhanced data preparation capabilities</span></span>](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities) | <span data-ttu-id="8cc0a-122">お客様からのフィードバックに基づいて、Power Query デスクトップの "Smart Data Prep" 機能を改善し、6 か月のうちに一般提供を開始します。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-122">Based on customer feedback, we’ll improve "Smart Data Prep" Power Query Desktop features and make them generally available over the next six months.</span></span> <br/>| <span data-ttu-id="8cc0a-123">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-123">General Availability</span></span> <br/>| <br><span data-ttu-id="8cc0a-124">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-124">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-125">接続プラットフォーム</span><span class="sxs-lookup"><span data-stu-id="8cc0a-125">Connectivity Platform</span></span>](./power-query.md#Increased-support-for-developers-on-the-Power-Query-platform)                          | <span data-ttu-id="8cc0a-126">開発者署名のカスタム コネクタへのサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-126">We're adding support for developer-signed custom connectors.</span></span>                        | <span data-ttu-id="8cc0a-127">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-127">Public Preview</span></span>       | <span data-ttu-id="8cc0a-128">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-128">April 2019</span></span>           |


## <a name="power-query-online"></a><span data-ttu-id="8cc0a-129">Power Query オンライン</span><span class="sxs-lookup"><span data-stu-id="8cc0a-129">Power Query Online</span></span>

|<span data-ttu-id="8cc0a-130">分野</span><span class="sxs-lookup"><span data-stu-id="8cc0a-130">Area</span></span>          | <span data-ttu-id="8cc0a-131">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-131">Feature</span></span>                   | <span data-ttu-id="8cc0a-132">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-132">Release type</span></span>         | <span data-ttu-id="8cc0a-133">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-133">Date</span></span> |
|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-134">改善された新しいデータ取得機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-134">New and enhanced get data capabilities</span></span>](power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                             | <span data-ttu-id="8cc0a-135">Power Query オンラインにデータを入力またはコピーして貼り付けてテーブルを作成し、Power Query オンラインのファイル ソースに接続するときに OneDrive for Business を参照できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-135">We're making it possible to create tables by typing or copy-pasting data into Power Query Online and to browse OneDrive for Business when connecting to file sources in Power Query Online.</span></span>                                                                     | <span data-ttu-id="8cc0a-136">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-136">General Availability</span></span> | <span data-ttu-id="8cc0a-137">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-137">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-138">SAP データ接続</span><span class="sxs-lookup"><span data-stu-id="8cc0a-138">SAP data connectivity</span></span>](./power-query.md#high-enterprise-value-connectors-become-generally-available-for-power-bi-customers) | <span data-ttu-id="8cc0a-139">発行済みのレポートについて、PowerBI.com での SAP HANA や BW の変数の修正をサポートします。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-139">Support for modifying SAP HANA and BW variables in PowerBI.com for a published report.</span></span>                                                                         | <span data-ttu-id="8cc0a-140">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-140">Public Preview</span></span>       | <span data-ttu-id="8cc0a-141">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-141">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-142">新しいデータ コネクタ</span><span class="sxs-lookup"><span data-stu-id="8cc0a-142">New data connectors</span></span>](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                                | <span data-ttu-id="8cc0a-143">Microsoft では、Amazon Redshift、Impala、Apache Spark、HDInsight Spark、HDInsight Hive Interactive Query、Vertica、Google BigQuery、Teradata、Informix、Sybase、MySQL、PostgreSQL 用の新しいデータ コネクタの作成に取り組んでいます。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-143">We're working on new data connectors, including Amazon Redshift, Impala, Apache Spark, HDInsight Spark, HDInsight Hive Interactive Query, Vertica, Google BigQuery, Teradata, Informix, Sybase, MySQL, and PostgreSQL.</span></span> | <span data-ttu-id="8cc0a-144">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-144">Public Preview</span></span>       | <span data-ttu-id="8cc0a-145">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-145">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-146">基礎とコンプライアンス</span><span class="sxs-lookup"><span data-stu-id="8cc0a-146">Fundamentals and compliance</span></span>](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                          | <span data-ttu-id="8cc0a-147">新しい地域や GCC での Power Query オンラインのサポート。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-147">Power Query Online support in new regions and GCC.</span></span>                                                                                                           | <span data-ttu-id="8cc0a-148">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-148">Public Preview</span></span>       | <span data-ttu-id="8cc0a-149">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-149">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-150">CDM スキーマへのエンティティのマッピング</span><span class="sxs-lookup"><span data-stu-id="8cc0a-150">Mapping entities to CDM schema</span></span>](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                     | <span data-ttu-id="8cc0a-151">Power Query オンライン データ統合を介して新しいエンティティを作成するときの CDS for Apps のデータ型のマッピングのサポートや、CDM スキーマにエンティティをマッピングするときのエンティティの参照エクスペリエンスの改善が含まれています。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-151">Includes support for mapping to CDS for Apps data types when creating new entities via Power Query Online Data Integration and improved experiences for browsing entities when mapping entities to CDM schema.</span></span> | <span data-ttu-id="8cc0a-152">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-152">Public Preview</span></span>       | <span data-ttu-id="8cc0a-153">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-153">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-154">Common Data Service for Apps</span><span class="sxs-lookup"><span data-stu-id="8cc0a-154">Common Data Service for Apps</span></span>](./power-query.md#power-query-online-adds-several-new-data-connectivity-and-preparation-capabilities)                                                       | <span data-ttu-id="8cc0a-155">Power Query オンライン データ統合を介して新しいエンティティを作成するときのナチュラル キーを使用したルックアップのインポートのサポートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="8cc0a-155">Includes support for lookup import using natural keys when creating new entities via Power Query Online Data Integration.</span></span>                                             | <span data-ttu-id="8cc0a-156">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-156">Public Preview</span></span>       | <span data-ttu-id="8cc0a-157">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-157">April 2019</span></span>           |

## <a name="common-data-model"></a><span data-ttu-id="8cc0a-158">Common Data Model</span><span class="sxs-lookup"><span data-stu-id="8cc0a-158">Common Data Model</span></span>

| <span data-ttu-id="8cc0a-159">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-159">Feature</span></span>                                                                                                                                                    | <span data-ttu-id="8cc0a-160">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-160">Release type</span></span>         | <span data-ttu-id="8cc0a-161">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-161">Date</span></span> |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-162">Common Data Model を使用して開発するための最新の資料とクイックスタート ガイド</span><span class="sxs-lookup"><span data-stu-id="8cc0a-162">Updated documentation and quick-start guides for developing with the Common Data Model</span></span>](common-data-model-cdm.md#updated-developer-and-consumer-documentation)                                          | <span data-ttu-id="8cc0a-163">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-163">General Availability</span></span> | <span data-ttu-id="8cc0a-164">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-164">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-165">名前空間とバージョン管理を含む CDM スキーマ文書の拡張</span><span class="sxs-lookup"><span data-stu-id="8cc0a-165">Extensions to CDM schema documents including namespace and versioning</span></span>](common-data-model-cdm.md#cdm-schema-documents)                                                           | <span data-ttu-id="8cc0a-166">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-166">Public Preview</span></span>       | <span data-ttu-id="8cc0a-167">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-167">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-168">CDM スキーマ文書、CDM フォルダー、model.json ファイル用の複数言語の SDK とツール</span><span class="sxs-lookup"><span data-stu-id="8cc0a-168">SDK and tooling in multiple languages for CDM schema documents, CDM folders, and model.json files</span></span>](common-data-model-cdm.md#sdk-and-tooling)                                                                | <span data-ttu-id="8cc0a-169">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-169">Public Preview</span></span>       | <span data-ttu-id="8cc0a-170">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-170">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-171">Finance、Operations、Marketing など人気のある Dynamics オファリングにおける主要なシナリオを対象とした新しい CDM エンティティの定義</span><span class="sxs-lookup"><span data-stu-id="8cc0a-171">New CDM entity definitions covering key scenarios from popular Dynamics offerings, including Finance, Operations, and Marketing</span></span>](common-data-model-cdm.md#new-entity-definitions) | <span data-ttu-id="8cc0a-172">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-172">Public Preview</span></span>       | <span data-ttu-id="8cc0a-173">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-173">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-174">教育、非営利、小売などの産業ソリューション向けの初期 CDM エンティティ パック</span><span class="sxs-lookup"><span data-stu-id="8cc0a-174">CDM entity packs for industry solutions such as education, non-profit, and retail</span></span>](common-data-model-cdm.md#new-entity-definitions)                                               | <span data-ttu-id="8cc0a-175">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-175">Public Preview</span></span>       | <span data-ttu-id="8cc0a-176">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-176">April 2019</span></span>           |


## <a name="dual-write-link-to-common-data-service-for-apps"></a><span data-ttu-id="8cc0a-177">二重書き込み (Common Data Service for Apps へのリンク)</span><span class="sxs-lookup"><span data-stu-id="8cc0a-177">Dual Write (Link to Common Data Service for Apps)</span></span>

| <span data-ttu-id="8cc0a-178">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-178">Feature</span></span>                                                                                                | <span data-ttu-id="8cc0a-179">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-179">Release type</span></span>   | <span data-ttu-id="8cc0a-180">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-180">Date</span></span> |
|--------------------------------------------------------------------------------------------------------|----------------|----------------------|
| [<span data-ttu-id="8cc0a-181">CDS 内の Dynamics 365 for Finance and Operations データを取得して最新に保つ</span><span class="sxs-lookup"><span data-stu-id="8cc0a-181">Get your Dynamics 365 Finance and Operations data in CDS and keep it up to date</span></span>](dual-write-link-common-data-service-apps.md) | <span data-ttu-id="8cc0a-182">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-182">Public Preview</span></span> | <span data-ttu-id="8cc0a-183">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-183">April 2019</span></span>           |


## <a name="cds-data-integrator"></a><span data-ttu-id="8cc0a-184">CDS データ インテグレーター</span><span class="sxs-lookup"><span data-stu-id="8cc0a-184">CDS Data Integrator</span></span>

| <span data-ttu-id="8cc0a-185">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-185">Feature</span></span>                                                                            | <span data-ttu-id="8cc0a-186">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-186">Release type</span></span>   | <span data-ttu-id="8cc0a-187">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-187">Date</span></span> |
|------------------------------------------------------------------------------------|----------------|----------------------|
| [<span data-ttu-id="8cc0a-188">データ インテグレーター用の SDK</span><span class="sxs-lookup"><span data-stu-id="8cc0a-188">SDK for Data Integrator</span></span>](cds-data-integrator.md#sdk-for-data-integrator)                             | <span data-ttu-id="8cc0a-189">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-189">Public Preview</span></span> | <span data-ttu-id="8cc0a-190">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-190">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-191">エラー処理、プロジェクト管理、トラブルシューティングの改善</span><span class="sxs-lookup"><span data-stu-id="8cc0a-191">Enhancements for error handling, project management, and troubleshooting</span></span>](cds-data-integrator.md#enhancements-in-project-management-error-handling-and-troubleshooting)   | <span data-ttu-id="8cc0a-192">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-192">Public Preview</span></span> | <span data-ttu-id="8cc0a-193">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-193">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-194">テンプレートの更新をプロジェクトに反映する機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-194">Ability to propagate template updates to projects</span></span>](cds-data-integrator.md#enhancements-in-project-management-error-handling-and-troubleshooting)                                  | <span data-ttu-id="8cc0a-195">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-195">Public Preview</span></span> | <span data-ttu-id="8cc0a-196">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-196">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-197">GCC 準拠のデータ インテグレーター</span><span class="sxs-lookup"><span data-stu-id="8cc0a-197">Data integrator is GCC compliant</span></span>](cds-data-integrator.md#compliance-for-government-cloud)                    | <span data-ttu-id="8cc0a-198">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-198">Public Preview</span></span> | <span data-ttu-id="8cc0a-199">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-199">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-200">大規模な統合と一般的に使用されている統合書き込みパターンに関するパフォーマンス ガイドライン</span><span class="sxs-lookup"><span data-stu-id="8cc0a-200">Performance guidelines for high-volume integration and for commonly used integration write patterns</span></span>](cds-data-integrator.md#guidance-for-performance-tuning-and-integration-write-patterns) | <span data-ttu-id="8cc0a-201">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-201">Public Preview</span></span> | <span data-ttu-id="8cc0a-202">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-202">April 2019</span></span>           |


## <a name="data-export-service"></a><span data-ttu-id="8cc0a-203">データ エクスポート サービス</span><span class="sxs-lookup"><span data-stu-id="8cc0a-203">Data Export Service</span></span>

| <span data-ttu-id="8cc0a-204">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-204">Feature</span></span>                                                                        | <span data-ttu-id="8cc0a-205">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-205">Release type</span></span>         | <span data-ttu-id="8cc0a-206">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-206">Date</span></span> |
|--------------------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-207">Dynamics 365 for Sales (CRM) や Azure SQL からのレコードの数と傾向を表示する</span><span class="sxs-lookup"><span data-stu-id="8cc0a-207">Show count and trends for records from Dynamics 365 for Sales (CRM) and Azure SQL</span></span>](data-export-service.md#trending-insights-that-show-your-records-are-up-to-date)          | <span data-ttu-id="8cc0a-208">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-208">General Availability</span></span> | <span data-ttu-id="8cc0a-209">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-209">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-210">既知の問題を軽減する</span><span class="sxs-lookup"><span data-stu-id="8cc0a-210">Mitigate known issues</span></span>](data-export-service.md#design-changes-to-mitigate-known-issues) | <span data-ttu-id="8cc0a-211">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-211">General Availability</span></span> | <span data-ttu-id="8cc0a-212">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-212">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-213">削除処理の待ち時間を減らしてパフォーマンスを向上させる</span><span class="sxs-lookup"><span data-stu-id="8cc0a-213">Reduce latency and improve perf on processing deletes</span></span>](data-export-service.md#reduce-latency-and-improve-performance)                          | <span data-ttu-id="8cc0a-214">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-214">General Availability</span></span> | <span data-ttu-id="8cc0a-215">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-215">April 2019</span></span>           |


## <a name="data-integration-templates"></a><span data-ttu-id="8cc0a-216">データ統合テンプレート</span><span class="sxs-lookup"><span data-stu-id="8cc0a-216">Data Integration Templates</span></span>

| <span data-ttu-id="8cc0a-217">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-217">Feature</span></span>                                                                                                                                                                                          | <span data-ttu-id="8cc0a-218">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-218">Release type</span></span>         | <span data-ttu-id="8cc0a-219">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-219">Date</span></span> |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-220">新しいテンプレートと既存のテンプレートの更新 (Dynamics 365 for Finance and Operations、Field Service、Project Service、Dynamics 365 for Talent、Salesforce)</span><span class="sxs-lookup"><span data-stu-id="8cc0a-220">New templates and updating existing templates (Dynamics 365 for Finance and Operations, Field Service, Project Service, Dynamics 365 for Talent and Salesforce)</span></span>](cds-data-integrator.md) | <span data-ttu-id="8cc0a-221">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-221">General Availability</span></span> | <span data-ttu-id="8cc0a-222">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-222">April 2019</span></span> |


## <a name="connector-platform-and-extensibility"></a><span data-ttu-id="8cc0a-223">コネクタ プラットフォームと拡張性</span><span class="sxs-lookup"><span data-stu-id="8cc0a-223">Connector Platform and Extensibility</span></span>

| <span data-ttu-id="8cc0a-224">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-224">Feature</span></span>                                                                                                    | <span data-ttu-id="8cc0a-225">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-225">Release type</span></span>         | <span data-ttu-id="8cc0a-226">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-226">Date</span></span> |
|------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-227">PowerApps と Microsoft Flow 用の新しいコネクタと改善されたコネクタ</span><span class="sxs-lookup"><span data-stu-id="8cc0a-227">New and enhanced connectors for PowerApps and Microsoft Flow</span></span>](connector-platform-extensibility.md#new-and-enhanced-connectors-for-powerapps-and-microsoft-flow)                                   | <span data-ttu-id="8cc0a-228">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-228">Public Preview</span></span>       | <span data-ttu-id="8cc0a-229">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-229">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-230">コネクタ開発用の豊富なドキュメントとガイド</span><span class="sxs-lookup"><span data-stu-id="8cc0a-230">Rich documentation and guides for developing connectors</span></span>](connector-platform-extensibility.md#rich-documentation-and-guides-for-developing-connectors)                        | <span data-ttu-id="8cc0a-231">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-231">General Availability</span></span> | <span data-ttu-id="8cc0a-232">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-232">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-233">PowerApps および Microsoft Flow 用のカスタム コネクタ SDK と API</span><span class="sxs-lookup"><span data-stu-id="8cc0a-233">Custom connector SDK and APIs for PowerApps and Microsoft Flow</span></span>](connector-platform-extensibility.md#custom-connector-sdk-and-apis-for-powerapps-and-microsoft-flow)                   | <span data-ttu-id="8cc0a-234">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-234">Public Preview</span></span>       | <span data-ttu-id="8cc0a-235">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-235">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-236">PowerApps および Microsoft Flow 用カスタム コネクタでのポリシー テンプレートのサポート</span><span class="sxs-lookup"><span data-stu-id="8cc0a-236">Support for policy templates in custom connectors for PowerApps and Microsoft Flow</span></span>](connector-platform-extensibility.md#support-for-policy-templates-in-custom-connectors-for-powerapps-and-microsoft-flow) | <span data-ttu-id="8cc0a-237">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-237">Public Preview</span></span>       | <span data-ttu-id="8cc0a-238">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-238">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-239">GitHub での PowerApps および Microsoft Flow 用のオープン ソース コネクタの開発</span><span class="sxs-lookup"><span data-stu-id="8cc0a-239">Open source connector development on GitHub for PowerApps and Microsoft Flow</span></span>](connector-platform-extensibility.md#open-source-connector-development-on-github-for-powerapps-and-microsoft-flow)    | <span data-ttu-id="8cc0a-240">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-240">General Availability</span></span> | <span data-ttu-id="8cc0a-241">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-241">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-242">改善されたコネクタ認定プロセス</span><span class="sxs-lookup"><span data-stu-id="8cc0a-242">Improved connector certification process</span></span>](connector-platform-extensibility.md#improved-certification-process)                               | <span data-ttu-id="8cc0a-243">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-243">General Availability</span></span> | <span data-ttu-id="8cc0a-244">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-244">April 2019</span></span>           |

## <a name="gateway"></a><span data-ttu-id="8cc0a-245">ゲートウェイ</span><span class="sxs-lookup"><span data-stu-id="8cc0a-245">Gateway</span></span>

| <span data-ttu-id="8cc0a-246">機能</span><span class="sxs-lookup"><span data-stu-id="8cc0a-246">Feature</span></span>                                                                                                                      | <span data-ttu-id="8cc0a-247">リリースの種類</span><span class="sxs-lookup"><span data-stu-id="8cc0a-247">Release type</span></span>         | <span data-ttu-id="8cc0a-248">日付</span><span class="sxs-lookup"><span data-stu-id="8cc0a-248">Date</span></span> |
|------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| [<span data-ttu-id="8cc0a-249">OOTB 認定カスタム データ コネクタのサポート (拡張性サポート)</span><span class="sxs-lookup"><span data-stu-id="8cc0a-249">OOTB certified data connectors support (Extensibility support)</span></span>](gateway.md#on-premises-data-gateway-supports-out-of-box-certified-data-connectors)                                 | <span data-ttu-id="8cc0a-250">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-250">Public Preview</span></span> | <span data-ttu-id="8cc0a-251">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-251">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-252">オンプレミスのデータ ソース用の複数の資格情報</span><span class="sxs-lookup"><span data-stu-id="8cc0a-252">Multiple credentials for an on-premises data source</span></span>](gateway.md#on-premises-data-gateway-supports-out-of-box-certified-data-connectors)                                                   | <span data-ttu-id="8cc0a-253">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-253">General Availability</span></span> | <span data-ttu-id="8cc0a-254">2019 年 6 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-254">June 2019</span></span>           |
| [<span data-ttu-id="8cc0a-255">テナント間のゲートウェイ管理</span><span class="sxs-lookup"><span data-stu-id="8cc0a-255">Gateway administration across a tenant</span></span>](gateway.md#gateway-administration-across-a-tenant)                                                    | <span data-ttu-id="8cc0a-256">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-256">General Availability</span></span> | <span data-ttu-id="8cc0a-257">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-257">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-258">ゲートウェイ管理の改善</span><span class="sxs-lookup"><span data-stu-id="8cc0a-258">Gateway management enhancements</span></span>](gateway.md#management-enhancements)                                                        | <span data-ttu-id="8cc0a-259">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-259">Public Preview</span></span> | <span data-ttu-id="8cc0a-260">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-260">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-261">改善された信頼性、サポート性、診断</span><span class="sxs-lookup"><span data-stu-id="8cc0a-261">Improved reliability, supportability, and diagnostics</span></span>](gateway.md#improved-reliability-supportability-and-diagnostics)                                | <span data-ttu-id="8cc0a-262">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-262">General Availability</span></span> | <span data-ttu-id="8cc0a-263">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-263">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-264">SAP BW アプリケーションおよびメッセージ サーバー用の Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP BW シングル サインオン (Kerberos)</span><span class="sxs-lookup"><span data-stu-id="8cc0a-264">SAP BW single sign-on (Kerberos) in Power BI Service (via On-premises data gateway), for SAP BW Application & Message Server</span></span>](gateway.md#sap-bw-single-sign-on-kerberos-in-power-bi-service-via-on-premises-data-gateway-for-sap-bw-application-and-message-server)  | <span data-ttu-id="8cc0a-265">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-265">General Availability</span></span> | <span data-ttu-id="8cc0a-266">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-266">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-267">Power BI サービス内の (オンプレミス データ ゲートウェイ経由の) SAP HANA シングル サインオン (SAML)</span><span class="sxs-lookup"><span data-stu-id="8cc0a-267">SAP HANA single sign-on (SAML) in Power BI Service (via On-premises data gateway)</span></span>](gateway.md#sap-hana-single-sign-on-saml-in-power-bi-service-via-on-premises-data-gateway)                                            | <span data-ttu-id="8cc0a-268">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cc0a-268">General Availability</span></span> | <span data-ttu-id="8cc0a-269">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-269">April 2019</span></span>           |
| [<span data-ttu-id="8cc0a-270">開発者署名のカスタム コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="8cc0a-270">Support for developer-signed custom connectors</span></span>](gateway.md)                                                                               | <span data-ttu-id="8cc0a-271">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cc0a-271">Public Preview</span></span>       | <span data-ttu-id="8cc0a-272">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8cc0a-272">April 2019</span></span>           |