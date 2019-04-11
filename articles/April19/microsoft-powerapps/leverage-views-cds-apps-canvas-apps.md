---
title: キャンバス アプリで Common Data Service からのビューを活用する
description: キャンバス アプリで Common Data Service からのビューを活用する
author: aorth
ms.reviewer: anneta
ms.date: 03/14/2019
ms.assetid: 5165dbf9-41e4-e811-a987-000d3a1362e3
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: 80816cd56bdb6f97dd8c4b698ab5b372f19eaf34
ms.sourcegitcommit: ca3b94f829721c2ba02b25134536a58babed2d2b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/27/2019
ms.locfileid: "900472"
---
# <a name="leverage-views-from-common-data-service-in-canvas-apps-public-preview"></a>キャンバス アプリで Common Data Service からのビューを活用する (パブリック プレビュー)


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

キャンバス アプリで、作成者は、Common Data Service のビューに基づいて、ギャラリーを並べ替えたりフィルター処理したりできます。 これにより、ビュー デザイナーの機能が解放され、複雑な一連のフィルター、並べ替え、関連するエンティティ フィールドを集中的に定義できます。 キャンバス デザイナーは、ギャラリーまたはデータ テーブルのコントロールでガイド付きエクスペリエンスを提供します。 これにより、使用するエンティティを推奨し、そのエンティティのパブリック ビューを選択することで、Common Data Service でのデータ ソースの選択が向上します。 作成者はアプリのフィルター処理と並べ替えで**アイテム** プロパティを拡張することができ、それはビューとマージされます。 これにより、共有ビューの値を取得するときにアプリ固有の動作を実行できます。
