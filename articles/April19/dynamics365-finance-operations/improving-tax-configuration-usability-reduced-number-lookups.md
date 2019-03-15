---
title: Global Tax Engine でのルックアップ数の削減による税コンフィギュレーションの使いやすさの向上
description: Global Tax Engine のこの機能により、税コンフィギュレーションの使いやすさが向上します。
author: yijialuan
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: riluan
ms.openlocfilehash: 5c17d560216d8de41ced03211bc06db742e9f07d
ms.sourcegitcommit: 365db01dde7ccb5c763d209fedbc715d128b18a6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2019
ms.locfileid: "376829"
---
#  <a name="global-tax-engine-india---improving-tax-configuration-usability-with-reduced-number-of-lookups"></a><span data-ttu-id="6d166-103">Global Tax Engine (インド) - ルックアップ数の削減による税コンフィギュレーションの使いやすさの向上</span><span class="sxs-lookup"><span data-stu-id="6d166-103">Global Tax Engine (India) - Improving tax configuration usability with reduced number of lookups</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

> [!NOTE]
> <span data-ttu-id="6d166-104">現在、GTE はインドでのみ利用可能です。</span><span class="sxs-lookup"><span data-stu-id="6d166-104">Currently, GTE is available for India only.</span></span>

<span data-ttu-id="6d166-105">Global Tax Engine (GTE) で税を構成しているときに、ユーザーは、複数のテーブルを定義して、税率、非控除割合、税コンポーネント、税期間などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="6d166-105">While configuring tax in Global Tax Engine (GTE), users can define multiple tables to look up tax rates, non-deductible percentages, tax components, tax periods, and more.</span></span> <span data-ttu-id="6d166-106">実際のビジネスの実践では、ユーザーはルックアップ テーブルを組み合わせてルックアップ テーブル数を減らすことを希望します。たとえば、原産国/地域、消費国/地域、製品タイプなどのデータ モデル プロパティによって、複数の場所で再利用できる税トランザクションの性質が決まります。</span><span class="sxs-lookup"><span data-stu-id="6d166-106">In the real business practice, users want to reduce the number of lookup tables by combining them; for example, such data model properties as Country/Region of Origin, Consumption of Country/Region, and Product type determine the nature of the tax transaction, which can be reused in many places.</span></span> <span data-ttu-id="6d166-107">このリリースでは、ユーザーは行レベルで文字列タイプのメジャーを追加できます。これはルックアップにすることができます。</span><span class="sxs-lookup"><span data-stu-id="6d166-107">In this release, users can add a string-type measure at the line level, which can be a lookup:</span></span>

<span data-ttu-id="6d166-108">![税設定イベント タイプ](media/Tax-setup-tax-event-type.jpg "税設定イベント タイプ")</span><span class="sxs-lookup"><span data-stu-id="6d166-108">![Tax setup event type](media/Tax-setup-tax-event-type.jpg "Tax setup event type")</span></span>

<span data-ttu-id="6d166-109">このメジャーを、レポート作成やレートなどの他のルックアップでさらに使用できます。</span><span class="sxs-lookup"><span data-stu-id="6d166-109">This measure can be further used in other lookups, like reporting, rate, and so on.</span></span> 

<span data-ttu-id="6d166-110">![レポート作成の税設定イベント タイプ](media/Tax-setup-tax-event-type-reporting.jpg "レポート作成の税設定イベント タイプ")</span><span class="sxs-lookup"><span data-stu-id="6d166-110">![Tax setup event type reporting](media/Tax-setup-tax-event-type-reporting.jpg "Tax setup event type reporting")</span></span>

<span data-ttu-id="6d166-111">![レートの税設定イベント タイプ](media/Tax-setup-tax-event-type-rate.jpg "レートの税設定イベント タイプ")</span><span class="sxs-lookup"><span data-stu-id="6d166-111">![Tax setup event type rate](media/Tax-setup-tax-event-type-rate.jpg "Tax setup event type rate")</span></span>

<span data-ttu-id="6d166-112">ユーザーが維持する必要のあるルックアップの数が大幅に減り、税コンフィギュレーションの使いやすさが向上します。</span><span class="sxs-lookup"><span data-stu-id="6d166-112">It will dramatically reduce the number of lookups that users need to maintain and will improve the tax configuration usability.</span></span> <span data-ttu-id="6d166-113">この行レベルの文字列型の措置は、税務署類ユーザー インターフェイスにも表示されます。</span><span class="sxs-lookup"><span data-stu-id="6d166-113">This line-level string-type measure will also be shown in the tax document user interface.</span></span> 


