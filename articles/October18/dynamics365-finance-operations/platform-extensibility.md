---
title: "プラットフォーム拡張性の機能強化"
description: "プラットフォーム拡張性の機能強化"
author: ChrisGarty
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 2b59c75306961c1f7182679096aa1336d32d508d
ms.openlocfilehash: de401295109fbcad486c958530bafb8c8c7ce4a0
ms.contentlocale: ja-jp
ms.lasthandoff: 09/20/2018

---

# <a name="platform-extensibility-enhancements"></a>プラットフォーム拡張性の機能強化

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

プラットフォーム更新プログラム 16 からプラットフォーム更新プログラム 20 で強化された拡張性機能:

- フォーム拡張機能を使用してカスタム パターンを使用するようにフォームを変更できます。 これにより、ISV は元のパターンに合わないタブや他のフォーム パーツを追加できます。 開発者は、**パターンをカスタムに設定する**アクションと**元のパターンに戻す**アクションを使用できます。

- 拡張機能で **TableField.AssetClassification** を変更して、一般データ保護規則 (GDPR) のデータ分類情報を提供できます。

- フォーム拡張機能メソッドで、他の拡張機能によって追加されたメソッドとコントロールを呼び出すことができます。 たとえば、現在のフォームにボタンと、拡張機能によって追加されたメソッドがある場合、そのフォームに対する将来の拡張で、新しいボタンとメソッドを呼び出すことができます。

- **update_recordset** メソッドによって、セット ベースの更新ステートメントにクエリ オブジェクトのサポートを追加します。

- クエリ拡張機能で結合クエリにルート データソースを追加できます。

- 拡張機能を使用してビューに範囲を追加できます。

- データ エンティティ ビュー拡張機能で **SupportsSetBasedSqlOperations** を設定できます。 基本要素を含むすべての拡張機能で Yes に設定されている場合にのみ設定できます。 いずれかの拡張機能または基本要素で値が No に設定されている場合、実行時の結果は No になります。

- **WorkflowEnabled**、**WorkflowDataSource**、**WorkflowType** を編集することにより、フォーム拡張機能でフォームにワークフローを追加できます。

- フォーム メソッドに対してコマンド チェーンを有効にします。 具体的には、これにより拡張機能は **canSubmitToWorkflow** メソッドを上書きすることによってフォームにワークフローを追加できます。 対象のフォーム メソッドが X++ 上書きのないカーネル メソッドである場合、対象フォームの再コンパイルが必要であることに注意してください。 

- データ エンティティに対してコマンド チェーンを有効にします。

- データソースとコントロールを含む、フォーム内の入れ子になった型でコマンド チェーンを有効にします。

拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。

