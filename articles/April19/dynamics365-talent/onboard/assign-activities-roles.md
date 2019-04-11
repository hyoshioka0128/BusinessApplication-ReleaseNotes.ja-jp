---
title: ロールにアクティビティを割り当てることでガイドの管理を効率化する
description: 特定のロールにアクティビティが割り当てられているテンプレートを作成し、ガイド作成時に具体的に指定することができます。
author: manavm77
ms.date: 3/7/2019
ms.topic: article
ms.service: business-applications
ms.author: mamandha
ms.openlocfilehash: 42a51361dade840ec07282b2165d9eedac6d7ee2
ms.sourcegitcommit: 3b77d2603bb0c2166c61729c589e1c2e2296fc9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/15/2019
ms.locfileid: "843669"
---
#  <a name="streamline-guide-administration-by-assigning-activities-to-roles"></a><span data-ttu-id="aabed-103">ロールにアクティビティを割り当てることでガイドの管理を効率化する</span><span class="sxs-lookup"><span data-stu-id="aabed-103">Streamline guide administration by assigning activities to roles</span></span>





[!include[dynamics365-talent banner](../../includes/dynamics365-talent.md)]

<span data-ttu-id="aabed-104">どのようなオンボーディング ガイドにも、新規採用者*によって*行われるのではなく、新規採用者*のために*行われることを意図したアクティビティがあります。</span><span class="sxs-lookup"><span data-stu-id="aabed-104">In any onboarding guide, there exist activities that are meant to be completed *for* a new hire, but not *by* the new hire.</span></span> <span data-ttu-id="aabed-105">そのために担当者の概念が導入されました。</span><span class="sxs-lookup"><span data-stu-id="aabed-105">This is why we introduced a notion of an assignee.</span></span> <span data-ttu-id="aabed-106">アクティビティによっては、オンボーディング担当者、IT 管理者、または採用担当マネージャーが行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="aabed-106">Depending on the activity, it might need to be completed by the onboarding buddy, IT admin, or even the hiring manager.</span></span> <span data-ttu-id="aabed-107">反復可能な動作を作成するために、マネージャーはこれらのアクティビティを特定のロールに割り当てることができる必要がありますが、だれがその新規採用者の担当者になるかが前もってわからない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aabed-107">To build a repeatable motion, managers want to be able to assign these activities to those specific roles but might not know in advance who that might be for a given new hire.</span></span> <span data-ttu-id="aabed-108">担当者のプレースホルダー機能を使用すると、ユーザーは特定のロールにアクティビティが割り当てられているテンプレートを作成し、ガイド作成時に担当者を入力することができます。</span><span class="sxs-lookup"><span data-stu-id="aabed-108">The assignee placeholders feature will allow users to create a template with activities assigned to specific roles that can then be filled at the time of guide creation.</span></span>

<span data-ttu-id="aabed-109">ロールはアドホックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="aabed-109">Roles can be created in an ad-hoc manner.</span></span> <span data-ttu-id="aabed-110">これは、後で個人に割り当てることができるプレースホルダーと考えてください。</span><span class="sxs-lookup"><span data-stu-id="aabed-110">Think of them as placeholders that can later be assigned to an individual.</span></span> <span data-ttu-id="aabed-111">ロールはテンプレートまたはガイドのコンテキスト内に存在します。</span><span class="sxs-lookup"><span data-stu-id="aabed-111">Roles live within the context of a template or guide.</span></span> 

## <a name="creating-a-new-role"></a><span data-ttu-id="aabed-112">新しいロールの作成</span><span class="sxs-lookup"><span data-stu-id="aabed-112">Creating a new role</span></span>

<span data-ttu-id="aabed-113">テンプレート内のアクティビティに移動します。</span><span class="sxs-lookup"><span data-stu-id="aabed-113">Navigate into an activity within a template.</span></span> <span data-ttu-id="aabed-114">担当者のフィールドには 2 つの選択肢があります。</span><span class="sxs-lookup"><span data-stu-id="aabed-114">Under the assignee field, you have two options:</span></span>

- <span data-ttu-id="aabed-115">個人に割り当てる: アクティビティは特定のユーザーに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="aabed-115">Assigning to an individual: Activity is assigned to a specific user.</span></span>
- <span data-ttu-id="aabed-116">ロールに割り当てる: アクティビティはプレースホルダーに割り当てられ、後でプレースホルダーに特定のユーザーが割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="aabed-116">Assigning to a role: Activity is assigned to a placeholder that will later be assigned to a specific user.</span></span>

<span data-ttu-id="aabed-117">**ロール**を選択すると、新しいドロップダウン フィールドが表示されます。</span><span class="sxs-lookup"><span data-stu-id="aabed-117">Selecting **Role** exposes a new drop-down field.</span></span> <span data-ttu-id="aabed-118">このドロップダウン フィールドには、テンプレート/ガイド内の既存のロールがすべて表示されます。</span><span class="sxs-lookup"><span data-stu-id="aabed-118">The drop-down field will expose all of your existing roles within a template/guide.</span></span> <span data-ttu-id="aabed-119">既存のロールがない場合は、**新規追加**オプションを選択して新しいロールを作成できます。</span><span class="sxs-lookup"><span data-stu-id="aabed-119">If you don't have any existing roles, you can choose the **Add new** option to create a new role.</span></span>

<span data-ttu-id="aabed-120">![担当者の新規追加ドロップダウン](../media/add_new_assignee_dropdown.png "担当者の新規追加ドロップダウン")</span><span class="sxs-lookup"><span data-stu-id="aabed-120">![Add new assignee drop-down](../media/add_new_assignee_dropdown.png "Add new assignee drop-down")</span></span>

<span data-ttu-id="aabed-121">新しいロールを作成するには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="aabed-121">To create a new role, do the following:</span></span>

- <span data-ttu-id="aabed-122">ロールの役職を割り当てます (必須)。</span><span class="sxs-lookup"><span data-stu-id="aabed-122">Assign a role title (Required).</span></span>
- <span data-ttu-id="aabed-123">ロールを個人に割り当てます (任意)。</span><span class="sxs-lookup"><span data-stu-id="aabed-123">Assign the role to an individual (Optional).</span></span>

<span data-ttu-id="aabed-124">![担当者ロールの作成](../media/create_assignee_role.png "担当者ロールの作成")</span><span class="sxs-lookup"><span data-stu-id="aabed-124">![Creating an assignee role](../media/create_assignee_role.png "Creating an assignee role")</span></span>

## <a name="assigning-an-existing-role"></a><span data-ttu-id="aabed-125">既存のロールの割り当て</span><span class="sxs-lookup"><span data-stu-id="aabed-125">Assigning an existing role</span></span>

<span data-ttu-id="aabed-126">ロールを作成したら、次のステップとして、そのロールを個人に割り当てます。</span><span class="sxs-lookup"><span data-stu-id="aabed-126">Once you have a role created, the next step is to assign the role to an individual.</span></span> <span data-ttu-id="aabed-127">それにより、ロールに割り当てられていたすべてのタスクもその個人に割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="aabed-127">By doing so, all tasks that were assigned to the role will also be assigned to the individual mentioned above.</span></span>

### <a name="creating-a-guide"></a><span data-ttu-id="aabed-128">ガイドの作成</span><span class="sxs-lookup"><span data-stu-id="aabed-128">Creating a guide</span></span>

<span data-ttu-id="aabed-129">ガイド作成プロセスの一環として、ロールを個人に割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="aabed-129">As part of the guide creation process, you'll have the opportunity to assign the roles to individuals.</span></span> <span data-ttu-id="aabed-130">新規採用者と開始日を選択した後で、このステップを実行します。</span><span class="sxs-lookup"><span data-stu-id="aabed-130">You arrive on this step once a new hire and start date have been selected.</span></span>

### <a name="manage-these-roles"></a><span data-ttu-id="aabed-131">ロールの管理</span><span class="sxs-lookup"><span data-stu-id="aabed-131">Manage these roles</span></span>

<span data-ttu-id="aabed-132">ロールを個人に割り当てるもう 1 つの方法は、**ロールの管理**オプションを使用することです。</span><span class="sxs-lookup"><span data-stu-id="aabed-132">Another way to assign roles to individuals is using the **Manage these roles** option.</span></span>

<span data-ttu-id="aabed-133">![担当者ロールの管理](../media/manage_assignee_roles.png "担当者ロールの管理")</span><span class="sxs-lookup"><span data-stu-id="aabed-133">![Manage assignee roles](../media/manage_assignee_roles.png "Manage assignee roles")</span></span>

> [!WARNING]
> <span data-ttu-id="aabed-134">未割り当てのロールに割り当てられているアクティビティは送信されません。</span><span class="sxs-lookup"><span data-stu-id="aabed-134">Activities assigned to roles that are unassigned will not be sent.</span></span>

<span data-ttu-id="aabed-135">![担当者ロールの管理の完了](../media/manage_roles_completed.png "担当者ロールの管理の完了")</span><span class="sxs-lookup"><span data-stu-id="aabed-135">![Manage assignee roles completed](../media/manage_roles_completed.png "Manage assignee roles completed")</span></span>
