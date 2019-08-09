---
title: 承認におけるゲスト ユーザーのサポート
description: 承認で、他のテナントとの共有と、それらのテナントへの割り当てがサポートされます。 これは、AAD のゲスト ユーザーを通じて実現されます。つまり、他のテナントのユーザーをゲストとして招待し、ロールとアクセス許可を割り当てることができます。
author: KaranSr
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: 9b88bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: karansr
audience: Power user
ms.openlocfilehash: d8bc1e87a106a6d0c517544550bf32688919d87f
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756873"
---
# <a name="support-for-guest-users-in-approvals"></a>承認におけるゲスト ユーザーのサポート

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

以前は、承認を同じ会社の他のユーザーにしか送ることができませんでした。プロセスが組織の境界をまたぐことは少なくないため、これは多くのビジネスにとって問題でした。 今リリースでは、他の組織のユーザーとの承認の共有、および他の組織のユーザーへの承認の割り当てがサポートされています。

これは、Azure Active Directory (Azure AD) のゲスト ユーザーをサポートすることで実現されています。なお、承認は引き続き元の組織内に配置されており、テナント管理者が管理できます。 そのうえで、他のテナントのユーザーを*ゲスト*として招待し、ロールを割り当てて、プロセスに参加するためのアクセス許可を付与することができます。
