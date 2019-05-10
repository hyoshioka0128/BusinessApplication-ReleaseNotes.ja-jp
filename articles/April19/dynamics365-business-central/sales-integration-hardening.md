---
title: Business Central と Dynamics 365 for Sales の統合の強化
description: Business Central と Dynamics 365 for Sales の統合の改善
author: ikoletic
ms.reviewer: edupont
ms.date: 02/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.author: ivkoleti
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.openlocfilehash: 42f167b4ecd06b350f7e91065a06236890960b03
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225388"
---
# <a name="hardening-the-integration-between-business-central-and-dynamics-365-for-sales"></a><span data-ttu-id="52ed2-103">Business Central と Dynamics 365 for Sales の統合の強化</span><span class="sxs-lookup"><span data-stu-id="52ed2-103">Hardening the integration between Business Central and Dynamics 365 for Sales</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="52ed2-104">Dynamics 365 for Sales を使用する Business Central ユーザーの増加に伴い、Business Central と Dynamics 365 for Sales の統合には、信頼性の高い同期、販売注文の統合の改善、Dynamics 365 for Sales との AI 分析情報の共有が求められるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52ed2-104">As an increasing number of Business Central users use Dynamics 365 for Sales, the Business Central integration with Dynamics 365 for Sales has to deliver reliable synchronization, improved sales order integration, and shared AI insights with Dynamics 365 for Sales.</span></span>

<span data-ttu-id="52ed2-105">詳細については、「[Dynamics 365 for Sales との統合](https://docs.microsoft.com/en-us/dynamics365/business-central/admin-prepare-dynamics-365-for-sales-for-integration)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="52ed2-105">For more information, see [Integrating with Dynamics 365 for Sales](https://docs.microsoft.com/en-us/dynamics365/business-central/admin-prepare-dynamics-365-for-sales-for-integration).</span></span>  

## <a name="business-value"></a><span data-ttu-id="52ed2-106">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="52ed2-106">Business value</span></span>
<span data-ttu-id="52ed2-107">データの重複入力を避けるために、データは Business Central と Sales の間で同期されます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-107">To avoid duplicated entry of data, data is synchronized between Business Central and Sales.</span></span> <span data-ttu-id="52ed2-108">Business Central と Sales の両方で同期データが変更されると、同期の競合が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="52ed2-108">When the synchronized data is changed in both Business Central and Sales, synchronization conflicts can occur.</span></span> <span data-ttu-id="52ed2-109">営業担当者は、このような競合を認識し、IT 部門やパートナーを介さずに簡単に解決できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="52ed2-109">Sales people must be made aware of such conflicts and must be able to resolve them easily without involving the IT department or a partner.</span></span>  

<span data-ttu-id="52ed2-110">外出先での作業を可能にするために、営業担当者は、Business Central と Sales の両方について、応答性の高いユーザー エクスペリエンスを備えた最新のモバイル アプリケーションで作業できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="52ed2-110">To enable work on the go, sales people must be able to work in a modern mobile app with a responsive user experience, both for Business Central and Sales.</span></span>  

<span data-ttu-id="52ed2-111">販売注文の処理中、注文処理の担当者は価格を更新する、営業担当者が入力したメモを読む、代替品目を入力する、出荷予定日を変更することなどを実行できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="52ed2-111">During the fulfillment of sales orders, order processors may update prices, read notes entered by sales people, enter substitute items, or change expected shipment dates.</span></span> <span data-ttu-id="52ed2-112">Sales で作業している営業担当者がこのような変更を確認し、すぐに顧客に通知できるようにすることが重要です。</span><span class="sxs-lookup"><span data-stu-id="52ed2-112">It is important that such changes are available to sales people who work in Sales so that they can quickly notify customers.</span></span>  

<span data-ttu-id="52ed2-113">Business Central と Sales のデータから生成された AI ベースの分析情報を共有することで、営業担当者は成立する可能性が最も高い商談に集中することが可能になり、支払いが遅れると予想される顧客のリスクを軽減できます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-113">Sharing AI-based insight generated from Business Central and Sales data helps sales people focus on the opportunities that are most likely to be closed and it reduces the risk with customers who are expected to be late with payments.</span></span>  

## <a name="self-service-in-resolving-synchronization-conflicts"></a><span data-ttu-id="52ed2-114">セルフサービスでの同期競合の解決</span><span class="sxs-lookup"><span data-stu-id="52ed2-114">Self-service in resolving synchronization conflicts</span></span>
<span data-ttu-id="52ed2-115">Sales や Relationship Manager のロール センターなどの営業関連のロール センターで対応可能な同期の問題を表面化することで、営業担当者はそのようなデータの所有者として (たとえば一括で) それらを解決する方法を決めることができます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-115">Surfacing actionable synchronization issues on sales-related Role Centers, such as the Sales and Relationship Manager Role Center, enables sales people to decide how to resolve them, for example in bulk, because they are the owners of such data.</span></span>  

<span data-ttu-id="52ed2-116">![同期が競合しているタイル](media/synch-resolution.png "ロール センターのデータ エラー タイル")</span><span class="sxs-lookup"><span data-stu-id="52ed2-116">![Synchronization conflicts tile](media/synch-resolution.png "Data errors tile in Role Center")</span></span>

## <a name="open-coupled-sales-records-from-business-central-in-unified-interface"></a><span data-ttu-id="52ed2-117">統一インターフェイスで Business Central から Sales の連結レコードを開く</span><span class="sxs-lookup"><span data-stu-id="52ed2-117">Open coupled sales records from Business Central in Unified Interface</span></span>
<span data-ttu-id="52ed2-118">新しい統一インターフェイスで、Business Central から Sales の連結エンティティを開くことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52ed2-118">You can now open coupled Sales entities from Business Central in the new Unified Interface.</span></span> <span data-ttu-id="52ed2-119">Dynamics 365 営業ハブ アプリがインストールされている場合は、**Microsoft Dynamics 365 接続の設定**ページの **Dynamics 365 営業ハブで連結エンティティを開く**チェック ボックスをオンにします。</span><span class="sxs-lookup"><span data-stu-id="52ed2-119">If you have the Dynamics 365 Sales Hub app installed, you can select the **Open Coupled Entities in Dynamics 365 Sales Hub** check box on the **Microsoft Dynamics 365 Connection Setup** page.</span></span> <span data-ttu-id="52ed2-120">これにより、**取引先企業**、**取引先担当者**、**製品**などのアクションを選択すると、統一インターフェイスに Dynamics 365 for Sales の連結エンティティが開きます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-120">This will open coupled Dynamics 365 for Sales entities in Unified Interface when you choose actions, such as **Accounts**, **Contacts**, and **Products**.</span></span>

<span data-ttu-id="52ed2-121">![Dynamics 365 営業ハブで連結エンティティを開く](media/open-coupled-in-uci.png "[接続の設定] ページの [Dynamics 365 営業ハブで連結エンティティを開く] チェック ボックスの図")</span><span class="sxs-lookup"><span data-stu-id="52ed2-121">![Open Coupled Entities in Dynamics 365 Sales Hub](media/open-coupled-in-uci.png "Visualization of Open Coupled Entities in Dynamics 365 Sales Hub check box in the Connection Setup page")</span></span>

<span data-ttu-id="52ed2-122">Sales への接続が確立されると、統一インターフェイス Sales アプリ (営業ハブ) がインストールされているかどうかが Business Central によって確認されてから、**Microsoft Dynamics 365 接続設定**ページの **Dynamics 365 営業ハブで連結エンティティを開く**チェック ボックスが自動的にオンになります。</span><span class="sxs-lookup"><span data-stu-id="52ed2-122">When the connection to Sales is established, Business Central checks if the Unified Interface Sales app (Sales Hub) is installed and then automatically selects the **Open Coupled Entities in Dynamics 365 Sales Hub** check box on the **Microsoft Dynamics 365 Connection Setup** page.</span></span>

## <a name="sales-order-synchronization"></a><span data-ttu-id="52ed2-123">販売注文の同期</span><span class="sxs-lookup"><span data-stu-id="52ed2-123">Sales order synchronization</span></span>
<span data-ttu-id="52ed2-124">Sales で送信された販売注文が Business Central で作成された後に、さまざまな変更が発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="52ed2-124">Once a sales order has been submitted in Sales and created in Business Central, various changes can occur.</span></span> <span data-ttu-id="52ed2-125">そのような変更は再度 Sales に同期させることができます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-125">Such changes can be synchronized back to Sales.</span></span> <span data-ttu-id="52ed2-126">Sales で営業担当者が作成したメモを Business Central と同期できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52ed2-126">You can now synchronize notes that your sales people make in Sales to Business Central.</span></span>

<span data-ttu-id="52ed2-127">![Business Central が Dynamics 365 for Sales で送信された販売注文を更新](media/sales-order-posts-from-bc.png "販売注文送信済みフォームの Dynamics 365 for Sales タイムラインに対して Business Central で行われた投稿の図")</span><span class="sxs-lookup"><span data-stu-id="52ed2-127">![Business Central updates submitted Sales order in Dynamics 365 for Sales](media/sales-order-posts-from-bc.png "Visualization of posts made by Business Central to Sales Order submitted form Dynamics 365 for Sales timeline")</span></span>

<span data-ttu-id="52ed2-128">詳細については、「[販売注文データの処理](https://docs.microsoft.com/en-us/dynamics365/business-central/marketing-integrate-dynamicscrm#handling-sales-order-data)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="52ed2-128">For more information, see [Handling Sales Order Data](https://docs.microsoft.com/en-us/dynamics365/business-central/marketing-integrate-dynamicscrm#handling-sales-order-data).</span></span>

## <a name="sales-quote-synchronization"></a><span data-ttu-id="52ed2-129">販売見積の同期</span><span class="sxs-lookup"><span data-stu-id="52ed2-129">Sales quote synchronization</span></span>
<span data-ttu-id="52ed2-130">Sales で有効になった販売見積を、Business Central でピックアップして作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52ed2-130">Once a sales quote has been activated in Sales, you can now pick it up and create it in Business Central.</span></span> <span data-ttu-id="52ed2-131">Sales では見積の改訂が発生する可能性があるので、Business Central で以前に同期された見積をアーカイブおよび更新することによって、そのような改訂が Business Central に再び同期されます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-131">As revisions of quotes can occur in Sales, such revisions are synchronized back to Business Central by archiving and updating previously synchronized quotes in Business Central.</span></span>

<span data-ttu-id="52ed2-132">![Dynamics 365 for Sales からのアクティブ化された見積の処理](media/process-quote-from-sales.png "Business Central で処理される予定の、Dynamics 365 for Sales から取得された販売見積の図")</span><span class="sxs-lookup"><span data-stu-id="52ed2-132">![Process activated quotes from Dynamics 365 for Sales](media/process-quote-from-sales.png "Visualization activated sales quotes comming from Dynamics 365 for Sales to be processed in Business Central")</span></span>

<span data-ttu-id="52ed2-133">詳細については、「[販売見積データの処理](https://docs.microsoft.com/en-us/dynamics365/business-central/marketing-integrate-dynamicscrm#handling-sales-quotes-data)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="52ed2-133">For more information, see [Handling Sales Quote Data](https://docs.microsoft.com/en-us/dynamics365/business-central/marketing-integrate-dynamicscrm#handling-sales-quotes-data).</span></span>

## <a name="shared-ai-between-business-central-and-sales-post-april-2019"></a><span data-ttu-id="52ed2-134">Business Central と Sales の間の共有 AI (2019 年 4 月投稿)</span><span class="sxs-lookup"><span data-stu-id="52ed2-134">Shared AI between Business Central and Sales (post April 2019)</span></span>
<span data-ttu-id="52ed2-135">Business Central で作業をしている営業担当者は AI for Sales で生成されたインテリジェンスを消費し、Sales で作業している営業担当者は Business Central で生成されたインテリジェンスを消費できます。</span><span class="sxs-lookup"><span data-stu-id="52ed2-135">Sales people working in Business Central can consume intelligence generated by AI for Sales, and sales people working in Sales can consume intelligence generated by Business Central.</span></span>  

## <a name="tell-us-what-you-think"></a><span data-ttu-id="52ed2-136">フィードバック</span><span class="sxs-lookup"><span data-stu-id="52ed2-136">Tell us what you think</span></span>
<span data-ttu-id="52ed2-137">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="52ed2-137">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="52ed2-138">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="52ed2-138">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>

<!--
### Who uses this feature
These features are intended for end users working in sales. They may require additional setup.
## Status
### Development status
In development
-->
