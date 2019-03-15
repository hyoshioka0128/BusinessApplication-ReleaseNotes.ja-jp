---
title: システム主導の作業優先順位
description: ''
author: Mirzaab
ms.date: 02/12/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
ms.openlocfilehash: d0c5b764ba527050e396da1a60b2f3963bd81ef8
ms.sourcegitcommit: 6b5a05bc2ba73d392be45ad6eb5369c6b810ebf0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "390355"
---
# <a name="system-directed-work-sequencing"></a><span data-ttu-id="2682c-102">システム主導の作業優先順位</span><span class="sxs-lookup"><span data-stu-id="2682c-102">System-directed work sequencing</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="2682c-103">システム主導の作業優先順位により、システムが実行のためにユーザーに提示する作業指示の並べ替えとフィルター処理を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="2682c-103">System-directed work sequencing allows you to sort and filter work orders that the system presents to the user for execution.</span></span> <span data-ttu-id="2682c-104">この機能は、倉庫ピッキング プロセスを促進するために追加の基準が必要なシナリオを解決します。</span><span class="sxs-lookup"><span data-stu-id="2682c-104">This functionality solves scenarios where additional criteria is required to drive warehouse picking processes.</span></span> <span data-ttu-id="2682c-105">追加の基準は、出荷の時間、ピッキング ゾーン、場所のプロファイルなどです。</span><span class="sxs-lookup"><span data-stu-id="2682c-105">Additional criteria might be the time of shipping, picking zone, and location profile.</span></span>

<span data-ttu-id="2682c-106">この機能は、現在のシステム主導のピッキングを新しいシステム主導のクエリ順序で拡張します。新しいクエリ順序では、ユーザーが、作成されたすべての作業指示を評価する優先順位と 1 つ以上のクエリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="2682c-106">This functionality extends the current system-directed picking with the new System-directed query order where the user can set up a sequence and a query or multiple queries that will evaluate all created work orders.</span></span> <span data-ttu-id="2682c-107">モバイル デバイスのメニュー項目設定の指定された基準を満たす作業指示のみを取り込んで表示します。</span><span class="sxs-lookup"><span data-stu-id="2682c-107">It will capture and present only the work orders that meet the specified criteria of the mobile device menu item setup.</span></span>

<span data-ttu-id="2682c-108">したがって、倉庫ピッキング プロセスは定義された基準に一致する作業指示書を識別し、それらを適切なモバイル デバイス メニュー項目に割り当て、その結果として特定のスキルセット、ピッキング機器、またはその他の要件に基づいて作業者に提示するので、この機能をさらに最適化できます。</span><span class="sxs-lookup"><span data-stu-id="2682c-108">Warehouse picking processes can therefore be further optimized as this feature identifies work orders that match the defined criteria and assigns those to the correct mobile device menu item, and consequently presents them to a worker based on a specific skillset, picking equipment, or any other requirement.</span></span> 
