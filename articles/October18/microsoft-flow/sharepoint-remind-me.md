---
title: SharePoint リマインダー
description: SharePoint のリストまたはライブラリに日付/時刻列がある場合、Microsoft Flow を使用し、未来の日付に基づいてアラートを設定することができます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/06/2019
ms.assetid: 430627f1-ce73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: ed587612381e36218f67074d9e4f508555072e2b
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391082"
---
# <a name="sharepoint-remind-me"></a>SharePoint リマインダー


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

個人の生産性はチームワークに不可欠です。  SharePoint のリストとライブラリでは、以前から日付を追跡するためのカスタム メタデータ列を定義することができました。  現在、これらのどの日付にでもリマインダーを設定できる新しい機能がリリースされています。  SharePoint 内の任意のドキュメントまたはアイテムに設定されている日付の `x` 日前に、個人的なメール アラートを受け取ることができます。

リマインダー フローを作成するには、リストまたはライブラリの現在のビューに少なくとも 1 つの日付/時刻列が必要です。 列があれば、**フロー** > **リマインダーを設定する**メニュー項目を選択して、リマインダーを作成することができます。

![フロー メニュー](media/sharepoint_reminder_01.png "フロー メニュー")

選択した日付列に基づいて、それより何日前にリマインダーを送信するかを指定できます。

![リマインダー パネル](media/sharepoint_reminder_02.png "リマインダー パネル")

選択に基づいて、アイテムまたはドキュメントに対する Microsoft Flow から、選択したデータ列の値の `x` 日前に、メールを受け取ります。

![リマインダー メール](media/sharepoint_reminder_03.png "リマインダー メール")
 
フローが作成されたら、Microsoft Flow ポータルからそれを編集できます。 **先行する日数**を変更したり、新しいアクションを追加したりできます。 この機能の詳細については、[SharePoint のドキュメント](https://support.office.com/article/set-a-reminder-flow-23c0e172-1fc1-4ac8-a9db-cd0b81d634d8)を参照してください。
