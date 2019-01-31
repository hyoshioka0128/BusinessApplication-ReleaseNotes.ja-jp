---
title: プラットフォーム拡張性の機能強化ウェーブ 3
description: プラットフォーム拡張性の機能強化ウェーブ 3
author: ChrisGarty
manager: AnnBe
ms.date: 01/08/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: cgarty
audience: developer, customizer
ms.openlocfilehash: 7f2b067f83d2a4dc96638c767548fdd6d1a35e3b
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199873"
---
# <a name="platform-extensibility-enhancements-wave-3"></a><span data-ttu-id="af615-103">プラットフォーム拡張性の機能強化ウェーブ 3</span><span class="sxs-lookup"><span data-stu-id="af615-103">Platform extensibility enhancements wave 3</span></span>

<span data-ttu-id="af615-104">プラットフォーム更新プログラム 22 で強化された拡張性機能:</span><span class="sxs-lookup"><span data-stu-id="af615-104">Enhanced extensibility capabilities in Platform update 22:</span></span>

- <span data-ttu-id="af615-105">コマンド チェーンを有効にして、データ エンティティのテーブルに実装されていないメソッドの上書きをターゲットにします (参照番号 198772)。</span><span class="sxs-lookup"><span data-stu-id="af615-105">Enable Chain of Command to target method overrides that have not been implemented to tables and data entities (Ref# 198772).</span></span>

- <span data-ttu-id="af615-106">クエリ **insert_recordset** メソッドのターゲット フィールド値をリテラル値に設定できます (参照番号 198849)。</span><span class="sxs-lookup"><span data-stu-id="af615-106">Allow setting the target field values in a query **insert_recordset** method to literal values (Ref# 198849).</span></span>

- <span data-ttu-id="af615-107">フォーム データソースの **StartPosition** を変更できます (参照番号 198821)。</span><span class="sxs-lookup"><span data-stu-id="af615-107">Allow changes to **StartPosition** on form datasources (Ref# 198821).</span></span>

- <span data-ttu-id="af615-108">テーブル フィールドの **Visible** と **CountryRegionContext** を変更できます (参照番号 198809、198776)。</span><span class="sxs-lookup"><span data-stu-id="af615-108">Allow changes to **Visible** and **CountryRegionContext** on table fields (Ref# 198809, 198776).</span></span>

- <span data-ttu-id="af615-109">拡張データソースで Write および ValidateWrite フォーム データソース メソッドをスキップして読み取り専用にできる機能が追加されます (参照番号 198754)。</span><span class="sxs-lookup"><span data-stu-id="af615-109">Add the ability to skip the Write and ValidateWrite form datasource methods on extended datasources so they can be made read-only (Ref# 198754).</span></span>

<span data-ttu-id="af615-110">当初は計画されていたが追加調査の結果追加されなくなった機能:</span><span class="sxs-lookup"><span data-stu-id="af615-110">Capabilities originally planned but not added after further investigation:</span></span>

- <span data-ttu-id="af615-111">テーブル フィールドで **AllowEdit**、**AllowEditOnCreate**、**Mandatory**、および **IgnoreEDTRelation** を変更できるようにする (参照番号 199206) - テーブル フィールドでこれらのプロパティを変更できるようにすると、フィールドの動作が大きく変化します。</span><span class="sxs-lookup"><span data-stu-id="af615-111">Allow changes to **AllowEdit**, **AllowEditOnCreate**, **Mandatory**, and **IgnoreEDTRelation** on table fields (Ref# 199206) – The ability to change these properties on Table Fields would result in breaking changes to the behavior of the field.</span></span> <span data-ttu-id="af615-112">代わりに、必要に応じて新しいフィールドを追加します。</span><span class="sxs-lookup"><span data-stu-id="af615-112">Instead, add new fields as needed.</span></span>

- <span data-ttu-id="af615-113">拡張データ型で **TimeZone** を変更できるようにする (参照番号 237002) – フィールドの EDT でタイム ゾーンの基本設定を変更すると、フィールドが保存される方法が変わります。</span><span class="sxs-lookup"><span data-stu-id="af615-113">Allow changes to **TimeZone** on extended data types (Ref# 237002) – If the timezone preference is changed for a field's EDT, then it changes the way that fields are stored.</span></span> <span data-ttu-id="af615-114">"Auto" は、値を UTC タイム ゾーンに変換することを意味します。</span><span class="sxs-lookup"><span data-stu-id="af615-114">"Auto" means convert the value to UTC timezone.</span></span> <span data-ttu-id="af615-115">"NoConversion" は、値を入力されたまま保存することを意味します。</span><span class="sxs-lookup"><span data-stu-id="af615-115">"NoConversion" means store the value as entered.</span></span> <span data-ttu-id="af615-116">既存の EDT に対する TimezonePreference を変更すると、その EDT を現在使用している機能に重大な変更が発生します。</span><span class="sxs-lookup"><span data-stu-id="af615-116">Changing the TimezonePreference for an existing EDT is a breaking change on the functionality currently leveraging that EDT.</span></span> <span data-ttu-id="af615-117">代わりに、必要な場合は別の EDT を使用してください。</span><span class="sxs-lookup"><span data-stu-id="af615-117">Instead, use a different EDT if needed.</span></span>
 
<span data-ttu-id="af615-118">参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。</span><span class="sxs-lookup"><span data-stu-id="af615-118">Ref numbers correspond to specific extensibility request IDs that are used internally and available externally.</span></span>

<span data-ttu-id="af615-119">すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="af615-119">For more information about all extensibility capabilities, see the [Extensibility home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>
