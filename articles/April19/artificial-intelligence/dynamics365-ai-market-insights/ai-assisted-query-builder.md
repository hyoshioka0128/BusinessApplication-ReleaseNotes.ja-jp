---
title: AI 支援クエリ ビルダー
description: Market Insights に対する関連検索トピックの作成を AI で支援します。
author: m-hartmann
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: mhart
ms.reviewer: m-hartmann
ms.openlocfilehash: d6ef6e395577edb175a4ef4bda433b344c26c50b
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287157"
---
#  <a name="ai-assisted-query-builder"></a>AI 支援クエリ ビルダー
[!include[dynamics365-ai-market-insights banner](../../includes/dynamics365-ai-market-insights.md)]


関連する市場のインサイトを得るためには、検索ルールを正しく設定し、ブランド、製品、およびトピックに関する、ユーザーのニーズとの関連性が高い正確なインサイトを提供することが極めて重要です。 現在、必要な精度レベルまでルールを調整するには通常何週間も作業を繰り返す必要があるため、ユーザーが最初の実行で正しく検索ルールを構成することは困難です。 

この難しさにはいくつかの理由があります。

- 消費者がブランドについて検索したり言及したりするときの呼び方は一通りではありません (たとえば、マクドナルドの代わりにマックや、Facebook の代わりに FB など)。 
- ブランド名は競合していて、複数の業界のエンティティを参照することがあります (たとえば、Dove は石鹸のブランドでもチョコレートのブランドでもあります)。 
- ユーザーはトピックから特定のエンティティを除外したいことがよくあります (たとえば、ユーザーは "Nike Air Jordan 1" のトレンドを追いたくても、"High Zip" モデルは除きたい場合があります)。 
- ユーザーは注目する価値のある関連トピックが何か予測できないことがあります (たとえば、Nike Air を検索した消費者は他に何を検索したでしょうか)。 

その結果、インサイト生成の関連性とコストは、ノイズのカットと適切な検索の設定に大きく依存します。

Microsoft の AI 支援クエリ ビルダーはこの核心的な問題を解決します。 ユーザーが検索語を入力し始めると、最も関連性の高い候補の語が表示されます。 たとえば、ユーザーが「Eagle」と入力した場合、"American Eagle" (衣料品ブランド)、"Eagles" (音楽バンド)、"Philadelphia Eagles" (フットボール チーム) などから選択できます。 AI 支援クエリ ビルダーは、選択候補として関連性の高いブランド、製品、エンティティのリストをユーザーに提供することにより、検索設定の認知的負荷を軽減し、検索の設定にかかる時間を短縮して、インサイトにより多くの時間を費やすことができるようにします。

次のサンプル画面は、ユーザーが「Con」と入力し始めたときのエクスペリエンスです。 "Contoso Ltd." を選択すると、 結果はそれに関連のあるものになり、他の "Con" 関連のノイズは除外されます。

![検索語句を入力したときの検索結果](media/assisted-query-suggestions.png "検索語句を入力したときの検索結果")

