---
title: Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用
description: Common Data Service ベースのアプリを AAD セキュリティ グループと共有する
author: alaug
ms.reviewer: anneta
ms.date: 05/17/2019
ms.assetid: bd88bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: alaug
audience: Power user
ms.openlocfilehash: b7a5f7ad3370171517151834f62211fa8cdf490b
ms.sourcegitcommit: 6c1c9ed9328a3b6194ebc4741d0beeef0ef435f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/23/2019
ms.locfileid: "1605614"
---
# <a name="using-security-roles-with-security-groups-in-azure-active-directory"></a>Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

Common Data Service 内のデータを、Azure Active Directory 内の 1 つ以上のセキュリティグループと共有できます。 このデータを共有するには、エンティティに対して 1 つ以上のカスタム セキュリティ ロールを作成し、それらのロールを個々のユーザーではなく、セキュリティ グループに割り当てます。 たとえば、アプリ、フロー、およびエンティティを同じセキュリティ グループと共有できます。
