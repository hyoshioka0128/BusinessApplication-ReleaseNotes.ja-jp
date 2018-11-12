---
title: "プラットフォーム拡張性の機能強化ウェーブ 3"
description: "プラットフォーム拡張性の機能強化ウェーブ 3"
author: ChrisGarty
manager: AnnBe
ms.date: 10/24/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 46b2e5187225a6f49cf6def793031fbc2a111a99
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---

# <a name="platform-extensibility-enhancements-wave-3"></a>プラットフォーム拡張性の機能強化ウェーブ 3

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

プラットフォーム更新プログラム 22 で強化された拡張性機能:

- コマンド チェーンを有効にして、データ エンティティのテーブルに実装されていないメソッドの上書きをターゲットにします (参照番号 198772)。

- クエリ **insert_recordset** メソッドのターゲット フィールド値をリテラル値に設定できます (参照番号 198849)。

- フォーム データソースの **StartPosition** を変更できます (参照番号 198821)。

- テーブル フィールドの **Visible** と **CountryRegionContext** を変更できます (参照番号 198809、198776)。

- 拡張データソースで Write および ValidateWrite フォーム データソース メソッドをスキップして読み取り専用にできる機能が追加されます (参照番号 198754)。

当初は計画されていたが追加調査の結果追加されなくなった機能:

- テーブル フィールドで **AllowEdit**、**AllowEditOnCreate**、**Mandatory**、および **IgnoreEDTRelation** を変更できるようにする (参照番号 199206) - テーブル フィールドでこれらのプロパティを変更できるようにすると、フィールドの動作が大きく変化します。 代わりに、必要に応じて新しいフィールドを追加します。

- 拡張データ型で **TimeZone** を変更できるようにする (参照番号 237002) – フィールドの EDT でタイム ゾーンの基本設定を変更すると、フィールドが保存される方法が変わります。 "Auto" は、値を UTC タイム ゾーンに変換することを意味します。 "NoConversion" は、値を入力されたまま保存することを意味します。 既存の EDT に対する TimezonePreference を変更すると、その EDT を現在使用している機能に重大な変更が発生します。 代わりに、必要な場合は別の EDT を使用してください。
 
参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。

すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。

