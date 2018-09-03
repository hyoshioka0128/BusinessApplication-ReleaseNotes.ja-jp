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
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 374dad1c0120667f742ef9bd216b79c591c04742
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---

# <a name="platform-extensibility-enhancements"></a><span data-ttu-id="0e68b-103">プラットフォーム拡張性の機能強化</span><span class="sxs-lookup"><span data-stu-id="0e68b-103">Platform extensibility enhancements</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="0e68b-104">強化された拡張性機能:</span><span class="sxs-lookup"><span data-stu-id="0e68b-104">Enhanced extensibility capabilities:</span></span>
- <span data-ttu-id="0e68b-105">フォーム拡張機能を使用してカスタム パターンを使用するようにフォームを変更できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-105">Enable changing a form to use a custom pattern using a form extension.</span></span> <span data-ttu-id="0e68b-106">これにより、ISV は元のパターンに合わないタブや他のフォーム パーツを追加できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-106">This is to enable ISVs to add tabs and other form parts that do not fit the original pattern.</span></span> <span data-ttu-id="0e68b-107">開発者は、**パターンをカスタムに設定する**アクションと**元のパターンに戻す**アクションを使用できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-107">Developers now have actions to **Set pattern to custom** and **Restore original pattern**.</span></span>
- <span data-ttu-id="0e68b-108">拡張機能で **TableField.AssetClassification** を変更して、一般データ保護規則 (GDPR) のデータ分類情報を提供できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-108">Allow an extension to change **TableField.AssetClassification** so General Data Protection Regulation (GDPR) data classification information can be provided.</span></span>
- <span data-ttu-id="0e68b-109">フォーム拡張機能メソッドで、他の拡張機能によって追加されたメソッドとコントロールを呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-109">Enable form extension methods to call methods and controls added via other extensions.</span></span> <span data-ttu-id="0e68b-110">たとえば、現在のフォームにボタンと、拡張機能によって追加されたメソッドがある場合、そのフォームに対する将来の拡張で、新しいボタンとメソッドを呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-110">For example, now when a form has a button and some methods added via extension, then future extensions to that form will be able to call the new button and methods.</span></span>
- <span data-ttu-id="0e68b-111">**update_recordset** メソッドによって、セット ベースの更新ステートメントにクエリ オブジェクトのサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="0e68b-111">Add query object support for set-based update statements via an **update_recordset** method.</span></span>
- <span data-ttu-id="0e68b-112">クエリ拡張機能で結合クエリにルート データソースを追加できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-112">Allow a query extension to add a root datasource to a union query.</span></span>
- <span data-ttu-id="0e68b-113">拡張機能を使用してビューに範囲を追加できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-113">Enable the addition of ranges into a view using an extension.</span></span>
- <span data-ttu-id="0e68b-114">データ エンティティ ビュー拡張機能で **SupportsSetBasedSqlOperations** を設定できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-114">Enable setting **SupportsSetBasedSqlOperations** on data entity view extensions.</span></span> <span data-ttu-id="0e68b-115">基本要素を含むすべての拡張機能で Yes に設定されている場合にのみ設定できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-115">Yes can only be set if all extensions have it set to Yes including the base element.</span></span> <span data-ttu-id="0e68b-116">いずれかの拡張機能または基本要素で値が No に設定されている場合、実行時の結果は No になります。</span><span class="sxs-lookup"><span data-stu-id="0e68b-116">If any extension or the base element has the value set to No, then runtime result will be No.</span></span>
- <span data-ttu-id="0e68b-117">**WorkflowEnabled**、**WorkflowDataSource**、**WorkflowType** を編集することにより、フォーム拡張機能でフォームにワークフローを追加できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-117">Allow a form extension to add workflow to a form by editing **WorkflowEnabled**, **WorkflowDataSource**, and **WorkflowType**.</span></span>
- <span data-ttu-id="0e68b-118">フォーム メソッドに対してコマンド チェーンを有効にします。</span><span class="sxs-lookup"><span data-stu-id="0e68b-118">Enable Chain of Command for form methods.</span></span> <span data-ttu-id="0e68b-119">具体的には、これにより拡張機能は **canSubmitToWorkflow** メソッドを上書きすることによってフォームにワークフローを追加できます。</span><span class="sxs-lookup"><span data-stu-id="0e68b-119">In particular this allows an extension to add workflow to a form by overriding the **canSubmitToWorkflow** method.</span></span> <span data-ttu-id="0e68b-120">対象のフォーム メソッドが X++ 上書きのないカーネル メソッドである場合、対象フォームの再コンパイルが必要であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="0e68b-120">Note that if the targeted form method is a kernel method without an X++ override, then a recompile of the target form will be needed.</span></span> 
- <span data-ttu-id="0e68b-121">データ エンティティに対してコマンド チェーンを有効にします。</span><span class="sxs-lookup"><span data-stu-id="0e68b-121">Enable Chain of Command for data entities.</span></span>
- <span data-ttu-id="0e68b-122">データソースとコントロールを含む、フォーム内の入れ子になった型でコマンド チェーンを有効にします。</span><span class="sxs-lookup"><span data-stu-id="0e68b-122">Enable Chain of Command on nested types within forms including datasources and controls.</span></span>

<span data-ttu-id="0e68b-123">すべての拡張機能の詳細については、[拡張機能のホーム ページ](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0e68b-123">For more information about all the extensibility capabilities, see the [Extensiblity home page](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>

