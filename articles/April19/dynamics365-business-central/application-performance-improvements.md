---
title: アプリケーションのパフォーマンスの向上
description: Business Central におけるアプリケーションのパフォーマンスの向上
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 3b90d7b310c45ffe6b98005f206e8c3f2ca57319
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878726"
---
# <a name="application-performance-improvements"></a>アプリケーションのパフォーマンスの向上

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

ユーザー テレメトリから、Business Central アプリケーションの多数のパフォーマンスの問題が特定され、修正されました。

- 実行時間の長い SQL クエリを分析した結果、キーが最適化され、予期しないロックの問題が発見されて除去されました。
- 販売明細行および購買注文明細行テーブルの SIFT インデックスにおけるロックの問題が修正されました。
- 上位 5/10 件の顧客グラフ、アクティビティ パーツ、およびミニ試算表でデータがキャッシュされるようになりました。
- 品目、仕入先、顧客の検索を高速化するために、それぞれの専用の検索ページが追加されました。
- 静的コード分析の結果、インデックスを減らした FlowFields とインデックスのない FlowFields がいくつか発生し、はるかに高速に読み取ることができるようになりました。
- 販売ドキュメントおよび購買ドキュメントの編集ページで、データ入力を高速化するためにフィールドごとのすべての明細行の再計算が廃止されました。
- ワークフロー サブシステムがより速く実行できるように最適化されました。
- [自分の顧客]、[自分の仕入先]、[自分の項目]、[自社会社コード] の実行が高速になりました。

## <a name="tell-us-what-you-think"></a>フィードバック

Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
