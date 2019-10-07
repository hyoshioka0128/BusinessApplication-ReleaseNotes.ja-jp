---
title: トピックの名前変更によってトピック生成を改善する
description: Dynamics 365 Customer Service Insights は、名前変更されたトピックからのシグナルを使用してトピック生成を改善します。
author: tpalmer
ms.date: 07/05/2019
ms.topic: article
ms.service: business-applications
ms.author: tpalmer
ms.reviewer: v-stsau
ms.openlocfilehash: e32f9fd885699a122c6e0f1f60c988fb3bcaff93
ms.sourcegitcommit: 9a214c9c1f0638ff7ce2bfe5320324310d5c14e9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2019
ms.locfileid: "1733284"
---
# <a name="rename-topics-to-improve-topic-generation"></a>トピックの名前変更によってトピック生成を改善する

[!include[customer-service banner](../../../includes/dynamics365-ai-customer-service.md)]

顧客は、トピックの名前を変更することで、AI によって生成されるトピックの品質を継続的に向上できます。 顧客サービス マネージャーはこれまで、AI によって生成されるトピックを読みやすくしたり基になっている問題をわかりやすく説明したりするために名前変更していました。 しかし、名前変更されたトピックのテキストは表示目的でのみ使用され、実際に将来のトピックのクラスタリングの結果に影響を及ぼすことはありませんでした。

今回のリリースには、名前変更されたトピックのテキストを、組織のニーズをよりよく理解できるように AI モデルをトレーニングするための追加のシグナルとして利用することで、AI によって生成されるトピックの品質を向上する新機能が含まれています。 今後は、ユーザーがトピックの名前を変更すると、名前変更されたタイトルが好意的なフィードバックを受けたサポート案件のように扱われます。 そのため、次の更新時には最も関連性の高いサポート案件がそのトピックにグループ化されます。 

トピックの名前変更はトピック一覧ページまたはサポート案件一覧ページで行います。 トピックの名前が変更されると、名前変更されたトピックが次のワークスペース更新時にフィードバック シグナルとして使用されることがダイアログで強調表示されます。

