---
title: 電子メール スケジュールのレコメンデーション
description: 受信者ごとに検出された希望の時間帯に近くなるように電子メールのスケジュールを設定します。
author: jain-shailesh
ms.author: shjain
ms.reviewer: kamaybac
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: b104384220c6f079ef1bf6efaac5dc763bf67286
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210930"
---
# <a name="smart-scheduling"></a><span data-ttu-id="bee73-103">スマート スケジューリング</span><span class="sxs-lookup"><span data-stu-id="bee73-103">Smart scheduling</span></span>

[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]


<span data-ttu-id="bee73-104">ユーザーは、一日の特定の時間に電子メールを読む傾向があります。</span><span class="sxs-lookup"><span data-stu-id="bee73-104">People tend to read their email at certain times of the day.</span></span> <span data-ttu-id="bee73-105">送ったメッセージは、受信者が積極的に電子メールに応答しているときに届くと最も注目を集める可能性が高く、受信トレイが注意を要する他のメッセージで既にいっぱいの場合はそうなりません。</span><span class="sxs-lookup"><span data-stu-id="bee73-105">Your message is likely to get the most attention if it arrives while the recipient is actively responding to email, but not when their inbox is already full of other messages that also demand attention.</span></span> <span data-ttu-id="bee73-106">このような複雑なパターンを理解するのは困難です。これらは、作業プロファイル、人口統計、コンテンツの性質、時期などのさまざまな要因に基づいています。</span><span class="sxs-lookup"><span data-stu-id="bee73-106">Understanding these complex patterns is difficult; they are based on many factors like work profile, demographics, nature of content, time of year, and more.</span></span> <span data-ttu-id="bee73-107">パターンを予測するのは難しく、電子メール キャンペーンの受信者ごとに手作業でスケジュールを設定することは事実上不可能です。</span><span class="sxs-lookup"><span data-stu-id="bee73-107">The patterns are hard to predict and practically impossible to schedule manually for each recipient of an email campaign.</span></span>

<span data-ttu-id="bee73-108">この AI 機能では、典型的なパターンが考慮されて、各取引先担当者に対する優先時間プロファイルを作成するための新しいパターンが発見されます。</span><span class="sxs-lookup"><span data-stu-id="bee73-108">This AI feature considers typical patterns and discovers new ones to build a preferred time profile for each contact.</span></span> <span data-ttu-id="bee73-109">顧客体験には既に異なる時間に通信を送信する機能があるため、各受信者に対して検出された希望時間帯の近くに電子メールをスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="bee73-109">Since customer journeys are already capable of sending communications at distinct times, they can schedule emails close to the detected preferred time slots for each recipient.</span></span> <span data-ttu-id="bee73-110">たとえば、AI では、中間レベルの管理者は通常毎日午前中に取引メッセージを読むが、週末に届くマーケティング電子メールは開かない、などと予測することができます。</span><span class="sxs-lookup"><span data-stu-id="bee73-110">For example, the AI may predict that mid-level managers typically read transactional messages first thing in the morning each day, but typically don't open marketing emails that arrive over the weekend.</span></span>

> <span data-ttu-id="bee73-111">![スマート スケジューリング](media/smart-scheduling.png.jpg "スマート スケジューリング")</span><span class="sxs-lookup"><span data-stu-id="bee73-111">![Smart Scheduling](media/smart-scheduling.png.jpg "Smart Scheduling")</span></span>
