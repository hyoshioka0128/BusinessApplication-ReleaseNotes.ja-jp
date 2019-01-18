---
title: "キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮"
description: "アプリ開発者は、複数の読み込みオペレーションを並列で実行して、アプリ ユーザーの全体的な待ち時間を短縮できます。"
author: gregli-msft
ms.reviewer: anneta
ms.date: 12/10/2018
ms.assetid: 4b1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 9dcc86299144009949bfa3d43b92bae5a26c331c
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a>キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮




多くのキャンバス アプリ開発者は、パフォーマンスを向上させるために、アプリの開始時に複数のテーブルやエンティティをプリロードします。 今日、これはロードごとに順次行われており、多くの場合はアプリの **OnStart** 式で行われます。 

この機能を使用すると、アプリ開発者は複数のデータセットを並列で読み込むことができ、エンドユーザーの待ち時間を大幅に短縮できます。  この機能は起動時だけに限定されておらず、並列処理がパフォーマンスを向上するどの場所でも使用できます。

## <a name="related-topic"></a>関連項目

[新しい同時実行機能によって起動時間が短縮されます](https://powerapps.microsoft.com/blog/enjoy-faster-startup-times-with-the-new-concurrent-function/)
