---
title: プラットフォーム拡張性の機能強化ウェーブ 2
description: プラットフォーム拡張性の機能強化ウェーブ 2
author: ChrisGarty
manager: AnnBe
ms.date: 02/25/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: cgarty
audience: developer, customizer
ms.openlocfilehash: b5f080c19c7d62aa004fb4e9dad962fffc2ef5bd
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225244"
---
# <a name="platform-extensibility-enhancements-wave-2"></a>プラットフォーム拡張性の機能強化ウェーブ 2
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

プラットフォーム更新プログラム 25 で強化された拡張性機能:

- InternalUseOnlyAttribute メソッドのコマンド チェーン (CoC) をエラーから警告にダウングレードします (参照番号 289075)。 InternalUseOnlyAttribute の詳細については、「[拡張性に関するよく寄せられる質問](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/app-sealing-faq)」を参照してください。

- 拡張機能を使用してクエリに 'order by' フィールドを追加できます (参照番号 198811)。

- 拡張機能を使用して追加された兄弟フォーム コントロールのスタイル プロパティ値の既定値の設定が向上します (参照番号 198824)。

- EDT の DisplayHeight を変更できます (参照番号 247167)。

- formHasMethod 関数が ExtentionOf クラスのメソッドに対して機能するようになります (参照番号 199220)。

- CoS を介してカスタム ボタンを追加できるように、SysSystemDefinedButtons.addButtonsToActionPane メソッドを protected に調整します (参照番号 272356)。

- CoC を介した重要部分のターゲット設定を可能にするために、NumberSequenceDetails.updateFormat、EventContextDrillDown.drillDown、SysEmailTable.showEmailBody からメソッドを抽出しました (参照番号 270780、278611、269568)。

- ワークフロー電子メールの書式設定を可能にするために、finalFormatMessageText デリゲートを WorkflowDocumentField.substitutePlaceholderAsUser に追加します (参照番号 262556)。

- CoC ターゲット設定を可能にするために、NumberSeqScope.getParameterValue を protected に変更します (参照番号 262866)。

- 拡張性を提供するために SysPickList にクラス変数 parmTxt を追加します (参照番号 235796)。

- CoC ターゲット設定を可能にするために、WorkflowDocIsQueueEnabledAttribute から InternalUseOnlyAttribute を削除します (参照番号 264119)。

- SysEmailDistributor に initializeMessageBuilder メソッドを追加して、送信前に電子メールにアクセスできるようにします (参照番号 256434)。

拡張性に関するすべての機能の詳細については、[拡張機能のホーム ページ](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。
