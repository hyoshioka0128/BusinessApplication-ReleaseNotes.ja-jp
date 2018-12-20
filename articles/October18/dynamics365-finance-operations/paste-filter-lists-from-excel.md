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
ms.sourcegitcommit: d97ebd0133cc27a2d24d0dc65beceac42894da89
ms.openlocfilehash: e815b473ce35a4e8cf5311befd2308e403ecad96
ms.contentlocale: ja-jp
ms.lasthandoff: 11/01/2018

---

# <a name="paste-lists-from-excel-into-filter-fields-with-the-is-one-of-operator"></a>「次の値のいずれか」演算子を使用して Excel からフィルター フィールドに一覧を貼り付ける

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

一部のタスクでは、ユーザーは Finance and Operations のデータをフィルター処理するために Excel 内の値の一覧を使用する場合があります。 たとえば、財務ユーザーはシステムで追加の調査が必要な 1 セットの伝票をレポートから特定している場合があり、このユーザーが Excel から Finance and Operations のフィルター フィールドに一覧を直接コピーできることが理想的です。   

Platform Update 22 以降、[フィルター] ウィンドウの「次の値のいずれか」演算子とグリッド列フィルターでは Excel からコピーされた一覧が認識されるようになったので、それらをフィルター フィールドに直接貼り付けることができます。 これには、Excel 内のさまざまな行や列からコピーされた値のコレクションが含まれます。

たとえば、Excel のこの伝票番号の一覧について考えてみましょう。 

> [!div class="mx-imgBorder"]
> ![Excel の伝票番号の一覧](media/excelFilterList.png  "Excel の伝票番号の一覧")

この一覧に基づいて Finance and Operations をフィルター処理する場合は、Excel から一覧を単純にコピーし、**伝票トランザクション** ページの [フィルター] ウィンドウで**伝票**フィールドを探し、フィルター演算子が**次の値のいずれか**に設定されていることを確認してから、クリップボードの内容をフィルター フィールドに貼り付けます。 次のように、Excel からの一覧がフィルター フィールドに展開されます。 

> [!div class="mx-imgBorder"]
> ![Excel からの値の一覧に貼り付けた後の伝票フィルター フィールド](media/oldPasteFromExcelFiltering.png  "Excel からの値の一覧に貼り付けた後の伝票フィルター フィールド")

同様に Platform Update 22 で使用可能な[最適化された「次の値のいずれか」フィルタリング結果](improved-isoneof-filtering.md)を有効にした場合、次の図に示すように、ビジュアル化が向上します。  

> [!div class="mx-imgBorder"]
> ![Excel からの値の一覧に貼り付けた後の最適化された伝票フィルター フィールド](media/newPasteFromExcelFiltering.png  "Excel からの値の一覧に貼り付けた後の最適化された伝票フィルター フィールド")




