---
title: グリッド列ヘッダーを使用した法人のフィルタリング
description: ユーザーは、列見出しのドロップダウンを使用して法人のフィルタリングを実行できます。
author: jasongre
manager: AnnBe
ms.date: 12/03/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jasongre
audience: admin, end user, customizer, business analyst, IT pro
ms.openlocfilehash: 4da7b94c1ef4b808a571a8c5e424c39f55185e64
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287674"
---
# <a name="legal-entity-filtering-using-grid-column-headers"></a><span data-ttu-id="37701-103">グリッド列ヘッダーを使用した法人のフィルタリング</span><span class="sxs-lookup"><span data-stu-id="37701-103">Legal entity filtering using grid column headers</span></span> 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="37701-104">Platform update 23 以降では、企業間クエリを使用するグリッドの場合、ユーザーは、グリッドの他の列と同じように、列のドロップダウン メニューを使用して*法人*列をフィルター処理できます。</span><span class="sxs-lookup"><span data-stu-id="37701-104">Starting in Platform update 23, for grids with cross-company queries, users are able to filter the *Legal entity* column using the column  drop-down menu, similar to other columns in the grid.</span></span> <span data-ttu-id="37701-105">たとえば、特定の顧客のグローバル トランザクションをユーザーが調べている場合、会社の小さいサブセット内でトランザクションを検索したいことがあります。</span><span class="sxs-lookup"><span data-stu-id="37701-105">For example, if a user is looking at the global transactions for a specific customer, they might want to find the transactions within a small subset of companies.</span></span> <span data-ttu-id="37701-106">この機能が導入される前は、[フィルターまたは並べ替えの編集] ダイアログ ボックスの [顧客範囲] タブを使用してフィルターを適用するか、ページ固有のカスタム フィルターを使用する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="37701-106">Prior to this feature, they had to filter using the Customer range tab on the Advanced filter or sort dialog box, or use page-specific custom filters.</span></span>  

<span data-ttu-id="37701-107">![他の列と同じ方法で法人列をフィルタリングする](media/legalEntityFiltering.png  "他の列と同じ方法で法人列をフィルタリングする")</span><span class="sxs-lookup"><span data-stu-id="37701-107">![Filter legal entity columns in the same way as any other column](media/legalEntityFiltering.png  "Filter legal entity columns in the same way as any other column")</span></span>
