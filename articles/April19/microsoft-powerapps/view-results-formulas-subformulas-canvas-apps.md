---
title: キャンバス アプリで式や下位式の結果を表示する
description: キャンバス アプリで式や下位式の結果を表示する
author: gregli-msft
ms.reviewer: anneta
ms.date: 04/22/2019
ms.assetid: c188bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: 080b5a0af4ba5d4e32495e2f105c17a0560f1896
ms.sourcegitcommit: 71c309c00b3ce1028adfd94f110aa6682b07af01
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1445882"
---
# <a name="view-results-of-formulas-and-subformulas-in-canvas-apps-public-preview"></a>キャンバス アプリで式や下位式の結果を表示する (パブリック プレビュー)



キャンバス アプリは、**フィルター**や**ソート**などの関数を使って、強力な式を構成することで機能します。 式の結果は、ギャラリーなどのコントロールに直接送られ、さらなる解析にかけられることもあります。

構成がさらに複雑になってくると、それぞれの関数が結果に及ぼす影響を把握するのが難しくなります。 作成者は、中間結果を変数にキャプチャしたり、別のデバッグ画面でそれを表示したりすることがあります。 透過性が欠如していると、何が起きているのか把握し、問題をデバッグするのが難しくなります。

この機能により、式の中身を把握し、何が起きているのか理解することができます。 他の多くのプログラミング環境と同様に、式バーでは、式全体や式の一部を直接選択して、その部分から流れているデータを表示することができます。 これにより、アプリ コードの把握やデバッグが大幅に簡単で迅速になります。

次に示すのは、数式バーでコンテンツとアカウントの種類を選択したときの画面を表した初期概念図です。

![初期概念図では、数式バーで選択したものの値が結果ビューに表示されています (この場合は Account テーブルのコンテンツ)](media/ResultView.png "初期概念図では、数式バーで選択したものの値が結果ビューに表示されています (この場合は Account テーブルのコンテンツ)")
