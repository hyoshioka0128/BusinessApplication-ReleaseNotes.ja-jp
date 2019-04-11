---
title: プラットフォーム拡張性の機能強化
description: プラットフォーム拡張性の機能強化
author: ChrisGarty
manager: AnnBe
ms.date: 03/19/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: cgarty
audience: developer, customizer
ms.openlocfilehash: cba088fc47a7a8296a7f22011c0fbe8d94116a3f
ms.sourcegitcommit: 9d9f57d7fa917a6e3185205bf59537229546a00c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/19/2019
ms.locfileid: "861127"
---
# <a name="platform-extensibility-enhancements"></a>プラットフォーム拡張性の機能強化

Platform update 24 で強化された拡張性機能:

- フォーム ボタン コントロールに 'OnClicking' イベントを追加します (参照番号 215644)。

- フォーム内の種類 (コントロールとデータ ソース) に対するカーネル メソッドのオーバーライドではないメソッドでコマンド チェーン (CoC) が可能です (参照番号 238379)。

- フォーム拡張機能を使用して参照データソースを追加できます (参照番号 224810)。

- テーブル リレーションに固定値を設定できます (参照番号 198778)。

- 拡張機能を使用してフォーム データソースの表示および編集メソッドを追加できます (参照番号 261093)。

- SysEmailTable.sendMail から SysEmailTable.getMessageBody を抽出し、EventNotificationWorkflow.sendMail で CoC を許可して、送信前に電子メール メッセージにアクセスできます (参照番号 269551、262554)。

- 新しい SysWorkflowWorkItemHelper クラスを使用して、SysWorkflowWorkItem.createWorkItems で作業項目の作成に影響を与えることができます (参照番号 246996)。

- NumberSeqScope、NumberSeqDatatype、NumberSequenceTable を変更して、番号順序の拡張性を向上させます (参照番号 262867、259702、245745)。

- SysChartTitle、PowerBIControlBuild、EventNotificationBatch などのさまざまなクラスの拡張性が向上します (参照番号 280964、280963、275376)。

拡張性に関するすべての機能の詳細については、[拡張機能のホーム ページ](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。
