---
title: 自動フローで CDS for Apps のすべてのアクションを呼び出すことが可能
description: Common Data Service for Apps で使用できるすべてのアクションを、自動フローで呼び出すことができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 177458cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 9aa71c06cfa6746485b8345dc4eb5eac717c5397
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288143"
---
# <a name="automated-flows-can-call-any-cds-for-apps-action"></a>自動フローで CDS for Apps のすべてのアクションを呼び出すことが可能


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

従来の Common Data Service (CDS) for Apps のワークフローと同等のものにする作業の一貫として、CDS for Apps で使用可能なすべてのアクションを自動フローで呼び出すことができるようになりました。 これには、販売注文の遂行から Excel ファイルのエクスポートまでのすべてが含まれます。 アクションは、レコードの作成や更新など、データベースに副作用を与える可能性がある操作を表します。 アクションは、パラメーターを必要としたり、値を返したりする場合があり、特定のレコードと関連付けることができます。

![CDS のアクションを呼び出すフロー](media/PerformActionInCDS-1.png "CDS のアクションを呼び出すフロー")

このようなアクションとしては、**すぐに使える SDK メッセージ**、**プロセスとカスタム アクション**、さらには**カスタム ワークフローア クティビティ**などがあります。
