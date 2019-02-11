---
title: IoT Central による埋め込み IoT の機能強化
description: IoT Central による埋め込み IoT の 2019 年 4 月リリースでの機能強化
author: VivianFSandCFS
ms.author: kyley
ms.reviewer: shellyha
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: c19fc5ec6c8ecd799171532b424d81dff8045a29
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210839"
---
#  <a name="embedded-iot-with-iot-central"></a><span data-ttu-id="9a238-103">埋め込み IoT (IoT Central)</span><span class="sxs-lookup"><span data-stu-id="9a238-103">Embedded IoT (with IoT Central)</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]

<span data-ttu-id="9a238-104">この記事では、2019 年 4 月リリースでの埋め込み IoT 機能に対する機能強化について説明します。</span><span class="sxs-lookup"><span data-stu-id="9a238-104">This article describes enhancements to embedded IoT capabilities in the April '19 release.</span></span>

## <a name="embedded-iot-visualizations"></a><span data-ttu-id="9a238-105">埋め込み IoT の視覚化</span><span class="sxs-lookup"><span data-stu-id="9a238-105">Embedded IoT visualizations</span></span>
<span data-ttu-id="9a238-106">IoT アラートを受け取った後は、アラートを診断する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9a238-106">After an IoT alert is received, the alert needs to be diagnosed.</span></span> <span data-ttu-id="9a238-107">IoT Central からの測定データは、Field Service に関連付けて使用することができます。</span><span class="sxs-lookup"><span data-stu-id="9a238-107">Measurement data from IoT Central is available to be related to and used throughout field service.</span></span> 

-   <span data-ttu-id="9a238-108">アラートを理解するための最初のステップは、資産またはデバイスの現在の状態です。</span><span class="sxs-lookup"><span data-stu-id="9a238-108">The current state of the asset or device is the first step to understanding the alert.</span></span> <span data-ttu-id="9a238-109">複数の測定値と調整可能な時間枠を表示する機能を備えた現在のハートビートが表示されます。</span><span class="sxs-lookup"><span data-stu-id="9a238-109">The current heartbeat with ability to view multiple measurements and adjustable time window will be shown.</span></span> <span data-ttu-id="9a238-110">これにより、デバイスで何が起こっているのかがリアルタイムでわかります。</span><span class="sxs-lookup"><span data-stu-id="9a238-110">This gives a picture of what is happening on the device in real time.</span></span>

-   <span data-ttu-id="9a238-111">次のレベルの分析は、資産からの測定値の履歴と傾向を見ることです。</span><span class="sxs-lookup"><span data-stu-id="9a238-111">The next level of analysis is to view the history and trending of measurements from the asset.</span></span> <span data-ttu-id="9a238-112">これは、孤立したイベント、またはパターンやトレンドの一部であるイベントがあるかどうかを理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="9a238-112">This helps to understand if there are isolated events, or part of a pattern or trend.</span></span> <span data-ttu-id="9a238-113">これには調整可能なタイム スケールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="9a238-113">This will include an adjustable time scale.</span></span> <span data-ttu-id="9a238-114">履歴ビューには、資産の最近の修復履歴も含まれます。</span><span class="sxs-lookup"><span data-stu-id="9a238-114">Recent repair history for the asset will also be included in the historical view.</span></span> <span data-ttu-id="9a238-115">これは修復、イベント、傾向との関係を理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="9a238-115">This helps to understand the relationship to repairs, events, and trends.</span></span>

-   <span data-ttu-id="9a238-116">分析のもう 1 つの分野は、類似の資産/デバイスとの比較です。</span><span class="sxs-lookup"><span data-stu-id="9a238-116">Another area of analysis is comparison with similar assets/devices.</span></span> <span data-ttu-id="9a238-117">たとえば、同じカテゴリー内の他の資産に対する同じ測定値を見てみます。</span><span class="sxs-lookup"><span data-stu-id="9a238-117">For example, view the same measurements for other assets in the same category.</span></span>
    <span data-ttu-id="9a238-118">これは、正常な状態をよりよく理解し、関連する資産/デバイスで同様のイベントまたは傾向が発生しているかどうかを判断するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="9a238-118">This is useful to better understand what is normal and determine if similar events or trends are occurring on related assets/devices.</span></span>

<span data-ttu-id="9a238-119">この情報は、次のようなコンテキストでの視覚化で利用できます。</span><span class="sxs-lookup"><span data-stu-id="9a238-119">This information is available through visualizations within the following contexts:</span></span>

| <span data-ttu-id="9a238-120">サポート案件または作業指示書</span><span class="sxs-lookup"><span data-stu-id="9a238-120">Case or Work order</span></span> | <span data-ttu-id="9a238-121">アラート</span><span class="sxs-lookup"><span data-stu-id="9a238-121">Alert</span></span> | <span data-ttu-id="9a238-122">資産</span><span class="sxs-lookup"><span data-stu-id="9a238-122">Asset</span></span> | <span data-ttu-id="9a238-123">モバイル</span><span class="sxs-lookup"><span data-stu-id="9a238-123">Mobile</span></span> |
|----------------------------|-----------------------------|----------------------------|---------------------------------|
| <span data-ttu-id="9a238-124">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="9a238-124">Current and recent history</span></span> | <span data-ttu-id="9a238-125">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="9a238-125">Current and recent history</span></span> | <span data-ttu-id="9a238-126">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="9a238-126">Current and recent history</span></span> | <span data-ttu-id="9a238-127">Field Service モバイル アプリ内</span><span class="sxs-lookup"><span data-stu-id="9a238-127">Within Field Service mobile app</span></span> |
| <span data-ttu-id="9a238-128">関連する修復履歴</span><span class="sxs-lookup"><span data-stu-id="9a238-128">Related repair history</span></span> | <span data-ttu-id="9a238-129">似たデバイスでのビュー</span><span class="sxs-lookup"><span data-stu-id="9a238-129">View across similar devices</span></span> | <span data-ttu-id="9a238-130">似た資産でのビュー</span><span class="sxs-lookup"><span data-stu-id="9a238-130">View across similar assets</span></span> | <span data-ttu-id="9a238-131">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="9a238-131">Current and recent history</span></span> |


> [!div class="mx-imgBorder"]
> <span data-ttu-id="9a238-132">![埋め込み IoT の視覚化](media/embedded-iot-visualization.png)</span><span class="sxs-lookup"><span data-stu-id="9a238-132">![Embedded IoT Visualization](media/embedded-iot-visualization.png)</span></span>

## <a name="device-commands"></a><span data-ttu-id="9a238-133">デバイスのコマンド</span><span class="sxs-lookup"><span data-stu-id="9a238-133">Device commands</span></span>

<span data-ttu-id="9a238-134">アラートを診断すると、デバイスにコマンドを送信することでアラートを解決できる場合があります。</span><span class="sxs-lookup"><span data-stu-id="9a238-134">When an alert is diagnosed, in some cases the alert can be resolved by sending a command to the device.</span></span> <span data-ttu-id="9a238-135">Field Service アプリケーションには、デバイスを分類し、そのカテゴリ内のデバイスに送信できるコマンドを定義する機能が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9a238-135">The Field Service application includes the capability to categorize devices and define commands that can be sent to any device within the category.</span></span>
<span data-ttu-id="9a238-136">コマンドは、Field Service で発行し (手動または自動)、IoT Central によってデバイス上で実行できます。</span><span class="sxs-lookup"><span data-stu-id="9a238-136">Commands can be originated in field service (manual or automated) and executed on the device through IoT Central.</span></span>

<span data-ttu-id="9a238-137">コマンド ペイロードは、フロー (Microsoft Flow テンプレートに基づく) を使用して Field Service アプリケーションから IoT Central に送信されます。</span><span class="sxs-lookup"><span data-stu-id="9a238-137">The command payload is sent from the Field Service application to IoT Central using flows (based on Microsoft Flow templates).</span></span> <span data-ttu-id="9a238-138">コマンドを送信した後は、IoT の視覚化を使用して結果を監視できます。</span><span class="sxs-lookup"><span data-stu-id="9a238-138">After sending a command, the result can be monitored using the IoT visualizations.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="9a238-139">![IoT の視覚化](media/embedded-iot-remotecommands.png "IoT の視覚化")</span><span class="sxs-lookup"><span data-stu-id="9a238-139">![IoT visualization](media/embedded-iot-remotecommands.png "IoT visualization")</span></span>

## <a name="device-provisioning"></a><span data-ttu-id="9a238-140">デバイスのプロビジョニング</span><span class="sxs-lookup"><span data-stu-id="9a238-140">Device provisioning</span></span>
<span data-ttu-id="9a238-141">IoT Central デバイスと Field Service デバイスまたは資産との間のマッピングは、Field Service アカウントへの適切なマッピングなど、埋め込み IoT 機能を使用するために重要です。</span><span class="sxs-lookup"><span data-stu-id="9a238-141">Mapping between IoT Central devices and Field Service devices or assets is key to using embedded IoT capability, including appropriate mapping to field service accounts.</span></span>

<span data-ttu-id="9a238-142">デバイス、資産、またはアカウントの同期マッピング機能を、IoT Central 統合の一部として使用できます。</span><span class="sxs-lookup"><span data-stu-id="9a238-142">The capability for synchronized mapping for a device, asset, or account is available as part of IoT Central integration.</span></span>
