---
title: Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用
description: Common Data Service ベースのアプリを AAD セキュリティ グループと共有する
author: alaug
ms.reviewer: pehecke
ms.date: 07/20/2019
ms.assetid: bd88bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: alaug
audience: Power user
ms.openlocfilehash: e9f5200f3b2de47ea4c20832fd049fd05cb82c27
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1994044"
---
# <a name="using-security-roles-with-security-groups-in-azure-active-directory"></a>Azure Active Directory のセキュリティ グループでのセキュリティ ロールの使用



Common Data Service 内のデータを、Azure Active Directory 内の 1 つ以上のセキュリティグループと共有できます。 このデータを共有するには、エンティティに対して 1 つ以上のカスタム セキュリティ ロールを作成し、それらのロールを個々のユーザーではなく、セキュリティ グループに割り当てます。 たとえば、アプリ、フロー、およびエンティティを同じセキュリティ グループと共有できます。
