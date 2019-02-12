---
title: プラットフォーム拡張性の機能強化ウェーブ 2
description: プラットフォーム拡張性の機能強化ウェーブ 2
author: ChrisGarty
manager: AnnBe
ms.date: 01/08/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: cgarty
audience: developer, customizer
ms.openlocfilehash: 0a5bb977b1831d2439d9ada34004004c15392011
ms.sourcegitcommit: 163b0e8ec8da8ef8bbe43f302c561bbaed43d0be
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/28/2019
ms.locfileid: "290673"
---
# <a name="platform-extensibility-enhancements-wave-2"></a>プラットフォーム拡張性の機能強化ウェーブ 2

プラットフォーム更新プログラム 21 で強化された拡張性機能:

- コマンド チェーン メソッドでは、リソースのクリーンアップやセキュリティ チェックの調整を容易にするために、次の句の周辺で **try-finally** または **unchecked** ブロックがサポートされるようになりました (参照番号 215266、223822)。

- EDT Reals の **ShowZero** を変更できます (参照番号 198765)。

- EDT Strings の **DisplayLength** を変更できます (参照番号 198766)。

- クエリ範囲の **Status** を変更できます (参照番号 198835)。

- フォームの **UseCaptionFromMenuItem** を変更できます (参照番号 198793)。

- ボタンの **NeedsRecord** および **SaveRecord** を変更できます (参照番号 198762)。

- フォーム コントロールの **AllowEdit** および **NeededPermission** を変更できます (参照番号 149754、198836)。

- 拡張クラスで定義された属性を返すように **DictClass.getAllAttributes** を更新しました (参照番号 216149)。

- **DiagnosticsArea**、**DocuFilePlace**、および **DocuTypeGroup** 列挙型を拡張可能にしました (参照番号 223436、241335、238162)。

- **delete_from** メソッドを使用してセット ベースの削除にクエリ オブジェクトのサポートを追加します (参照番号 185500)。

参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。
すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。
