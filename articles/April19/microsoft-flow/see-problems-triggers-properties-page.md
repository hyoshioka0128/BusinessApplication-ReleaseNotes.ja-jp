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
# <a name="see-problems-with-triggers-on-the-flow-properties-page"></a>フローのプロパティ ページでトリガーの問題を表示する

フローのプロパティ ページには、フローの**実行履歴**が表示されるセクションがあります。 これにより、フロー内のいずれかのアクションに問題があるかどうかを簡単に確認できます。 ただし、フローのトリガーに問題がある場合はフローが実行されません。 これにより、フローのエラーに移動することが難しくなります。 今回、トリガーの失敗が原因でフローが実行されない場合に、フローのプロパティ ページにエラーの詳細へのリンクを含むメッセージが表示される機能が導入されました。

![プロパティ ページに表示された警告](media/trigger-failures-01.png)

さらに、**実行履歴**ページに移動して画面の右上にあるフィルター メニューから**失敗したチェック**を選択すると、トリガーが失敗したすべての時刻が表示されます。 今月、前に表示されていたポーリングのトリガーの失敗に加えて、すべての webhook の失敗が追加されました。

![[失敗したチェック] フィルター](media/trigger-failures-02.png)


