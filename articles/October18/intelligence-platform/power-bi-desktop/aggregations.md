---
title: "集約"
description: "DirectQuery によってユーザーによる詳細レベルへのドリルダウンを可能にしながら、集約されたクエリのキャッシュをサポート"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 40cbd22fb19eb8a5799b6ccb8a9ea5eec6a1576f
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="aggregations-public-preview"></a>集約 (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

大量のデータには、フィルターによる対話型分析と詳細レベル レポートのニーズのバランスを取る新しい情報格納方法が必要です。 集約機能により、モデル開発者は対話型分析のために高レベルでキャッシュされた値を表示でき、ユーザーは基になるデータからクエリされた詳細データにドリルダウンすることができます。

Spark クラスターや大規模データ ウェアハウスなど、大量のデータ ソースに対する DirectQuery モデルを作成できます。 対話型分析の場合、これらのデータセットに対してクエリを直接実行するのは実際的でありません。 しかし、数百テラバイトもの大きさになる可能性があるデータセットでは、すべてのデータをメモリ内にキャッシュすることはできません。 集約を使うと、集約データだけをメモリにキャッシュしてすばやくアクセスできます。 集約テーブルとしてデータ モデル内にテーブルを定義し、詳細レベルでテーブルにリンクします。 

詳細テーブルは DirectQuery モードのままですが、集約はデュアル モードとして定義されるので、データは集約レベルでメモリにもキャッシュされます。 ユーザーがメモリ内キャッシュから応答できるクエリを実行したりビジュアルを作成したりした場合、結果はメモリから取得されます。 一方、クエリで詳細データが必要な場合は、基になる DirectQuery ソースに動的に渡されます。 エンド ユーザーが Power BI レポートのエクスペリエンスで違いに気付くことはありません。

<!--
### Who uses this feature
This feature is intended for advanced modelers. It enables them to create data models with aggregate tables linked together to make sure that their end-user reports are designed to encourage filtering of data before queries are served from the DirectQuery source. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

