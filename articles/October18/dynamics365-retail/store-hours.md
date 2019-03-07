---
title: 営業時間
description: 印刷されたレシートに対して営業時間を設定できます。
author: rapraj
manager: AnnBe
ms.date: 01/17/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rapraj
audience: IT Pro
ms.openlocfilehash: a95f1e9271965be1359faeff199a349781e09064
ms.sourcegitcommit: 44ed9eddd89e00c08da16c86bae997d3110a6e26
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2019
ms.locfileid: "392015"
---
# <a name="store-hours"></a><span data-ttu-id="97f54-103">営業時間</span><span class="sxs-lookup"><span data-stu-id="97f54-103">Store hours</span></span>


<span data-ttu-id="97f54-104">新しい営業時間機能により、小売業者は複数の店舗の営業時間を取得して維持することができます。</span><span class="sxs-lookup"><span data-stu-id="97f54-104">The new store hours feature provides the ability to capture and maintain multiple sets of store operating hours for a retailer.</span></span> <span data-ttu-id="97f54-105">Dynamics 365 for Retail にはこれまで、小売業者が店舗、コール センター、モバイル、電子商取引などのさまざまなチャネルで営業時間を紹介できる、すぐに使えるソリューションはありませんでした。</span><span class="sxs-lookup"><span data-stu-id="97f54-105">Dynamics 365 for Retail currently had no out-of-box solution to let retailers showcase their store operating hours across different channels like store, call center, mobile, e-commerce, and so on.</span></span>

<span data-ttu-id="97f54-106">小売業者は、Retail で店舗時間を作成して管理できるようになりました。レジ係は、さまざまな場所の店舗の営業時間を調べられるようになり、顧客が買い物をしやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="97f54-106">Retailers can now create and manage their store hours in Retail and have cashiers look up store hours across various locations to assist customers in their shopping experience.</span></span> <span data-ttu-id="97f54-107">また、小売業者はレシートのフッターにそれらを印刷して、小売顧客がいつ店舗を利用できるかを顧客に通知することもできます。</span><span class="sxs-lookup"><span data-stu-id="97f54-107">It also allows retailers to print them at the footer of the receipt to notify customers when the stores are accessible to retail customers.</span></span> 

## <a name="business-value"></a><span data-ttu-id="97f54-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="97f54-108">Business value</span></span>
<span data-ttu-id="97f54-109">すべての小売店には、小売顧客向けにオープンしている営業時間があります。</span><span class="sxs-lookup"><span data-stu-id="97f54-109">All retail stores have store hours when they are open for retail customers.</span></span> <span data-ttu-id="97f54-110">多くの場合、店舗の営業時間は平日と週末で異なり、地域や季節によって、また 1 年のどの時期かによっても異なります。</span><span class="sxs-lookup"><span data-stu-id="97f54-110">In many cases, store hours vary from weekdays to weekends, from various geographies, seasons, and times of the year.</span></span> <span data-ttu-id="97f54-111">顧客は、小売店がいつオープンしているかを一目で簡単に確認できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="97f54-111">Customers need to be able to quickly glance and be aware of when the retail stores are open.</span></span> 

<span data-ttu-id="97f54-112">小売業者は新しい営業時間機能を使用して、地理的に異なる複数の店舗の営業時間を一か所で作成、維持、管理できます。</span><span class="sxs-lookup"><span data-stu-id="97f54-112">Retailers can use the new store hours feature to create, maintain, and manage the store hours for different stores across geographies from a single point.</span></span> <span data-ttu-id="97f54-113">小売業者は POS 端末で新しい営業時間を表示することができ、レジ係は顧客に店舗の営業時間を知らせたり、他の店舗の在庫を探すときに買い物客を支援したりできます。</span><span class="sxs-lookup"><span data-stu-id="97f54-113">Retailers can showcase the new store hours in POS terminals, letting the cashiers share store hours to customers and assist shoppers while looking for inventory in different stores.</span></span> <span data-ttu-id="97f54-114">顧客はまた、店舗を再度利用したいときに、レシートに印刷された新しい営業時間を確認できます。</span><span class="sxs-lookup"><span data-stu-id="97f54-114">Customers also can see the new store hours printed on their receipts in case they wish to return to the store.</span></span> 

<span data-ttu-id="97f54-115">営業時間機能は、e コマース Web サイト、モバイル アプリ、キオスクなどで活用できます。</span><span class="sxs-lookup"><span data-stu-id="97f54-115">Store hours functionality can be leveraged on e-commerce websites, mobile apps, kiosks, and so on.</span></span> <span data-ttu-id="97f54-116">この機能の今後の機能拡張では、小売業者が休日の営業時間と店舗の休みに基づいて、適切な集荷日を設定できるようになる見込みです。</span><span class="sxs-lookup"><span data-stu-id="97f54-116">Future enhancements to this feature might be to enable the retailer to set an appropriate pickup date based on holiday hours and store closures.</span></span>

## <a name="how-to-use-the-store-hours-feature"></a><span data-ttu-id="97f54-117">営業時間機能の使用方法</span><span class="sxs-lookup"><span data-stu-id="97f54-117">How to use the store hours feature</span></span>
<span data-ttu-id="97f54-118">休日と営業時間がわかっている場合、管理者は 1 年間の営業時間またはそれより長いスケジュールを設定できます。</span><span class="sxs-lookup"><span data-stu-id="97f54-118">When the holiday and store hours are known, the admin can set the store hours for the whole year or to an even longer schedule.</span></span>

<span data-ttu-id="97f54-119">![営業時間テンプレート](../../media/Storehours1.png "営業時間テンプレート")</span><span class="sxs-lookup"><span data-stu-id="97f54-119">![Store Hours Template](../../media/Storehours1.png "Store hours template")</span></span> 

<span data-ttu-id="97f54-120">このカレンダーは、さまざまな店舗または店舗グループで利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="97f54-120">This calendar is now made available for the different store or store groups.</span></span> <span data-ttu-id="97f54-121">このカレンダーはすべての店舗向けに設定され、参照用に POS に表示されます。</span><span class="sxs-lookup"><span data-stu-id="97f54-121">The calendar is set for all the stores and should be visible in the POS for reference.</span></span>

<span data-ttu-id="97f54-122">![営業時間テンプレートの保存](../../media/Storehours2.png "営業時間テンプレートの保存")</span><span class="sxs-lookup"><span data-stu-id="97f54-122">![Save Store Hours Template](../../media/Storehours2.png "Save Store hours template")</span></span> 

<span data-ttu-id="97f54-123">販売を完了したレジ係がレシートを印刷します。そこには顧客が確認できるように営業時間が示されます。</span><span class="sxs-lookup"><span data-stu-id="97f54-123">A cashier completing a sale prints the receipt, where the store hours are visible for the customer.</span></span> <span data-ttu-id="97f54-124">今後の休日 (店舗が閉まる日) もレシートに示されます。</span><span class="sxs-lookup"><span data-stu-id="97f54-124">Upcoming holidays—when the store is closed—are also made visible on the receipt.</span></span>

<span data-ttu-id="97f54-125">![レシート テンプレート](../../media/Storehours3.png "レシート テンプレート")</span><span class="sxs-lookup"><span data-stu-id="97f54-125">![Receipt Template](../../media/Storehours3.png "Receipt template")</span></span> 

<span data-ttu-id="97f54-126">顧客から別の店舗の集荷注文を受けた場合、レジ係は、その店舗で集荷が利用できる正しい日付を選択できます。</span><span class="sxs-lookup"><span data-stu-id="97f54-126">If a customer has a pickup order for a different store, the cashier can select the right dates where the pickup will be available in that store.</span></span> <span data-ttu-id="97f54-127">店舗検索によって必要な日付と営業時間を参照できます。</span><span class="sxs-lookup"><span data-stu-id="97f54-127">The store lookup will provide a reference to the dates and store times.</span></span> <span data-ttu-id="97f54-128">レジ係は日付と場所を選択して、営業時間と一緒に集荷レシートを印刷します。</span><span class="sxs-lookup"><span data-stu-id="97f54-128">The cashier will choose a date and location and print a pickup receipt with the store hours.</span></span> 

<span data-ttu-id="97f54-129">![店舗カード テンプレート](../../media/Storehours4.png "店舗カード テンプレート")</span><span class="sxs-lookup"><span data-stu-id="97f54-129">![Store Card Template](../../media/Storehours4.png "Store Card template")</span></span> 
