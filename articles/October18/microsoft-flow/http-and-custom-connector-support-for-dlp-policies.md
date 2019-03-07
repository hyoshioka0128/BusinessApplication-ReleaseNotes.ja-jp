---
title: DLP ポリシーに対する HTTP コネクタとカスタム コネクタのサポート
description: PowerShell またはフロー テンプレートがサポートされている DLP ポリシーに、HTTP コネクタおよびカスタム コネクタのサポートが追加されています。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/04/2019
ms.assetid: d582dcff-1621-e911-a975-000d3a1d51a5
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 8b20d087172b66d1e47abfbf4833c7a9fcdef44a
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391318"
---
# <a name="http-and-custom-connector-support-for-dlp-policies"></a><span data-ttu-id="9b906-103">DLP ポリシーに対する HTTP コネクタとカスタム コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="9b906-103">HTTP and custom connector support for DLP policies</span></span>




<span data-ttu-id="9b906-104">最近、データ損失防止 (DLP) 機能への投資が行われています。</span><span class="sxs-lookup"><span data-stu-id="9b906-104">We have made some recent investments into our Data Loss Prevention (DLP) capabilities.</span></span> <span data-ttu-id="9b906-105">具体的には、PowerShell またはフロー テンプレートを使用して作成または変更できる DLP ポリシーに、HTTP コネクタおよびカスタム コネクタのサポートが追加されています。</span><span class="sxs-lookup"><span data-stu-id="9b906-105">More specifically, we are adding support for HTTP and custom connectors to DLP policies that can be created or modified using PowerShell or the given Flow Templates.</span></span>

## <a name="data-loss-prevention-policies"></a><span data-ttu-id="9b906-106">データ損失防止ポリシー</span><span class="sxs-lookup"><span data-stu-id="9b906-106">Data Loss Prevention policies</span></span>

<span data-ttu-id="9b906-107">データ損失防止ポリシーでは、同じアプリ内またはフロー内で使用できるコネクタを制限することができます。</span><span class="sxs-lookup"><span data-stu-id="9b906-107">Data Loss Prevention policies provide an ability to restrict which connectors can be used within the same app or flow.</span></span> <span data-ttu-id="9b906-108">これらのポリシーは、環境管理者またはテナント管理者のどちらでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="9b906-108">These policies can be established by either Environment or Tenant Administrators.</span></span> <span data-ttu-id="9b906-109">各 DLP ポリシーには、ビジネス データと非ビジネス データの 2 つのデータ グループが含まれます。</span><span class="sxs-lookup"><span data-stu-id="9b906-109">Each DLP policy includes two data groups: Business and Non-business data.</span></span> <span data-ttu-id="9b906-110">管理者は、既定のデータ グループを選択して、PowerApps および Microsoft Flow で使用できるようになった新しいコネクタを自動的に含めることができます。</span><span class="sxs-lookup"><span data-stu-id="9b906-110">An administrator can choose a default data group to automatically include any new connectors that become available to PowerApps and Microsoft Flow.</span></span>

<span data-ttu-id="9b906-111">![DLP ポリシー](media/http_custom_dlp_1.png "DLP ポリシー")</span><span class="sxs-lookup"><span data-stu-id="9b906-111">![DLP policies](media/http_custom_dlp_1.png "DLP policies")</span></span>

## <a name="http-connector-support"></a><span data-ttu-id="9b906-112">HTTP コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="9b906-112">HTTP connector support</span></span>

<span data-ttu-id="9b906-113">これまでの HTTP アクションとトリガーは、コネクタとは見なされていませんでした。</span><span class="sxs-lookup"><span data-stu-id="9b906-113">The HTTP actions and triggers up to this point have not been considered connectors.</span></span> <span data-ttu-id="9b906-114">お客様からのフィードバックにより、これらの項目を DLP の対象となるように分類し直すことで、お客様がよりいっそう柔軟かつきめ細かく環境を制御できるようにしました。</span><span class="sxs-lookup"><span data-stu-id="9b906-114">Due to customer feedback, we decided to go ahead and re-categorize those items so they could be subject to DLP to offer customers a greater level of flexibility and control over their environments.</span></span>

<span data-ttu-id="9b906-115">PowerShell コマンドレットまたは特定のフロー テンプレートを使用してポリシーを作成または変更するときに、これらのトリガー/アクションをサポートするオプションを追加しました。</span><span class="sxs-lookup"><span data-stu-id="9b906-115">We have added the option to support these triggers/actions when a policy is created or modified using the PowerShell cmdlets or given Flow Templates.</span></span> <span data-ttu-id="9b906-116">具体的には、次のものを管理できます。</span><span class="sxs-lookup"><span data-stu-id="9b906-116">More specifically, you can now manage:</span></span>

- <span data-ttu-id="9b906-117">HTTP (および HTTP + Swagger)</span><span class="sxs-lookup"><span data-stu-id="9b906-117">HTTP (and HTTP + Swagger)</span></span>
- <span data-ttu-id="9b906-118">HTTP webhook</span><span class="sxs-lookup"><span data-stu-id="9b906-118">HTTP Webhook</span></span>
- <span data-ttu-id="9b906-119">HTTP 要求</span><span class="sxs-lookup"><span data-stu-id="9b906-119">HTTP Request</span></span>

<span data-ttu-id="9b906-120">![HTTP アクション](media/http_custom_dlp_2.png "HTTP アクション")</span><span class="sxs-lookup"><span data-stu-id="9b906-120">![HTTP actions](media/http_custom_dlp_2.png "HTTP actions")</span></span>

## <a name="custom-connector-support"></a><span data-ttu-id="9b906-121">カスタム コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="9b906-121">Custom connector support</span></span>

<span data-ttu-id="9b906-122">また、DLP ポリシーにカスタム コネクタを組み込んで管理する機能も追加されました。</span><span class="sxs-lookup"><span data-stu-id="9b906-122">We have also added the ability to include and manage custom connectors in DLP policies.</span></span> <span data-ttu-id="9b906-123">これらのコネクタをポリシーに追加するには PowerShell またはフロー テンプレートを使用する必要があり、その後は管理ポータルで管理できるようになります。</span><span class="sxs-lookup"><span data-stu-id="9b906-123">These connectors must also be added to a policy via the PowerShell or Flow Template and will then be manageable in the Admin Portal.</span></span>

 > [!NOTE]
 > <span data-ttu-id="9b906-124">ポリシー エディターに指定されたアイコンと表示名が表示されるのは、テナントの既定の環境に格納されているカスタム コネクタだけです。</span><span class="sxs-lookup"><span data-stu-id="9b906-124">Only custom connectors stored in a tenant’s default environment will be displayed with its given icon and display name in the policy editor.</span></span> <span data-ttu-id="9b906-125">他のすべてのカスタム コネクタには、既定のコネクタ アイコンとその内部名が表示されます。</span><span class="sxs-lookup"><span data-stu-id="9b906-125">All other custom connectors will be displayed with the default connector icon and their internal name.</span></span>

<span data-ttu-id="9b906-126">**前提条件**</span><span class="sxs-lookup"><span data-stu-id="9b906-126">**Prerequisites**</span></span>

<span data-ttu-id="9b906-127">管理コマンドレットで管理操作を実行するには、次のものが必要です。</span><span class="sxs-lookup"><span data-stu-id="9b906-127">To perform the administration operations in the admin cmdlets, you’ll need the following:</span></span>

- <span data-ttu-id="9b906-128">有料の Microsoft Flow/PowerApps プラン 2 ライセンス、または Microsoft Flow/PowerApps プラン 2 の試用版ライセンス。</span><span class="sxs-lookup"><span data-stu-id="9b906-128">A paid Microsoft Flow/PowerApps Plan 2 license or a Microsoft Flow/PowerApps Plan 2 trial license.</span></span> <span data-ttu-id="9b906-129"> [http://web.powerapps.com/trial](http://web.powerapps.com/trial) で、30 日間の試用版ライセンスにサインアップできます。</span><span class="sxs-lookup"><span data-stu-id="9b906-129">You can sign up for a 30-day trial license at [http://web.powerapps.com/trial](http://web.powerapps.com/trial).</span></span> <span data-ttu-id="9b906-130">試用版ライセンスは、有効期限が切れたら更新することができます。</span><span class="sxs-lookup"><span data-stu-id="9b906-130">Trial licenses can be renewed if they’ve expired.</span></span>
- <span data-ttu-id="9b906-131">別のユーザーのリソースを検索する必要がある場合は、[Office 365 グローバル管理者](https://support.office.com/article/assign-admin-roles-in-office-365-for-business-eac4d046-1afd-4f1a-85fc-8219c79e1504)または [Azure Active Directory グローバル管理者](https://docs.microsoft.com/azure/active-directory/active-directory-assign-admin-roles-azure-portal)のアクセス許可。</span><span class="sxs-lookup"><span data-stu-id="9b906-131">[Office 365 Global Administrator](https://support.office.com/article/assign-admin-roles-in-office-365-for-business-eac4d046-1afd-4f1a-85fc-8219c79e1504) or [Azure Active Directory Global Administrator](https://docs.microsoft.com/azure/active-directory/active-directory-assign-admin-roles-azure-portal) permissions if you need to search through another user’s resources.</span></span> <span data-ttu-id="9b906-132">(環境管理者は、自分がアクセス許可を持っている環境および環境リソースにのみアクセスできることに注意してください。)</span><span class="sxs-lookup"><span data-stu-id="9b906-132">(Note that Environment Admins only have access to those environments and environment resources for which they have permissions.)</span></span>
- <span data-ttu-id="9b906-133">最新の [PowerShell コマンドレット](https://docs.microsoft.com/en-us/powerapps/administrator/powerapps-powershell)。</span><span class="sxs-lookup"><span data-stu-id="9b906-133">The latest [PowerShell cmdlets](https://docs.microsoft.com/en-us/powerapps/administrator/powerapps-powershell).</span></span>

## <a name="implementation"></a><span data-ttu-id="9b906-134">実装</span><span class="sxs-lookup"><span data-stu-id="9b906-134">Implementation</span></span>

<span data-ttu-id="9b906-135">現在、DLP ポリシーに対する HTTP コネクタおよびカスタム コネクタのサポートはフロー テンプレートおよび PowerShell スクリプトとして実装されていますが、将来的には UI でのサポートが計画されています。</span><span class="sxs-lookup"><span data-stu-id="9b906-135">We are currently implementing HTTP and custom connector support for DLP policies as Flow Templates and PowerShell scripts with plans for UI support in the future.</span></span> <span data-ttu-id="9b906-136">これにより、管理者はこの新しい機能を実装するかどうかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="9b906-136">This provides administrators with an opt-in choice as to whether they would like to implement this new capability.</span></span> <span data-ttu-id="9b906-137">カスタム コネクタを追加するには、[こちらのテンプレート](https://flow.microsoft.com/galleries/public/templates/ae9683086770420e902c043e5ed4b363/)を使用してください。</span><span class="sxs-lookup"><span data-stu-id="9b906-137">To add a custom connector, please use [this template](https://flow.microsoft.com/galleries/public/templates/ae9683086770420e902c043e5ed4b363/).</span></span> <span data-ttu-id="9b906-138">DLP ポリシーに HTTP のサポートを追加するには、[こちらのテンプレート](https://flow.microsoft.com/galleries/public/templates/834eb1366aa54335a5f979014a9e0477/)を使用してください。</span><span class="sxs-lookup"><span data-stu-id="9b906-138">To add HTTP support to a DLP policy, please use [this template](https://flow.microsoft.com/galleries/public/templates/834eb1366aa54335a5f979014a9e0477/).</span></span>

 > [!NOTE]
 >  <span data-ttu-id="9b906-139">DLP ポリシーをプログラムで変更する場合は、DLP ポリシーが破損しないように十分注意する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9b906-139">Modifying a DLP policy programmatically requires careful attention to avoid DLP policy corruption.</span></span> <span data-ttu-id="9b906-140">そのため、以下の予防措置を講じる必要があります。</span><span class="sxs-lookup"><span data-stu-id="9b906-140">As a result, the following precautions should take place:</span></span>
 > - <span data-ttu-id="9b906-141">PowerShell コマンドレットまたは Power プラットフォーム管理コネクタを使用して、既存のポリシーをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="9b906-141">Backing up existing policies using the PowerShell cmdlets or the Power Platform management connector.</span></span>
 > - <span data-ttu-id="9b906-142">非実稼働テナントでは、次の PowerShell コマンドレットを実行します。</span><span class="sxs-lookup"><span data-stu-id="9b906-142">Running the following PowerShell cmdlets in a non-production tenant.</span></span> <span data-ttu-id="9b906-143">ポリシーが破損すると、他の DLP ポリシーが PowerApps/Flow 管理ポータルに表示されなくなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="9b906-143">A corrupt policy might impact other DLP policies from being displayed within the PowerApps/Flow admin portal.</span></span>

## <a name="templates"></a><span data-ttu-id="9b906-144">テンプレート</span><span class="sxs-lookup"><span data-stu-id="9b906-144">Templates</span></span>

<span data-ttu-id="9b906-145">新しいテンプレートを使用してカスタム コネクタをポリシーに追加するには、ポリシー名、コネクタを追加するグループ、およびコネクタの名前、ID、種類を入力するだけです。</span><span class="sxs-lookup"><span data-stu-id="9b906-145">To add a custom connector to a policy via the new template, simply enter the policy name, the group to add the connector to, and the connector’s name, ID, and type.</span></span> <span data-ttu-id="9b906-146">フローを 1 回実行すると、指定したポリシーとグループにカスタム コネクタが追加されます。</span><span class="sxs-lookup"><span data-stu-id="9b906-146">Run the flow once and the custom connector will be added to the policy and group specified.</span></span>

<span data-ttu-id="9b906-147">新しいテンプレートを使用して既存のポリシーに HTTP コネクタを追加するには、コネクタを追加するポリシーの名前を入力して、フローを実行します。</span><span class="sxs-lookup"><span data-stu-id="9b906-147">To add the HTTP connectors to an existing policy via the new template, enter the name of the policy you’d like to add them to and run the flow.</span></span>

## <a name="powershell"></a><span data-ttu-id="9b906-148">PowerShell</span><span class="sxs-lookup"><span data-stu-id="9b906-148">PowerShell</span></span>

<span data-ttu-id="9b906-149">PowerShell を使用してカスタム コネクタや HTTP コネクタのサポートをポリシーに追加するには、上記のリンクから最新の PowerApps PowerShell スクリプトをダウンロードしてインポートし、コマンドレット "New-AdminDlpPolicy"、"Set-AdminDlpPolicy"、"Add-CustomConnectorToPolicy"、および "Remove-CustomConnectorFromPolicy" を使用してポリシーを変更します。</span><span class="sxs-lookup"><span data-stu-id="9b906-149">To add support for custom connectors and/or HTTP connectors to a policy using the PowerShell, download and import the latest PowerApps PowerShell scripts from the link above and use the cmdlets ‘New-AdminDlpPolicy’, ‘Set-AdminDlpPolicy’, ‘Add-CustomConnectorToPolicy’, and ‘Remove-CustomConnectorFromPolicy’ to modify a policy.</span></span> <span data-ttu-id="9b906-150">リファレンスとしては、コマンドレット "Get-Help <cmdlet name> -detailed" を使用できます。</span><span class="sxs-lookup"><span data-stu-id="9b906-150">The cmdlet ‘Get-Help <cmdlet name> -detailed’ can be used as a reference.</span></span>

<span data-ttu-id="9b906-151">HTTP コネクタを含むように DLP ポリシーを作成または更新するときは、スキーマバージョン `2018-11-01` を使用します。</span><span class="sxs-lookup"><span data-stu-id="9b906-151">Use the schema version `2018-11-01` when creating or updating a DLP policy to include HTTP connectors.</span></span> <span data-ttu-id="9b906-152">テンプレートまたは PowerShell を使用して HTTP のサポートが追加されるのは、指定したポリシーだけです。</span><span class="sxs-lookup"><span data-stu-id="9b906-152">Adding HTTP support using the template or PowerShell will only affect the specified policy.</span></span> <span data-ttu-id="9b906-153">管理センターで作成した新しいポリシーには、HTTP コネクタは含まれません。</span><span class="sxs-lookup"><span data-stu-id="9b906-153">New policies created via the Admin Center will not contain the HTTP connectors.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="9b906-154">スキーマ バージョン `2018-11-01` からのダウングレードはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="9b906-154">We do not support downgrading from schema version `2018-11-01`.</span></span> <span data-ttu-id="9b906-155">いったんポリシーに追加した HTTP のサポートを、除去することはできません。</span><span class="sxs-lookup"><span data-stu-id="9b906-155">Once HTTP support is added to a policy, it cannot be taken away.</span></span> <span data-ttu-id="9b906-156">除去しようとすると、その DLP ポリシーが破損する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="9b906-156">Attempting to do so might corrupt that DLP policy.</span></span> <span data-ttu-id="9b906-157">さらに、HTTP コネクタをサポートするように DLP ポリシーを更新した場合、現在それらの HTTP 機能を使用しているフローが遮断される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="9b906-157">Furthermore, if a DLP policy is updated to support HTTP connectors, current flows using these HTTP capabilities might be shut off.</span></span>
