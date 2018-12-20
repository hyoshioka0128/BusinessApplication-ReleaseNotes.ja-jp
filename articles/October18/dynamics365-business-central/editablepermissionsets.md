---
title: "編集可能なアクセス許可セット"
description: "エンド ユーザーがアクセス許可セットを編集できるようになります"
author: bnielse
manager: edupont04
ms.date: 11/07/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: bnielse
audience: developer, admin, end user, customizer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: cdbe692282951665ec1a0d55010d4adbeddb1cba
ms.openlocfilehash: d402e30454de93e061c6923d9b8d22596d4e8bbd
ms.contentlocale: ja-jp
ms.lasthandoff: 11/07/2018

---

# <a name="permission-sets-are-editable"></a><span data-ttu-id="871a3-103">アクセス許可セットを編集可能</span><span class="sxs-lookup"><span data-stu-id="871a3-103">Permission sets are editable</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="871a3-104">顧客には Business Central でユーザーが実行できる必要があることについての独自の定義が存在することがよくあり、これらの定義が定義済みのアクセス許可セットと一致していないことがあります。</span><span class="sxs-lookup"><span data-stu-id="871a3-104">Customers often have their own definitions of what people should be able to do in Business Central, and those definitions do not always align with our predefined permission sets.</span></span> <span data-ttu-id="871a3-105">これに対処するため、アクセス許可セットを編集可能にして、追加、削除、変更できるようにしました。</span><span class="sxs-lookup"><span data-stu-id="871a3-105">To address that, we have made permission sets editable so that you can add, delete, and modify them.</span></span>

<span data-ttu-id="871a3-106">アクセス許可セットのリストからは、新しいアクセス許可を追加したり、既存のアクセス許可セットをコピーしたりできます。</span><span class="sxs-lookup"><span data-stu-id="871a3-106">From the list of permission sets, you can add new and copy an existing permission set.</span></span> <span data-ttu-id="871a3-107">結果セットの種類はユーザー定義になります。</span><span class="sxs-lookup"><span data-stu-id="871a3-107">The resulting set will be of type User-Defined.</span></span> <span data-ttu-id="871a3-108">既存のアクセス許可セットをコピーする場合は、元のアクセス許可セットが変更されたら通知を受け取ることを選択できるので、必要に応じてカスタマイズ セットを更新できます。</span><span class="sxs-lookup"><span data-stu-id="871a3-108">If you copy an existing permission set, you can choose to be notified if the original permission set changes so that you can update the customized set if needed.</span></span>  

> [!div class="mx-imgBorder"]
> <span data-ttu-id="871a3-109">![](media/editablepermissionsets_list.png "必要なアクセス許可セットを追加する。")</span><span class="sxs-lookup"><span data-stu-id="871a3-109">![](media/editablepermissionsets_list.png "Add the permission sets you need.")</span></span>

<span data-ttu-id="871a3-110">さらに、アクセス許可セットの定義を含むファイル (パートナー提供のファイルや、別の会社からコピーされたファイルなど) をインポートしたり、RapidStart を使用してアクセス許可セットを追加したりすることもできます。</span><span class="sxs-lookup"><span data-stu-id="871a3-110">Additionally, you can now import files with permission sets definitions, such as files provided by a partner or copied from another company, and you can use RapidStart to add permission sets.</span></span>

# <a name="overview-of-effective-permissions-for-a-user"></a><span data-ttu-id="871a3-111">ユーザーに対する有効なアクセス許可の概要</span><span class="sxs-lookup"><span data-stu-id="871a3-111">Overview of effective permissions for a user</span></span>

<span data-ttu-id="871a3-112">セットアップとトラブルシューティングでは、ユーザーのアクセス許可がどこから付与され、ユーザーの資格 (ライセンス) によって何に対するアクセス権が与えられるのかについての情報が必要です。</span><span class="sxs-lookup"><span data-stu-id="871a3-112">For setup and troubleshooting, you need information on where the user’s permissions come from and what the user’s entitlement (license) gives them access to.</span></span>

<span data-ttu-id="871a3-113">各ユーザー カードからの [有効なアクセス許可] ウィンドウには、ユーザーが持っているアクセス許可と、付与に使用されるアクセス許可セット (権利、既定のセット (システム)、またはカスタマイズ セット (ユーザー定義) のいずれか) が表示されます。</span><span class="sxs-lookup"><span data-stu-id="871a3-113">From each user card, the Effective Permissions window shows which permissions a user has and through which permission set(s) they are granted, either through the entitlement, through a default set (System), or through a customized set (User-Defined).</span></span> <span data-ttu-id="871a3-114">ここでは、ユーザー定義の種類のアクセス許可セットを変更することもできます。</span><span class="sxs-lookup"><span data-stu-id="871a3-114">Here you can also change permission sets of type User-Defined.</span></span>  

> [!NOTE]
> <span data-ttu-id="871a3-115">アクセス許可セットを編集すると、アクセス許可セットが割り当てられている他のユーザーにも変更内容が適用されます。</span><span class="sxs-lookup"><span data-stu-id="871a3-115">When you edit a permission set, the changes will also apply to other users that have the permission set assigned.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="871a3-116">![](media/effective_permission_sets.png "有効なアクセス許可の概要。")</span><span class="sxs-lookup"><span data-stu-id="871a3-116">![](media/effective_permission_sets.png "Overview of effective permissions.")</span></span>

## <a name="resources"></a><span data-ttu-id="871a3-117">リソース</span><span class="sxs-lookup"><span data-stu-id="871a3-117">Resources</span></span>
[<span data-ttu-id="871a3-118">ユーザーとアクセス許可の管理</span><span class="sxs-lookup"><span data-stu-id="871a3-118">Managing Users and Permissions</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/ui-how-users-permissions)

<!--
### Who uses this feature
End users, admins, customizers, developers, IT pros
## Status
### Availability
Cloud, On-premises, Hybrid
### Regional availability
No regional restrictions. All Dynamics 365 Business Central supported markets.
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="871a3-119">フィードバック</span><span class="sxs-lookup"><span data-stu-id="871a3-119">Tell us what you think</span></span>
<span data-ttu-id="871a3-120">Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。</span><span class="sxs-lookup"><span data-stu-id="871a3-120">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="871a3-121">Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="871a3-121">Use the Business Central forum at https://aka.ms/businesscentralideas.</span></span>

