---
title: Global Tax Engine での税通貨と消費税コードによる税コンフィギュレーションの有効化
description: この機能のリリースにより、ユーザーは、ルックアップ テーブルで税コンポーネントの税通貨を定義することができます。 ユーザーは、税設定で消費税コードを保守し、ルックアップ テーブル内の消費税コードに税コンポーネントをマップし、これらの消費税コードの期間およびレポート コードを保守することもできます。
author: yijialuan
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: riluan
ms.openlocfilehash: e25b3e8f5db704e1ecdb41e1d8ea5842e7246427
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225296"
---
#  <a name="global-tax-engine-india---enabling-tax-configuration-with-tax-currency-and-sales-tax-codes"></a><span data-ttu-id="26118-104">Global Tax Engine (インド) - 税通貨と消費税コードによる税コンフィギュレーションの有効化</span><span class="sxs-lookup"><span data-stu-id="26118-104">Global Tax Engine (India) - Enabling tax configuration with tax currency and sales tax codes</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

> [!NOTE]
> <span data-ttu-id="26118-105">現在、Global Tax Engine はインドでのみ利用可能です。</span><span class="sxs-lookup"><span data-stu-id="26118-105">Currently, Global Tax Engine is available for India only.</span></span>

<span data-ttu-id="26118-106">消費税コードは、Global Tax Engine (GTE) と Dynamics 365 for Finance and Operations を統合するために必須の設定です。</span><span class="sxs-lookup"><span data-stu-id="26118-106">Sales tax code is a mandatory setup for Global Tax Engine (GTE) to integrate with Dynamics 365 for Finance and Operations.</span></span> <span data-ttu-id="26118-107">以前は、税コンフィギュレーションを同期するときに GTE によって税コンポーネントと同じ名前の消費税コードが作成され、自動作成の消費税コードには会計通貨が使用されていました。</span><span class="sxs-lookup"><span data-stu-id="26118-107">Previously, GTE created sales tax code with the same name as the tax component when synchronizing the tax configuration, and it used the accounting currency for the auto-create sales tax codes.</span></span> 

<span data-ttu-id="26118-108">世界中で複数の税を登録している企業では、異なる国で使用されている税コンポーネントに対して異なる税通貨を維持する必要があります。</span><span class="sxs-lookup"><span data-stu-id="26118-108">Companies with multiple tax registration across the world need to maintain different tax currencies for tax components used in different countries.</span></span> <span data-ttu-id="26118-109">この機能のリリースにより、ユーザーは、税設定で消費税コードを保守し、ルック アップテーブル内の消費税コードに税コンポーネントをマップし、これらの消費税コードの税通貨と決済期間を維持できます。</span><span class="sxs-lookup"><span data-stu-id="26118-109">With the release of this feature, users can maintain the sales tax code in tax setup, map the tax component to sales tax code in lookup tables, and maintain tax currency and settlement period of these sales tax codes.</span></span>

<span data-ttu-id="26118-110">![税設定レポート](media/Tax-setup-Reporting.jpg "税設定レポート")</span><span class="sxs-lookup"><span data-stu-id="26118-110">![Tax setup reporting](media/Tax-setup-Reporting.jpg "Tax setup reporting")</span></span>

<span data-ttu-id="26118-111">税設定では、GTE はマッピングされた消費税コード、税通貨、および決済期間を使用して税取引を転記します。</span><span class="sxs-lookup"><span data-stu-id="26118-111">With the tax setup, GTE will use the mapped sales tax code, tax currency, and settlement period for posting the tax transactions.</span></span>

<span data-ttu-id="26118-112">![税設定レポートで転記された消費税](media/Tax-setup-Reporting-Posted-Sales-tax.jpg "税設定レポートで転記された消費税")</span><span class="sxs-lookup"><span data-stu-id="26118-112">![Tax setup reporting posted sales tax](media/Tax-setup-Reporting-Posted-Sales-tax.jpg "Tax setup reporting posted sales tax")</span></span>


