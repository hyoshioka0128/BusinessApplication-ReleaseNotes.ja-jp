---
title: Retail 拡張プラットフォームと開発者エクスペリエンスの改善
description: Retail 拡張プラットフォームと開発者エクスペリエンスの改善
author: ReneeW-CPub
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 1d183bedf009adc5dd3156e378d0874545fbf598
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210989"
---
#  <a name="retail-extension-platform-and-developer-experience-enhancement"></a>Retail 拡張プラットフォームと開発者エクスペリエンスの改善
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


注文属性などの新機能の導入や拡張ポイントの増加 (API、トリガー、オーバーライド可能なハンドラー) により、カスタマイズ、パッケージ化、展開エクスペリエンスを簡略化する Retail の拡張フレームワークを大幅に強化しています。

## <a name="business-value"></a>ビジネス バリュー

新しいフレームワークと拡張ポイントにより、新しいバージョンをカスタマイズするのに必要な作業が軽減され、簡単にアップグレードできます。

### <a name="development-enhancements"></a>開発に関わる機能の強化

さまざまな拡張シナリオに対応するために、多くの新しい拡張ポイントを追加しました。 開発者は、カスタム コントロール、アプリ バー ボタン、カスタム列でユーザー インターフェイスを拡張したり、カスタム ビューを作成したりできます。 さまざまな拡張シナリオに対応するために、多くの新しいオーバーライド可能な要求とトリガーが POS に追加されました。 カートとジャーナル ビューにはカスタム コメントのサポートが追加され、POS UI 拡張を簡素化するために多くのダイアログ コントロールと POS コントロールが追加されました。 また、POS 画面レイアウト デザイナーは、成果物タブのカスタム列および合計パネルのカスタム コントロールとカスタム フィールドをサポートするように拡張されました。

**新しい拡張ポイントの完全なリストについては、次のトピックを参照してください。**

[POS API ](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-apis "Retail POS API ")

[POS ビュー](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-view-extension "POS ビュー拡張")

[POS トリガー](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-trigger-printing "POS トリガー拡張")

[CRT サービス](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/crt-services "CRT サービス")

[POS カスタム列](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/pos-custom-transaction-column "POS カスタム列")

[POS カスタム フィールド](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/custom-field-pos-totals "POS 合計パネル") 

### <a name="order-attributes"></a>注文属性

現金持ち帰り (C&C) トランザクションと顧客注文の属性値を POS から直接表示し、更新するように注文属性フレームワークの機能を強化しています。 この新機能により、小売業者は小売用バックオフィスの画面レイアウト デザイナーで属性コントロールのレイアウト位置を構成し、POS でそのパネルにアクセスして C&C トランザクションと顧客注文ヘッダーおよび明細行の両方の属性値をコードを使用せずに設定できます。


#### <a name="display-attribute-in-pos"></a>POS の属性を表示する

![POS トランザクション ビューの新しい属性コントロール](media/retail-extension-platform-developer-experience-enhancement-4.png "POS トランザクション ビューの新しい属性コントロール")


#### <a name="edit-attribute-in-pos"></a>POS の属性を編集する

![POS の属性値を編集するためのダイアログ コントロール](media/retail-extension-platform-developer-experience-enhancement-5.png "POS の属性値を編集するためのダイアログ コントロール")


