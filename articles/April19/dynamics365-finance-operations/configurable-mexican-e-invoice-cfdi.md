---
title: メキシコ向けの構成可能な E-Invoice (CFDI)
description: メキシコ向けの構成可能な E-Invoice (CFDI)
author: mrolecki
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
ms.openlocfilehash: 46ef36a76ebb8c4e9a8e47389a667871ffbbd488
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225251"
---
#  <a name="configurable-mexican-e-invoice-cfdi"></a><span data-ttu-id="699b7-103">メキシコ向けの構成可能な E-Invoice (CFDI)</span><span class="sxs-lookup"><span data-stu-id="699b7-103">Configurable Mexican e-invoice (CFDI)</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="699b7-104">メキシコでの電子請求には、Comprobantes fiscales digitales por internet (CFDI) 電子請求書フォーマットが必要です。</span><span class="sxs-lookup"><span data-stu-id="699b7-104">Electronic billing in Mexico requires the Comprobantes fiscales digitales por internet (CFDI) electronic invoice format.</span></span> <span data-ttu-id="699b7-105">電子請求書は、組織がメキシコの税務当局 Servicio de Administración Tributaria (SAT) に提出する、合法的に承認されたデジタル納税領収書です。</span><span class="sxs-lookup"><span data-stu-id="699b7-105">An electronic invoice is a legally accepted digital tax receipt that your organization submits to the Mexican tax authority - Servicio de Administración Tributaria (SAT).</span></span> 

<span data-ttu-id="699b7-106">CFDI は、SAT が要求する形式で電子請求書を生成するための現在の方法です。</span><span class="sxs-lookup"><span data-stu-id="699b7-106">CFDI is the current method for generating electronic invoices in the format that SAT requires.</span></span> <span data-ttu-id="699b7-107">この方法では、請求書はデジタル署名サービス プロバイダー (PAC) によって検証および認定されます。</span><span class="sxs-lookup"><span data-stu-id="699b7-107">In this method, the invoices are verified and certified by a digital signature service provider (PAC).</span></span> <span data-ttu-id="699b7-108">CFDI 方式を使用して電子請求書を生成する前に、組織は承認された PAC への Web サービス接続を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="699b7-108">Before you can use the CFDI method to generate electronic invoices, your organization must set up a web service connection to an authorized PAC.</span></span> <span data-ttu-id="699b7-109">CFDI 方式の場合、Finance and Operations から PAC に XML メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="699b7-109">For the CFDI method, you send an XML message from Finance and Operations to the PAC.</span></span> <span data-ttu-id="699b7-110">PAC によって各請求書が検証され、フォリオ番号が割り当てられてから、サービス税務当局によって提供されるデジタル スタンプが組み込まれます。</span><span class="sxs-lookup"><span data-stu-id="699b7-110">The PAC validates each invoice, assigns a folio number, and then incorporates the digital stamp that the service tax authorities provide.</span></span> <span data-ttu-id="699b7-111">PAC による承認プロセスが完了すると、組織は承認された XML メッセージを受け取り、請求書を XML または PDF 形式で顧客に送信できます。</span><span class="sxs-lookup"><span data-stu-id="699b7-111">After the PAC completes the approval process, your organization receives the approved XML message, and can then submit the invoice to the customer in XML or PDF format.</span></span> <span data-ttu-id="699b7-112">印刷可能な CFDI フォームの例:</span><span class="sxs-lookup"><span data-stu-id="699b7-112">Example of the printable CFDI form:</span></span>

<span data-ttu-id="699b7-113">![印刷可能な CFDI フォーム](media/Configurable_CFDI_1.png "印刷可能な CFDI フォーム")</span><span class="sxs-lookup"><span data-stu-id="699b7-113">![Printable CFDI form](media/Configurable_CFDI_1.png "Printable CFDI form")</span></span>

<span data-ttu-id="699b7-114">PAC Web サービスとの統合は、メキシコ向けローカライズの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="699b7-114">Integration with the PAC web service is not part of the Mexican localization.</span></span> <span data-ttu-id="699b7-115">それとは別に、CFDI は最近頻繁に行われる法律変更の対象となっており、印刷可能な CFDI フォームをカスタマイズする需要が高まっています。</span><span class="sxs-lookup"><span data-stu-id="699b7-115">Apart from that, CFDI has recently become a subject to frequent law changes and there is increasing demand for customizing printable CFDI forms.</span></span> <span data-ttu-id="699b7-116">この機能によってそれが完全に構成可能になるため、PAC Web サービスとの統合および規制に関する更新のリリースが容易になります。</span><span class="sxs-lookup"><span data-stu-id="699b7-116">This feature will make it fully configurable, so it will be easier to integrate with PAC web services and to release regulatory updates.</span></span> <span data-ttu-id="699b7-117">パートナーおよび顧客向けのエクスペリエンスが向上し、コードを変更することなく、必要に応じて、統合、エクスポートとインポートの形式、および印刷可能なフォームをカスタマイズできるようになります。</span><span class="sxs-lookup"><span data-stu-id="699b7-117">Partners and customers will have a better experience to customize integrations, export and import formats and printable forms, if required, without code changes.</span></span>

<span data-ttu-id="699b7-118">構成可能性の目標は、電子メッセージングとの統合および電子報告機能の使用によって達成される予定です。</span><span class="sxs-lookup"><span data-stu-id="699b7-118">Configurability goals are planned to be met through integration with Electronic messaging and using Electronic Reporting capabilities.</span></span> 

<span data-ttu-id="699b7-119">**メッセージ処理アクションの例**</span><span class="sxs-lookup"><span data-stu-id="699b7-119">**Message processing actions example**</span></span>

<span data-ttu-id="699b7-120">![電子メッセージング - メッセージ処理アクション](media/Configurable_EM_1.png "電子メッセージング - メッセージ処理アクション")</span><span class="sxs-lookup"><span data-stu-id="699b7-120">![Electronic messaging - Message processing actions](media/Configurable_EM_1.png "Electronic messaging - Message processing actions")</span></span>

> [!NOTE]
> <span data-ttu-id="699b7-121">この機能は、既存の構成不可能な CFDI の機能の一部を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="699b7-121">This feature will replace some parts of already existing non-configurable CFDI functionality.</span></span> <span data-ttu-id="699b7-122">新しい機能と更新されたユーザー エクスペリエンスの導入により、古い機能は廃止され、対応するコードは将来のアップデートで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="699b7-122">With introduction of the new feature and updated user experience, the old feature will be deprecated and corresponding code will be removed in a future update.</span></span>  
