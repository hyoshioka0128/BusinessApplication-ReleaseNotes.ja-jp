---
title: "POS 仕訳帳の向上"
description: "この機能リリースでは、強化された機能が利用可能になって電子仕訳に記録され、構成されている場合は受領書を電子仕訳から印刷および再印刷できるようにもなります。"
author: jblucher
manager: AnnBe
ms.date: 10/25/2018
ms.assetid: 7b453328-5b4e-423a-90d9-3069f7cc918f
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jeffbl
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 13f29c65ca9fad83b8e831c6dd84fa3cb0c4c243
ms.openlocfilehash: d7c84f44ddce689dff81e66118cd4eb3b3ea574e
ms.contentlocale: ja-jp
ms.lasthandoff: 01/23/2019

---

# <a name="pos-journal-improvements"></a><span data-ttu-id="278dd-103">POS 仕訳帳の向上</span><span class="sxs-lookup"><span data-stu-id="278dd-103">POS journal improvements</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

<span data-ttu-id="278dd-104">POS (販売時点管理) 内の電子仕訳は、店舗内のトランザクション情報を確認する中心的な場所です。</span><span class="sxs-lookup"><span data-stu-id="278dd-104">The Electronic Journal within the point of sale (POS) is a central location for reviewing transaction information within a store.</span></span> <span data-ttu-id="278dd-105">このフォームにより、店舗内で行われていることとトランザクション情報の確認について、適切なアクセス許可レベルを持つマネージャーとその他のユーザーに対して店舗全体が可視化されます。</span><span class="sxs-lookup"><span data-stu-id="278dd-105">This form gives visibility across the store to managers and other users with appropriate permission levels as to what is happening in the store as well as reviewing transaction information.</span></span> <span data-ttu-id="278dd-106">仕訳にいくつかのトランザクション タイプが追加されたことに加え、免税トランザクションの詳細、トランザクションの無効化、ドロワーを開く機能の実行、POS で電子仕訳に記録せずに印刷できるギフト カード残高照会のレイアウトなど、可視性を高めるための受領書の機能強化が行われています。</span><span class="sxs-lookup"><span data-stu-id="278dd-106">Several additional transaction types have been included in the journal, as well as receipt enhancements, for visibility including tax exempt transaction details, voided transactions, when the open drawer function is executed, and a layout for gift card balance inquiry that will not log in the electronic journal at a POS but can be printed.</span></span> <span data-ttu-id="278dd-107">その結果、店舗のユーザーは、以前は店舗の POS フォームまたは HQ フォームでは表示されなかったこれらのトランザクションを詳しく把握できるようになります。</span><span class="sxs-lookup"><span data-stu-id="278dd-107">As a result, store users will now have detailed visibility into these transactions that previously went without visibility through the POS or HQ forms in the store.</span></span> 

<span data-ttu-id="278dd-108">この機能リリースでは、強化された機能が利用可能になって電子仕訳に記録され、構成されている場合は受領書を電子仕訳から印刷および再印刷できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="278dd-108">With this feature release, the enhanced capabilities will be available and logged within the electronic journal and if configured will also have a receipt available to print and be reprinted from the electronic journal.</span></span>

## <a name="open-drawer-transaction"></a><span data-ttu-id="278dd-109">ドロワーを開くトランザクション</span><span class="sxs-lookup"><span data-stu-id="278dd-109">Open drawer transaction</span></span>

<span data-ttu-id="278dd-110">既存のドロワーを開く操作は同じ店舗内の電子仕訳に表示されるようになり、構成可能な受領書を印刷できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-110">The existing Open drawer operation will now be visible in the electronic journal within the same store and have a configurable receipt that can print.</span></span> <span data-ttu-id="278dd-111">適切なアクセス許可があれば、ログインしているユーザーは、デバイスが接続されている店舗内で実行されたドロワーを開くトランザクションを表示できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-111">With appropriate permissions, the logged-in user will be able to see Open drawer transactions that were performed within the store the device is attached to.</span></span> <span data-ttu-id="278dd-112">構成された印刷動作に基づき、構成された受領書フォーマットに応じて、POS 内でドロワーを開く操作が実行されるたびに受領書を印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="278dd-112">Based on the configured print behavior, and depending on a configured receipt format, a receipt can be printed each time the Open drawer operation is executed within the POS.</span></span> <span data-ttu-id="278dd-113">この機能を使用すると、キャッシュ ドロワーを開いているトランザクションをより目立たせることができ、詐欺の手段を低減できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-113">This feature can be used to make more visible those transactions that are opening the cash drawer, reducing an avenue of fraud.</span></span> 

<span data-ttu-id="278dd-114">![ドロワーを開く仕訳](../../media/journal1.png "ドロワーを開く仕訳")</span><span class="sxs-lookup"><span data-stu-id="278dd-114">![Open drawer journal](../../media/journal1.png "Open drawer journal")</span></span>


## <a name="transaction-void"></a><span data-ttu-id="278dd-115">トランザクションの無効化</span><span class="sxs-lookup"><span data-stu-id="278dd-115">Transaction void</span></span>

<span data-ttu-id="278dd-116">既存のトランザクションの無効化操作は同じ店舗内の電子仕訳に表示されるようになり、構成可能な受領書を印刷できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-116">The existing Transaction void operation will now be visible in the electronic journal within the same store and have a configurable receipt that can print.</span></span> <span data-ttu-id="278dd-117">適切なアクセス許可があれば、ログインしているユーザーは、デバイスが接続されている店舗内で実行されたトランザクションの無効化を表示できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-117">With appropriate permissions, the logged-in user will be able to see voided transactions that were performed within the store the device is attached to.</span></span> <span data-ttu-id="278dd-118">構成された印刷動作に基づき、構成された受領書フォーマットに応じて、POS 内でトランザクションの無効化操作が実行されるたびに受領書を印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="278dd-118">Based on the configured print behavior, and depending on a configured receipt format, a receipt can be printed each time the Transaction void operation is executed within the POS.</span></span> <span data-ttu-id="278dd-119">この機能を使用すると、無効化されるトランザクションをより目立たせることができ、詐欺の手段を低減できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-119">This feature can be used to make more visible those transaction that are voided, reducing an avenue of fraud.</span></span>

<span data-ttu-id="278dd-120">![トランザクション無効化仕訳](../../media/journal3.png "トランザクション無効化仕訳")</span><span class="sxs-lookup"><span data-stu-id="278dd-120">![Transaction void journal](../../media/journal3.png "Transaction void journal")</span></span>

<span data-ttu-id="278dd-121">![トランザクション無効化受領書](../../media/journal4.png "トランザクション無効化受領書")</span><span class="sxs-lookup"><span data-stu-id="278dd-121">![Transaction void receipt](../../media/journal4.png "Transaction void receipt")</span></span>

## <a name="tax-exempt-details"></a><span data-ttu-id="278dd-122">免税の詳細</span><span class="sxs-lookup"><span data-stu-id="278dd-122">Tax exempt details</span></span>

<span data-ttu-id="278dd-123">税の上書き機能を使用すると、消費税コードが消費税グループ内で免税としてマークされている場合に、POS で免税トランザクションを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="278dd-123">The Override tax function allows for tax exempt transactions to be created in the POS if the sales tax code is marked as tax exempt within the sales tax group.</span></span> <span data-ttu-id="278dd-124">この機能により、POS トランザクション グリッド内、電子仕訳内に免税の詳細を表示でき、構成されている場合は受領書に印刷できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-124">This capability allows for the tax exempt details to be visible within the POS transaction grid, electronic journal, and to be printed on the receipt if configured.</span></span> <span data-ttu-id="278dd-125">免税インジケーターというラベルの付いた受領書デザイナーの新しいフィールドには、POS の機能プロファイルから取得された構成可能な値が出力されます。</span><span class="sxs-lookup"><span data-stu-id="278dd-125">A new field in the receipt designer labeled Tax Exempt Indicator prints a configurable value from the functionality profiles for POS.</span></span> <span data-ttu-id="278dd-126">受領書デザイナー内の請求書コメント フィールドを活用することで、トランザクション レベルの情報コードを取得して、免税情報 (情報コードに構成されている場合) を受領書に表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="278dd-126">Leveraging the invoice comment fields within the receipt designer also allows the capture of transaction level info codes to display tax exempt information on the receipt if configured on the info code.</span></span> <span data-ttu-id="278dd-127">これにより、店舗のユーザーと消費者は、トランザクションまたは行が免税としてタグ付けされていることを明確に把握できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-127">This allows for store users and consumers to have clear visibility that a transaction or line has been tagged as tax exempt.</span></span> 

<span data-ttu-id="278dd-128">![免税仕訳](../../media/journal5.png "免税仕訳")</span><span class="sxs-lookup"><span data-stu-id="278dd-128">![Tax exempt journal](../../media/journal5.png "Tax exempt journal")</span></span>

<span data-ttu-id="278dd-129">![免税受領書](../../media/journal6.png "免税受領書")</span><span class="sxs-lookup"><span data-stu-id="278dd-129">![Tax exempt receipt](../../media/journal6.png "Tax exempt receipt")</span></span>

## <a name="gift-card-balance-inquiry-receipt"></a><span data-ttu-id="278dd-130">ギフト カード残高照会受領書</span><span class="sxs-lookup"><span data-stu-id="278dd-130">Gift card balance inquiry receipt</span></span>

<span data-ttu-id="278dd-131">POS でギフト カードの残高を確認するための既存の操作では、残高だけが画面に戻されます。</span><span class="sxs-lookup"><span data-stu-id="278dd-131">The existing operation for checking balance on a gift card in POS only returns the balance to the screen.</span></span> <span data-ttu-id="278dd-132">ギフト カード残高照会の受領書を構成して印刷する機能を追加しました。</span><span class="sxs-lookup"><span data-stu-id="278dd-132">We have added the capability to configure and print a receipt for gift card balance inquiry.</span></span> <span data-ttu-id="278dd-133">このトランザクションは、POS 内の電子仕訳には表示されません。</span><span class="sxs-lookup"><span data-stu-id="278dd-133">This transaction will not show up in the electronic journal within the POS.</span></span> <span data-ttu-id="278dd-134">受領書は、常に印刷するか、プロンプトを表示するか、印刷しないように構成できます。</span><span class="sxs-lookup"><span data-stu-id="278dd-134">The receipt can be configured to print always, by prompt, or never print.</span></span> <span data-ttu-id="278dd-135">POS で印刷できるようにするには、受領書のフォーマットを本社で定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="278dd-135">The format for the receipt must be defined in headquarters for the POS to be able to print.</span></span> <span data-ttu-id="278dd-136">[小売パラメーター] | [転記] タブで機能を有効にし、受領書フォーマットにトランザクション履歴フィールドを追加することで、データを Dynamics 365 for Retail で利用できる場合は、販売/返品トランザクション履歴を印刷するように残高照会受領書を構成することもできます。</span><span class="sxs-lookup"><span data-stu-id="278dd-136">The balance inquiry receipt can also be configured to print the sales/return transaction history if the data is available to Dynamics 365 for Retail by enabling the functionality on the Retail parameters | Posting tab and adding the transaction history fields to the receipt format.</span></span> 

<span data-ttu-id="278dd-137">![ギフト カード仕訳](../../media/journal7.png "ギフト カード仕訳")</span><span class="sxs-lookup"><span data-stu-id="278dd-137">![Gift card journal](../../media/journal7.png "Gift card journal")</span></span>


