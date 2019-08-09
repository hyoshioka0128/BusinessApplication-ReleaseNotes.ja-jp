---
title: フローのプロパティ ページでトリガーの問題を表示する
description: フローのプロパティ ページでトリガーの問題が表示され、フローがトリガーされない理由を簡単に確認できるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 07/01/2019
ms.assetid: 5adfd750-1297-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 4588ec657e8d3714e4651ee5be9a1a153089f675
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1757237"
---
# <a name="see-problems-with-triggers-on-the-flow-properties-page"></a><span data-ttu-id="6b02b-103">フローのプロパティ ページでトリガーの問題を表示する</span><span class="sxs-lookup"><span data-stu-id="6b02b-103">See problems with triggers on the flow properties page</span></span>

<span data-ttu-id="6b02b-104">フローのプロパティ ページには、フローの**実行履歴**が表示されるセクションがあります。</span><span class="sxs-lookup"><span data-stu-id="6b02b-104">The flow properties page has a section that shows you the **Run history** of your flow.</span></span> <span data-ttu-id="6b02b-105">これにより、フロー内のいずれかのアクションに問題があるかどうかを簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="6b02b-105">This makes it easy to see if there’s a problem with any of the actions in your flow.</span></span> <span data-ttu-id="6b02b-106">ただし、フローのトリガーに問題がある場合はフローが実行されません。</span><span class="sxs-lookup"><span data-stu-id="6b02b-106">However, if there is an issue with your flow’s trigger, there won’t be any flow runs.</span></span> <span data-ttu-id="6b02b-107">これにより、フローのエラーに移動することが難しくなります。</span><span class="sxs-lookup"><span data-stu-id="6b02b-107">This makes it difficult to navigate to the flow’s error.</span></span> <span data-ttu-id="6b02b-108">今回、トリガーの失敗が原因でフローが実行されない場合に、フローのプロパティ ページにエラーの詳細へのリンクを含むメッセージが表示される機能が導入されました。</span><span class="sxs-lookup"><span data-stu-id="6b02b-108">We’re now introducing a feature where, if your flow isn’t running because of a trigger failure, a message appears on the flow’s properties page with a link to the error details.</span></span>

![プロパティ ページに表示された警告](media/trigger-failures-01.png)

<span data-ttu-id="6b02b-110">さらに、**実行履歴**ページに移動して画面の右上にあるフィルター メニューから**失敗したチェック**を選択すると、トリガーが失敗したすべての時刻が表示されます。</span><span class="sxs-lookup"><span data-stu-id="6b02b-110">Additionally, you can navigate to the **Run history** page and select **Failed checks** from the filter menu at the top-right of the screen to see all the times that your trigger failed.</span></span> <span data-ttu-id="6b02b-111">今月、前に表示されていたポーリングのトリガーの失敗に加えて、すべての webhook の失敗が追加されました。</span><span class="sxs-lookup"><span data-stu-id="6b02b-111">This month we've added all webhook failures, in addition to the polling trigger failures that appeared before.</span></span>

![[失敗したチェック] フィルター](media/trigger-failures-02.png)


