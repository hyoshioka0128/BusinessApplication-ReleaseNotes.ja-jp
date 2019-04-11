---
title: AI 支援クエリ ビルダー
description: Market Insights に対する関連検索トピックの作成を AI で支援します。
author: m-hartmann
ms.date: 03/20/2019
ms.topic: article
ms.service: business-applications
ms.author: mhart
ms.reviewer: m-hartmann
ms.openlocfilehash: 920f89b009e611a551a42a7cec815bc44803943c
ms.sourcegitcommit: 4db495226091126eecdfb6795702b2d7a4c22a3d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2019
ms.locfileid: "881190"
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

![支援クエリの入力候補](media/assisted-query-list.png "支援クエリの入力候補")

Microsoft の AI 支援クエリ ビルダーはこの核心的な問題を解決します。 ユーザーが検索語を入力し始めると、最も関連性の高い候補の語が表示されます。 たとえば、ユーザーが「Eag」と入力し始めると、"Eagle" (鳥)、""Philadelphia Eagles" (フットボール チーム)、"Eagle Scout" (ボーイスカウト) などから選択できます。 AI 支援クエリ ビルダーは、選択候補として関連性の高いブランド、製品、エンティティのリストをユーザーに提供することにより、検索設定の認知的負荷を軽減し、検索の設定にかかる時間を短縮して、インサイトにより多くの時間を費やすことができるようにします。
