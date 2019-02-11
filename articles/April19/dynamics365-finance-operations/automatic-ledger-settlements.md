---
title: 自動元帳決済
description: 自動元帳決済を使用すると、総勘定元帳で借方と貸方のトランザクションを照合し、それらを決済済みとしてマークすることができます。
author: aprilolson
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: 3ee596139828d811f25c1bf1e6c3cb1b905dc850
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210940"
---
#  <a name="automatic-ledger-settlements"></a><span data-ttu-id="4ab03-103">自動元帳決済</span><span class="sxs-lookup"><span data-stu-id="4ab03-103">Automatic ledger settlements</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="4ab03-104">元帳決済を使用すると、総勘定元帳で借方と貸方のトランザクションを照合し、それらを決済済みとしてマークすることができます。</span><span class="sxs-lookup"><span data-stu-id="4ab03-104">Ledger settlements let you match debit and credit transactions in the general ledger and mark them as settled.</span></span> <span data-ttu-id="4ab03-105">高度な元帳決済では、トランザクションのフィルタリングと選択のための追加機能が提供されていました。</span><span class="sxs-lookup"><span data-stu-id="4ab03-105">Advanced ledger settlements provided additional capabilities for filtering and selecting transactions.</span></span> <span data-ttu-id="4ab03-106">情報の追加のフィルタリングを可能にし、自動的にトランザクションを決済する、ルール作成機能を追加しています。</span><span class="sxs-lookup"><span data-stu-id="4ab03-106">We are adding the ability to create rules that will enable additional filtering of the information and will automatically settle transactions.</span></span> 

## <a name="rules-filtering"></a><span data-ttu-id="4ab03-107">ルール フィルタリング</span><span class="sxs-lookup"><span data-stu-id="4ab03-107">Rules filtering</span></span>

<span data-ttu-id="4ab03-108">元帳決済ルールを使用すると、トランザクションのフィルタリング方法を定義できます。</span><span class="sxs-lookup"><span data-stu-id="4ab03-108">The ledger settlement rules will allow you define how you want to filter transactions.</span></span> <span data-ttu-id="4ab03-109">フィルターを定義する取引先企業、分析コード、その他の条件を選択できます。</span><span class="sxs-lookup"><span data-stu-id="4ab03-109">You'll be able to select accounts, dimensions, and other criteria that will define your filter.</span></span> <span data-ttu-id="4ab03-110">その後、元帳トランザクションにルールを適用し、照合前に結果をプレビューできます。</span><span class="sxs-lookup"><span data-stu-id="4ab03-110">You can then apply the rule to your ledger transactions and preview the results before matching.</span></span>

## <a name="automatic-matching"></a><span data-ttu-id="4ab03-111">自動照合</span><span class="sxs-lookup"><span data-stu-id="4ab03-111">Automatic matching</span></span>

<span data-ttu-id="4ab03-112">元帳決済ルールでは、照合するトランザクションを定義する取引先企業、分析コード、転記タイプなどの条件のリストから選択することもできます。</span><span class="sxs-lookup"><span data-stu-id="4ab03-112">The ledger settlement rules will also allow you to select from a list of criteria such as accounts, dimensions, and posting types that define which transactions you want to match.</span></span> <span data-ttu-id="4ab03-113">元帳トランザクションにルールを追加すると、フィルターが適用されるだけでなく、照合トランザクションが決済に対して選択されます。</span><span class="sxs-lookup"><span data-stu-id="4ab03-113">When you add the rule to your ledger transactions, not only will the filter be applied but the matching transactions will be selected for settlement.</span></span> <span data-ttu-id="4ab03-114">プロセスはバッチ処理にも利用可能です。</span><span class="sxs-lookup"><span data-stu-id="4ab03-114">The process will also be available for processing in batch.</span></span>
