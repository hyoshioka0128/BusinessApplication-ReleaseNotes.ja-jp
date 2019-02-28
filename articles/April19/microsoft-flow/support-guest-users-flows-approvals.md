---
title: フローと承認におけるゲスト ユーザーのサポート
description: フローと承認の両方で、他のテナントとの共有と、それらのテナントへの割り当てがサポートされます。 これは、AAD のゲスト ユーザーを使用して実現されます。つまり、他のテナントのユーザーをゲストとして招待し、ロールとアクセス許可を割り当てることができます。
author: Mhade
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: eb7358cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: mhade
audience: Power user
ms.openlocfilehash: 90f89eaf5afe51627562377cc3d2f9769d85359d
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "211053"
---
# <a name="support-for-guest-users-in-flows-and-approvals"></a>フローと承認におけるゲスト ユーザーのサポート


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

以前は、フローは同じ組織内の他のユーザーとしか共有できませんでした。 また、*承認*に関しては、同じ会社の他のユーザーにしか送ることができませんでした。プロセスが組織の境界をまたぐことは少なくないため、これは多くのビジネスにとって問題でした。 今リリースでは、フローと承認の両方について、他の組織のユーザーとの共有と、それらのユーザーへの割り当てがサポートされます。

これは、Azure Active Directory (Azure AD) のゲスト ユーザーをサポートすることで実現されています。なお、フローと承認は今後も元の組織内に配置されるので、テナント管理者が管理できます。 そのうえで、他のテナントのユーザーを*ゲスト*として招待し、ロールを割り当てて、プロセスに参加するためのアクセス許可を付与することができます。
