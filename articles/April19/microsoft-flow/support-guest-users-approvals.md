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
# <a name="support-for-guest-users-in-approvals"></a><span data-ttu-id="3d49e-104">承認におけるゲスト ユーザーのサポート</span><span class="sxs-lookup"><span data-stu-id="3d49e-104">Support for guest users in approvals</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="3d49e-105">以前は、承認を同じ会社の他のユーザーにしか送ることができませんでした。プロセスが組織の境界をまたぐことは少なくないため、これは多くのビジネスにとって問題でした。</span><span class="sxs-lookup"><span data-stu-id="3d49e-105">Before, approvals could only be sent to other people in the same company, which is problematic for many businesses because processes often span organizational boundaries.</span></span> <span data-ttu-id="3d49e-106">今リリースでは、他の組織のユーザーとの承認の共有、および他の組織のユーザーへの承認の割り当てがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="3d49e-106">Now, approvals support sharing and assignment to people in other organizations.</span></span>

<span data-ttu-id="3d49e-107">これは、Azure Active Directory (Azure AD) のゲスト ユーザーをサポートすることで実現されています。なお、承認は引き続き元の組織内に配置されており、テナント管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="3d49e-107">This is enabled through support for Azure Active Directory (Azure AD) guest users—approvals are still in the original organization, so that they can be managed by their tenant administrators.</span></span> <span data-ttu-id="3d49e-108">そのうえで、他のテナントのユーザーを*ゲスト*として招待し、ロールを割り当てて、プロセスに参加するためのアクセス許可を付与することができます。</span><span class="sxs-lookup"><span data-stu-id="3d49e-108">However, users from other tenants can be invited as *guests* and then assigned roles, giving them the permissions to participate in processes.</span></span>
