---
title: "「次の値のいずれか」演算子を使用して Excel からフィルター フィールドに一覧を貼り付ける"
description: "ユーザーは、「次の値のいずれか」演算子を使用して Excel からフィルター フィールドに一覧を正しく貼り付けられるようになりました。"
author: jasongre
manager: AnnBe
ms.date: 11/01/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: 56c3cfe74093764b02d6a8cc4aa95e3b3e957cb9
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

# <a name="paste-lists-from-excel-into-filter-fields-with-the-is-one-of-operator"></a><span data-ttu-id="119a5-103">「次の値のいずれか」演算子を使用して Excel からフィルター フィールドに一覧を貼り付ける</span><span class="sxs-lookup"><span data-stu-id="119a5-103">Paste lists from Excel into filter fields with the "is one of" operator</span></span>

<span data-ttu-id="119a5-104">一部のタスクでは、ユーザーは Finance and Operations のデータをフィルター処理するために Excel 内の値の一覧を使用する場合があります。</span><span class="sxs-lookup"><span data-stu-id="119a5-104">For some tasks, users might have a list of values in Excel that they'd like to use to filter data in Finance and Operations.</span></span> <span data-ttu-id="119a5-105">たとえば、財務ユーザーはシステムで追加の調査が必要な 1 セットの伝票をレポートから特定している場合があり、このユーザーが Excel から Finance and Operations のフィルター フィールドに一覧を直接コピーできることが理想的です。</span><span class="sxs-lookup"><span data-stu-id="119a5-105">As an example, a finance user might have identified a set of vouchers from a report that need additional research in the system, and it would be ideal for this user to be able to copy the list directly from Excel into a filter field in Finance and Operations.</span></span>   

<span data-ttu-id="119a5-106">Platform Update 22 以降、[フィルター] ウィンドウの「次の値のいずれか」演算子とグリッド列フィルターでは Excel からコピーされた一覧が認識されるようになったので、それらをフィルター フィールドに直接貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="119a5-106">Starting in Platform Update 22, the "is one of" operator in the Filter Pane and grid column filtering now recognizes lists copied from Excel so that they can be pasted directly into a filter field.</span></span> <span data-ttu-id="119a5-107">これには、Excel 内のさまざまな行や列からコピーされた値のコレクションが含まれます。</span><span class="sxs-lookup"><span data-stu-id="119a5-107">This includes a collection of values copied from different rows and columns in Excel.</span></span>

<span data-ttu-id="119a5-108">たとえば、Excel のこの伝票番号の一覧について考えてみましょう。</span><span class="sxs-lookup"><span data-stu-id="119a5-108">So for example, consider this list of voucher numbers in Excel:</span></span> 

<span data-ttu-id="119a5-109">![Excel の伝票番号の一覧](media/excelFilterList.png  "Excel の伝票番号の一覧")</span><span class="sxs-lookup"><span data-stu-id="119a5-109">![List of voucher numbers in Excel](media/excelFilterList.png  "List of voucher numbers in Excel")</span></span>

<span data-ttu-id="119a5-110">この一覧に基づいて Finance and Operations をフィルター処理する場合は、Excel から一覧を単純にコピーし、**伝票トランザクション** ページの [フィルター] ウィンドウで**伝票**フィールドを探し、フィルター演算子が**次の値のいずれか**に設定されていることを確認してから、クリップボードの内容をフィルター フィールドに貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="119a5-110">If you want to filter Finance and Operations based on this list, simply copy the list from Excel, find the **Voucher** field filter in the Filter Pane on the **Voucher transactions** page, ensure the filter operator is set to **is one of**, and then paste the clipboard contents into the filter field.</span></span> <span data-ttu-id="119a5-111">次のように、Excel からの一覧がフィルター フィールドに展開されます。</span><span class="sxs-lookup"><span data-stu-id="119a5-111">The list from Excel will get expanded in the filter field as shown:</span></span> 

<span data-ttu-id="119a5-112">![Excel からの値の一覧に貼り付けた後の伝票フィルター フィールド](media/oldPasteFromExcelFiltering.png  "Excel からの値の一覧に貼り付けた後の伝票フィルター フィールド")</span><span class="sxs-lookup"><span data-stu-id="119a5-112">![Voucher filter field after pasting in a list of values from Excel](media/oldPasteFromExcelFiltering.png  "Voucher filter field after pasting in a list of values from Excel")</span></span>

<span data-ttu-id="119a5-113">同様に Platform Update 22 で使用可能な[最適化された「次の値のいずれか」フィルタリング結果](improved-isoneof-filtering.md)を有効にした場合、次の図に示すように、ビジュアル化が向上します。</span><span class="sxs-lookup"><span data-stu-id="119a5-113">If you've enabled the [Optimized "is one of" filtering experience](improved-isoneof-filtering.md) that is also available in Platform Update 22, the visualization is even nicer, as shown in the following image.</span></span>  

<span data-ttu-id="119a5-114">![Excel からの値の一覧に貼り付けた後の最適化された伝票フィルター フィールド](media/newPasteFromExcelFiltering.png  "Excel からの値の一覧に貼り付けた後の最適化された伝票フィルター フィールド")</span><span class="sxs-lookup"><span data-stu-id="119a5-114">![Optimized voucher filter field after pasting in a list of values from Excel](media/newPasteFromExcelFiltering.png  "Optimized voucher filter field after pasting in a list of values from Excel")</span></span>




