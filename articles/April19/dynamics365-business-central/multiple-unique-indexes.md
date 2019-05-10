---
title: 複数の固有キー
description: 複数の固有キー
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: b72dafd23f1f9f445d2348d2c44637fb4d0d8e9a
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225050"
---
# <a name="multiple-unique-keys"></a><span data-ttu-id="b408f-103">複数の固有キー</span><span class="sxs-lookup"><span data-stu-id="b408f-103">Multiple unique keys</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="b408f-104">AL のキー定義には Unique プロパティが含まれるようになり、それを使用して SQL Server のテーブルに一意制約を作成できます。</span><span class="sxs-lookup"><span data-stu-id="b408f-104">In AL, a key definition now includes the Unique property that you can use to create a unique constraint on the table in SQL Server.</span></span> <span data-ttu-id="b408f-105">固有キーは、テーブル内のレコードが同じフィールド値を持たないようにします。</span><span class="sxs-lookup"><span data-stu-id="b408f-105">A unique key ensures that records in a table do not have identical field values.</span></span> <span data-ttu-id="b408f-106">固有キーがあると、テーブルが検証されるときに、キー値の一意性がチェックされます。</span><span class="sxs-lookup"><span data-stu-id="b408f-106">With a unique key, when a table is validated, the key value is checked for uniqueness.</span></span> <span data-ttu-id="b408f-107">テーブルに重複値を持つレコードが含まれていると、検証は失敗します。</span><span class="sxs-lookup"><span data-stu-id="b408f-107">If the table includes records with duplicate values, the validation fails.</span></span> <span data-ttu-id="b408f-108">固有インデックスのもう 1 つの利点は、より効率的な実行計画を作成するのに役立つ情報がクエリ オプティマイザーに提供されることです。</span><span class="sxs-lookup"><span data-stu-id="b408f-108">Another benefit of unique indexes is providing information to the query optimizer that helps produce more efficient execution plans.</span></span>

<span data-ttu-id="b408f-109">主キーと同様に、複数のフィールドで構成される固有の予備キーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="b408f-109">Like primary keys, you can create unique secondary keys that are composed of multiple fields.</span></span> <span data-ttu-id="b408f-110">この場合、一意でなければならないのは予備キーの値の組み合わせです。</span><span class="sxs-lookup"><span data-stu-id="b408f-110">In this case, it's the combination of the values in the secondary key that must be unique.</span></span> <span data-ttu-id="b408f-111">たとえば、Customer テーブルがある場合、Name、Address、City フィールドに固有キーを作成して、これらのフィールドの値の同じ組み合わせを持つ顧客がいないようにできます。</span><span class="sxs-lookup"><span data-stu-id="b408f-111">For example, if you have a Customer table, you could create a unique key for the Name, Address, and City fields to make sure that there are no customers that have the same combination of values for these fields.</span></span> <span data-ttu-id="b408f-112">主キーとは異なり、1 つのテーブルに複数の固有予備キーを定義することができます。</span><span class="sxs-lookup"><span data-stu-id="b408f-112">Unlike primary keys, it is possible to define multiple unique secondary keys on a table.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="b408f-113">フィードバック</span><span class="sxs-lookup"><span data-stu-id="b408f-113">Tell us what you think</span></span>
<span data-ttu-id="b408f-114">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="b408f-114">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="b408f-115">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="b408f-115">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
