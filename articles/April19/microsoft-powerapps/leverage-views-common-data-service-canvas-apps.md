---
title: キャンバス アプリで Common Data Service からのビューを活用する
description: キャンバス アプリで Common Data Service からのビューを活用する
author: aorth
ms.reviewer: anneta
ms.date: 04/22/2019
ms.assetid: ed87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: d3b33cb3e209c4702d5fca406daf20a3be96ba8c
ms.sourcegitcommit: 71c309c00b3ce1028adfd94f110aa6682b07af01
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1446329"
---
# <a name="leverage-views-from-common-data-service-in-canvas-apps-public-preview"></a>キャンバス アプリで Common Data Service からのビューを活用する (パブリック プレビュー)

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

キャンバス アプリで、作成者は、Common Data Service のビューに基づいて、ギャラリーを並べ替えたりフィルター処理したりできます。 これにより、ビュー デザイナーの機能が解放され、複雑な一連のフィルター、並べ替え、関連するエンティティ フィールドを集中的に定義できます。 キャンバス デザイナーは、ギャラリーまたはデータ テーブルのコントロールでガイド付きエクスペリエンスを提供します。 これにより、使用するエンティティを推奨し、そのエンティティのパブリック ビューを選択することで、Common Data Service でのデータ ソースの選択が向上します。 作成者はアプリのフィルター処理と並べ替えで**アイテム** プロパティを拡張することができ、それはビューとマージされます。 この改善により、共有ビューの値を取得するときにアプリ固有の動作を実行できます。
