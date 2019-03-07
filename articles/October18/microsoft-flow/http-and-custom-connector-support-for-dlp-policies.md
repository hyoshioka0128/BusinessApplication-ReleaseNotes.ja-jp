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
# <a name="http-and-custom-connector-support-for-dlp-policies"></a>DLP ポリシーに対する HTTP コネクタとカスタム コネクタのサポート




最近、データ損失防止 (DLP) 機能への投資が行われています。 具体的には、PowerShell またはフロー テンプレートを使用して作成または変更できる DLP ポリシーに、HTTP コネクタおよびカスタム コネクタのサポートが追加されています。

## <a name="data-loss-prevention-policies"></a>データ損失防止ポリシー

データ損失防止ポリシーでは、同じアプリ内またはフロー内で使用できるコネクタを制限することができます。 これらのポリシーは、環境管理者またはテナント管理者のどちらでも設定できます。 各 DLP ポリシーには、ビジネス データと非ビジネス データの 2 つのデータ グループが含まれます。 管理者は、既定のデータ グループを選択して、PowerApps および Microsoft Flow で使用できるようになった新しいコネクタを自動的に含めることができます。

![DLP ポリシー](media/http_custom_dlp_1.png "DLP ポリシー")

## <a name="http-connector-support"></a>HTTP コネクタのサポート

これまでの HTTP アクションとトリガーは、コネクタとは見なされていませんでした。 お客様からのフィードバックにより、これらの項目を DLP の対象となるように分類し直すことで、お客様がよりいっそう柔軟かつきめ細かく環境を制御できるようにしました。

PowerShell コマンドレットまたは特定のフロー テンプレートを使用してポリシーを作成または変更するときに、これらのトリガー/アクションをサポートするオプションを追加しました。 具体的には、次のものを管理できます。

- HTTP (および HTTP + Swagger)
- HTTP webhook
- HTTP 要求

![HTTP アクション](media/http_custom_dlp_2.png "HTTP アクション")

## <a name="custom-connector-support"></a>カスタム コネクタのサポート

また、DLP ポリシーにカスタム コネクタを組み込んで管理する機能も追加されました。 これらのコネクタをポリシーに追加するには PowerShell またはフロー テンプレートを使用する必要があり、その後は管理ポータルで管理できるようになります。

 > [!NOTE]
 > ポリシー エディターに指定されたアイコンと表示名が表示されるのは、テナントの既定の環境に格納されているカスタム コネクタだけです。 他のすべてのカスタム コネクタには、既定のコネクタ アイコンとその内部名が表示されます。

**前提条件**

管理コマンドレットで管理操作を実行するには、次のものが必要です。

- 有料の Microsoft Flow/PowerApps プラン 2 ライセンス、または Microsoft Flow/PowerApps プラン 2 の試用版ライセンス。  [http://web.powerapps.com/trial](http://web.powerapps.com/trial) で、30 日間の試用版ライセンスにサインアップできます。 試用版ライセンスは、有効期限が切れたら更新することができます。
- 別のユーザーのリソースを検索する必要がある場合は、[Office 365 グローバル管理者](https://support.office.com/article/assign-admin-roles-in-office-365-for-business-eac4d046-1afd-4f1a-85fc-8219c79e1504)または [Azure Active Directory グローバル管理者](https://docs.microsoft.com/azure/active-directory/active-directory-assign-admin-roles-azure-portal)のアクセス許可。 (環境管理者は、自分がアクセス許可を持っている環境および環境リソースにのみアクセスできることに注意してください。)
- 最新の [PowerShell コマンドレット](https://docs.microsoft.com/en-us/powerapps/administrator/powerapps-powershell)。

## <a name="implementation"></a>実装

現在、DLP ポリシーに対する HTTP コネクタおよびカスタム コネクタのサポートはフロー テンプレートおよび PowerShell スクリプトとして実装されていますが、将来的には UI でのサポートが計画されています。 これにより、管理者はこの新しい機能を実装するかどうかを選択できます。 カスタム コネクタを追加するには、[こちらのテンプレート](https://flow.microsoft.com/galleries/public/templates/ae9683086770420e902c043e5ed4b363/)を使用してください。 DLP ポリシーに HTTP のサポートを追加するには、[こちらのテンプレート](https://flow.microsoft.com/galleries/public/templates/834eb1366aa54335a5f979014a9e0477/)を使用してください。

 > [!NOTE]
 >  DLP ポリシーをプログラムで変更する場合は、DLP ポリシーが破損しないように十分注意する必要があります。 そのため、以下の予防措置を講じる必要があります。
 > - PowerShell コマンドレットまたは Power プラットフォーム管理コネクタを使用して、既存のポリシーをバックアップします。
 > - 非実稼働テナントでは、次の PowerShell コマンドレットを実行します。 ポリシーが破損すると、他の DLP ポリシーが PowerApps/Flow 管理ポータルに表示されなくなる可能性があります。

## <a name="templates"></a>テンプレート

新しいテンプレートを使用してカスタム コネクタをポリシーに追加するには、ポリシー名、コネクタを追加するグループ、およびコネクタの名前、ID、種類を入力するだけです。 フローを 1 回実行すると、指定したポリシーとグループにカスタム コネクタが追加されます。

新しいテンプレートを使用して既存のポリシーに HTTP コネクタを追加するには、コネクタを追加するポリシーの名前を入力して、フローを実行します。

## <a name="powershell"></a>PowerShell

PowerShell を使用してカスタム コネクタや HTTP コネクタのサポートをポリシーに追加するには、上記のリンクから最新の PowerApps PowerShell スクリプトをダウンロードしてインポートし、コマンドレット "New-AdminDlpPolicy"、"Set-AdminDlpPolicy"、"Add-CustomConnectorToPolicy"、および "Remove-CustomConnectorFromPolicy" を使用してポリシーを変更します。 リファレンスとしては、コマンドレット "Get-Help <cmdlet name> -detailed" を使用できます。

HTTP コネクタを含むように DLP ポリシーを作成または更新するときは、スキーマバージョン `2018-11-01` を使用します。 テンプレートまたは PowerShell を使用して HTTP のサポートが追加されるのは、指定したポリシーだけです。 管理センターで作成した新しいポリシーには、HTTP コネクタは含まれません。

> [!IMPORTANT]
> スキーマ バージョン `2018-11-01` からのダウングレードはサポートされていません。 いったんポリシーに追加した HTTP のサポートを、除去することはできません。 除去しようとすると、その DLP ポリシーが破損する可能性があります。 さらに、HTTP コネクタをサポートするように DLP ポリシーを更新した場合、現在それらの HTTP 機能を使用しているフローが遮断される可能性があります。
