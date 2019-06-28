---
title: 承認におけるゲスト ユーザーのサポート
description: 承認で、他のテナントとの共有と、それらのテナントへの割り当てがサポートされます。 これは、AAD のゲスト ユーザーを通じて実現されます。つまり、他のテナントのユーザーをゲストとして招待し、ロールとアクセス許可を割り当てることができます。
author: KaranSr
ms.reviewer: deonhe
ms.date: 05/06/2019
ms.assetid: 9b88bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: karansr
audience: Power user
ms.openlocfilehash: e9da2f4a8dc710bc4061cab2d08d572cf09cdda5
ms.sourcegitcommit: 2377f9a8537925401f30f33dd73d1eb1eecda35a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/06/2019
ms.locfileid: "1621481"
---
# <a name="support-for-guest-users-in-approvals"></a>承認におけるゲスト ユーザーのサポート

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

以前は、承認を同じ会社の他のユーザーにしか送ることができませんでした。プロセスが組織の境界をまたぐことは少なくないため、これは多くのビジネスにとって問題でした。 今リリースでは、他の組織のユーザーとの承認の共有、および他の組織のユーザーへの承認の割り当てがサポートされています。

これは、Azure Active Directory (Azure AD) のゲスト ユーザーをサポートすることで実現されています。なお、承認は引き続き元の組織内に配置されており、テナント管理者が管理できます。 そのうえで、他のテナントのユーザーを*ゲスト*として招待し、ロールを割り当てて、プロセスに参加するためのアクセス許可を付与することができます。
