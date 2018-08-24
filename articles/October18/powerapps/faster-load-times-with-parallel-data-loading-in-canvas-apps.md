---
title: "キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮"
description: "アプリ開発者は、複数の読み込みオペレーションを並列で実行して、アプリ ユーザーの全体的な待ち時間を短縮できます。"
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 4b1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 587d76f50fead1766f5dc810e2f9b0bf34bd760a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a>キャンバス アプリでの並列データ読み込みによる読み込み時間の短縮


[!include[banner](../../includes/banner.md)]

多くのキャンバス アプリ開発者は、パフォーマンスを向上させるために、アプリの開始時に複数のテーブルやエンティティをプリロードします。 今日、これはロードごとに順次行われており、多くの場合はアプリの **OnStart** 式で行われます。 

この機能を使用すると、アプリ開発者は複数のデータセットを並列で読み込むことができ、エンドユーザーの待ち時間を大幅に短縮できます。  この機能は起動時だけに限定されておらず、並列処理がパフォーマンスを向上するどの場所でも使用できます。

