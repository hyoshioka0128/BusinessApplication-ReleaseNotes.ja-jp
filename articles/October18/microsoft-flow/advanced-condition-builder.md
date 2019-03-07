---
title: 高度な条件ビルダー
description: 新しい高度な条件ビルダーを使用すると、フロー内の And/Or ステートメントに基づいて条件付きロジックを作成できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/07/2019
ms.assetid: 296b4bdb-65d9-e811-a987-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 762c9c39fe8fca781728bf7f5cacd1feb365cf8b
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391316"
---
# <a name="advanced-condition-builder"></a><span data-ttu-id="8c610-103">高度な条件ビルダー</span><span class="sxs-lookup"><span data-stu-id="8c610-103">Advanced condition builder</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="8c610-104">Microsoft Flow での条件付きロジックの作成が、新しい高度な条件ビルダーを使用することで、これまでより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8c610-104">It's now easier than ever to write conditional logic in Microsoft Flow by using the new advanced condition builder.</span></span> <span data-ttu-id="8c610-105">これまでも、式を使って複雑な条件を書くことはできましたが、今では Microsoft Flow デザイナーの簡単なポイント アンド クリック UI で条件を作成できます。</span><span class="sxs-lookup"><span data-stu-id="8c610-105">Previously, you could write complex conditions using expressions, but now it's possible to build conditions with the Microsoft Flow designer's simple point-and-click UI.</span></span> 

<span data-ttu-id="8c610-106">![行の追加](media/advanced_condition_builder_01.png "行の追加")</span><span class="sxs-lookup"><span data-stu-id="8c610-106">![Add row](media/advanced_condition_builder_01.png "Add row")</span></span>

<span data-ttu-id="8c610-107">**新しいステップ**を選択してから、使用可能な最初のアクションである**条件**を選択して、フローに条件を追加できます。</span><span class="sxs-lookup"><span data-stu-id="8c610-107">You can add a condition to your flow by selecting **New step** and then the first action available to you: **Condition**.</span></span> <span data-ttu-id="8c610-108">新しい**追加**ボタンを選択すると、2 つのオプションが表示されます。</span><span class="sxs-lookup"><span data-stu-id="8c610-108">There is a new **Add** button that you can select that presents two options:</span></span>

- <span data-ttu-id="8c610-109">**行の追加**: チェックする個々の条件 (値が 10 より大きい、リストに `Test` が含まれていない、など) に対して、条件ビルダーに新しい*行*が作成されます。</span><span class="sxs-lookup"><span data-stu-id="8c610-109">**Add row**: Each individual condition you check for (such as the value is greater than 10, or the list does not contain `Test`) creates a new *row* in the condition builder.</span></span>
- <span data-ttu-id="8c610-110">**グループの追加**: 1 つ以上の行を、*グループ*にまとめることができます。各グループは、**And** または **Or** によって結合されます。</span><span class="sxs-lookup"><span data-stu-id="8c610-110">**Add group**: You can combine one or more rows together in a *group*—each group is combined by either an **And** or an **Or**.</span></span> <span data-ttu-id="8c610-111">**And** を選択した場合は、すべての行が true になる必要があります。</span><span class="sxs-lookup"><span data-stu-id="8c610-111">If you select **And**, then all the rows must be true.</span></span> <span data-ttu-id="8c610-112">**Or** を選択した場合は、1 行だけ true になる必要があります。</span><span class="sxs-lookup"><span data-stu-id="8c610-112">If you select **Or**, then only one of the rows needs to be true.</span></span>

<span data-ttu-id="8c610-113">![高度な条件ビルダー](media/advanced_condition_builder_02.png "高度な条件ビルダー")</span><span class="sxs-lookup"><span data-stu-id="8c610-113">![Advanced condition builder](media/advanced_condition_builder_02.png "Advanced condition builder")</span></span>

<span data-ttu-id="8c610-114">ただし、ロジックを構築するために必要な行またはグループが多数ある場合があり、**追加**ボタンを使用することにより、条件の最上位レベルとグループ内の両方で、行 (またはグループ) の追加を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="8c610-114">You can have however many rows or groups you need to build out your logic, and can continue adding rows (or groups) both at the top level of the condition, and inside groups using their **Add** buttons.</span></span> <span data-ttu-id="8c610-115">条件の表示を簡潔にしたい場合は、各グループの右上にあるボタンを使用して*折りたたむ*ことができます。</span><span class="sxs-lookup"><span data-stu-id="8c610-115">If you want a simplified view of the condition, there is a button at the top-right of each group to *collapse* it.</span></span>

<span data-ttu-id="8c610-116">さらに、各行とグループの右側には `...` メニューがあります。</span><span class="sxs-lookup"><span data-stu-id="8c610-116">Additionally, there is a `...` menu at the right side of each row and group.</span></span> <span data-ttu-id="8c610-117">これには、行を上下に移動するためのオプション (グループの内部で、またはグループの外部に移動できます)、および行またはグループを**削除**するオプションが含まれます。</span><span class="sxs-lookup"><span data-stu-id="8c610-117">This contains options for moving rows up or down (which can move them in and out of groups), and an option to **Delete** a row or group.</span></span> <span data-ttu-id="8c610-118">また、各行または各グループの左側にはチェック ボックスがあります。</span><span class="sxs-lookup"><span data-stu-id="8c610-118">Also, there are check boxes on the left side of each row or group.</span></span> <span data-ttu-id="8c610-119">これを使用すると、複数の異なる行を選択してから、右側にある `...` メニューの**グループ**を選択して、行を 1 つのグループにまとめることができます。</span><span class="sxs-lookup"><span data-stu-id="8c610-119">This allows you to select several different rows, and then select **Group** from the `...` menu at the right to combine the rows into a single group.</span></span>

<span data-ttu-id="8c610-120">場合によっては、高度な条件ビルダーでも無理なほど複雑な式のモデル化が必要になることがあります。</span><span class="sxs-lookup"><span data-stu-id="8c610-120">Sometimes, there might be an expression that is more complex than what you want to model in even the advanced condition builder.</span></span> <span data-ttu-id="8c610-121">以前は、**高度なモードで編集**を選択してから、テキスト ボックスに式を入力することができました。</span><span class="sxs-lookup"><span data-stu-id="8c610-121">Previously, you could select **Edit in advanced mode** and then enter the expressions in a text box.</span></span> <span data-ttu-id="8c610-122">ただし、この古いモードでは、式や動的コンテンツの IntelliSense にアクセスできないため、作業が困難でした。</span><span class="sxs-lookup"><span data-stu-id="8c610-122">However, this old mode was difficult to work with because it did not give you access to IntelliSense for expressions or Dynamic content.</span></span> <span data-ttu-id="8c610-123">**高度なモードで編集**はなくなっています。</span><span class="sxs-lookup"><span data-stu-id="8c610-123">There is no longer an **Edit in advanced mode**.</span></span> <span data-ttu-id="8c610-124">代わりに、非常に複雑な式が必要な場合は、通常の動的コンテンツ式ビルダーを使用して、行の左側に式を入力できます。</span><span class="sxs-lookup"><span data-stu-id="8c610-124">Instead, if you want a very complex expression, you can use the regular Dynamic Content expression builder to enter your expression on the left side of the row.</span></span> <span data-ttu-id="8c610-125">そして、**次の値に等しい**を選択し、右側に「`true`」と入力します。</span><span class="sxs-lookup"><span data-stu-id="8c610-125">Then, select **Equals to** and enter `true` in the right side.</span></span>

<span data-ttu-id="8c610-126">![複雑な式](media/advanced_condition_builder_03.png "複雑な式")</span><span class="sxs-lookup"><span data-stu-id="8c610-126">![Complex expressions](media/advanced_condition_builder_03.png "Complex expressions")</span></span>

<span data-ttu-id="8c610-127">高度な条件ビルダーは、フローに追加するすべての新しい条件に対して使用できます。</span><span class="sxs-lookup"><span data-stu-id="8c610-127">The advanced condition builder is available for all new conditions that you add to your flows.</span></span> <span data-ttu-id="8c610-128">既存の条件に対しては使用できないので、既存のフローで使用したい場合は、新しいステップを追加し、古い条件から新しい条件にアクションをドラッグする必要があります。</span><span class="sxs-lookup"><span data-stu-id="8c610-128">It will not be enabled for existing conditions, so if you would like to use it with existing flows you will need to add a new step and drag the actions from the old condition to the new condition.</span></span>
