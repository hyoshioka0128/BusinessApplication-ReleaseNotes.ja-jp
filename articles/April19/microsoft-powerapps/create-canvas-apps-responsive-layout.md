---
title: レスポンシブ レイアウトでのキャンバス アプリの作成
description: 上級の作成者は、レスポンシブなアプリを作成して、さまざまな環境に動的に調整できます。
author: emcoope-msft
ms.reviewer: anneta
ms.date: 01/09/2019
ms.assetid: 91925503-5314-e911-a97e-000d3a1378f6
ms.topic: article
ms.service: business-applications
ms.author: emcoope
audience: Power user
ms.openlocfilehash: 1d689c355dd83fa0e9acc0a81d94345058dda73b
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210250"
---
# <a name="create-canvas-apps-with-responsive-layout-public-preview"></a>レスポンシブ レイアウトでのキャンバス アプリの作成 (パブリック プレビュー)


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

通常、キャンバス アプリの画面は、アプリ ホストが提供するスペースに収まるように拡張または縮小されます。 これにより、任意の画面で正しい比率で表示されるアプリを作成するのが簡単になります。 ただし、デメリットもあります。画面が大きくなると、アプリは余分な領域を有効活用できなくなります。 今日の多くの Web サイトは "レスポンシブ" です。表示される画面に応じてサイズを調整し、スマートフォンの小さな画面からデスクトップの大きな画面にまで対応しています。  

この機能を使用して、経験豊富なアプリ作成者はレスポンシブなキャンバス アプリを作成できます。 ランタイム時の画面のサイズに基づいて、コントロールのサイズと位置を調整する式を記述する必要があります。 既定のスケーリング動作は無効にできます。 その結果、適切なフォント サイズの情報が画面に表示されるようになり、アプリのエクスペリエンスが向上します。
