---
title: ページの検査
description: ページおよびページの部分を調べて、データの問題をトラブルシューティングしたり、基になっているデータ モデルを理解したりします。 ページ インスペクターは、現在のレコード、フィルター、およびページに影響を与えている拡張機能についての情報を明らかにします。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: 00ff20da44081218a0560d278f98afbfb64e8e80
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210295"
---
# <a name="page-inspection"></a>ページの検査
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

ビジネス データまたは機能構成のエラーのトラブルシューティングを行うときは、多くの場合、ページに表示されているもの以外の追加レベルの分析情報が必要です。 パワー ユーザーとサポート スタッフは、ページまたはページ内の部分を調べて、ページに表示されていないフィールドなど、現在のレコードの内容全体を明らかにすることができます。

<!--
> ![Inspecting a Sales Order factbox](media/inspect-factbox.png "The page inspection pane alongside a sales order where one of the factboxes is being inspected.")
-->

## <a name="getting-started"></a>作業の開始
デスクトップ ブラウザーまたは Windows デスクトップ アプリで現在表示しているページの検査を開始するには、トップ メニューから**検査**を選択するか、またはキーボード ショートカット **Ctrl + Alt + F1** を使用します。

## <a name="an-evolution-of-the-toolset"></a>ツールセットの進化
Microsoft Dynamics NAV での前身 (一般的に "このページについて" と呼ばれていたもの) とは異なり、ページの検査は、イマーシブで高度にインタラクティブであり、ポイント アンド クリック操作によって、ページ自体の操作を中断することなくページの横に情報が表示されます。 検査対象についての正確な情報の明確さが向上したこととは別に、ページや基になっているテーブルに影響を与えている拡張機能を表示し、それらの拡張機能によって追加されたページやフィールドを知ることができるようになりました。

## <a name="feature-highlights"></a>主な機能
調べているページに応じて、以下の一部または全部が表示されます。

- ページまたはページの部分の名前と識別子。
- 基になっているテーブルの名前と識別子。
- キャプション、値、フィールド識別子、主キー インジケーター、およびそれらを追加した拡張機能など、現在のレコードのテーブル フィールドのセット全体。
- ページまたは基になっているテーブルを拡張する拡張機能。
- テーブルに現在適用されているフィルター。


<!--
 
## Try it now
Inspect the full record data for one of the products or services that you offer, by signing in to your online environment at https://businesscentral.dynamics.com/?page=30

## Resources
Inspecting pages
FAQ about inspecting pages
Keyboard Shortcuts

-->

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
