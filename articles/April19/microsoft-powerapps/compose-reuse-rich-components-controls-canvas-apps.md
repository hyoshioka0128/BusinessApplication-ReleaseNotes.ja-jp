---
title: キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する
description: キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する
author: yifwang
ms.reviewer: anneta
ms.date: 01/09/2019
ms.assetid: a77bde74-bcc5-e811-a973-000d3a137a43
ms.topic: article
ms.service: business-applications
ms.author: yifwang
audience: Power user
ms.openlocfilehash: 25d392683f17ed64aec8b0f2370783c85f437f72
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287961"
---
# <a name="compose-and-reuse-rich-components-and-controls-in-canvas-apps-public-preview"></a>キャンバス アプリでリッチ コンポーネントとコントロールを作成して再利用する (パブリック プレビュー)


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

作成者は、メニューやカレンダーなどの要素を作成し、同じアプリまたは複数のアプリの複数の画面で共有できます。 作成者は、これらの再利用可能なコンポーネントと複合コントロールを、キャンバス アプリを構築するのと同じように、PowerApps Studio で作成できます。

これらに関する改善点は次のとおりです。

- PowerApps Studio を使用し、キャンバス コントロールと式を使用してコンポーネントを構築する。
- 1 つのアプリ内でコンポーネントを複数回使用する。
- 異なるアプリ間でコンポーネントを使用する。
- コンポーネントを使用するときに必要な入力と出力を定義する。
- 一箇所でコンポーネントを更新し、アプリで使用されるコンポーネントの更新とバージョンを管理する。
- コンポーネントを環境からエクスポートし、環境にインポートする。
- 一般的なシナリオ用の組み込みコンポーネントを使用する。

キャンバス コンポーネントを使用することで、作成者は、画面やアプリ間で構成要素をすばやく作成、使用、共有し、アプリをより迅速に構築し、アプリをより簡単に維持することができます。

![キャンバス コンポーネントを作成する](media/createcomponent.JPG "キャンバス コンポーネントを作成する")