---
title: 依存関係を持つアクションを変更する
description: 出力が他のステップで使用されるトリガーとアクションの名前を変更すること、および削除することができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/20/2019
ms.assetid: 2778ee84-6d1c-e911-a980-000d3a1378f6
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 26105892b67c41ff1f23c7bcdb322a97a23fca10
ms.sourcegitcommit: 1de869f4ccb74ccc9b9cd26817e3d5c30734c3c3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2019
ms.locfileid: "289051"
---
# <a name="change-actions-that-have-dependencies"></a><span data-ttu-id="c29b2-103">依存関係を持つアクションを変更する</span><span class="sxs-lookup"><span data-stu-id="c29b2-103">Change actions that have dependencies</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="c29b2-104">自動化されたフローの強力な特徴の 1 つは、任意のアクションにおいて、フロー内で上流にあるトリガーまたはアクションによって出力されたデータを使用できることです。</span><span class="sxs-lookup"><span data-stu-id="c29b2-104">One of the powerful aspects of automated flows is that any action can use data output by any trigger or action above it in the flow.</span></span> <span data-ttu-id="c29b2-105">ただし、変更したいステップがフローの先頭にあり、他のアクションがそのステップに依存している場合、これは容易ではありません。</span><span class="sxs-lookup"><span data-stu-id="c29b2-105">However, this presents a challenge if you want to change a step at the top of the flow on which other actions depend.</span></span> <span data-ttu-id="c29b2-106">以前は、フロー設計者が、ユーザーがそのような変更を行うことをブロックしていました。そのような変更を行うと、フロー内の他のアクションが中断されるためです。</span><span class="sxs-lookup"><span data-stu-id="c29b2-106">Previously, the flow designer would block you from making such a change because doing so would break other actions in the flow.</span></span>
<span data-ttu-id="c29b2-107">新しい**フロー チェッカー**では、フロー内で修復が必要なアクションが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="c29b2-107">The new **Flow checker** highlights actions within a flow that need to be repaired.</span></span> <span data-ttu-id="c29b2-108">これで、他のステップが依存しているアクションを削除または名前変更することができます。</span><span class="sxs-lookup"><span data-stu-id="c29b2-108">Now, you can delete or rename actions on which other steps depend.</span></span> <span data-ttu-id="c29b2-109">**フロー チェッカー**を使用して、発生する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="c29b2-109">Use the **Flow checker** to fix the issues that arise.</span></span>


