---
title: 1 つの価格表で複数の時間単位をサポート
description: 価格表で、複数の時間単位に対して価格を指定できるようになります
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.openlocfilehash: ec0b4b4fbef8ec0a6ca8c3d59c5ded858615d6c3
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199605"
---
#   <a name="support-for-multiple-time-units-on-a-single-price-list"></a><span data-ttu-id="e167f-103">1 つの価格表で複数の時間単位をサポート</span><span class="sxs-lookup"><span data-stu-id="e167f-103">Support for multiple time units on a single price list</span></span>

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="e167f-104">Project Service では、リソース時間の価格設定がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="e167f-104">Project Service supports pricing resource time.</span></span> <span data-ttu-id="e167f-105">ユーザーは、価格の設定方法として、時間、日、またはその他の時間単位を選択できます。</span><span class="sxs-lookup"><span data-stu-id="e167f-105">Users may choose to set up prices in hours, days, or any other unit of time.</span></span> <span data-ttu-id="e167f-106">現時点では、時間単位は価格表のヘッダーで決定され、リソース時間について価格を個別に変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="e167f-106">One current limitation is that the unit of time is decided on the header of the price list, and can't be changed on individual price setup lines for resource time.</span></span> 

<span data-ttu-id="e167f-107">今回の更新プログラムでは、それぞれの価格表で、複数の時間単位に対して価格を指定できるようになります。</span><span class="sxs-lookup"><span data-stu-id="e167f-107">With this update, each price list will allow you to specify prices for multiple time units.</span></span> <span data-ttu-id="e167f-108">この機能は、労働に関する法令や慣習が異なる複数の地域で業務を運営している企業にとっては特に便利です。</span><span class="sxs-lookup"><span data-stu-id="e167f-108">This is particularly useful for companies that operate across geographies with different labor laws and practices.</span></span> 

<span data-ttu-id="e167f-109">例: "稼働日" のレートを表す場合に、多国籍プロジェクト サービス企業の各事業部で、稼働日を独自に定義することができます。</span><span class="sxs-lookup"><span data-stu-id="e167f-109">For example: When expressing rates for a “working day,” each division of a multi-national project service company might have its own definition of a working day.</span></span> <span data-ttu-id="e167f-110">インドの事業部では稼働日を 8 時間とし、スコットランドの事業部では稼働日を 7.5 時間とする、などといったことが可能です。</span><span class="sxs-lookup"><span data-stu-id="e167f-110">Its India division might work 8-hour days, while its Scotland division might work 7.5-hour days.</span></span> <span data-ttu-id="e167f-111">この機能によって、企業は各事業部に固有の日単位を使用し、1 日あたりの価格を設定できるようになります。</span><span class="sxs-lookup"><span data-stu-id="e167f-111">With this feature, companies will be able to set up prices per day using the day unit that is specific to each division.</span></span>

<span data-ttu-id="e167f-112">![複数の時間単位に対して原価率が指定された価格表](media/multiple-time-unit-on-pricelist.png "複数の時間単位に対して原価率が指定された価格表")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="e167f-112">![Cost rates for multiple time units on Price List](media/multiple-time-unit-on-pricelist.png "Cost rates for multiple time units on price list")
<!-- Picture 2 --></span></span>
