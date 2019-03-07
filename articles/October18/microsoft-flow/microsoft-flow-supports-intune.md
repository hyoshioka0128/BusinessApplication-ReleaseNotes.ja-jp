---
title: Microsoft Flow が Intune をサポート
description: Android と iOS 上の Microsoft Flow アプリが、Intune モバイル アプリケーション管理をサポートするようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/07/2019
ms.assetid: 3a5abc17-66d9-e811-a987-000d3a1362e3
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 65b53223e2784402b39bde4e30481a19b0338bf6
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391138"
---
# <a name="microsoft-flow-supports-intune"></a>Microsoft Flow が Intune をサポート




Apple iOS および Android 向けの新しいバージョンの Microsoft Flow モバイル アプリケーションでは、デバイスを登録しなくても Microsoft Application Management (MAM) がサポートされるようになりました。 MAM を使用すると、IT 管理者はモバイル データ ポリシーを作成して適用し、企業データを保護することができます。

## <a name="support-for-intune-is-important"></a>Intune のサポートは重要です

顧客が Bring Your Own Device (BYOD) 戦略を採用しているかどうか、または従業員に会社の電話を供与しているかどうかに関係なく、顧客はモバイル デバイスに存在するデータの管理を強化することを望んでいます。 組織では、デバイス上でのデータの移動方法を制限し、従業員が組織を離れるときにデータを確実に削除することができます。

## <a name="mam-definition"></a>MAM の定義

MAM を使用すると、テナント内でのアプリケーションの使用方法を管理するポリシーを作成できます。 これには、アプリ データの暗号化を強制すること、データのコピー/抽出を承認されたアプリケーションのみに制限すること、デバイスで PIN を強制することなどが含まれます。

## <a name="your-device-doesnt-need-to-be-enrolled"></a>デバイスを登録する必要はありません

登録なしの Intune MAM では、ユーザーは Intune MAM に自分のデバイスを登録する必要はありません。 ただし、ポリシーを適用するには、ポータル サイト アプリケーションをデバイスにインストールする必要があります。 MAM が機能するために、ポータル サイト アプリケーションにログインする必要はありません。 ポータル サイト アプリケーションは、Apple ストアおよび Android アプリ ストアからダウンロードできます。

![ポータル サイト](media/microsoft-flow-supports-intune/intune-mam-1-companyportal.png "ポータル サイト")

## <a name="required-version-of-the-microsoft-flow-mobile-app"></a>Microsoft Flow モバイル アプリの必要なバージョン

バージョン 2.31.0 のアプリが必要です。 iOS 向けの展開は、すべての地域を 100％ カバーするようになりました。 Android の場合は、段階的にロールアウトを行っているので、このバージョンのアプリを使用できるようになるまでしばらくお待ちいただくことがあります。

## <a name="set-up-a-mam-policy"></a>MAM ポリシーの設定

管理者は Azure portal でポリシーを作成できます。 この例では、フローのユーザーが Microsoft Flow モバイル アプリケーションを使用するときに PIN を要求するアプリ保護ポリシーを作成します。

- Azure portal から **Intune アプリ保護**に移動します。
- **アプリ保護ポリシー – ポリシーの作成**を選択します。
- 表示される**ポリシーの追加**フォームでは、**名前**、**説明**、**プラットフォーム**を入力する必要があります。

    ![MAM ポリシー](media/microsoft-flow-supports-intune/intune-mam-2-mampolicy.png "MAM ポリシー")

ここで、管理するアプリケーションを選択する必要があります。 現在、Microsoft Flow アプリケーションは次のいずれかとして識別できます。

- **com.microsoft.procsimo (iOS)**
- **com.microsoft.flow (Android)**

> [!NOTE]
> 今月の後半には、もっとわかりやすい "Microsoft Flow" の表示名が表示されるようになります。</div>

- 対象のプラットフォームに基づいて、適切なアプリケーションが選択されていることを確認します。 アプリの一覧で見つからない場合は、**バンドル ID** フィールドに適切な値を入力して検索します。 **追加**ボタンを選択してこのアプリケーションを必要なアプリとして追加し、**選択**を選択してこの構成を完了します。

    ![必要なアプリの選択](media/microsoft-flow-supports-intune/intune-mam-3-selectrequiredapps.png "必要なアプリの選択")

- ここで、**必要な設定の構成**を選択して、特定のアプリケーション動作を強制するポリシーを定義する必要があります。
- **必要な設定の構成**エクスペリエンスでは、**データ再配置**、**アクセス要件**、**条件付き起動**の 3 つの領域を構成する必要があります。 まずは**データ再配置**を設定します。 Microsoft Flow アプリはローカル データの生成に使用されないので、既定のポリシーを使用できます。

    > [!NOTE]
    > このポリシーは例として使用されています。 組織のニーズに合わせてそれを変更してください。

    ![データ再配置](media/microsoft-flow-supports-intune/intune-mam-4-datarelocation.png "データ再配置")

- 次に、**アクセス要件**に移動し、以下のようなポリシーを確立することができます。 **アクセス要件**の構成が終わったら、**OK** ボタンを選択します。

    ![アクセス要件](media/microsoft-flow-supports-intune/intune-mam-5-accessrequirements.png "アクセス要件")

    > [!NOTE]
    > テストするときは、**(分数) 後にアクセス要件を再確認する** の設定を小さくして、プロンプトを待つ時間を短縮できます。

- さらに、**条件付き起動**の構成も提供できます。 この例では、既定のポリシーをそのまま使用し、[OK] を選択してこの操作を完了できます。
- **OK** を選択して**設定**パネルを閉じます。
- **作成**を選択してポリシーを確定します。
- ポリシーの一覧に、作成したポリシーが表示されるはずです。
- ここで、このポリシーを適用する Azure AD グループを割り当てる必要があります。 ポリシーを選択し、**割り当て**を選択することによって、アクセス権を割り当てることができます。

    ![割り当て](media/microsoft-flow-supports-intune/intune-mam-6-assignments.png "割り当て")

Azure AD グループを選択するには、**含めるグループを選択**を選択して、適切なグループを選択します。 この例では、Azure AD グループを作成し、これらのポリシーを適用するメンバーを含めました。

## <a name="testing"></a>テスト

次に Microsoft Flow モバイル アプリにサインインし、次の手順に従って MAM ポリシーをテストします。

- iOS または Android アプリが最新バージョン (**バージョン 2.31.0** 以降) であることを確認します。
- Microsoft Flow モバイル アプリを閉じます。
- Microsoft Flow モバイル アプリを起動します。
- 次のメッセージが表示されます。

    ![MAM の通知](media/microsoft-flow-supports-intune/intune-mam-7-mamnotice.png "MAM の通知")

ポリシーを作成するときに指紋を許可したので、指紋を提供することができます。

![MAM の指紋](media/microsoft-flow-supports-intune/intune-mam-8-mamfingerprint.png "MAM の指紋")

それ以外の場合は、ユーザーが PIN 番号を設定して提供する必要があります。

![MAM の PIN](media/microsoft-flow-supports-intune/intune-mam-9-mampin.png "MAM の PIN")

## <a name="conclusion"></a>まとめ

MAM のサポートは、Intune App Protection を使用してモバイル デバイス上の企業データを管理しているお客様からの主要な要望でした。 このサポートを提供することにより、組織が一貫した方法でモバイル データを管理できるようにするという Microsoft のお客様との約束に対応します。