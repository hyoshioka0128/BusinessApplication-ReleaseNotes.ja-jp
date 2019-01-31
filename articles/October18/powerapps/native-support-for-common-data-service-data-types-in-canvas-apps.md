---
title: キャンバス アプリでの Common Data Service データ型のネイティブ サポート
description: アプリ開発者は、オプションセット、GUID、日付のみ、およびタイム ゾーンなしの日付のみのデータ型を簡単に処理できます。
author: gregli-msft
ms.reviewer: anneta
ms.date: 12/10/2018
ms.assetid: 3f1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: d7d5e6f72322eaab0be8bc8eaa206fe4c407824f
ms.sourcegitcommit: 4516c399d430cc569513d46822c70670809fe5c6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/12/2019
ms.locfileid: "202327"
---
# <a name="native-support-for-common-data-service-data-types-in-canvas-apps-public-preview"></a><span data-ttu-id="2bebe-103">キャンバス アプリでの Common Data Service データ型のネイティブ サポート (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="2bebe-103">Native support for Common Data Service data types in canvas apps (Public Preview)</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="2bebe-104">現在、一部の Common Data Service データ型のサポートは使用が制限されているか困難です。</span><span class="sxs-lookup"><span data-stu-id="2bebe-104">Today, support for some Common Data Service data types is limited or hard to use.</span></span> <span data-ttu-id="2bebe-105">オプションセット値はメーカー ポータルで手動で検索する必要があり、GUID は比較の問題の原因となる文字列を通じて処理されます。日付のみのフィールドと日時フィールドにはタイム ゾーンの問題があります。</span><span class="sxs-lookup"><span data-stu-id="2bebe-105">Optionset values must be looked up manually on the maker portal, GUIDs are handled through strings that can cause problems in comparisons, and there are time zone issues with date only and date/time fields.</span></span>

<span data-ttu-id="2bebe-106">この機能は、オプションセットと GUID のネイティブ サポートを追加し、日時値のタイム ゾーン処理を改善して、問題をすべて解決します。</span><span class="sxs-lookup"><span data-stu-id="2bebe-106">This feature cleans all that up, adding native support for optionsets and GUIDs and improving the time zone handling for date/time values.</span></span>
