---
title: 自動フローであらゆる Common Data Service アクションを呼び出すことが可能
description: Common Data Service で使用できるすべてのアクションを自動フローで呼び出すことができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: fd86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: c4b6807481fba7fb07b337aa8cbbd13af5374bcd
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756778"
---
# <a name="automated-flows-can-call-any-common-data-service-action"></a>自動フローであらゆる Common Data Service アクションを呼び出すことが可能

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

Common Data Service のワークフローと同等のものにする作業の一貫として、Common Data Service で使用可能なすべてのアクションを自動フローで呼び出すことができるようになりました。 これには、販売注文の遂行から Excel ファイルのエクスポートまでのすべてが含まれます。 アクションは、レコードの作成や更新など、データベースに副作用を与える可能性がある操作を表します。 アクションは、パラメーターを必要としたり、値を返したりする場合があり、特定のレコードと関連付けることができます。

![Common Data Service のアクションを呼び出すフロー](media/PerformActionInCDS-1.png "Common Data Service のアクションを呼び出すフロー")

このようなアクションとしては、**すぐに使える SDK メッセージ**、**プロセスとカスタム アクション**、さらには**カスタム ワークフローア クティビティ**などがあります。
