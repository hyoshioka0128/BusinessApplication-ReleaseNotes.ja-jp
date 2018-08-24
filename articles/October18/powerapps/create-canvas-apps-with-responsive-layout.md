---
title: "レスポンシブ レイアウトでのキャンバス アプリの作成"
description: "上級の作成者は、レスポンシブなアプリを作成して、さまざまな環境に動的に調整できます。"
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 626bd7380196584d2a772f4c1233c2fb876b2359
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="create-canvas-apps-with-responsive-layout"></a>レスポンシブ レイアウトでのキャンバス アプリの作成

[!include[powerapps banner](../includes/powerapps.md)]




通常、キャンバス アプリの画面はアプリ ホストが提供するスペースに収まるように拡張または縮小されます。  これにより、任意の画面で正しい比率で表示されるアプリを作成するのが簡単になります。  ただし、デメリットもあります。画面が大きくなると、アプリは余分な領域を有効活用できなくなります。  今日の多くの Web サイトは「レスポンシブ」です。表示される画面に応じてサイズを調整し、スマートフォンの小さな画面からデスクトップの大きな画面にまで対応しています。  

この機能を使用して、経験豊富なアプリ開発者はレスポンシブなキャンバス アプリを作成できます。  ランタイム時の画面のサイズに基づいて、コントロールのサイズと位置を調整する式を記述する必要があります。  既定のスケーリング動作は無効にできます。  その結果、適切なフォント サイズの情報が画面に表示されるようになり、アプリのエクスペリエンスが向上します。

