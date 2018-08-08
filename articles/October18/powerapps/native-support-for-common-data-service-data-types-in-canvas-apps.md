---
title: "キャンバス アプリでの Common Data Service データ型のネイティブ サポート"
description: "アプリ メーカーは、オプションセット、GUID、日付のみ、およびタイム ゾーンなしの日付のみのデータ型を簡単に処理できます。"
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 94039419a4491ff73e7b9b09418e964242036b59
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="native-support-for-common-data-service-data-types-in-canvas-apps"></a><span data-ttu-id="d6a6f-103">キャンバス アプリでの Common Data Service データ型のネイティブ サポート</span><span class="sxs-lookup"><span data-stu-id="d6a6f-103">Native support for Common Data Service data types in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="d6a6f-104">現在、一部の Common Data Service データ型のサポートは使用が制限されているか困難です。</span><span class="sxs-lookup"><span data-stu-id="d6a6f-104">Today, support for some Common Data Service data types is limited or hard to use.</span></span> <span data-ttu-id="d6a6f-105">オプションセット値はメーカー ポータルで手動で検索する必要があり、GUID は比較の問題の原因となる文字列を通じて処理されます。日付のみのフィールドと日時フィールドにはタイム ゾーンの問題があります。</span><span class="sxs-lookup"><span data-stu-id="d6a6f-105">Optionset values must be looked up manually on the maker portal, GUIDs are handled through strings that can cause problems in comparisons, and there are time zone issues with date only and date/time fields.</span></span>

<span data-ttu-id="d6a6f-106">この機能は、オプションセットと GUID のネイティブ サポートを追加し、日時値のタイム ゾーン処理を改善して、問題をすべて解決します。</span><span class="sxs-lookup"><span data-stu-id="d6a6f-106">This feature cleans all that up, adding native support for optionsets and GUIDs and improving the time zone handling for date/time values.</span></span>
