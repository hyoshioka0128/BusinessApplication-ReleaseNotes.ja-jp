---
title: Microsoft Flow による SharePoint ページの承認のカスタマイズ
description: SharePoint ライブラリのページの承認フローを作成して、すべての新規ページと更新されたページのレビュー プロセスを追加します。
author: Mhade
ms.reviewer: deonhe
ms.date: 01/09/2019
ms.assetid: fbc151eb-4a98-e811-a969-000d3a1378f6
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mhade
audience: Power user
ms.openlocfilehash: 92cf4574c0576d374ae3c1486b43fe77f1d9c931
ms.sourcegitcommit: 851bbbbeaac02e33829dfbf5f6f8e4055acf0822
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "203565"
---
# <a name="customize-sharepoint-page-approvals-with-flow"></a>Flow による SharePoint ページの承認のカスタマイズ




最近の SharePointサイトでは、所有者はサイトの標準公開プロセスを向上させるためにページの承認を構成できます。 ページの承認フローを追加した後、新規ページと更新されたページは直接公開されなくなります。 代わりに、ページに変更が加えられるたびに、そのページは保留中モードになり、承認のために送信されます。 その結果、指定された承認者の新しい承認項目が作成されます。 承認者は変更をレビューし、埋め込み Microsoft Flow エクスペリエンスを使用して SharePoint で直接承認するか、承認センターを介して応答します。 応答は電話で、または電子メールから直接行われます。 承認者が応答すると、コンテンツ作成者に通知され、変更が公開され、ページが更新されます。

[ページの承認フロー](https://support.office.com/article/page-approval-flow-a8b2e689-d4a1-4639-8028-333c0ece30d9)の動作と[ページの承認を構成する](https://support.office.com/article/configure-page-approval-14ce6976-a0a7-427b-b4ab-d28d344a5222)方法の詳細をお読みください。

## <a name="configure-page-approval"></a>ページの承認を構成する

サイト所有者は、ページのライブラリの**フロー** メニューからページの承認フローを構成します。

![ページの承認フローを作成する](media/sharepoint-page-approvals-1.png "ページの承認フローを作成する")

## <a name="submitting-a-page-for-approval"></a>承認のためのページの送信

ページの承認が構成されたら、作成者は承認のためにそれらを送信します。 [公開] ボタンが [承認のために送信] ボタンに変わります。

![承認のためのページの送信](media/sharepoint-page-approvals-2.png "承認のためのページの送信")

ページは承認後に公開されます。 却下された場合、ページはドラフト ステータスに戻ります。

## <a name="approving-a-page"></a>ページの承認

承認者は、ページの承認要求に関する電子メールを受け取ります。 電子メールでページを直接承認する (アクション可能なメッセージをサポートする電子メール クライアントの場合) か、電子メールからページを開いてレビューしてから SharePoint でページを承認することができます。

![ページの承認](media/sharepoint-page-approvals-3.png "ページの承認")

承認フローが完了すると、変更はサイトのすべての閲覧者に表示されるようになります。

## <a name="customizing-the-page-approval-flow"></a>ページの承認フローのカスタマイズ

ページの承認はバックグラウンドで Microsoft Flow を使用するので、サイト所有者はページの承認フローを利用してフロー内のカスタム ビジネス プロセス アイテムを変更および追加することができます。 フローを作成した後、サイト所有者はページ ライブラリで**フロー** > **フローの表示**を選択してページの承認フローを検索できます。

たとえば、既定の承認タイプは**だれでも承認できる**ように設定されています。 サイト所有者はフローを変更し、必要に応じて承認タイプを**全員の承認が必要**なように変更できます。

![承認タイプの変更](media/sharepoint-page-approvals-4.png "承認タイプの変更")

## <a name="known-issues"></a>既知の問題

1. ページが別のユーザーによってチェックアウトされていて、ユーザー (この場合は作成者) が承認のためにページを送信した場合、そのページは通知せずに承認を続行します。 フローが実行され、ページの公開中にエラーが発生したことを示す電子メールが作成者に送信されます。 
2. サイト ページ ライブラリに対して有効になっているメジャー バージョンのみがある場合は、承認の送信結果として次のエラーが発生します: `Could not complete that action: The type of data at position 0 is different than the one expected.`
3. 英国地域でのみ、2018 年 3 月より後に作成されたテナントでは、この機能がサポートされません。 これは 9 月末までに解決する予定です。 詳しくは、[このスレッドをご覧ください](https://techcommunity.microsoft.com/t5/SharePoint/Announcing-SharePoint-page-approvals/m-p/225587/highlight/true#M20376)。
