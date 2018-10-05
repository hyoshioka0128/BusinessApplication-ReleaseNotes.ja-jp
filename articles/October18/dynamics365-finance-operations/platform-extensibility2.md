---
title: "プラットフォーム拡張性の機能強化ウェーブ 2"
description: "プラットフォーム拡張性の機能強化ウェーブ 2"
author: ChrisGarty
manager: AnnBe
ms.date: 08/09/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 2b59c75306961c1f7182679096aa1336d32d508d
ms.openlocfilehash: eef19354500687c16206dbbba817d6da858a4071
ms.contentlocale: ja-jp
ms.lasthandoff: 09/20/2018

---

# <a name="platform-extensibility-enhancements-wave-2"></a>プラットフォーム拡張性の機能強化ウェーブ 2

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

プラットフォーム更新プログラム 21 で強化された拡張性機能:
- コマンド チェーン メソッドでは、リソースのクリーンアップやセキュリティ チェックの調整を容易にするために、次の句の周辺で **try-finally** または **unchecked** ブロックがサポートされるようになりました (参照番号 215266、223822)。
- EDT Reals の **ShowZero** を変更できます (参照番号 198765)。
- EDT Strings の **DisplayLength** を変更できます (参照番号 198766)。
- クエリ範囲の **Status** を変更できます (参照番号 198835)。
- フォームの **UseCaptionFromMenuItem** を変更できます (参照番号 198793)。
- ボタンの **NeedsRecord** および **SaveRecord** を変更できます (参照番号 198762)。
- フォーム コントロールの **AllowEdit** および **NeededPermission** を変更できます (参照番号 149754、198836)。
- フォーム データソースの **StartPosition** を変更できます (参照番号 198821)。
- 拡張クラスで定義された属性を返すように **DictClass.getAllAttributes** を更新しました (参照番号 216149)。
- **DiagnosticsArea**、**DocuFilePlace**、および **DocuTypeGroup** 列挙型を拡張可能にしました (参照番号 223436、241335、238162)。

参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。
すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。
)。

