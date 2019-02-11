---
title: Global Tax Engine でのルックアップ数の削減による税コンフィギュレーションの使いやすさの向上
description: Global Tax Engine のこの機能により、税コンフィギュレーションの使いやすさが向上します。
author: yijialuan
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: riluan
ms.openlocfilehash: b9e22fc0e8f9d4785aef9e90dd0dc07f548ddf06
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210491"
---
#  <a name="global-tax-engine---improving-tax-configuration-usability-with-reduced-number-of-lookups"></a><span data-ttu-id="eb455-103">Global Tax Engine - ルックアップ数の削減による税コンフィギュレーションの使いやすさの向上</span><span class="sxs-lookup"><span data-stu-id="eb455-103">Global Tax Engine - Improving tax configuration usability with reduced number of lookups</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="eb455-104">Global Tax Engine (GTE) で税を構成しているときに、ユーザーは、複数のテーブルを定義して、税率、非控除割合、税コンポーネント、税期間などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="eb455-104">While configuring tax in Global Tax Engine (GTE), users can define multiple tables to look up tax rates, non-deductible percentages, tax components, tax periods, and more.</span></span> <span data-ttu-id="eb455-105">実際のビジネスの実践では、ユーザーはルックアップ テーブルを組み合わせてルックアップ テーブル数を減らすことを希望します。たとえば、原産国/地域、消費国/地域、製品タイプなどのデータ モデル プロパティによって、複数の場所で再利用できる税トランザクションの性質が決まります。</span><span class="sxs-lookup"><span data-stu-id="eb455-105">In the real business practice, users want to reduce the number of lookup tables by combining them; for example, such data model properties as Country/Region of Origin, Consumption of Country/Region, and Product type determine the nature of the tax transaction, which can be reused in many places.</span></span> <span data-ttu-id="eb455-106">このリリースでは、ユーザーは行レベルで文字列タイプのメジャーを追加できます。これはルックアップにすることができます。</span><span class="sxs-lookup"><span data-stu-id="eb455-106">In this release, users can add a string-type measure at the line level, which can be a lookup:</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="eb455-107">![税設定イベント タイプ](media/Tax-setup-tax-event-type.jpg "税設定イベント タイプ")</span><span class="sxs-lookup"><span data-stu-id="eb455-107">![Tax setup event type](media/Tax-setup-tax-event-type.jpg "Tax setup event type")</span></span>

<span data-ttu-id="eb455-108">このメジャーを、レポート作成やレートなどの他のルックアップでさらに使用できます。</span><span class="sxs-lookup"><span data-stu-id="eb455-108">This measure can be further used in other lookups, like reporting, rate, and so on.</span></span> 

> [!div class="mx-imgBorder"]
> <span data-ttu-id="eb455-109">![レポート作成の税設定イベント タイプ](media/Tax-setup-tax-event-type-reporting.jpg "レポート作成の税設定イベント タイプ")</span><span class="sxs-lookup"><span data-stu-id="eb455-109">![Tax setup event type reporting](media/Tax-setup-tax-event-type-reporting.jpg "Tax setup event type reporting")</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="eb455-110">![レートの税設定イベント タイプ](media/Tax-setup-tax-event-type-rate.jpg "レートの税設定イベント タイプ")</span><span class="sxs-lookup"><span data-stu-id="eb455-110">![Tax setup event type rate](media/Tax-setup-tax-event-type-rate.jpg "Tax setup event type rate")</span></span>

<span data-ttu-id="eb455-111">ユーザーが維持する必要のあるルックアップの数が大幅に減り、税コンフィギュレーションの使いやすさが向上します。</span><span class="sxs-lookup"><span data-stu-id="eb455-111">It will dramatically reduce the number of lookups that users need to maintain and will improve the tax configuration usability.</span></span> <span data-ttu-id="eb455-112">この行レベルの文字列型の措置は、税務署類ユーザー インターフェイスにも表示されます。</span><span class="sxs-lookup"><span data-stu-id="eb455-112">This line-level string-type measure will also be shown in the tax document user interface.</span></span> 

> [!NOTE]
> <span data-ttu-id="eb455-113">現在、GTE はインドでのみ利用可能です。</span><span class="sxs-lookup"><span data-stu-id="eb455-113">Currently, GTE is available for India only.</span></span>
