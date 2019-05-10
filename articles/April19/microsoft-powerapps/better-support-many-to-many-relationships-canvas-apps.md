---
title: キャンバス アプリでの多対多リレーションシップのサポート強化
description: キャンバス アプリケーションで一対多および多対多の関係をたどり、レコード相互の関連付け/関連付け解除を行います
author: gregli-msft
ms.reviewer: anneta
ms.date: 04/26/2019
ms.assetid: 0587bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: 746277f651c17041522e6b9aa1f590ba4c8c95b4
ms.sourcegitcommit: 71c309c00b3ce1028adfd94f110aa6682b07af01
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1446115"
---
# <a name="better-support-for-many-to-many-relationships-in-canvas-apps-public-preview"></a><span data-ttu-id="9613f-103">キャンバス アプリでの多対多リレーションシップのサポート強化 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="9613f-103">Better support for many-to-many relationships in canvas apps (Public Preview)</span></span>



<span data-ttu-id="9613f-104">ビジネス データはリレーショナルです。</span><span class="sxs-lookup"><span data-stu-id="9613f-104">Business data is relational.</span></span> <span data-ttu-id="9613f-105">顧客、従業員、供給業者、荷主、製品、在庫が、注文と発注を通じて相互に関連しています。</span><span class="sxs-lookup"><span data-stu-id="9613f-105">Customers, employees, suppliers, shippers, products, and inventory inter-relate through orders and purchase orders.</span></span> <span data-ttu-id="9613f-106">Common Data Service では、これらのリレーションシップが一対多、多対一、または多対多のリレーションシップとしてモデル化されます。</span><span class="sxs-lookup"><span data-stu-id="9613f-106">In Common Data Service, these relationships are modeled as one-to-many, many-to-one, or many-to-many relationships.</span></span>

<span data-ttu-id="9613f-107">作成者は、以前の多対一リレーションシップで行ったのと同じように、単純なオブジェクト ドット表記を使用して、Common Data Service のこれらすべての種類のリレーションシップをたどることができます。</span><span class="sxs-lookup"><span data-stu-id="9613f-107">Makers can walk all of these types of relationships in Common Data Service by using a simple object-dot notation, just as they have previously done with many-to-one relationships.</span></span> <span data-ttu-id="9613f-108">たとえば、注文.従業員.名前は、注文エンティティから多対一のリレーションシップをたどって従業員エンティティに至り、名前フィールドを取得します。</span><span class="sxs-lookup"><span data-stu-id="9613f-108">For example, Orders.Employees.Name walks from the Orders entity across a many-to-one relationship to the Employees entity and retrieves the Name field.</span></span> <span data-ttu-id="9613f-109">逆に、従業員.注文では、この従業員が割り当てた注文のテーブルが返され、多対多のリレーションシップも同じ方法で処理されます。</span><span class="sxs-lookup"><span data-stu-id="9613f-109">Conversely, Employees.Orders returns the table of orders that this employee has assigned, and many-to-many relationships are handled in the same manner.</span></span> <span data-ttu-id="9613f-110">さらに、多対多のリレーションシップはどちらのエンティティのルックアップ フィールドにも基づいていないため、作成者は新しい関数を使用してレコードを関連付けたりレコードの関連付けを解除したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="9613f-110">In addition, many-to-many relationships aren't based on a lookup field in either entity, so makers can relate and unrelate records by using new functions.</span></span>

<span data-ttu-id="9613f-111">![簡単な式で製品エンティティから選択した製品のレビューまでたどる](media/OneToMany.png "簡単な式で製品エンティティから選択した製品のレビューまでたどる")</span><span class="sxs-lookup"><span data-stu-id="9613f-111">![Walking from the Products entity to the reviews of a selected product with a simple formula](media/OneToMany.png "Walking from the Products entity to the reviews of a selected product with a simple formula")</span></span>
