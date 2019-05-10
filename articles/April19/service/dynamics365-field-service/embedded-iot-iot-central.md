---
title: 埋め込み IoT の機能強化
description: 2019 年 4 月リリースでの埋め込み IoT の機能強化
author: VivianFSandCFS
ms.author: kyley
ms.reviewer: shellyha
ms.date: 04/09/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: 9e113e306d9b21d73c1bb5ab87635b5b24839978
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225455"
---
#  <a name="embedded-iot"></a><span data-ttu-id="afd34-103">埋め込み IoT</span><span class="sxs-lookup"><span data-stu-id="afd34-103">Embedded IoT</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]

<span data-ttu-id="afd34-104">この記事では、2019 年 4 月リリースでの埋め込み IoT 機能に対する機能強化について説明します。</span><span class="sxs-lookup"><span data-stu-id="afd34-104">This article describes enhancements to embedded IoT capabilities in the April '19 release.</span></span>

## <a name="embedded-iot-visualizations"></a><span data-ttu-id="afd34-105">埋め込み IoT の視覚化</span><span class="sxs-lookup"><span data-stu-id="afd34-105">Embedded IoT visualizations</span></span>
<span data-ttu-id="afd34-106">IoT アラートを受け取った後は、アラートを診断する必要があります。</span><span class="sxs-lookup"><span data-stu-id="afd34-106">After an IoT alert is received, the alert needs to be diagnosed.</span></span> <span data-ttu-id="afd34-107">Azure IoT からの測定データは、フィールド サービスに関連付けて使用することができます。</span><span class="sxs-lookup"><span data-stu-id="afd34-107">Measurement data from Azure IoT is available to be related to and used throughout field service.</span></span> 

-   <span data-ttu-id="afd34-108">アラートを理解するための最初のステップは、資産またはデバイスの現在の状態です。</span><span class="sxs-lookup"><span data-stu-id="afd34-108">The current state of the asset or device is the first step to understanding the alert.</span></span> <span data-ttu-id="afd34-109">複数の測定値と調整可能な時間枠を表示する機能を備えた現在のハートビートが表示されます。</span><span class="sxs-lookup"><span data-stu-id="afd34-109">The current heartbeat with ability to view multiple measurements and adjustable time window will be shown.</span></span> <span data-ttu-id="afd34-110">これにより、デバイスで何が起こっているのかがリアルタイムでわかります。</span><span class="sxs-lookup"><span data-stu-id="afd34-110">This gives a picture of what is happening on the device in real time.</span></span>

-   <span data-ttu-id="afd34-111">次のレベルの分析は、資産からの測定値の履歴と傾向を見ることです。</span><span class="sxs-lookup"><span data-stu-id="afd34-111">The next level of analysis is to view the history and trending of measurements from the asset.</span></span> <span data-ttu-id="afd34-112">これは、孤立したイベント、またはパターンやトレンドの一部であるイベントがあるかどうかを理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="afd34-112">This helps to understand if there are isolated events, or part of a pattern or trend.</span></span> <span data-ttu-id="afd34-113">これには調整可能なタイム スケールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="afd34-113">This will include an adjustable time scale.</span></span> <span data-ttu-id="afd34-114">履歴ビューには、資産の最近の修復履歴も含まれます。</span><span class="sxs-lookup"><span data-stu-id="afd34-114">Recent repair history for the asset will also be included in the historical view.</span></span> <span data-ttu-id="afd34-115">これは修復、イベント、傾向との関係を理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="afd34-115">This helps to understand the relationship to repairs, events, and trends.</span></span>

-   <span data-ttu-id="afd34-116">分析のもう 1 つの分野は、類似の資産/デバイスとの比較です。</span><span class="sxs-lookup"><span data-stu-id="afd34-116">Another area of analysis is comparison with similar assets/devices.</span></span> <span data-ttu-id="afd34-117">たとえば、同じカテゴリー内の他の資産に対する同じ測定値を見てみます。</span><span class="sxs-lookup"><span data-stu-id="afd34-117">For example, view the same measurements for other assets in the same category.</span></span>
    <span data-ttu-id="afd34-118">これは、正常な状態をよりよく理解し、関連する資産/デバイスで同様のイベントまたは傾向が発生しているかどうかを判断するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="afd34-118">This is useful to better understand what is normal and determine if similar events or trends are occurring on related assets/devices.</span></span>

<span data-ttu-id="afd34-119">この情報は、次のようなコンテキストでのビジュアル化でプレビューとして利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="afd34-119">This information will be available through visualizations as a preview within the following contexts:</span></span>

| <span data-ttu-id="afd34-120">サポート案件または作業指示書</span><span class="sxs-lookup"><span data-stu-id="afd34-120">Case or Work order</span></span> | <span data-ttu-id="afd34-121">アラート</span><span class="sxs-lookup"><span data-stu-id="afd34-121">Alert</span></span> | <span data-ttu-id="afd34-122">資産</span><span class="sxs-lookup"><span data-stu-id="afd34-122">Asset</span></span> | <span data-ttu-id="afd34-123">モバイル</span><span class="sxs-lookup"><span data-stu-id="afd34-123">Mobile</span></span> |
|----------------------------|-----------------------------|----------------------------|---------------------------------|
| <span data-ttu-id="afd34-124">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="afd34-124">Current and recent history</span></span> | <span data-ttu-id="afd34-125">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="afd34-125">Current and recent history</span></span> | <span data-ttu-id="afd34-126">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="afd34-126">Current and recent history</span></span> | <span data-ttu-id="afd34-127">Field Service モバイル アプリ内</span><span class="sxs-lookup"><span data-stu-id="afd34-127">Within Field Service mobile app</span></span> |
| <span data-ttu-id="afd34-128">関連する修復履歴</span><span class="sxs-lookup"><span data-stu-id="afd34-128">Related repair history</span></span> | <span data-ttu-id="afd34-129">似たデバイスでのビュー</span><span class="sxs-lookup"><span data-stu-id="afd34-129">View across similar devices</span></span> | <span data-ttu-id="afd34-130">似た資産でのビュー</span><span class="sxs-lookup"><span data-stu-id="afd34-130">View across similar assets</span></span> | <span data-ttu-id="afd34-131">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="afd34-131">Current and recent history</span></span> |



## <a name="device-commands"></a><span data-ttu-id="afd34-132">デバイスのコマンド</span><span class="sxs-lookup"><span data-stu-id="afd34-132">Device commands</span></span>

<span data-ttu-id="afd34-133">アラートを診断すると、デバイスにコマンドを送信することでアラートを解決できる場合があります。</span><span class="sxs-lookup"><span data-stu-id="afd34-133">When an alert is diagnosed, in some cases the alert can be resolved by sending a command to the device.</span></span> <span data-ttu-id="afd34-134">Field Service アプリケーションには、デバイスを分類し、そのカテゴリ内のデバイスに送信できるコマンドを定義する機能が含まれています。</span><span class="sxs-lookup"><span data-stu-id="afd34-134">The Field Service application includes the capability to categorize devices and define commands that can be sent to any device within the category.</span></span>
<span data-ttu-id="afd34-135">コマンドは、Field Service で発行し (手動または自動)、IoT Central によってデバイス上で実行できます。</span><span class="sxs-lookup"><span data-stu-id="afd34-135">Commands can be originated in field service (manual or automated) and executed on the device through IoT Central.</span></span>

<span data-ttu-id="afd34-136">コマンド ペイロードは、フロー (Microsoft Flow テンプレートに基づく) を使用して Field Service アプリケーションから IoT Central に送信されます。</span><span class="sxs-lookup"><span data-stu-id="afd34-136">The command payload is sent from the Field Service application to IoT Central using flows (based on Microsoft Flow templates).</span></span> <span data-ttu-id="afd34-137">コマンドを送信した後は、IoT の視覚化を使用して結果を監視できます。</span><span class="sxs-lookup"><span data-stu-id="afd34-137">After sending a command, the result can be monitored using the IoT visualizations.</span></span>

<span data-ttu-id="afd34-138">![IoT の視覚化](media/embedded-iot-remotecommands.png "IoT の視覚化")</span><span class="sxs-lookup"><span data-stu-id="afd34-138">![IoT visualization](media/embedded-iot-remotecommands.png "IoT visualization")</span></span>

## <a name="device-provisioning"></a><span data-ttu-id="afd34-139">デバイスのプロビジョニング</span><span class="sxs-lookup"><span data-stu-id="afd34-139">Device provisioning</span></span>
<span data-ttu-id="afd34-140">IoT Central デバイスと Field Service デバイスまたは資産との間のマッピングは、フィールド サービスの取引先企業への適切なマッピングなど、埋め込み IoT 機能を使用するために重要です。</span><span class="sxs-lookup"><span data-stu-id="afd34-140">Mapping between IoT Central devices and Field Service devices or assets is key to using embedded IoT capability, including appropriate mapping to field service accounts.</span></span>

<span data-ttu-id="afd34-141">デバイスまたは資産の同期マッピング機能を、IoT Central 統合でプレビューとして使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="afd34-141">The capability for synchronized mapping for a device or asset will be available as a preview with the IoT Central integration.</span></span>
