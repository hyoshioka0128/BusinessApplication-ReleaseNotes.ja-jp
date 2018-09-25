---
title: "CFS - IoT Central との統合"
description: "統合の最初のフェーズでは、統合ソリューションの焦点は Flow によるものです。"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: ce0f2e97-8ded-4530-9c50-fc82ce4a6171
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b1a0f1e04786d2daef091fc6f6f9c168f2b005e7
ms.openlocfilehash: ef5b92a8512bcadda31c515aab20c81d26fcac6d
ms.contentlocale: ja-jp
ms.lasthandoff: 09/25/2018

---
#  <a name="cfs---integration-with-iot-central"></a><span data-ttu-id="ce827-103">CFS - IoT Central との統合</span><span class="sxs-lookup"><span data-stu-id="ce827-103">CFS - Integration with IoT Central</span></span>

[!include[field-service banner](../../../includes/field-service.md)]




<span data-ttu-id="ce827-104">統合の最初のフェーズでは、統合ソリューションの焦点は Microsoft Flow によるものです。</span><span class="sxs-lookup"><span data-stu-id="ce827-104">For the first phase of integration, the focus of the integration solution will be through Microsoft Flow.</span></span> <span data-ttu-id="ce827-105">これは、IoT Central から Connected Field Service への一方向の通信です。</span><span class="sxs-lookup"><span data-stu-id="ce827-105">This is a one-way communication from IoT Central to Connected Field Service.</span></span> <span data-ttu-id="ce827-106">IoT Central によるリモート デバイスの監視では、IoT Central で定義されているしきい値を測定値が超えると、CFS でアラートを生成するアクションがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="ce827-106">With IoT Central monitoring remote devices, any measurements that exceed thresholds defined in IoT Central will trigger an action to fire an alert in CFS.</span></span> <span data-ttu-id="ce827-107">フィールド サービス マネージャーは、顧客の資産やインシデントの種類などの条件に基づいて、これらのアラートをグループ化できます。</span><span class="sxs-lookup"><span data-stu-id="ce827-107">Field service managers can group these alerts by criteria such as customer asset and incident type.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="ce827-108">![](media/enhanced-iot-central-integration-1.png "強化された IoT Central 統合")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="ce827-108">![](media/enhanced-iot-central-integration-1.png "Enhanced IoT Central integration")
<!-- picture --></span></span>


<span data-ttu-id="ce827-109">2018 年 10 月のリリースでは、技術者はサイトにいるときに、IoT Central の状態に応じた少数のオプションで、IoT デバイスから分析情報を取得して対応できます。</span><span class="sxs-lookup"><span data-stu-id="ce827-109">For the October '18 release, technicians can be equipped with and act on insight from IoT devices when on site, with a few options depending on the state of IoT Central.</span></span>

-   <span data-ttu-id="ce827-110">IoT Central のデバイス状態と測定のビジュアルを、Field Service モバイル アプリケーション内に直接埋め込みます。</span><span class="sxs-lookup"><span data-stu-id="ce827-110">Embed IoT Central device state and measurement visuals directly within the Field Service mobile application.</span></span>
-   <span data-ttu-id="ce827-111">IoT Central からの利用統計情報を Azure BLOB に格納し、埋め込まれた Power BI でデータを視覚化できるようにします。</span><span class="sxs-lookup"><span data-stu-id="ce827-111">Store telemetry data from IoT Central in an Azure blob and enable an embedded Power BI visualizing the data.</span></span>
-   <span data-ttu-id="ce827-112">技術者は Field Service モバイル アプリケーションから IoT Central にコマンドを送信できます。</span><span class="sxs-lookup"><span data-stu-id="ce827-112">Allow technicians to send commands from the Field Service mobile application back to IoT Central.</span></span>

