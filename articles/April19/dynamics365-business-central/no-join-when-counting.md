---
title: 不要な付属テーブルの結合の削除
description: 不要な付属テーブルの結合の削除
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 3892212f9ce5a11cc8cf5f61b4d44e92e04b6fe6
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878728"
---
# <a name="removed-unnecessary-companion-table-joins"></a><span data-ttu-id="adad4-103">不要な付属テーブルの結合の削除</span><span class="sxs-lookup"><span data-stu-id="adad4-103">Removed unnecessary companion table joins</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="adad4-104">拡張によって拡張されたテーブルに対して AL メソッド COUNT または ISEMPTY を実行するとき、テーブルを拡張するフィールドにフィルターが設定されていない場合、Business Central Server では追加フィールドが格納されている付属テーブルが結合されません。</span><span class="sxs-lookup"><span data-stu-id="adad4-104">When executing AL methods COUNT or ISEMPTY on a table that is extended by an extension, if no filters have been set on the fields extending the table, then the Business Central Server will not join the companion table that is storing the extra fields.</span></span> <span data-ttu-id="adad4-105">これにより、パフォーマンスが 2 倍に向上します。</span><span class="sxs-lookup"><span data-stu-id="adad4-105">This gives a twofold performance improvement.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="adad4-106">フィードバック</span><span class="sxs-lookup"><span data-stu-id="adad4-106">Tell us what you think</span></span>
<span data-ttu-id="adad4-107">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="adad4-107">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="adad4-108">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="adad4-108">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
