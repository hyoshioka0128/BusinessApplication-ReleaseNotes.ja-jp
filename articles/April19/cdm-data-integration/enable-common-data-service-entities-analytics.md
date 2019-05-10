---
title: 分析用 Common Data Service エンティティの有効化
description: 分析用 Common Data Service エンティティの有効化
author: sabinn-msft
ms.date: 04/22/2019
ms.topic: article
ms.service: business-applications
ms.author: sabinn
ms.reviewer: deonhe
ms.openlocfilehash: e8f3af8998d794319b92e11e46b9e7004fcdf80c
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225148"
---
# <a name="enable-common-data-service-entities-for-analytics"></a><span data-ttu-id="f79b2-103">分析用 Common Data Service エンティティの有効化</span><span class="sxs-lookup"><span data-stu-id="f79b2-103">Enable Common Data Service entities for analytics</span></span>
[!include[cdm-data-integration banner](../includes/cdm-data-integration.md)]



<span data-ttu-id="f79b2-104">Microsoft は、顧客が Common Data Service 内のデータに基づいて包括的な分析情報を取得し、ビジネス アクションを推進できるようにすることをビジョンとして掲げています。</span><span class="sxs-lookup"><span data-stu-id="f79b2-104">Our vision is to empower our customers to gain comprehensive insights and drive business actions based on their data in Common Data Service.</span></span> <span data-ttu-id="f79b2-105">これを達成するために、分析を実行してデータからインテリジェンスを抽出するには、データを Azure Data Lake にプッシュする必要があります。これにより、Azure Storage の基本的な可用性、セキュリティ、持続性の機能と共に、クラス最高の分析パフォーマンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="f79b2-105">To be able to achieve this, to run analytics and extract intelligence from your data, there is a need to push the data to Azure Data Lake, which enables best-in-class analytics performance along with the fundamental availability, security, and durability capabilities of Azure Storage.</span></span> <span data-ttu-id="f79b2-106">この取り組みによって、Common Data Service から Azure Data Lake にデータをプッシュしてファースト パーティの分析アプリで豊富な分析機能を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="f79b2-106">With this effort, we will enable first-party analytics apps to run rich analytics by pushing data from Common Data Service to Azure Data Lake.</span></span> <span data-ttu-id="f79b2-107">さらに、顧客が既存の Azure Data Lake を自分の Common Data Service 環境にリンクできる、自分のレイクの持ち込み/自分のストレージの持ち込み機能もサポートされます。</span><span class="sxs-lookup"><span data-stu-id="f79b2-107">Additionally, we will also support Bring your own lake/Bring your own storage functionality where customers can link their existing Azure Data Lake to their Common Data Service environment.</span></span> <span data-ttu-id="f79b2-108">これにより顧客は、自分の Common Data Service データに対して豊富な分析機能を実行できます。</span><span class="sxs-lookup"><span data-stu-id="f79b2-108">This will enable customers to run rich analytics on their Common Data Service data.</span></span>

<span data-ttu-id="f79b2-109">![Common Data Service から ADLS へ](media/enable-common-data-service-entities-analytics.jpg "Common Data Service から ADLS への図")</span><span class="sxs-lookup"><span data-stu-id="f79b2-109">![Common Data Service to ADLS](media/enable-common-data-service-entities-analytics.jpg "Common Data Service to ADLS image")</span></span>

## <a name="extract-intelligence-from-your-common-data-service-data-through-first-party-analytics-apps"></a><span data-ttu-id="f79b2-110">ファースト パーティの分析アプリを介して Common Data Service データからインテリジェンスを抽出する</span><span class="sxs-lookup"><span data-stu-id="f79b2-110">Extract intelligence from your Common Data Service data through first-party analytics apps</span></span>

<span data-ttu-id="f79b2-111">顧客との完全な対話履歴に関心のある営業担当者や、自分のチームに関する分析情報を必要としている営業マネージャー、ケースの傾向に関する分析情報を活用してニーズを予測しパフォーマンスを向上したいと考えている顧客サービス マネージャーは、Dynamics 365 Customer Insights、Sales Insights、Customer Service Insights などのファースト パーティの分析アプリを使用して目的を達成できます。</span><span class="sxs-lookup"><span data-stu-id="f79b2-111">If you are a salesperson interested in the complete interaction history of a customer, a sales manager looking to gain insights into your team, or a customer service manager looking to anticipate needs and improve performance with insights into case trends, our first-party analytics apps such as Dynamics 365 Customer Insights, Sales Insights, and Customer Service Insights lets you do just that.</span></span>  <span data-ttu-id="f79b2-112">この機能は、Azure Data Lake に Common Data Service のデータを補給して、ファースト パーティの分析アプリを強化することによって豊富な分析情報を利用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="f79b2-112">This feature lets you hydrate Azure Data Lake with your Common Data Service data to avail of rich insights driven by empowering first-party analytics apps.</span></span>

## <a name="frictionless-experience-to-connect-and-hydrate-your-azure-data-lake-storage"></a><span data-ttu-id="f79b2-113">Azure Data Lake Storage を接続してデータを補給するためのスムーズなエクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="f79b2-113">Frictionless experience to connect and hydrate your Azure Data Lake Storage</span></span> 

<span data-ttu-id="f79b2-114">この機能では、簡単に自分の Azure Data Lake を持ち込み (または作成して)、自分の Common Data Service 環境にリンクして、レイクにデータを補給する Common Data Service エンティティを選択することができます。</span><span class="sxs-lookup"><span data-stu-id="f79b2-114">With this feature, you can easily bring your own Azure Data Lake (or, we will create one for you), link to your Common Data Service environment, and select Common Data Service entities to hydrate the lake.</span></span> <span data-ttu-id="f79b2-115">これにより、Power BI やその他の強力な分析および機械学習サービスを使用して充実したレポートを作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="f79b2-115">This gives you the ability to create rich reports using Power BI and other powerful analytics and Machine Learning services.</span></span>  

## <a name="support-for-initial-and-incremental-writes"></a><span data-ttu-id="f79b2-116">初期書き込みと増分書き込みのサポート</span><span class="sxs-lookup"><span data-stu-id="f79b2-116">Support for initial and incremental writes</span></span>  

<span data-ttu-id="f79b2-117">この機能を使用すると、既存および増分の Common Data Service データをレイクに書き込むことができます。</span><span class="sxs-lookup"><span data-stu-id="f79b2-117">This feature enables writing existing and incremental Common Data Service data to the lake.</span></span> <span data-ttu-id="f79b2-118">顧客は更新のたびにデータ全体をコピーしたくないと考えており、増分データ更新に関するこの重要な要請をサポートすることはきわめて重要です。</span><span class="sxs-lookup"><span data-stu-id="f79b2-118">Customers don’t want a full copy of their data at every refresh and it is imperative that we support this critical ask for incremental data refreshes.</span></span>  

## <a name="support-for-data-and-metadata-changes-in-the-azure-data-lake"></a><span data-ttu-id="f79b2-119">Azure Data Lake でのデータとメタデータの変更のサポート</span><span class="sxs-lookup"><span data-stu-id="f79b2-119">Support for data and metadata changes in the Azure Data Lake</span></span> 

<span data-ttu-id="f79b2-120">あらゆるビジネスにおいて、データは絶えず変化しています。そこで Microsoft では、CRUD (作成、読み取り、更新、削除) 操作のサポートと共に、データとメタデータの変更を Azure Data Lake に反映するための完全なサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="f79b2-120">We understand that, with every business, data is constantly changing, and we will provide complete support for data and metadata changes to propagate to the Azure Data Lake along with support for CRUD (Create Read Update Delete) operations.</span></span> 
