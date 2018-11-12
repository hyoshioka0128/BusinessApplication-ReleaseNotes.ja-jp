---
title: "グリッド内の既定の付箋アクション"
description: "既定の付箋アクション機能は、個人用設定が適用された後で既定のアクション列がグリッド内に表示される位置を制御します。"
author: jasongre
manager: AnnBe
ms.date: 10/09/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 4e870aa1a93bbb42d8d9c61a539ff10bcf216d2e
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---

# <a name="sticky-default-actions-in-grids"></a><span data-ttu-id="378e3-103">グリッド内の既定の付箋アクション</span><span class="sxs-lookup"><span data-stu-id="378e3-103">Sticky default actions in grids</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="378e3-104">Finance and Operations の多くのグリッドで、*既定のアクション*が定義されています。</span><span class="sxs-lookup"><span data-stu-id="378e3-104">Many grids in Finance and Operations have a defined *default action*.</span></span> <span data-ttu-id="378e3-105">これは、すべての行の値が常にハイパーリンクとして表示されるグリッド内の単一の列です。これに対し、他の列では、アクティブな行の値のみがハイパーリンクとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="378e3-105">This is a single column in the grid where the value in every row always appears as a hyperlink, as opposed to other columns where only the value in the active row appears as a hyperlink.</span></span> <span data-ttu-id="378e3-106">これまでの Finance and Operations では、この既定のアクションは常に、ユーザーが個人用設定を適用する前の、グリッドの最初のテキスト列に表示されます。</span><span class="sxs-lookup"><span data-stu-id="378e3-106">To date, in Finance and Operations, this default action always appears on the first textual column in a grid before any user personalization is applied.</span></span> <span data-ttu-id="378e3-107">たとえば、次のような**顧客**リストの**取引先企業**列について考えます。</span><span class="sxs-lookup"><span data-stu-id="378e3-107">As an example, consider the **Account** column in the **Customer** list below.</span></span>

<span data-ttu-id="378e3-108">![顧客リスト](media/customerGrid.png  "顧客リスト")</span><span class="sxs-lookup"><span data-stu-id="378e3-108">![Customer list](media/customerGrid.png  "Customer list")</span></span>

<span data-ttu-id="378e3-109">*顧客リスト*</span><span class="sxs-lookup"><span data-stu-id="378e3-109">*Customer list*</span></span>

<span data-ttu-id="378e3-110">Platform Update 21 以降で利用可能な**既定の付箋アクション**機能は、列の順序や表示を変更する個人用設定が適用された後で、既定のアクション列がグリッドに表示される位置を制御します。</span><span class="sxs-lookup"><span data-stu-id="378e3-110">The **sticky default action** feature, which is available starting in Platform Update 21, controls where the default action column appears in the grid after personalizations are applied that change the order or visibility of columns.</span></span>   

<span data-ttu-id="378e3-111">既定の付箋アクションをオフにすると (これは、Platform Update 21 より前の既定のアクションの動作に対応します)、既定のアクションのハイパーリンクは、個人用設定が適用された後の最初のテキスト列に変更されます。</span><span class="sxs-lookup"><span data-stu-id="378e3-111">With sticky default actions off, which corresponds to how default actions work prior to Platform Update 21, the default action hyperlink would change to whatever column is the first textual column after personalizations are applied.</span></span> <span data-ttu-id="378e3-112">たとえば、**取引先企業**列をグリッドの 4 番目の列に移動すると (または、**取引先企業**列を非表示にすると)、既定のアクションを表すハイパーリンクは**名前**列に移動します。</span><span class="sxs-lookup"><span data-stu-id="378e3-112">For example, if you move the **Account** column to be the fourth column in the grid (or alternatively if you hide the **Account** column), the hyperlink representing the default action moves to the **Name** column.</span></span> 

<span data-ttu-id="378e3-113">![既定の付箋アクションをオフにする](media/stickyDAOff.png  "既定の付箋アクションをオフにすると、[取引先企業] 列が最初の列以外に移動された場合、[名前] 列が既定のアクション列になります。")</span><span class="sxs-lookup"><span data-stu-id="378e3-113">![Sticky default actions off](media/stickyDAOff.png  "With sticky default actions off, the Name column becomes the default action column if the Account column is moved to not be the first column.")</span></span>

<span data-ttu-id="378e3-114">*既定の付箋アクションをオフにすると、[取引先企業] 列が最初の列位置以外に移動された場合、[名前] 列が既定のアクション列になります。*</span><span class="sxs-lookup"><span data-stu-id="378e3-114">*With sticky default actions off, the Name column becomes the default action column if the Account column is moved out of the first column position*</span></span>

<span data-ttu-id="378e3-115">既定の付箋アクションをオンにすると、フォームに適用された個人用設定に関係なく、既定のアクションのハイパーリンクは同じ列に表示されます。</span><span class="sxs-lookup"><span data-stu-id="378e3-115">With sticky default actions on, the default action hyperlink will be on the same column regardless of any personalizations applied to the form.</span></span> <span data-ttu-id="378e3-116">この顧客リストの場合、これは、**取引先企業**列を移動または非表示にしても、**取引先企業**列が引き続き既定のアクション列であることを意味します。</span><span class="sxs-lookup"><span data-stu-id="378e3-116">This means for this customer list, the **Account** column will continue to be the default action column regardless of whether the **Account** column is moved or is hidden.</span></span>

<span data-ttu-id="378e3-117">![既定の付箋アクションをオンにする](media/stickyDAOn.png  "既定の付箋アクションをオンにすると、個人用設定に関係なく、[取引先企業] 列が引き続き既定のアクション列です。")</span><span class="sxs-lookup"><span data-stu-id="378e3-117">![Sticky default actions off](media/stickyDAOn.png  "With sticky default actions on, the Account column is still the default action column despite any personalizations.")</span></span>

<span data-ttu-id="378e3-118">*既定の付箋アクションをオンにすると、個人用設定に関係なく、[取引先企業] 列が引き続き既定のアクション列です。*</span><span class="sxs-lookup"><span data-stu-id="378e3-118">*With sticky default actions on, the Account column is still the default action column despite any personalizations*</span></span>

<span data-ttu-id="378e3-119">Platform Update 21 では、既定の付箋アクション機能はオフになっていますが、システム管理者は環境に対してオンにすることができます。</span><span class="sxs-lookup"><span data-stu-id="378e3-119">With Platform Update 21, the sticky default action feature is off, but a system administrator can turn it on for an environment.</span></span> <span data-ttu-id="378e3-120">この機能を有効にするには、**システム管理**の**クライアント パフォーマンス オプション** ページにある、**既定の付箋アクションの有効化**スイッチを使用します。</span><span class="sxs-lookup"><span data-stu-id="378e3-120">To turn on this feature, navigate to the **Client performance options** page under **System administration** and find the **Enable sticky default action** switch.</span></span>   




