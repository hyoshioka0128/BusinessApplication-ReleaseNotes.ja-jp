---
title: リストのスクロールの改善
description: リストの行を読み込む、スクロールする、ナビゲートするときのエクスペリエンスとパフォーマンスを改善しました。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 02/06/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: end user
ms.openlocfilehash: dc31f8ec4c863afdac6d143b83771157e8c958aa
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225036"
---
#  <a name="improvements-to-scrolling-in-lists"></a>リストのスクロールの改善
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

グリッド パフォーマンス、スクロールおよびキーボード ナビゲーションが向上した Dynamics 365 Business Central のリストで効率的に作業できます。

バックオフィスのインフォメーション ワーカーは、傾向や異常の分析、データの入力や変更など、リストの操作に多くの時間を費やします。 業務データベースが大きくなっても、エクスペリエンスはパフォーマンスを維持し、ユーザーが効率的に作業を続けられるようにする必要があります。 

## <a name="improved-scrolling-and-load-time"></a>スクロールと読み込み時間の向上
リスト内の行の表示方法とデータのフェッチ方法を修正したことで、リストが初めて表示されるまでの時間が短縮され、セル間の移動がスムーズになりました。 ユーザーはキーボードやスクロール バーを使用してリスト内のどこにでも制約なくスクロールできます。「行をさらにフェッチする」のメッセージにより中断が発生することはありません。 行を快適に読むことができるペースでスクロールすると、スクロール エクスペリエンスはシームレスになります。 行は常にオンデマンドで読み込まれ、リストの大きさによってエクスペリエンスが低下しないようにします。 Business Central の 2019 年 4 月の更新プログラムでは、レンガとして表示されたレコードに変更はありません。

![リストをゆっくりスクロールしてからすばやくスクロールする](media/scroll-experience2.gif "長いリストをゆっくりスクロールしてからすばやくスクロールする図")

## <a name="improved-keyboard-navigation"></a>キーボード ナビゲーションの向上
キーボードのカーソル キーを使用した次の行までの上下移動がスムーズになり、キーを押したまま制約なしにナビゲートすることもできます。 複数の行を選択すると、遅延が大幅に短縮されます。

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
