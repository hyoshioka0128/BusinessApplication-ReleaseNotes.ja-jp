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
# <a name="alert-users-before-sessions-end-due-to-inactivity"></a>非アクティブのためセッションが終了する前にユーザーに警告する
Finance and Operations のアイドル タイムアウトの現在の既定値は 60 分です。 その非アクティブ制限をユーザーが超えると、予告なしに、ユーザーはセッションが終了されたことを警告されます。 

より良いエクスペリエンスを提供するため、非アクティブによるセッションの中断が差し迫っていることをユーザーに知らせて、中断が発生しても保存されていない変更が失われないように、非アクティブのためにセッションが終了される 3 分前にユーザーは通知を受け取り、セッション終了前に再接続する機会が提供されます。

セッションが非アクティブのために終了する数分前に、ユーザーに次のメッセージが表示されます。

![非アクティブによるセッション終了の 3 分前に表示されるユーザー アラート](media/cli-idleTimeoutAlert.png  "非アクティブによるセッション終了の 3 分前に表示されるユーザー アラート")

タイマーがゼロに達すると、ユーザーのセッションは終了され、次のメッセージがユーザーに表示されます。  

![非アクティブによるセッション終了後のユーザー アラート](media/cli-sessionEndedAlert.png  "非アクティブによるセッション終了後のユーザー アラート")




