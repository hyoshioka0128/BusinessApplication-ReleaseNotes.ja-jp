---
title: 簡単入力
description: 簡単入力機能は、使用頻度の低いフィールドはスキップすることで、レコードの繰り返し入力に要する時間を短縮します。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: ea8949190962c780898a0eb0ed5d0a3c11256478
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210829"
---
# <a name="quick-entry"></a>簡単入力
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

デスクトップ ブラウザーおよび Windows デスクトップ アプリ用の強力な簡単入力機能を使用して、レコードの繰り返し入力に要する時間を短縮します。

## <a name="business-value"></a>ビジネス バリュー
デスクトップ ユーザーは、電話での注文の受付、領収書のデジタル化、新しい品目の登録など、情報を繰り返し入力して連続するレコードを作成するのに、かなりの時間を費やしています。 ユーザーはページ上でできるだけ多くの詳細を表示することを求める一方で、レコードを作成するときに一貫して入力する必要があるフィールドはほんの一部に過ぎません。 Tab キーを使用したページ上のフィールドの移動順序は決まっているため、マウスを使用せずに作業しているユーザーにとって、それらの必須フィールドを移動することは負担になります。

簡単入力は、ページ上の編集可能なフィールドを移動する代替手段を提供する、シンプルかつ強力な機能です。 Enter キーの動作は Tab キーの動作とは異なり、必須でないフィールドをスキップし、そのページの次の簡単入力フィールドにフォーカスを移動します。

> [!div class="mx-imgBorder"] 
> ![簡単入力の対象のフィールドが人為的にハイライト表示されている、複数のフィールドが存在するページのスクリーンショット。](media/quick-entry-animated.gif "簡単入力の対象のフィールドが人為的にハイライト表示されている文書ページ")

## <a name="including-or-excluding-fields-from-the-quick-entry-path"></a>簡単入力パスに対するフィールドの追加または除外
簡単入力は最新かつイマーシブなパーソナル化エクスペリエンスを使用してパーソナライズ可能で、ユーザーは Business Central を自身または自身の部署のデータ入力方法に合わせてカスタマイズできます。

開発者は自身のアプリケーションで簡単入力フィールドの初期パスをページごとに定義し、それを拡張機能でカスタマイズできるほか、特定のロールのプロファイルに合わせてカスタマイズすることもできます。 さらに、QuickEntry AL プロパティは簡単入力の動的パスを別個のフィールドに作成する式をサポートします。

## <a name="a-truly-productive-experience"></a>生産性の高いエクスペリエンス
簡単入力は集中的に利用するユーザーのニーズに合わせて慎重に設計されており、Dynamics NAV の以前の簡単入力機能から次のように改善されています。

- **Enter** キー、**Shift+Enter** キー、**Shift+Ctrl+Enter** などの強力なキーの組み合わせを使用することで、編集可能な部分 (リスト部分など) の内外への移動を含め、そのページのすべての簡単入力フィールドに移動できる。
- 次の簡単入力フィールドがそのグループ内にある場合に、折りたたまれたクイック タブ (フィールド グループ) を展開する。
- そのページの最後の簡単入力フィールドに到達すると一回りして最初のフィールドに戻る。
 
<!--
 
## Try it now
Experience the difference between using Tab and Enter keys on a new sales order by signing in to your online environment at https://businesscentral.dynamics.com/?page=42&mode=create

## Resources
Using Quick Entry 
Keyboard Shortcuts
Personalize your workspace
Technical Documentation: QuickEntry property
Technical Documentation: Using the Designer

-->

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
