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
# <a name="sharepoint-remind-me"></a><span data-ttu-id="36265-103">SharePoint リマインダー</span><span class="sxs-lookup"><span data-stu-id="36265-103">SharePoint Remind Me</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="36265-104">個人の生産性はチームワークに不可欠です。</span><span class="sxs-lookup"><span data-stu-id="36265-104">Personal productivity is essential to teamwork.</span></span>  <span data-ttu-id="36265-105">SharePoint のリストとライブラリでは、以前から日付を追跡するためのカスタム メタデータ列を定義することができました。</span><span class="sxs-lookup"><span data-stu-id="36265-105">SharePoint lists and libraries have long allowed you to define custom metadata columns to track dates.</span></span>  <span data-ttu-id="36265-106">現在、これらのどの日付にでもリマインダーを設定できる新しい機能がリリースされています。</span><span class="sxs-lookup"><span data-stu-id="36265-106">We now are releasing a new capability that lets you set reminders for any of these dates.</span></span>  <span data-ttu-id="36265-107">SharePoint 内の任意のドキュメントまたはアイテムに設定されている日付の `x` 日前に、個人的なメール アラートを受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="36265-107">You’ll be able to receive a personal email alert `x` days in advance of a date on any document or item in SharePoint.</span></span>

<span data-ttu-id="36265-108">リマインダー フローを作成するには、リストまたはライブラリの現在のビューに少なくとも 1 つの日付/時刻列が必要です。</span><span class="sxs-lookup"><span data-stu-id="36265-108">To create the reminder flow, your list or library should have at least one date/time column in the current view.</span></span> <span data-ttu-id="36265-109">列があれば、**フロー** > **リマインダーを設定する**メニュー項目を選択して、リマインダーを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="36265-109">You’ll then be able to create a reminder by selecting the **Flow** > **Set a reminder** menu item.</span></span>

<span data-ttu-id="36265-110">![フロー メニュー](media/sharepoint_reminder_01.png "フロー メニュー")</span><span class="sxs-lookup"><span data-stu-id="36265-110">![Flow menu](media/sharepoint_reminder_01.png "Flow menu")</span></span>

<span data-ttu-id="36265-111">選択した日付列に基づいて、それより何日前にリマインダーを送信するかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="36265-111">You can enter the number of days in advance for the reminder, based on the selected date column.</span></span>

<span data-ttu-id="36265-112">![リマインダー パネル](media/sharepoint_reminder_02.png "リマインダー パネル")</span><span class="sxs-lookup"><span data-stu-id="36265-112">![Reminder panel](media/sharepoint_reminder_02.png "Reminder panel")</span></span>

<span data-ttu-id="36265-113">選択に基づいて、アイテムまたはドキュメントに対する Microsoft Flow から、選択したデータ列の値の `x` 日前に、メールを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="36265-113">Based on your selection, you’ll get an email from Microsoft Flow for any items or documents `x` days in advance of the selected data column value.</span></span>

<span data-ttu-id="36265-114">![リマインダー メール](media/sharepoint_reminder_03.png "リマインダー メール")</span><span class="sxs-lookup"><span data-stu-id="36265-114">![Reminder email](media/sharepoint_reminder_03.png "Reminder email")</span></span>
 
<span data-ttu-id="36265-115">フローが作成されたら、Microsoft Flow ポータルからそれを編集できます。</span><span class="sxs-lookup"><span data-stu-id="36265-115">Once the flow is created, it can be edited from the Microsoft Flow portal.</span></span> <span data-ttu-id="36265-116">**先行する日数**を変更したり、新しいアクションを追加したりできます。</span><span class="sxs-lookup"><span data-stu-id="36265-116">You can modify **days in advance**, or add additional actions.</span></span> <span data-ttu-id="36265-117">この機能の詳細については、[SharePoint のドキュメント](https://support.office.com/article/set-a-reminder-flow-23c0e172-1fc1-4ac8-a9db-cd0b81d634d8)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="36265-117">Read more about this feature in the [SharePoint documentation](https://support.office.com/article/set-a-reminder-flow-23c0e172-1fc1-4ac8-a9db-cd0b81d634d8).</span></span>
