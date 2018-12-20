---
title: "Microsoft Flow が Intune をサポート"
description: "Android と iOS 上の Microsoft Flow アプリが、Intune モバイル アプリケーション管理をサポートするようになりました。"
author: KentWeareMSFT
manager: KVivek
ms.date: 11/27/2018
ms.assetid: 3a5abc17-66d9-e811-a987-000d3a1362e3
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: keweare
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: ba1e0a919b45697fd78e54e462b89f37cc8880b5
ms.openlocfilehash: 87c07ffd95c4cd42cb4aae2160d5208301d313fa
ms.contentlocale: ja-jp
ms.lasthandoff: 11/30/2018

---
# <a name="microsoft-flow-supports-intune"></a><span data-ttu-id="e2bcb-103">Microsoft Flow が Intune をサポート</span><span class="sxs-lookup"><span data-stu-id="e2bcb-103">Microsoft Flow supports Intune</span></span>




<span data-ttu-id="e2bcb-104">Apple iOS および Android 向けの新しいバージョンの Microsoft Flow モバイル アプリケーションでは、デバイスを登録しなくても Microsoft アプリケーション管理 (MAM) がサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-104">We have now shipped a new version of the Microsoft Flow mobile application for Apple iOS and Android that supports Microsoft Application Management (MAM) without device enrollment.</span></span> <span data-ttu-id="e2bcb-105">MAM を使用すると、IT 管理者はモバイル データ ポリシーを作成して適用し、企業データを保護することができます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-105">Using MAM allows IT administrators to create and enforce mobile data policies to safeguard company data.</span></span>

## <a name="support-for-intune-is-important"></a><span data-ttu-id="e2bcb-106">Intune のサポートは重要です</span><span class="sxs-lookup"><span data-stu-id="e2bcb-106">Support for Intune is important</span></span>

<span data-ttu-id="e2bcb-107">顧客が Bring Your Own Device (BYOD) 戦略を採用しているかどうか、または従業員に会社の電話を供与しているかどうかに関係なく、顧客はモバイル デバイスに存在するデータの管理を強化することを望んでいます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-107">Whether a customer has adopted a Bring Your Own Device (BYOD) strategy or is providing employees with a corporate phone, they are looking for more control over the data that resides on a mobile device.</span></span> <span data-ttu-id="e2bcb-108">組織では、デバイス上でのデータの移動方法を制限し、従業員が組織を離れるときにデータを確実に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-108">Organizations may want to restrict how data moves on the device and ensure the data is removed, should the employee leave the organization.</span></span>

## <a name="mam-definition"></a><span data-ttu-id="e2bcb-109">MAM の定義</span><span class="sxs-lookup"><span data-stu-id="e2bcb-109">MAM definition</span></span>

<span data-ttu-id="e2bcb-110">MAM を使用すると、テナント内でのアプリケーションの使用方法を管理するポリシーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-110">MAM allows organizations to create policies that govern how an application is used within a tenant.</span></span> <span data-ttu-id="e2bcb-111">これには、アプリ データの暗号化を強制すること、データのコピー/抽出を承認されたアプリケーションのみに制限すること、デバイスで PIN を強制することなどが含まれます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-111">This can include enforcing app data encryption, limiting the ability to copy/extract data to only approved applications or enforcing a PIN on a device.</span></span>

## <a name="your-device-doesnt-need-to-be-enrolled"></a><span data-ttu-id="e2bcb-112">デバイスを登録する必要はありません</span><span class="sxs-lookup"><span data-stu-id="e2bcb-112">Your device doesn't need to be enrolled</span></span>

<span data-ttu-id="e2bcb-113">登録なしの Intune MAM では、ユーザーは Intune MAM に自分のデバイスを登録する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-113">Intune MAM without enrollment does not require a user to enroll their device in Intune MAM.</span></span> <span data-ttu-id="e2bcb-114">ただし、ポリシーを適用するには、ポータル サイト アプリケーションをデバイスにインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-114">However, the Company Portal application needs to be installed on the device to enforce policies.</span></span> <span data-ttu-id="e2bcb-115">MAM が機能するために、会社のポータル アプリケーションにログインする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-115">A user does not need to sign in to the company portal application for MAM to function.</span></span> <span data-ttu-id="e2bcb-116">ポータル サイト アプリケーションは、Apple ストアおよび Android アプリ ストアからダウンロードできます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-116">The Company Portal application can be downloaded from the Apple and Android app stores.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e2bcb-117">![ポータル サイト](./media/microsoft-flow-supports-intune/intune-mam-1-companyportal.png "ポータル サイト")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-117">![Company portal](./media/microsoft-flow-supports-intune/intune-mam-1-companyportal.png "Company portal")</span></span>

## <a name="required-version-of-the-microsoft-flow-mobile-app"></a><span data-ttu-id="e2bcb-118">Microsoft Flow モバイル アプリの必要なバージョン</span><span class="sxs-lookup"><span data-stu-id="e2bcb-118">Required version of the Microsoft Flow mobile app</span></span>

<span data-ttu-id="e2bcb-119">バージョン 2.31.0 のアプリが必要です。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-119">Version 2.31.0 of the app is required.</span></span> <span data-ttu-id="e2bcb-120">iOS 向けの展開は、すべての地域を 100％ カバーするようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-120">Our deployments for iOS have reached 100% coverage to all regions.</span></span> <span data-ttu-id="e2bcb-121">Android の場合は、段階的にロールアウトを行っているので、このバージョンのアプリを使用できるようになるまでしばらくお待ちいただくことがあります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-121">For Android, we are staging our rollout so there may be a delay in this version of the app being available.</span></span>

## <a name="set-up-a-mam-policy"></a><span data-ttu-id="e2bcb-122">MAM ポリシーの設定</span><span class="sxs-lookup"><span data-stu-id="e2bcb-122">Set up a MAM policy</span></span>

<span data-ttu-id="e2bcb-123">管理者は Azure portal でポリシーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-123">An administrator can create policies from the Azure portal.</span></span> <span data-ttu-id="e2bcb-124">この例では、フローのユーザーが Microsoft Flow モバイル アプリケーションを使用するときに PIN を要求するアプリ保護ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-124">For this example, we will create an App protection policy that enforces a flow user to require a pin when using the Microsoft Flow mobile application.</span></span>

- <span data-ttu-id="e2bcb-125">Azure portal から **Intune アプリ保護**に移動します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-125">From the Azure portal, navigate to **Intune App Protection**.</span></span>
- <span data-ttu-id="e2bcb-126">**アプリ保護ポリシー – ポリシーの作成**を選択します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-126">Select **App protection policies – Create Policy**.</span></span>
- <span data-ttu-id="e2bcb-127">表示される**ポリシーの追加**フォームでは、**名前**、**説明**、**プラットフォーム**を入力する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-127">An **Add a policy** form will appear that requires a **Name**, **Description**, and **Platform**.</span></span>

    > [!div class="mx-imgBorder"]
    > <span data-ttu-id="e2bcb-128">![MAM ポリシー](media/microsoft-flow-supports-intune/intune-mam-2-mampolicy.png "MAM ポリシー")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-128">![MAM policy](media/microsoft-flow-supports-intune/intune-mam-2-mampolicy.png "MAM policy")</span></span>

<span data-ttu-id="e2bcb-129">ここで、管理するアプリケーションを選択する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-129">We now need to select an application that we want to manage.</span></span> <span data-ttu-id="e2bcb-130">現在、Microsoft Flow アプリケーションは次のいずれかとして識別できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-130">Currently, the Microsoft Flow application can be identified as one of the following:</span></span>

- <span data-ttu-id="e2bcb-131">**com.microsoft.procsimo (iOS)**</span><span class="sxs-lookup"><span data-stu-id="e2bcb-131">**com.microsoft.procsimo (iOS)**</span></span>
- <span data-ttu-id="e2bcb-132">**com.microsoft.flow (Android)**</span><span class="sxs-lookup"><span data-stu-id="e2bcb-132">**com.microsoft.flow (Android)**</span></span>

> [!NOTE]
> <span data-ttu-id="e2bcb-133">今月の後半には、もっとわかりやすい "Microsoft Flow" の表示名が表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-133">A more friendly “Microsoft Flow” display name will appear in this experience later this month.</span></span></div>

- <span data-ttu-id="e2bcb-134">対象のプラットフォームに基づいて、適切なアプリケーションが選択されていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-134">Ensure the appropriate application is selected based upon the platform that you are targeting.</span></span> <span data-ttu-id="e2bcb-135">アプリの一覧で見つからない場合は、**バンドル ID** フィールドに適切な値を入力して検索します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-135">If you do not find it in the list of apps, search for it by typing the appropriate value into the **Bundle ID** field.</span></span> <span data-ttu-id="e2bcb-136">**追加**ボタンを選択してこのアプリケーションを必要なアプリとして追加し、**選択**を選択してこの構成を完了します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-136">Select the **Add** button to add this application as a required app, and then select **Select** to complete this configuration.</span></span>

    > [!div class="mx-imgBorder"]
    > <span data-ttu-id="e2bcb-137">![必要なアプリの選択](media/microsoft-flow-supports-intune/intune-mam-3-selectrequiredapps.png "必要なアプリの選択")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-137">![Select required apps](media/microsoft-flow-supports-intune/intune-mam-3-selectrequiredapps.png "Select required apps")</span></span>

- <span data-ttu-id="e2bcb-138">ここで、**必要な設定の構成**を選択して、特定のアプリケーション動作を強制するポリシーを定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-138">We now need to define our policy that will impose specific application behaviors by selecting **Configure required settings**.</span></span>
- <span data-ttu-id="e2bcb-139">**必要な設定の構成**エクスペリエンスでは、**データ再配置**、**アクセス要件**、**条件付き起動**の 3 つの領域を構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-139">Within the **Configure required settings** experience, there are three areas that we need to configure: **Data relocation**, **Access requirements**, and **Conditional launch**.</span></span>
- <span data-ttu-id="e2bcb-140">まずは**データ再配置**を設定します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-140">Let’s start with the **Data relocation** settings.</span></span> <span data-ttu-id="e2bcb-141">Microsoft Flow アプリはローカル データの生成に使用されないので、既定のポリシーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-141">Since the Microsoft Flow app is not used to generate local data, we can use the default policy.</span></span>

    > [!NOTE]
    > <span data-ttu-id="e2bcb-142">このポリシーは例として使用されています。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-142">This policy has been used as an example.</span></span> <span data-ttu-id="e2bcb-143">組織のニーズに合わせてそれを変更してください。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-143">Please modify it to meet your organization’s needs.</span></span>

    > [!div class="mx-imgBorder"]
    > <span data-ttu-id="e2bcb-144">![データ再配置]( media/microsoft-flow-supports-intune/intune-mam-4-datarelocation.png "データ再配置")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-144">![Data relocation]( media/microsoft-flow-supports-intune/intune-mam-4-datarelocation.png "Data relocation")</span></span>

- <span data-ttu-id="e2bcb-145">次に、**アクセス要件**に移動し、以下のようなポリシーを確立することができます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-145">Next, we are going to focus on **Access requirements** and can establish a policy like the one below.</span></span> <span data-ttu-id="e2bcb-146">**アクセス要件**の構成が終わったら、**OK** ボタンを選択します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-146">Once we are done configuring our **Access requirements**, we can select the **OK** button.</span></span>

    > [!div class="mx-imgBorder"]
    > <span data-ttu-id="e2bcb-147">![アクセス要件](media/microsoft-flow-supports-intune/intune-mam-5-accessrequirements.png "アクセス要件")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-147">![Access requirements](media/microsoft-flow-supports-intune/intune-mam-5-accessrequirements.png "Access requirements")</span></span>

    > [!NOTE]
    > <span data-ttu-id="e2bcb-148">テストするときは、**(分数) 後にアクセス要件を再確認する** の設定を小さくして、プロンプトを待つ時間を短縮できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-148">When testing, you can lower the **Recheck the access requirements after (minutes)** setting to reduce the amount of time you need to wait for a prompt.</span></span>

- <span data-ttu-id="e2bcb-149">さらに、**条件付き起動**の構成も提供できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-149">In addition, we can also provide a **Conditional launch** configuration.</span></span> <span data-ttu-id="e2bcb-150">この例では、既定のポリシーをそのまま使用し、[OK] を選択してこの操作を完了できます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-150">For the purposes of this example, we will keep the default policy and you can select OK to complete this interaction.</span></span>
- <span data-ttu-id="e2bcb-151">**OK** を選択して**設定**パネルを閉じます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-151">Select **OK** to close the **Settings** panel.</span></span>
- <span data-ttu-id="e2bcb-152">**作成**を選択してポリシーを確定します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-152">Select **Create** to finalize the policy.</span></span>
- <span data-ttu-id="e2bcb-153">ポリシーの一覧に、作成したポリシーが表示されるはずです。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-153">Within our policy list, we should now see the policy that we just created.</span></span>
- <span data-ttu-id="e2bcb-154">ここで、このポリシーを適用する Azure AD グループを割り当てる必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-154">We now need to assign the Azure AD groups for which this policy should apply.</span></span> <span data-ttu-id="e2bcb-155">ポリシーを選択し、**割り当て**を選択することによって、アクセス権を割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-155">We can assign access by selecting our policy and then by selecting **Assignments**.</span></span>

    > [!div class="mx-imgBorder"]
    > <span data-ttu-id="e2bcb-156">![割り当て](media/microsoft-flow-supports-intune/intune-mam-6-assignments.png "割り当て")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-156">![Assignments](media/microsoft-flow-supports-intune/intune-mam-6-assignments.png "Assignments")</span></span>

<span data-ttu-id="e2bcb-157">Azure AD グループを選択するには、**含めるグループを選択**を選択して、適切なグループを選択します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-157">To select an Azure AD group, select **Select groups to include**, and then select the appropriate group.</span></span> <span data-ttu-id="e2bcb-158">この例では、Azure AD グループを作成し、これらのポリシーを適用するメンバーを含めました。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-158">For this example, we have created an Azure AD group and included members for whom we want these policies applied.</span></span>

## <a name="testing"></a><span data-ttu-id="e2bcb-159">テスト</span><span class="sxs-lookup"><span data-stu-id="e2bcb-159">Testing</span></span>

<span data-ttu-id="e2bcb-160">次に、Microsoft Flow モバイル アプリにログインし、次の手順に従って、MAM ポリシーをテストします。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-160">We can now go ahead and test our MAM policy by logging into the Microsoft Flow mobile app and following these instructions:</span></span>

- <span data-ttu-id="e2bcb-161">iOS または Android アプリが最新バージョンであることを確認します (**バージョン 2.31.0** 以降)。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-161">Ensure you have the latest version of the iOS or Android app (**version 2.31.0** or later).</span></span>
- <span data-ttu-id="e2bcb-162">Microsoft Flow モバイル アプリを閉じます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-162">Close the Microsoft Flow mobile app.</span></span>
- <span data-ttu-id="e2bcb-163">Microsoft Flow モバイル アプリを起動します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-163">Launch Microsoft Flow mobile app.</span></span>
- <span data-ttu-id="e2bcb-164">次のメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-164">You should be prompted with the following message:</span></span>

    > [!div class="mx-imgBorder"]
    > <span data-ttu-id="e2bcb-165">![MAM の通知](media/microsoft-flow-supports-intune/intune-mam-7-mamnotice.png "MAM の通知")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-165">![MAM notice](media/microsoft-flow-supports-intune/intune-mam-7-mamnotice.png "MAM notice")</span></span>

<span data-ttu-id="e2bcb-166">ポリシーを作成するときに指紋を許可したので、指紋を提供することができます。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-166">Since we opted to allow fingerprints when we created our policy, we can provide our fingerprint.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e2bcb-167">![MAM の指紋](media/microsoft-flow-supports-intune/intune-mam-8-mamfingerprint.png "MAM の指紋")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-167">![MAM fingerprint](media/microsoft-flow-supports-intune/intune-mam-8-mamfingerprint.png "MAM fingerprint")</span></span>

<span data-ttu-id="e2bcb-168">それ以外の場合は、ユーザーが PIN 番号を設定して提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-168">Otherwise, a user will be required to set up and provide a PIN number.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e2bcb-169">![MAM の PIN](media/microsoft-flow-supports-intune/intune-mam-9-mampin.png "MAM の PIN")</span><span class="sxs-lookup"><span data-stu-id="e2bcb-169">![MAM PIN](media/microsoft-flow-supports-intune/intune-mam-9-mampin.png "MAM PIN")</span></span>

## <a name="conclusion"></a><span data-ttu-id="e2bcb-170">まとめ</span><span class="sxs-lookup"><span data-stu-id="e2bcb-170">Conclusion</span></span>

<span data-ttu-id="e2bcb-171">MAM のサポートは、Intune App Protection を使用してモバイル デバイス上の企業データを管理しているお客様からの主要な要望でした。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-171">MAM support has been a key ask by our customers who are using Intune App Protection to manage company data on mobile devices.</span></span> <span data-ttu-id="e2bcb-172">このサポートを提供することにより、組織が一貫した方法でモバイル データを管理できるようにするという Microsoft のお客様との約束に対応します。</span><span class="sxs-lookup"><span data-stu-id="e2bcb-172">By providing this support, we are aligning with Microsoft customer promises to ensure that organizations have a consistent way to manage their mobile data.</span></span>
