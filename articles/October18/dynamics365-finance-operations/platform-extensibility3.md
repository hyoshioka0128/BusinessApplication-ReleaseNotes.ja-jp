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

# <a name="platform-extensibility-enhancements-wave-3"></a><span data-ttu-id="2ccb1-103">プラットフォーム拡張性の機能強化ウェーブ 3</span><span class="sxs-lookup"><span data-stu-id="2ccb1-103">Platform extensibility enhancements wave 3</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="2ccb1-104">プラットフォーム更新プログラム 22 で強化された拡張性機能:</span><span class="sxs-lookup"><span data-stu-id="2ccb1-104">Enhanced extensibility capabilities in Platform update 22:</span></span>
- <span data-ttu-id="2ccb1-105">コマンド チェーンを有効にして、データ エンティティのテーブルに実装されていないメソッドの上書きをターゲットにします (参照番号 198772)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-105">Enable Chain of Command to target method overrides that have not been implemented to Tables and Data Entities (Ref# 198772).</span></span>
- <span data-ttu-id="2ccb1-106">テーブル拡張機能でフィールド グループ内のフィールドの順序を変更できます (参照番号 198798)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-106">Enable a table extension to change the order of fields in a field group (Ref# 198798).</span></span>
- <span data-ttu-id="2ccb1-107">開発者が**拡張機能の拡張機能**を作成できるように、拡張機能クラスでコマンド チェーンを有効にします (参照番号 198848)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-107">Enable Chain of Command on extension classes so that developers can create **extensions of extensions** (Ref# 198848).</span></span>
- <span data-ttu-id="2ccb1-108">拡張クラスでの **DataMemberAttribute** の追加をサポートします (参照番号 199219)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-108">Support adding **DataMemberAttribute** on extension classes (Ref# 199219).</span></span>
- <span data-ttu-id="2ccb1-109">クエリ **insert_recordset** メソッドのターゲット フィールド値をリテラル値に設定できます (参照番号 198849)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-109">Allow setting the target field values in a Query **insert_recordset** method to literal values (Ref# 198849).</span></span>
- <span data-ttu-id="2ccb1-110">**delete_from** メソッドを使用してセット ベースの削除にクエリ オブジェクトのサポートを追加します (参照番号 185500)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-110">Add query object support for set-based delete by using a **delete_from** method (Ref# 185500).</span></span>
- <span data-ttu-id="2ccb1-111">コマンド チェーンはオーバーライドされたカーネル メソッドではないフォーム コントロールおよびデータ ソースを X++ メソッドのターゲットにすることができます (参照番号 238379)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-111">Enable Chain of Command to target X++ methods on form controls and data sources that are not overridden kernel methods (Ref# 238379).</span></span>
- <span data-ttu-id="2ccb1-112">インターフェイスを実装するためのフォームの拡張をサポートします (参照番号 199225)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-112">Support extending a form to implement an interface (Ref# 199225).</span></span>
- <span data-ttu-id="2ccb1-113">拡張機能を使用して FormDataSource に表示および編集メソッドを追加できます (参照番号 235521)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-113">Enable adding display and edit methods to a FormDataSource via extension (Ref# 235521).</span></span>
- <span data-ttu-id="2ccb1-114">ビュー拡張機能で計算列を使用できます (参照番号 198807)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-114">Allow computed columns on view extensions (Ref# 198807).</span></span>
- <span data-ttu-id="2ccb1-115">外部結合データ ソースを追加し、**Write** および **ValidateWrite** カーネル呼び出しをスキップして読み取り専用にすることができます (参照番号 198768)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-115">Allow adding outer join data sources and making them read-only by skipping the **Write** and **ValidateWrite** kernel calls (Ref# 198768).</span></span>
- <span data-ttu-id="2ccb1-116">テーブル フィールドの **Visible**、**CountryRegionContext**、**AllowEdit**、**AllowEditOnCreate**、**Mandatory**、**IgnoreEDTRelation** を変更できます (参照番号 198809、198776、199206)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-116">Allow changes to **Visible**, **CountryRegionContext**, **AllowEdit**, **AllowEditOnCreate**, **Mandatory**, and **IgnoreEDTRelation** on table fields (Ref# 198809, 198776, 199206).</span></span>
- <span data-ttu-id="2ccb1-117">データ エンティティ フィールドの **Mandatory**、**IsManuallyUpdated**、**AllowEdit**、**AllowEditOnCreate** を変更できます (参照番号 198818)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-117">Allow changes to **Mandatory**, **IsManuallyUpdated**, **AllowEdit**, and **AllowEditOnCreate** on data entity fields (Ref# 198818).</span></span>
- <span data-ttu-id="2ccb1-118">セキュリティ ロールに **duties** と **privileges** を追加できます (参照番号 198819)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-118">Allow adding **duties** and **privileges** into a security role (Ref# 198819).</span></span>
- <span data-ttu-id="2ccb1-119">拡張データ型の **TimeZone** と **Extends** を変更できます (参照番号 237002、238531)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-119">Allow changes to **TimeZone** and **Extends** on extended data types (Ref# 237002, 238531).</span></span>
- <span data-ttu-id="2ccb1-120">クエリ データソースに新しい関係を追加できます (参照番号 198823)。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-120">Allow adding new relations to query datasources (Ref# 198823).</span></span>

<span data-ttu-id="2ccb1-121">参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-121">Ref numbers correspond to specific extensibility request IDs that are used internally and available externally.</span></span>

<span data-ttu-id="2ccb1-122">すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2ccb1-122">For more information about all extensibility capabilities, see the [Extensibility home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>

