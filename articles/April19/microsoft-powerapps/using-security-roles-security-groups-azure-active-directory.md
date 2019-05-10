---
title: Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用
description: Common Data Service ベースのアプリを AAD セキュリティ グループと共有する
author: alaug
ms.reviewer: anneta
ms.date: 04/26/2019
ms.assetid: bd88bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: alaug
audience: Power user
ms.openlocfilehash: 9cd0e32ca257dfb8b74ce03b99a9295c9cf94a08
ms.sourcegitcommit: 71c309c00b3ce1028adfd94f110aa6682b07af01
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1446332"
---
# <a name="using-security-roles-with-security-groups-in-azure-active-directory"></a><span data-ttu-id="1694f-103">Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用</span><span class="sxs-lookup"><span data-stu-id="1694f-103">Using security roles with security groups in Azure Active Directory</span></span>

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="1694f-104">Common Data Service 内のデータを、Azure Active Directory 内の 1 つ以上のセキュリティグループと共有できます。</span><span class="sxs-lookup"><span data-stu-id="1694f-104">You can share data in Common Data Service with one or more security groups in Azure Active Directory.</span></span> <span data-ttu-id="1694f-105">このデータを共有するには、エンティティに対して 1 つ以上のカスタム セキュリティ ロールを作成し、それらのロールを個々のユーザーではなく、セキュリティ グループに割り当てます。</span><span class="sxs-lookup"><span data-stu-id="1694f-105">To share this data, create one or more custom security roles for your entities and assign those roles to security groups instead of to individual users.</span></span> <span data-ttu-id="1694f-106">たとえば、アプリ、フロー、およびエンティティを同じセキュリティ グループと共有できます。</span><span class="sxs-lookup"><span data-stu-id="1694f-106">You can, for example, share apps, flows, and entities with the same security group.</span></span>
