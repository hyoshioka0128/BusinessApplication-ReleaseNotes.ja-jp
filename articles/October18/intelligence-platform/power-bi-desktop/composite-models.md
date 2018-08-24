---
title: "複合モデル"
description: "Power BI Desktop での DirectQuery とインポート データ ソースのマッシュアップのサポート"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, citizen developer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3256b373787e8c32a7ef80faad85e2ebd5f3634e
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="composite-models-public-preview"></a>複合モデル (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

複合モデルを使用すると、インポート ソースと表形式の直接クエリ ソースを混在させることができ、複数の表形式 DirectQuery ソースを使用できます。 これにより、インポートされたテーブルでエンタープライズ データ モデルを拡大できます。 

モデラーは、DirectQuery データ ソースを基にして Power BI Desktop ファイルを作成した後、別のデータ ソースからインポートされたテーブルを追加することもできます。 この新しいモデル構造をサポートするため、デュアル モードの多対多リレーションシップとテーブルが導入されています。これは、ビジュアルに追加される他のテーブルに応じて、インポートまたは DirectQuery として動作できることを意味します。 Power BI は、インポートされたデータから、または基盤となるデータ ソースにクエリをプッシュすることにより、ユーザーの分析に対する回答をインテリジェントに提供します。

<!--
### Who uses this feature
This feature is intended for model developers. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

