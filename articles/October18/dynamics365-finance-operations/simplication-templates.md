---
title: 構成可能なテンプレートによる簡略化
description: 構成可能なテンプレートによる簡略化
author: Annbe
manager: AnnBe
ms.date: 09/06/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: end-user
ms.openlocfilehash: b6a9664c7dee1e53db19eaf6ea09f30073f255ea
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199301"
---
#  <a name="simplification-through-configurable-templates"></a><span data-ttu-id="944a0-103">構成可能なテンプレートによる簡略化</span><span class="sxs-lookup"><span data-stu-id="944a0-103">Simplification through configurable templates</span></span> 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="944a0-104">お客様は、構成可能な顧客請求書やその他の外部レポート形式を使用することで、時間とコストを節約することができます。</span><span class="sxs-lookup"><span data-stu-id="944a0-104">Customers will save time and money by using configurable customer invoice and other external report formats.</span></span> <span data-ttu-id="944a0-105">各形式では、事前印刷用紙や普通紙にドキュメントを印刷するためのオプションが提供されます。</span><span class="sxs-lookup"><span data-stu-id="944a0-105">The formats provide options to print documents to preprinted forms as well as plain paper.</span></span> <span data-ttu-id="944a0-106">構成可能なテンプレートを使用すると、請求書や顧客取引明細書を X++ コードや SQL Server Reporting Services (SSRS) で変更する必要性をなくしたり、最小限に減らすことができます。</span><span class="sxs-lookup"><span data-stu-id="944a0-106">Using the configurable templates will either eliminate or minimize the need to modify invoices and customer statements in X++ code or in SQL Server Reporting Services (SSRS).</span></span> <span data-ttu-id="944a0-107">2018 年 10 月リリースでは、構成可能なテンプレートは自由書式の請求書でのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="944a0-107">In the October '18 release, the configurable template is available for free text invoices only.</span></span> <span data-ttu-id="944a0-108">テンプレートは、既存の自由書式請求書から作成することもできますし、新しい請求書の作成時に新規作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="944a0-108">A template can be created from an existing free text invoice, or a new template can be created and used when creating new invoices.</span></span> <span data-ttu-id="944a0-109">今後の更新プログラムでは、顧客請求書、取引明細書、およびその他の外部ドキュメント用に、構成可能なテンプレートの数を増やしていく予定です。</span><span class="sxs-lookup"><span data-stu-id="944a0-109">In later updates we will extend the number of configurable templates for customer invoices, statements, and other external documents.</span></span>

> [!NOTE]
> <span data-ttu-id="944a0-110">2018 年 10 月リリースでは、パブリック レビューに使用した自由書式の請求書テンプレートのサンプル構成と、それがベースとするデータ モデル (顧客請求書モデル) が廃止され、使用できなくなりました。</span><span class="sxs-lookup"><span data-stu-id="944a0-110">In the October '18 release, the sample Free Text Invoice template configuration that was used for public review and the data model it is based on (Customer invoicing model) are discontinued and can no longer be used.</span></span>

<span data-ttu-id="944a0-111">![構成可能な自由書式の請求書の例](media/configurablefti.png "構成可能な自由書式の請求書の例")</span><span class="sxs-lookup"><span data-stu-id="944a0-111">![Configurable free text invoice example](media/configurablefti.png "Configurable free text invoice example")</span></span>
