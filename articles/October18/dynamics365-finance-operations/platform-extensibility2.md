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
# <a name="platform-extensibility-enhancements-wave-2"></a><span data-ttu-id="04700-103">プラットフォーム拡張性の機能強化ウェーブ 2</span><span class="sxs-lookup"><span data-stu-id="04700-103">Platform extensibility enhancements wave 2</span></span>

<span data-ttu-id="04700-104">プラットフォーム更新プログラム 21 で強化された拡張性機能:</span><span class="sxs-lookup"><span data-stu-id="04700-104">Enhanced extensibility capabilities in Platform update 21:</span></span>

- <span data-ttu-id="04700-105">コマンド チェーン メソッドでは、リソースのクリーンアップやセキュリティ チェックの調整を容易にするために、次の句の周辺で **try-finally** または **unchecked** ブロックがサポートされるようになりました (参照番号 215266、223822)。</span><span class="sxs-lookup"><span data-stu-id="04700-105">Chain of command methods now support **try-finally** or **unchecked** blocks around the next clause to facilitate resource cleanup  or security check adjustments (Ref# 215266, 223822).</span></span>

- <span data-ttu-id="04700-106">EDT Reals の **ShowZero** を変更できます (参照番号 198765)。</span><span class="sxs-lookup"><span data-stu-id="04700-106">Allow changes to **ShowZero** on EDT Reals (Ref# 198765).</span></span>

- <span data-ttu-id="04700-107">EDT Strings の **DisplayLength** を変更できます (参照番号 198766)。</span><span class="sxs-lookup"><span data-stu-id="04700-107">Allow changes to **DisplayLength** on EDT Strings (Ref# 198766).</span></span>

- <span data-ttu-id="04700-108">クエリ範囲の **Status** を変更できます (参照番号 198835)。</span><span class="sxs-lookup"><span data-stu-id="04700-108">Allow changes to **Status** on query ranges (Ref# 198835).</span></span>

- <span data-ttu-id="04700-109">フォームの **UseCaptionFromMenuItem** を変更できます (参照番号 198793)。</span><span class="sxs-lookup"><span data-stu-id="04700-109">Allow changes to **UseCaptionFromMenuItem** on forms (Ref# 198793).</span></span>

- <span data-ttu-id="04700-110">ボタンの **NeedsRecord** および **SaveRecord** を変更できます (参照番号 198762)。</span><span class="sxs-lookup"><span data-stu-id="04700-110">Allow changes to **NeedsRecord** and **SaveRecord** on buttons (Ref# 198762).</span></span>

- <span data-ttu-id="04700-111">フォーム コントロールの **AllowEdit** および **NeededPermission** を変更できます (参照番号 149754、198836)。</span><span class="sxs-lookup"><span data-stu-id="04700-111">Allow changes to **AllowEdit** and **NeededPermission** on form controls (Ref# 149754, 198836).</span></span>

- <span data-ttu-id="04700-112">拡張クラスで定義された属性を返すように **DictClass.getAllAttributes** を更新しました (参照番号 216149)。</span><span class="sxs-lookup"><span data-stu-id="04700-112">Updated **DictClass.getAllAttributes** to return the attributes defined on extension classes (Ref# 216149).</span></span>

- <span data-ttu-id="04700-113">**DiagnosticsArea**、**DocuFilePlace**、および **DocuTypeGroup** 列挙型を拡張可能にしました (参照番号 223436、241335、238162)。</span><span class="sxs-lookup"><span data-stu-id="04700-113">Made the **DiagnosticsArea**, **DocuFilePlace**, and **DocuTypeGroup** enumerations extensible (Ref# 223436, 241335, 238162).</span></span>

- <span data-ttu-id="04700-114">**delete_from** メソッドを使用してセット ベースの削除にクエリ オブジェクトのサポートを追加します (参照番号 185500)。</span><span class="sxs-lookup"><span data-stu-id="04700-114">Add query object support for set-based delete by using a **delete_from** method (Ref# 185500).</span></span>

<span data-ttu-id="04700-115">参照番号は、内部的に使用される、外部から利用可能な特定の拡張機能の要求 ID に対応します。</span><span class="sxs-lookup"><span data-stu-id="04700-115">Ref numbers correspond to specific extensibility request IDs that are used internally and available externally.</span></span>
<span data-ttu-id="04700-116">すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="04700-116">For more information about all extensibility capabilities, see the [Extensibility home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>
