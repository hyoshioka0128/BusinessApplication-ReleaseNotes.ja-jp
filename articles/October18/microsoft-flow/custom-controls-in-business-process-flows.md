---
title: "業務プロセス フロー内のカスタム コントロール"
description: "業務プロセス フローは、カスタム コントロールや業務ルールを含むあらゆるフォーム機能をサポートします。"
author: KaranSr
manager: KVivek
ms.date: 8/10/2018
ms.assetid: 357e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: karansr
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: 8a89a9ef9d7a84980eeebc44f72692acacc7e744
ms.openlocfilehash: 79228ed622d245d15b9b2b715c8d6509062b8ca9
ms.contentlocale: ja-jp
ms.lasthandoff: 08/20/2018

---
# <a name="custom-controls-in-business-process-flows"></a><span data-ttu-id="9f71e-103">業務プロセス フロー内のカスタム コントロール</span><span class="sxs-lookup"><span data-stu-id="9f71e-103">Custom controls in business process flows</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="9f71e-104">業務プロセス フローでは、ステージとステップの形式で作業を行う手順がガイドされます。</span><span class="sxs-lookup"><span data-stu-id="9f71e-104">Business process flows provide a guided way to get work done in the form of stages and steps.</span></span> <span data-ttu-id="9f71e-105">ステージはプロセス内での位置を示すのに対し、ステップは目的の結果に至るアクション項目です。</span><span class="sxs-lookup"><span data-stu-id="9f71e-105">Stages tell you where you are in the process, while steps are action items that lead to a desired outcome.</span></span> <span data-ttu-id="9f71e-106">ステップは、アプリ用 Common Data Service (CDS) エンティティのフィールドに対してバインドされており、今のところ、フィールドの種類 (テキスト ボックス、ドロップダウン、数値など) に対して許可されている唯一の既定のビジュアル化です。</span><span class="sxs-lookup"><span data-stu-id="9f71e-106">Steps are bound to fields in a Common Data Service for Apps (CDS) entity and until now, only allowed default visualizations for the field type (text boxes, dropdowns, numbers, and so on).</span></span> <span data-ttu-id="9f71e-107">このリリースの業務プロセス フローのステップは、スライダー、放射状ノブ、LinkedIn コントロールなどの形式で、リッチなビジュアル化のためのカスタム コントロールをサポートします。</span><span class="sxs-lookup"><span data-stu-id="9f71e-107">With this release, business process flow steps support custom controls for rich visualizations in the form of sliders, radial knobs, the LinkedIn control, and more.</span></span> <span data-ttu-id="9f71e-108">この機能は、統一インターフェイスと Web クライアントの両方で使用できます。</span><span class="sxs-lookup"><span data-stu-id="9f71e-108">This feature is available in both the Unified Interface and the Web Client.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="9f71e-109">![カスタム コントロールの例](media/custom-controls_01.png "カスタム コントロールの例")</span><span class="sxs-lookup"><span data-stu-id="9f71e-109">![Example of custom controls](media/custom-controls_01.png "Example of custom controls")</span></span>

<span data-ttu-id="9f71e-110">この機能は、わかりやすくてイマーシブなプロセス ランタイム エクスペリエンスの可能性を高めます。</span><span class="sxs-lookup"><span data-stu-id="9f71e-110">This feature increases the potential for intuitive and immersive process runtime experiences.</span></span>

