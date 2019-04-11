---
title: Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用
description: CDS ベースのアプリを AAD セキュリティ グループと共有する
author: matthewbolanos
ms.reviewer: anneta
ms.date: 03/20/2019
ms.assetid: 9fab1c2c-b9c5-e811-a973-000d3a137a43
ms.topic: article
ms.service: business-applications
ms.author: mabolan
audience: Power user
ms.openlocfilehash: 2b269112839f5b98bec04cbc51f98bd83059f306
ms.sourcegitcommit: ca3b94f829721c2ba02b25134536a58babed2d2b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/27/2019
ms.locfileid: "900461"
---
# <a name="using-security-roles-with-security-groups-in-azure-active-directory"></a><span data-ttu-id="98ad5-103">Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用</span><span class="sxs-lookup"><span data-stu-id="98ad5-103">Using security roles with security groups in Azure Active Directory</span></span>


[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

<span data-ttu-id="98ad5-104">Common Data Service for Apps 内のデータを、Azure Active Directory 内の 1 つ以上のセキュリティグループと共有できます。</span><span class="sxs-lookup"><span data-stu-id="98ad5-104">You can share data in Common Data Service for Apps with one or more security groups in Azure Active Directory.</span></span> <span data-ttu-id="98ad5-105">このデータを共有するには、エンティティに対して 1 つ以上のカスタム セキュリティ ロールを作成し、それらのロールを個々のユーザーではなく、セキュリティ グループに割り当てます。</span><span class="sxs-lookup"><span data-stu-id="98ad5-105">To share this data, create one or more custom security roles for your entities and assign those roles to security groups instead of to individual users.</span></span> <span data-ttu-id="98ad5-106">たとえば、アプリ、フロー、およびエンティティを同じセキュリティ グループと共有できます。</span><span class="sxs-lookup"><span data-stu-id="98ad5-106">You can, for example, share apps, flows, and entities with the same security group.</span></span>
