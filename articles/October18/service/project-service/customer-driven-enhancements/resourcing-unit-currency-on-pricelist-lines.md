---
title: コストのロール価格明細のリソース単位通貨
description: リソース時間の原価率をリソース単位の通貨で表現できるようになりました
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.openlocfilehash: 3991215e52ecc9eb1cf741e880bc0c04bfec71e8
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199662"
---
#  <a name="resourcing-unit-currency-on-role-price-lines-for-cost"></a><span data-ttu-id="adbf9-103">コストのロール価格明細のリソース単位通貨</span><span class="sxs-lookup"><span data-stu-id="adbf9-103">Resourcing unit currency on role price lines for cost</span></span> 

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="adbf9-104">Project Service では、価格表ヘッダーで指定された、価格表あたり 1 つの通貨のみ許可されます。</span><span class="sxs-lookup"><span data-stu-id="adbf9-104">Project Service allows only one currency per price list, which is specified on the price list header.</span></span> <span data-ttu-id="adbf9-105">リソース価格の価格表明細に、価格表ヘッダーで指定されているものと同じ通貨があります。</span><span class="sxs-lookup"><span data-stu-id="adbf9-105">The price list line for resource pricing has the same currency specified on the price list header.</span></span> <span data-ttu-id="adbf9-106">ただし、国をまたがるすべての事業部に対して一元化された価格を持つ、グローバルに活動しているプロジェクト サービス企業の場合、販売またはコストが発生する通貨ごとに価格表を設定する必要があるデータ中心のセットアップが必要な場合があります。</span><span class="sxs-lookup"><span data-stu-id="adbf9-106">However, for globally operating project service companies that have centralized pricing across all of their divisions across countries, this can necessitate a data-intensive setup where they'll need to set up a price list for each distinct currency that they sell or incur costs in.</span></span> 

<span data-ttu-id="adbf9-107">この機能を使用すると、Project Service は価格表ヘッダーの通貨とは異なるリソース価格の明細行レベル通貨に対応できます。</span><span class="sxs-lookup"><span data-stu-id="adbf9-107">With this feature, Project Service will allow for a line-level currency for resource prices that differs from the price list header currency.</span></span> <span data-ttu-id="adbf9-108">価格表ヘッダー上の通貨は、リソース価格明細で既定として使用されます。</span><span class="sxs-lookup"><span data-stu-id="adbf9-108">Currency on the price list header will be used as a default on the resource price lines.</span></span> <span data-ttu-id="adbf9-109">このようにして、より一元的な価格設定を望む大規模なグローバル企業は、多くの通貨でリソース価格を指定する 1 つのグローバル価格表を操作できます。</span><span class="sxs-lookup"><span data-stu-id="adbf9-109">This way, large global firms that would like more centralized pricing setup may work with one global price list that specifies resource prices in many currencies.</span></span> <span data-ttu-id="adbf9-110">これにより、各リソース単位によって管理される価格が 1 つのマスター価格表としてまとめられるシナリオも可能になります。</span><span class="sxs-lookup"><span data-stu-id="adbf9-110">This could also enable scenarios where prices managed by each resourcing unit come together as one master price list.</span></span>

<span data-ttu-id="adbf9-111">依然として価格表あたり 1 つの通貨を使用することもできます。これは、より分権的な価格設定に対応する企業や、リソースの換算価格を追跡する企業にとってメリットがあります。</span><span class="sxs-lookup"><span data-stu-id="adbf9-111">Using a single currency per price list will still function, which benefits companies that allow for more decentralized pricing and that track exchange prices for resources.</span></span> <span data-ttu-id="adbf9-112">これは、価格表のリソース価格が価格表ヘッダーの通貨に従うようにカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="adbf9-112">This can be customized so that the resource prices on a price list follow the currency of the price list header.</span></span>

<span data-ttu-id="adbf9-113">![複数通貨での価格表明細があるコストの価格表](media/Resourcing-unit-currency-on-pricelist.png "複数通貨での価格表明細があるコストの価格表")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="adbf9-113">![Price list for cost with price list lines in multiple currencies](media/Resourcing-unit-currency-on-pricelist.png "Price list for cost with price list lines in multiple currencies")
<!-- Picture 2 --></span></span>
