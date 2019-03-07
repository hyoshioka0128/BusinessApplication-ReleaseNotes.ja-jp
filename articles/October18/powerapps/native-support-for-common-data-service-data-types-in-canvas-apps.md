---
title: キャンバス アプリでの Common Data Service for Apps データ型のネイティブ サポート
description: アプリ開発者は、オプションセット、GUID、日付のみ、およびタイム ゾーンなしの日付のみのデータ型を簡単に処理できます。
author: gregli-msft
ms.reviewer: anneta
ms.date: 02/04/2019
ms.assetid: 3f1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: 655cc6caf3deb77066d5c378d7cb701fbb4ce939
ms.sourcegitcommit: b0c22af04369d4d8d0d0a5d67c06d26b3474ceb6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/11/2019
ms.locfileid: "379519"
---
# <a name="native-support-for-common-data-service-for-apps-data-types-in-canvas-apps-public-preview"></a><span data-ttu-id="a5652-103">キャンバス アプリでの Common Data Service for Apps データ型のネイティブ サポート (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="a5652-103">Native support for Common Data Service for Apps data types in canvas apps (Public Preview)</span></span>




<span data-ttu-id="a5652-104">現在、Common Data Service for Apps での一部のデータ型のサポートは、制限されているか、使用が難しい状況です。</span><span class="sxs-lookup"><span data-stu-id="a5652-104">Today, support for some data types in Common Data Service for Apps is limited or hard to use.</span></span> <span data-ttu-id="a5652-105">オプション セット値はメーカー ポータルで手動で検索する必要があり、GUID は文字列を通じて処理されるため比較時に問題が発生する可能性があります。日付のみのフィールドと日時フィールドにはタイム ゾーンの問題があります。</span><span class="sxs-lookup"><span data-stu-id="a5652-105">Optionset values must be looked up manually on the maker portal, GUIDs are handled through strings that can cause problems in comparisons, and there are time-zone issues with date only and date/time fields.</span></span>

<span data-ttu-id="a5652-106">この機能は、オプション セットと GUID のネイティブ サポートを追加し、日時値のタイム ゾーン処理を改善して、問題をすべて解決します。</span><span class="sxs-lookup"><span data-stu-id="a5652-106">This feature cleans all that up, adding native support for optionsets and GUIDs and improving the time-zone handling for date/time values.</span></span>