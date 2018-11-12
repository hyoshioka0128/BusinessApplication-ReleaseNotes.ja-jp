---
title: "中断/再開の改善"
description: "この機能により、POS でトランザクションを中断および再開するユーザーの機能が向上し、POS 仕訳帳およびバックオフィス トランザクション履歴に監査機能が追加されます。"
author: jblucher
manager: AnnBe
ms.date: 10/15/2018
ms.assetid: 7b453328-5b4e-423a-90d9-3069f7cc918f
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jeffbl
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 212f292c41bc405136663d6a86e5f9d49f320a55
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
---

# <a name="suspendresume-improvements"></a><span data-ttu-id="5da70-103">中断/再開の改善</span><span class="sxs-lookup"><span data-stu-id="5da70-103">Suspend/resume improvements</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

<span data-ttu-id="5da70-104">この機能は店舗関係者を対象としています。</span><span class="sxs-lookup"><span data-stu-id="5da70-104">This feature is intended for store associates.</span></span> <span data-ttu-id="5da70-105">ユーザーが POS のトランザクションを一時停止および再開する機能が向上します。</span><span class="sxs-lookup"><span data-stu-id="5da70-105">It improves their ability to suspend and resume transactions in the POS.</span></span> <span data-ttu-id="5da70-106">また、この機能により、POS 仕訳帳およびバックオフィス トランザクション履歴に監査機能が追加されます。</span><span class="sxs-lookup"><span data-stu-id="5da70-106">This feature also adds additional auditing capabilities in the POS journal and back office transaction history.</span></span>

<span data-ttu-id="5da70-107">この機能は、進行中のトランザクションを中断し、おそらくは店内の別のデバイス/レジスターから後で再開する必要がある、POS レジ係や店員に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="5da70-107">This feature helps a POS cashier or sales associate who needs to suspend an in-progress transaction and resume it later, possibly from a different device/register within the store.</span></span>

## <a name="improvements-and-capabilities"></a><span data-ttu-id="5da70-108">改善点と機能</span><span class="sxs-lookup"><span data-stu-id="5da70-108">Improvements and capabilities</span></span>
<span data-ttu-id="5da70-109">POS の既存の中断/再開機能は、以下の改善点と機能を含むように強化されています。</span><span class="sxs-lookup"><span data-stu-id="5da70-109">The existing suspend/resume functionality in the POS has been enhanced to include the following improvements and capabilities.</span></span>

### <a name="ability-to-print-a-suspend-transaction-slip"></a><span data-ttu-id="5da70-110">"トランザクションの中断" 伝票を印刷する機能</span><span class="sxs-lookup"><span data-stu-id="5da70-110">Ability to print a “Suspend transaction” slip</span></span>
<span data-ttu-id="5da70-111">小売業者はレシート テンプレートを構成できるようになり、トランザクションを中断するたびに POS で伝票を印刷できます。</span><span class="sxs-lookup"><span data-stu-id="5da70-111">Retailers can now configure a receipt template, so POS will print a slip each time a transaction is suspended.</span></span> <span data-ttu-id="5da70-112">テンプレートには、ヘッダーおよび明細レベルのトランザクション情報と、固有のレシート番号とバーコードを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="5da70-112">The template can include header and line-level transaction information as well as a unique receipt number and barcode.</span></span>

### <a name="quickly-recall-suspended-transactions-by-scanning-barcodes"></a><span data-ttu-id="5da70-113">バーコードをスキャンすることで中断したトランザクションをすばやく呼び出す</span><span class="sxs-lookup"><span data-stu-id="5da70-113">Quickly recall suspended transactions by scanning barcodes</span></span>
<span data-ttu-id="5da70-114">POS ユーザーは、"トランザクションの中断" 伝票に印刷されたバーコードをスキャンして、トランザクションを迅速かつ簡単に再開できます。</span><span class="sxs-lookup"><span data-stu-id="5da70-114">POS users can scan the barcode printed on the “Suspend transaction” slip to quickly and easily recall the transaction.</span></span>

### <a name="view-suspended-transactions-in-the-pos-journal"></a><span data-ttu-id="5da70-115">POS 仕訳帳に中断したトランザクションを表示する</span><span class="sxs-lookup"><span data-stu-id="5da70-115">View suspended transactions in the POS journal</span></span>
<span data-ttu-id="5da70-116">ヘッダーおよび明細レベルの詳細を含む中断されたトランザクション情報は POS 仕訳帳に保存され、追加の店内監査機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="5da70-116">Suspended transaction information including header and line-level detail will now be saved in the POS journal, providing additional in-store audit capabilities.</span></span>  

### <a name="view-suspended-transactions-in-back-office-inquiries"></a><span data-ttu-id="5da70-117">バックオフィスの照会で中断されたトランザクションを表示する</span><span class="sxs-lookup"><span data-stu-id="5da70-117">View suspended transactions in back office inquiries</span></span>
<span data-ttu-id="5da70-118">中断されたトランザクションのエントリはバックオフィスに複製されて、小売店舗トランザクションの照会に表示されます。</span><span class="sxs-lookup"><span data-stu-id="5da70-118">Suspended transaction entries will now be replicated to the back office and displayed in the Retail store transaction inquiry.</span></span> <span data-ttu-id="5da70-119">ユーザーは、トランザクションが中断された場所と日時の詳細を見ることができます。</span><span class="sxs-lookup"><span data-stu-id="5da70-119">Users can view details about where and when the transaction was suspended.</span></span> <span data-ttu-id="5da70-120">さらに、再開されて完了または無効化されたトランザクションを、元の中断されたトランザクションにリンクすることができます。</span><span class="sxs-lookup"><span data-stu-id="5da70-120">In addition, resumed transactions that are either completed or voided can be linked back to the original suspended transaction.</span></span>

### <a name="automatically-void-suspended-transactions-at-the-end-of-each-shift"></a><span data-ttu-id="5da70-121">各シフトの終了時に中断されたトランザクションを自動的に無効にする</span><span class="sxs-lookup"><span data-stu-id="5da70-121">Automatically void suspended transactions at the end of each shift</span></span>
<span data-ttu-id="5da70-122">小売業者は、中断されたトランザクションが放置されてたまるのを防ぐため、各シフトの終了時に中断されたトランザクションを自動的に無効にするように POS を構成できます。</span><span class="sxs-lookup"><span data-stu-id="5da70-122">Retailers can configure POS to automatically void suspended transactions at the end of each shift to prevent accumulation of abandoned suspended transactions.</span></span> <span data-ttu-id="5da70-123">無効化された各トランザクションは、監査のために、仕訳帳に追加され、バックオフィスに複製されます。</span><span class="sxs-lookup"><span data-stu-id="5da70-123">Each voided transaction is journaled and replicated to the back office for audit purposes.</span></span>

### <a name="ability-to-bulk-select-and-void-suspended-transactions"></a><span data-ttu-id="5da70-124">中断されたトランザクションを一括選択して無効にする機能</span><span class="sxs-lookup"><span data-stu-id="5da70-124">Ability to bulk select and void suspended transactions</span></span>
<span data-ttu-id="5da70-125">シフト終了時に中断されたトランザクションを必要に応じて無効にすることに加え、アクセス許可を持つユーザーは、POS 内から中断されたトランザクションを複数選択して無効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="5da70-125">In addition to optionally voiding suspended transactions when closing shifts, users with permission can multiselect and void suspended transactions from within the POS.</span></span> 



