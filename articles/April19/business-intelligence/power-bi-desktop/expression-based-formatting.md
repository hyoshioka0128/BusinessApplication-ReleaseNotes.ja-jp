---
title: 式ベースの書式設定
description: 式ベースの書式設定
author: kimmanis
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: kimani
ms.reviewer: mihart
ms.openlocfilehash: d69d3014179abf8892be392850a699119dd736a4
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287841"
---
# <a name="expression-based-formatting"></a>式ベースの書式設定
[!include[business-intelligence banner](../../includes/business-intelligence.md)]


Power BI ではそのすべてのビジュアルに対してさまざまな書式設定オプションが用意されており、このリリースでは、レポート作成者のために、モデル内のデータに基づいて書式設定を動的に変更するためのより高度な制御が追加されています。 アナリストは、グラフ内のすべての要素の色、スタイル、または表示設定を変更する式を定義できます。 たとえば、金額が目標を超えるたらデータポイントの色が変わるように構成できます。

![式ベースの書式設定を使用したデータの色](media/expression-based-formatting-1.png "式ベースの書式設定を使用したデータの色")
<!-- picture -->
*式ベースの書式設定を使用したデータの色*

または、シリーズの中の 1 行だけスタイルを調整して注意を促すこともできます。

![式ベースの書式設定を使用した線のスタイル](media/expression-based-formatting-2.png "式ベースの書式設定を使用した線のスタイル")
<!-- picture -->
*式ベースの書式設定を使用した線のスタイル*

書式設定は、任意の DAX 式に基づくことができ、レポート内のフィルターのコンテキストの影響を受けます。

この機能は、次の Power BI アイデア要求に応えたものです。

-   [全体的な条件付き書式設定](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/9588453-conditional-formatting-throughout)

-   [より良い条件付き書式設定ツール](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/15495174-better-conditional-formatting-tools)

-   [テキストの条件付き書式設定](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/32184037-conditional-formatting-for-text)

-   [列を使用してデータの色を動的に指定する (例: \#A66999)](https://ideas.powerbi.com/forums/265200-power-bi-ideas/suggestions/13757925-dynamically-specify-data-colour-using-column-e-g)
