---
title: Azure Active Directory のセキュリティ グループを使用してエンティティを共有する
description: CDS ベースのアプリを AAD セキュリティ グループと共有する
author: litran
ms.reviewer: anneta
ms.date: 01/08/2019
ms.assetid: 9fab1c2c-b9c5-e811-a973-000d3a137a43
ms.topic: article
ms.service: business-applications
ms.author: litran
audience: Power user
ms.openlocfilehash: 9d67da05aa43ed112d8c1cfffe7ac271c5f2bbf2
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210319"
---
# <a name="share-entities-by-using-security-groups-in-azure-active-directory"></a><span data-ttu-id="5316c-103">Azure Active Directory のセキュリティ グループを使用してエンティティを共有する</span><span class="sxs-lookup"><span data-stu-id="5316c-103">Share entities by using security groups in Azure Active Directory</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="5316c-104">Common Data Service for Apps 内のデータを、Azure Active Directory 内の 1 つ以上のセキュリティグループと共有できます。</span><span class="sxs-lookup"><span data-stu-id="5316c-104">You can share data in Common Data Service for Apps with one or more security groups in Azure Active Directory.</span></span> <span data-ttu-id="5316c-105">このデータを共有するには、エンティティに対して 1 つ以上のカスタム セキュリティ ロールを作成し、それらのロールを個々のユーザーではなく、セキュリティ グループに割り当てます。</span><span class="sxs-lookup"><span data-stu-id="5316c-105">To share this data, create one or more custom security roles for your entities and assign those roles to security groups instead of to individual users.</span></span> <span data-ttu-id="5316c-106">たとえば、アプリ、フロー、およびエンティティを同じセキュリティ グループと共有できます。</span><span class="sxs-lookup"><span data-stu-id="5316c-106">You can, for example, share apps, flows, and entities with the same security group.</span></span>
