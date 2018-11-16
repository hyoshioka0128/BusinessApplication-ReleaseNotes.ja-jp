---
title: "キャンバス アプリでの Common Data Service データ型のネイティブ サポート"
description: "アプリ開発者は、オプションセット、GUID、日付のみ、およびタイム ゾーンなしの日付のみのデータ型を簡単に処理できます。"
author: gregli-msft
manager: KVivek
ms.date: 11/8/2018
ms.assetid: 3f1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: cefcf9f22fa7701234cd81e9c3e4e02b4dcb659c
ms.openlocfilehash: 811242faa77b0c92beed8bb535f43a6698cf452f
ms.contentlocale: ja-jp
ms.lasthandoff: 11/16/2018

---
# <a name="native-support-for-common-data-service-data-types-in-canvas-apps"></a><span data-ttu-id="e67af-103">キャンバス アプリでの Common Data Service データ型のネイティブ サポート</span><span class="sxs-lookup"><span data-stu-id="e67af-103">Native support for Common Data Service data types in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="e67af-104">現在、一部の Common Data Service データ型のサポートは使用が制限されているか困難です。</span><span class="sxs-lookup"><span data-stu-id="e67af-104">Today, support for some Common Data Service data types is limited or hard to use.</span></span> <span data-ttu-id="e67af-105">オプションセット値はメーカー ポータルで手動で検索する必要があり、GUID は比較の問題の原因となる文字列を通じて処理されます。日付のみのフィールドと日時フィールドにはタイム ゾーンの問題があります。</span><span class="sxs-lookup"><span data-stu-id="e67af-105">Optionset values must be looked up manually on the maker portal, GUIDs are handled through strings that can cause problems in comparisons, and there are time zone issues with date only and date/time fields.</span></span>

<span data-ttu-id="e67af-106">この機能は、オプションセットと GUID のネイティブ サポートを追加し、日時値のタイム ゾーン処理を改善して、問題をすべて解決します。</span><span class="sxs-lookup"><span data-stu-id="e67af-106">This feature cleans all that up, adding native support for optionsets and GUIDs and improving the time zone handling for date/time values.</span></span>

