---
title: 製品の見つけやすさの改善
description: 製品の見つけやすさの改善
author: ReneeW-CPub
ms.date: 05/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 7b1e31b07c3ec00757aef56f15e7682bad5c21bb
ms.sourcegitcommit: cab3880e061232d8975a39a1fb6952556bd55274
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "1595000"
---
#  <a name="product-discoverability-enhancements"></a>製品の見つけやすさの改善
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


## <a name="business-value"></a>ビジネス バリュー

すべての小売業者は顧客との対話において、全小売チャネルにわたって製品を見つけやすくすることを重要なツールであると見なしています。

小売業者の顧客は、Web 検索エンジン、洗練された E コマース Web サイト、関連性の高い製品を提案するソーシャル アプリ、入力中の検索候補、ファセット ナビゲーション、ハイライト表示などの機能をすべてほぼ瞬時の応答時間で利用することに慣れています。 適切な商品をすぐに見つけられない場合は、次の E コマース ストアに躊躇なく移動します。

Dynamics 365 for Retail で製品の見つけやすさを改善することで、小売業者がすべてのチャネルにおいて消費者を維持し、コンバージョン率を継続的に高めるのに役立ちます。

## <a name="feature-description"></a>機能の説明

この投資により、既存のエンドユーザーが触れる全クライアントにわたって Azure Search の力を活用し、全チャネルにわたって一貫したエクスペリエンスを提供できます。

**閲覧と検索**

製品の見つけやすさは、主に情報を取得するための検索とコンテンツのナビゲーションに依存するため、オムニチャネル エクスペリエンスにとって検索の関連性とパフォーマンスを高めることが重要です。 効果的かつ効率的な検索は、コンバージョン率の向上に役立ちます。

**リファイナーとファセット ナビゲーション**

ファセット ナビゲーションは、用語セット内の用語に紐付けられているリファイナーに対してフィルターを適用することで、ユーザーがコンテンツをより簡単に閲覧できるようにします。 ファセット ナビゲーションを使用すると、追加のページを作成することなく、用語セット内の異なる用語に対して別個のリファイナーを構成できます。

**価格設定 API の機能強化**

多くの顧客にとって、価格は購入決定を左右する最も重要な要素の 1 つであり、多くの顧客は購入する前にさまざまなサイトで価格を比較します。 そこで、小売業者は競合企業に目を光らせ、頻繁にプロモーションを手がけて競争力のある価格を提供します。 そのため、製品検索、閲覧、品目リスト、製品詳細ページで最も正確な価格を表示することが非常に重要です。 この機能強化により、GetActivePrices API は、カート内の他の品目に依存しない単一明細割引などの単純な割引を含む価格を返します。そのため、表示される価格は、顧客が品目に対して実際に支払う金額に近くなります。 さらに、API は適用された割引の名前と有効性を返して、小売業者が価格についてより詳しい説明を提供し、割引の有効期限がもうすぐ切れる場合に切迫感を生み出せるようにします。 
