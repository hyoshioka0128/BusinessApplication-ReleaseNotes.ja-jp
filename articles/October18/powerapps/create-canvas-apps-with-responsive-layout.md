---
title: "レスポンシブ レイアウトでのキャンバス アプリの作成"
description: "上級の作成者は、レスポンシブなアプリを作成して、さまざまな環境に動的に調整できます。"
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 1f1c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: d05b7f98dacf2b7de00e82ea53c5314b3c703826
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---
# <a name="create-canvas-apps-with-responsive-layout-public-preview"></a>レスポンシブ レイアウトでのキャンバス アプリの作成 (パブリック プレビュー)


[!include[banner](../../includes/banner.md)]

通常、キャンバス アプリの画面はアプリ ホストが提供するスペースに収まるように拡張または縮小されます。  これにより、任意の画面で正しい比率で表示されるアプリを作成するのが簡単になります。  ただし、デメリットもあります。画面が大きくなると、アプリは余分な領域を有効活用できなくなります。  今日の多くの Web サイトは "レスポンシブ" です。表示される画面に応じてサイズを調整し、スマートフォンの小さな画面からデスクトップの大きな画面にまで対応しています。  

この機能を使用して、経験豊富なアプリ開発者はレスポンシブなキャンバス アプリを作成できます。  ランタイム時の画面のサイズに基づいて、コントロールのサイズと位置を調整する式を記述する必要があります。  既定のスケーリング動作は無効にできます。  その結果、適切なフォント サイズの情報が画面に表示されるようになり、アプリのエクスペリエンスが向上します。

