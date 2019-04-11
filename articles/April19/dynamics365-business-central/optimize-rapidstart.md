---
title: ラピッドスタートの最適化
description: ラピッドスタートの最適化
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 96dad2dcdfe69876834687182e49686c2d49093a
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878731"
---
# <a name="rapidstart-optimization"></a><span data-ttu-id="c042a-103">ラピッドスタートの最適化</span><span class="sxs-lookup"><span data-stu-id="c042a-103">RapidStart optimization</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="c042a-104">ラピッドスタートとも呼ばれる構成パッケージのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="c042a-104">The performance of configuration packages, also known as RapidStart, has been improved.</span></span> <span data-ttu-id="c042a-105">各テーブル ノードを順番に処理する代わりに、多数の行を含むノードをバックグラウンド セッションに並列に送信し、システムが過負荷にならないように同時バックグラウンド セッションの数を調整します。</span><span class="sxs-lookup"><span data-stu-id="c042a-105">Instead of processing each table node serially, we now send nodes with many rows to a background session in parallel, and throttle the number of simultaneous background sessions so we don’t overload the system.</span></span> <span data-ttu-id="c042a-106">この最適化の影響として、ラピッドスタート パッケージのインポートが約 2 倍速くなり、パッケージの削除が 3 倍以上速くなっています。</span><span class="sxs-lookup"><span data-stu-id="c042a-106">The impact of this optimization is that the import of a RapidStart package is approximately 2 times faster, and the deletion of a package is more than 3 times faster.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="c042a-107">フィードバック</span><span class="sxs-lookup"><span data-stu-id="c042a-107">Tell us what you think</span></span>
<span data-ttu-id="c042a-108">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="c042a-108">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="c042a-109">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="c042a-109">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
