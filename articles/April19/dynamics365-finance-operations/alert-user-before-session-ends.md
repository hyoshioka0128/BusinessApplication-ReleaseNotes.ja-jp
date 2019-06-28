---
title: 非アクティブのためセッションが終了する前にユーザーに警告する
description: 非アクティブのためにセッションが終了する前にユーザーに警告します
author: jasongre
manager: AnnBe
ms.date: 05/31/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jasongre
audience: admin, end user, IT pro
ms.openlocfilehash: 257d9d01ecbfb83b90df6e1d1233d43725cabfb7
ms.sourcegitcommit: 5abe4a0456393b40e185930060091ca6c6756708
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/04/2019
ms.locfileid: "1617907"
---
# <a name="alert-users-before-sessions-end-due-to-inactivity"></a><span data-ttu-id="d8207-103">非アクティブのためセッションが終了する前にユーザーに警告する</span><span class="sxs-lookup"><span data-stu-id="d8207-103">Alert users before sessions end due to inactivity</span></span>
<span data-ttu-id="d8207-104">Finance and Operations のアイドル タイムアウトの現在の既定値は 60 分です。</span><span class="sxs-lookup"><span data-stu-id="d8207-104">The idle timeout for Finance and Operations is currently defaulted at 60 minutes.</span></span> <span data-ttu-id="d8207-105">その非アクティブ制限をユーザーが超えると、予告なしに、ユーザーはセッションが終了されたことを警告されます。</span><span class="sxs-lookup"><span data-stu-id="d8207-105">After that inactivity limit has been surpassed by a user and with no forewarning, the user is alerted that their session has been terminated.</span></span> 

<span data-ttu-id="d8207-106">より良いエクスペリエンスを提供するため、非アクティブによるセッションの中断が差し迫っていることをユーザーに知らせて、中断が発生しても保存されていない変更が失われないように、非アクティブのためにセッションが終了される 3 分前にユーザーは通知を受け取り、セッション終了前に再接続する機会が提供されます。</span><span class="sxs-lookup"><span data-stu-id="d8207-106">To provide a better experience, to give awareness of an impending session suspension due to inactivity, and to help prevent losing any unsaved changes when this occurs, users will now be notified 3 minutes before their sessions are set to be terminated due to inactivity and given an opportunity to reconnect before the session is ended.</span></span>

<span data-ttu-id="d8207-107">セッションが非アクティブのために終了する数分前に、ユーザーに次のメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="d8207-107">Users will now see the following message a few minutes before their session is set to be terminated due to inactivity.</span></span>

<span data-ttu-id="d8207-108">![非アクティブによるセッション終了の 3 分前に表示されるユーザー アラート](media/cli-idleTimeoutAlert.png  "非アクティブによるセッション終了の 3 分前に表示されるユーザー アラート")</span><span class="sxs-lookup"><span data-stu-id="d8207-108">![User alert displayed 3 minutes before session closes due to inactivity](media/cli-idleTimeoutAlert.png  "User alert displayed 3 minutes before session closes due to inactivity")</span></span>

<span data-ttu-id="d8207-109">タイマーがゼロに達すると、ユーザーのセッションは終了され、次のメッセージがユーザーに表示されます。</span><span class="sxs-lookup"><span data-stu-id="d8207-109">Once the timer has reached zero, the user's session will be terminated and the following message will be shown to the user.</span></span>  

<span data-ttu-id="d8207-110">![非アクティブによるセッション終了後のユーザー アラート](media/cli-sessionEndedAlert.png  "非アクティブによるセッション終了後のユーザー アラート")</span><span class="sxs-lookup"><span data-stu-id="d8207-110">![User alert after a session has ended due to inactivity](media/cli-sessionEndedAlert.png  "User alert after a session has ended due to inactivity")</span></span>




