---
title: Power BI データフローの一般提供
description: Power BI データフローの一般提供
author: antonfrMSFT
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.reviewer: mihart
ms.openlocfilehash: 837c7f1bee2a74ba2e40ecc99b8a0a71ddf66609
ms.sourcegitcommit: e9ae36f4f7ff145fcdc3d3ebfb2080fc33083f69
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2019
ms.locfileid: "849659"
---
# <a name="general-availability-of-power-bi-dataflows"></a><span data-ttu-id="1df78-103">Power BI データフローの一般提供</span><span class="sxs-lookup"><span data-stu-id="1df78-103">General availability of Power BI dataflows</span></span>
[!include[business-intelligence banner](../../../includes/business-intelligence.md)]


<span data-ttu-id="1df78-104">Power BI では、異なるソースのデータを統合し、それらをモデリング用に準備する作業を支援するために、データフローが導入されました。</span><span class="sxs-lookup"><span data-stu-id="1df78-104">Power BI introduces dataflows to help organizations unify data from disparate sources and prepare it for modeling.</span></span> <span data-ttu-id="1df78-105">アナリストは、使い慣れたセルフサービス ツールを使用してデータフローを簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="1df78-105">Analysts can easily create dataflows using familiar, self-service tools.</span></span> <span data-ttu-id="1df78-106">データフローは、データ ソース接続、ETL (抽出、変換、読み込み) ロジック、更新スケジュールなどを定義して、ビッグデータの取り込み、変換、統合、エンリッチを行うために使用されます。</span><span class="sxs-lookup"><span data-stu-id="1df78-106">Dataflows are used to ingest, transform, integrate, and enrich big data by defining data source connections, ETL (extract, transform, load) logic, refresh schedules, and more.</span></span> <span data-ttu-id="1df78-107">データは、Azure Data Lake Storage Gen2 で、Common Data Model に準拠したフォルダー内のエンティティとして保存されます。</span><span class="sxs-lookup"><span data-stu-id="1df78-107">Data is stored as entities in Common Data Model-compliant folders in Azure Data Lake Storage Gen2.</span></span> <span data-ttu-id="1df78-108">データフローは、Power BI サービスを使用して、アプリ ワークスペース内で作成および管理されます。</span><span class="sxs-lookup"><span data-stu-id="1df78-108">Dataflows are created and managed in app workspaces by using the Power BI service.</span></span>   

<span data-ttu-id="1df78-109">ユーザーはデータフローを使用して、サポートされているオンプレミスやクラウドベースのさまざまなデータ ソース (Dynamics 365、Salesforce、Azure SQL Database、Excel、SharePoint など) からデータを取り込むことができます。</span><span class="sxs-lookup"><span data-stu-id="1df78-109">You can use dataflows to ingest data from a large and growing set of supported on-premises and cloud-based data sources, including Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, and more.</span></span>

<span data-ttu-id="1df78-110">またその後、データを既知の Common Data Model エンティティにマップし、既存のエンティティを変更および拡張して、ユーザー定義エンティティを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="1df78-110">You can then map data to known Common Data Model entities, modify and extend existing entities, and create custom entities.</span></span> <span data-ttu-id="1df78-111">上級ユーザーは、コーディングを一切 (またはほとんど) 必要としないセルフサービスの組み込み Power Query 作成エクスペリエンスを通じて、完全にカスタマイズされたデータフローを作成することができます。これは、数百万人の Power BI Desktop ユーザーや Excel ユーザーが既に知っている Power Query と同様のエクスペリエンスです。</span><span class="sxs-lookup"><span data-stu-id="1df78-111">Advanced users can create fully customized dataflows using a self-service, low-code/no-code, built-in Power Query authoring experience, similar to the Power Query experience that millions of Power BI Desktop and Excel users already know.</span></span>  

<span data-ttu-id="1df78-112">データフローを作成したら、Power BI Desktop と Power BI サービスを使用して、Common Data Model のパワーを活用したデータセット、レポート、ダッシュボード、およびアプリを作成し、ビジネス活動に関する、より詳細な分析情報を取得することができます。</span><span class="sxs-lookup"><span data-stu-id="1df78-112">Once you’ve created a dataflow, you can use Power BI Desktop and the Power BI service to create datasets, reports, dashboards, and apps that leverage the power of the Common Data Model to drive deep insights into your business activities.</span></span> 

<span data-ttu-id="1df78-113">データフローの更新スケジュールは、データセットと同様、データフローが作成されたワークスペースから直接管理されます。</span><span class="sxs-lookup"><span data-stu-id="1df78-113">Dataflow refresh scheduling is managed directly from the workspace in which your dataflow was created, just like your datasets.</span></span> 

<span data-ttu-id="1df78-114">Power BI のデータフローには、一般的なデータ ソースへのコネクタが 40 以上含まれています (Excel、SQL Server、Oracle、Azure SQL Data Warehouse、Dynamics 365、Salesforce など)。</span><span class="sxs-lookup"><span data-stu-id="1df78-114">Power BI dataflows include more than 40 connectors to common data sources such as Excel, SQL Server, Oracle, Azure SQL Data Warehouse, Dynamics 365, and Salesforce.</span></span> 

[!include[feedback](../../includes/service-feedback.md)]