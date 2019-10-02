---
title: キャンバス アプリによる所有者、顧客、関連エンティティに対するポリモーフィック ルックアップのサポート
description: キャンバス アプリでは、新しいデータ型とヘルパー関数を使用して、タイプセーフな方法で所有者、顧客、関連ポリモーフィック ルックアップ フィールドにアクセスできます。
author: gregli-msft
ms.reviewer: pehecke
ms.date: 07/16/2019
ms.assetid: c186bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: 69c85031d5702871f7b96c2490f1dd9f41a9c88a
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1994295"
---
# <a name="canvas-app-support-for-polymorphic-lookups-to-the-owner-customer-and-regarding-entities"></a><span data-ttu-id="d1da7-103">キャンバス アプリによる所有者、顧客、関連エンティティに対するポリモーフィック ルックアップのサポート</span><span class="sxs-lookup"><span data-stu-id="d1da7-103">Canvas-app support for polymorphic lookups to the Owner, Customer, and Regarding entities</span></span>



<span data-ttu-id="d1da7-104">キャンバス アプリ メーカーは、**所有者**、**顧客**、**関連**エンティティに対するポリモーフィック ルックアップを厳密に型指定された方法で操作できます。</span><span class="sxs-lookup"><span data-stu-id="d1da7-104">Canvas-app makers can work with polymorphic lookups to the **Owner**, **Customer**, and **Regarding** entities in a strongly typed manner.</span></span> <span data-ttu-id="d1da7-105">キャンバス アプリの式言語では、これらの参照を操作するために**レコードの参照**データ型と **IsType** および **AsType** 関数を追加しました。</span><span class="sxs-lookup"><span data-stu-id="d1da7-105">In the formula language for canvas apps, we've added the **Record Reference** data type and the **IsType** and **AsType** functions for working with those references.</span></span> <span data-ttu-id="d1da7-106">この機能では、**アプリの設定**の下の **CDS のリレーショナル データ、オプション セット、その他の新機能**の設定を有効にする必要があります。これは既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="d1da7-106">This functionality requires the **Relational data, option sets, and other new features for CDS** setting under **App settings** to be enabled, as it is by default.</span></span> 

<span data-ttu-id="d1da7-107">この変更を行う前は、これらのフィールドをブロックしていました。ポリモーフィック ルックアップは Common Data Service で型指定なしで公開され、キャンバス アプリは本質的に厳密に型指定されるためです。</span><span class="sxs-lookup"><span data-stu-id="d1da7-107">Before this change, we blocked these fields because polymorphic lookups are exposed in an untyped manner in Common Data Service and canvas apps are inherently strongly typed.</span></span> <span data-ttu-id="d1da7-108">これらのフィールドを操作するには、アプリ メーカーが GUID ID とエンティティ タイプ文字列を管理する必要があり、マイクロソフトでは、これらのフィールドを使用可能にする前に、より優れたエクスペリエンスを提供したいと考えていました。</span><span class="sxs-lookup"><span data-stu-id="d1da7-108">To work with these fields, app makers would have had to manage GUID IDs and entity-type strings, and we wanted to provide a better experience before we made these fields available.</span></span>
