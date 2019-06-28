---
title: 埋め込み IoT の機能強化
description: 2019 年 4 月リリースでの埋め込み IoT の機能強化
author: VivianFSandCFS
ms.author: kyley
ms.reviewer: shellyha
ms.date: 04/09/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: af2631408884554fd6512d0ea05acf33f3c06f39
ms.sourcegitcommit: d099a82effbb96a7079a9d088ee40847fa8d7a7f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/03/2019
ms.locfileid: "1616193"
---
#  <a name="embedded-iot"></a><span data-ttu-id="da84a-103">埋め込み IoT</span><span class="sxs-lookup"><span data-stu-id="da84a-103">Embedded IoT</span></span>
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]

<span data-ttu-id="da84a-104">この記事では、2019 年 4 月リリースでの埋め込み IoT 機能に対する機能強化について説明します。</span><span class="sxs-lookup"><span data-stu-id="da84a-104">This article describes enhancements to embedded IoT capabilities in the April '19 release.</span></span>

## <a name="embedded-iot-visualizations"></a><span data-ttu-id="da84a-105">埋め込み IoT の視覚化</span><span class="sxs-lookup"><span data-stu-id="da84a-105">Embedded IoT visualizations</span></span>
<span data-ttu-id="da84a-106">IoT アラートを受け取った後は、アラートを診断する必要があります。</span><span class="sxs-lookup"><span data-stu-id="da84a-106">After an IoT alert is received, the alert needs to be diagnosed.</span></span> <span data-ttu-id="da84a-107">Azure IoT からの測定データは、フィールド サービスに関連付けて使用することができます。</span><span class="sxs-lookup"><span data-stu-id="da84a-107">Measurement data from Azure IoT is available to be related to and used throughout field service.</span></span> 

-   <span data-ttu-id="da84a-108">アラートを理解するための最初のステップは、資産またはデバイスの現在の状態です。</span><span class="sxs-lookup"><span data-stu-id="da84a-108">The current state of the asset or device is the first step to understanding the alert.</span></span> <span data-ttu-id="da84a-109">複数の測定値と調整可能な時間枠を表示する機能を備えた現在のハートビートが表示されます。</span><span class="sxs-lookup"><span data-stu-id="da84a-109">The current heartbeat with ability to view multiple measurements and adjustable time window will be shown.</span></span> <span data-ttu-id="da84a-110">これにより、デバイスで何が起こっているのかがリアルタイムでわかります。</span><span class="sxs-lookup"><span data-stu-id="da84a-110">This gives a picture of what is happening on the device in real time.</span></span>

-   <span data-ttu-id="da84a-111">次のレベルの分析は、資産からの測定値の履歴と傾向を見ることです。</span><span class="sxs-lookup"><span data-stu-id="da84a-111">The next level of analysis is to view the history and trending of measurements from the asset.</span></span> <span data-ttu-id="da84a-112">これは、孤立したイベント、またはパターンやトレンドの一部であるイベントがあるかどうかを理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="da84a-112">This helps to understand if there are isolated events, or part of a pattern or trend.</span></span> <span data-ttu-id="da84a-113">これには調整可能なタイム スケールが含まれます。</span><span class="sxs-lookup"><span data-stu-id="da84a-113">This will include an adjustable time scale.</span></span> <span data-ttu-id="da84a-114">履歴ビューには、資産の最近の修復履歴も含まれます。</span><span class="sxs-lookup"><span data-stu-id="da84a-114">Recent repair history for the asset will also be included in the historical view.</span></span> <span data-ttu-id="da84a-115">これは修復、イベント、傾向との関係を理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="da84a-115">This helps to understand the relationship to repairs, events, and trends.</span></span>


<span data-ttu-id="da84a-116">この情報は、次のようなコンテキストでのビジュアル化でプレビューとして利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="da84a-116">This information will be available through visualizations as a preview within the following contexts:</span></span>

| <span data-ttu-id="da84a-117">サポート案件または作業指示書</span><span class="sxs-lookup"><span data-stu-id="da84a-117">Case or Work order</span></span> | <span data-ttu-id="da84a-118">アラート</span><span class="sxs-lookup"><span data-stu-id="da84a-118">Alert</span></span> | <span data-ttu-id="da84a-119">資産</span><span class="sxs-lookup"><span data-stu-id="da84a-119">Asset</span></span> | <span data-ttu-id="da84a-120">モバイル</span><span class="sxs-lookup"><span data-stu-id="da84a-120">Mobile</span></span> |
|----------------------------|-----------------------------|----------------------------|---------------------------------|
| <span data-ttu-id="da84a-121">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="da84a-121">Current and recent history</span></span> | <span data-ttu-id="da84a-122">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="da84a-122">Current and recent history</span></span> | <span data-ttu-id="da84a-123">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="da84a-123">Current and recent history</span></span> | <span data-ttu-id="da84a-124">Field Service モバイル アプリ内</span><span class="sxs-lookup"><span data-stu-id="da84a-124">Within Field Service mobile app</span></span> |
| <span data-ttu-id="da84a-125">関連する修復履歴</span><span class="sxs-lookup"><span data-stu-id="da84a-125">Related repair history</span></span> | <span data-ttu-id="da84a-126">似たデバイスでのビュー</span><span class="sxs-lookup"><span data-stu-id="da84a-126">View across similar devices</span></span> | <span data-ttu-id="da84a-127">似た資産でのビュー</span><span class="sxs-lookup"><span data-stu-id="da84a-127">View across similar assets</span></span> | <span data-ttu-id="da84a-128">現在および最近の履歴</span><span class="sxs-lookup"><span data-stu-id="da84a-128">Current and recent history</span></span> |



## <a name="device-commands"></a><span data-ttu-id="da84a-129">デバイスのコマンド</span><span class="sxs-lookup"><span data-stu-id="da84a-129">Device commands</span></span>

<span data-ttu-id="da84a-130">アラートを診断すると、デバイスにコマンドを送信することでアラートを解決できる場合があります。</span><span class="sxs-lookup"><span data-stu-id="da84a-130">When an alert is diagnosed, in some cases the alert can be resolved by sending a command to the device.</span></span> <span data-ttu-id="da84a-131">Field Service アプリケーションには、デバイスを分類し、そのカテゴリ内のデバイスに送信できるコマンドを定義する機能が含まれています。</span><span class="sxs-lookup"><span data-stu-id="da84a-131">The Field Service application includes the capability to categorize devices and define commands that can be sent to any device within the category.</span></span>
<span data-ttu-id="da84a-132">コマンドは、Field Service で発行し (手動または自動)、IoT Central によってデバイス上で実行できます。</span><span class="sxs-lookup"><span data-stu-id="da84a-132">Commands can be originated in field service (manual or automated) and executed on the device through IoT Central.</span></span>

<span data-ttu-id="da84a-133">コマンド ペイロードは、フロー (Microsoft Flow テンプレートに基づく) を使用して Field Service アプリケーションから IoT Central に送信されます。</span><span class="sxs-lookup"><span data-stu-id="da84a-133">The command payload is sent from the Field Service application to IoT Central using flows (based on Microsoft Flow templates).</span></span> <span data-ttu-id="da84a-134">コマンドを送信した後は、IoT の視覚化を使用して結果を監視できます。</span><span class="sxs-lookup"><span data-stu-id="da84a-134">After sending a command, the result can be monitored using the IoT visualizations.</span></span>

<span data-ttu-id="da84a-135">![IoT の視覚化](media/embedded-iot-remotecommands.png "IoT の視覚化")</span><span class="sxs-lookup"><span data-stu-id="da84a-135">![IoT visualization](media/embedded-iot-remotecommands.png "IoT visualization")</span></span>

## <a name="connected-field-service-solution-in-field-service-75-release"></a><span data-ttu-id="da84a-136">Field Service 7.5 リリースの Connected Field Service ソリューション</span><span class="sxs-lookup"><span data-stu-id="da84a-136">Connected Field Service solution in Field Service 7.5 release</span></span>
<span data-ttu-id="da84a-137">これまで Field Service バージョン 7.5 を使用していたお客様にとって、Connected Field Service と IoT ソリューションのインストールは Microsoft AppSource での追加ステップでした。</span><span class="sxs-lookup"><span data-stu-id="da84a-137">Previously for customers using Field Service version 7.5, installing Connected Field Service and IoT solution was an additional step through Microsoft AppSource.</span></span> <span data-ttu-id="da84a-138">このリリースでは、Connected Field Service と IoT ソリューションを Field Service ソリューションに含めることでこの余分なステップを削除し、お客様が IoT 機能を簡単にオンボードして展開時間を短縮できるようにします。</span><span class="sxs-lookup"><span data-stu-id="da84a-138">With this release, we remove this extra step by including Connected Field Service and IoT solution with the Field Service solution, allowing customers to easily onboard the IoT capabilities and improve deployment time.</span></span>
