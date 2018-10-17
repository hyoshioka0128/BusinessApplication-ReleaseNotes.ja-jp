---
title: "プラットフォーム拡張性の機能強化ウェーブ 3"
description: "プラットフォーム拡張性の機能強化ウェーブ 3"
author: ChrisGarty
manager: AnnBe
ms.date: 09/18/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 2b59c75306961c1f7182679096aa1336d32d508d
ms.openlocfilehash: ce99db818fd1609c944fd2602a04dab5928ccb85
ms.contentlocale: ja-jp
ms.lasthandoff: 09/20/2018

---

# <a name="platform-extensibility-enhancements-wave-3"></a>プラットフォーム拡張性の機能強化ウェーブ 3

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

プラットフォーム更新プログラム 22 で強化された拡張性機能:
- コマンド チェーンを有効にして、データ エンティティのテーブルに実装されていないメソッドの上書きをターゲットにします (参照番号 198772)。
- テーブル拡張機能でフィールド グループ内のフィールドの順序を変更できます (参照番号 198798)。
- 開発者が**拡張機能の拡張機能**を作成できるように、拡張機能クラスでコマンド チェーンを有効にします (参照番号 198848)。
- 拡張クラスでの **DataMemberAttribute** の追加をサポートします (参照番号 199219)。
- クエリ **insert_recordset** メソッドのターゲット フィールド値をリテラル値に設定できます (参照番号 198849)。
- **delete_from** メソッドを使用してセット ベースの削除にクエリ オブジェクトのサポートを追加します (参照番号 185500)。
- コマンド チェーンはオーバーライドされたカーネル メソッドではないフォーム コントロールおよびデータ ソースを X++ メソッドのターゲットにすることができます (参照番号 238379)。
- インターフェイスを実装するためのフォームの拡張をサポートします (参照番号 199225)。
- 拡張機能を使用して FormDataSource に表示および編集メソッドを追加できます (参照番号 235521)。
- ビュー拡張機能で計算列を使用できます (参照番号 198807)。
- 外部結合データ ソースを追加し、**Write** および **ValidateWrite** カーネル呼び出しをスキップして読み取り専用にすることができます (参照番号 198768)。
- テーブル フィールドの **Visible**、**CountryRegionContext**、**AllowEdit**、**AllowEditOnCreate**、**Mandatory**、**IgnoreEDTRelation** を変更できます (参照番号 198809、198776、199206)。
- データ エンティティ フィールドの **Mandatory**、**IsManuallyUpdated**、**AllowEdit**、**AllowEditOnCreate** を変更できます (参照番号 198818)。
- セキュリティ ロールに **duties** と **privileges** を追加できます (参照番号 198819)。
- 拡張データ型の **TimeZone** と **Extends** を変更できます (参照番号 237002、238531)。
- クエリ データソースに新しい関係を追加できます (参照番号 198823)。

参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。

すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。

