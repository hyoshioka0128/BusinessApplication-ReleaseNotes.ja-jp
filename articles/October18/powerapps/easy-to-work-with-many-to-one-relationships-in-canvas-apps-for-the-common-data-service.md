---
title: "アプリ用 Common Data Service のキャンバス アプリで多対一リレーションシップを簡単に操作"
description: "手動で参加または検索する必要がありません。 PowerApps は多対一リレーションシップを自動で拡張するため、必要な情報はすぐそこにあります。"
author: gregli-msft
manager: KVivek
ms.date: 9/3/2018
ms.assetid: 421c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Power user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 659e0c32c9f23801ecb6e98a53d60423135cfb5b
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a>アプリ用 Common Data Service のキャンバス アプリで多対一リレーションシップを簡単に操作


[!include[banner](../../includes/banner.md)]

リレーショナル データの活用はほとんどのビジネス アプリケーションで鍵となります。 とはいえ、必要な情報を取り込み、外部キーを組み込み、プロジェクションを制御するクエリを記述するのは面倒な場合があります。

この機能により、キャンバス アプリ開発者はアプリ用 Common Data Service を使うと簡単に行えるようになります。 たとえば、アプリ用 CDS の標準モデルには、取引先担当者エンティティを示す PrimaryContact を参照する取引先企業エンティティがあります。 仮に、ギャラリー コントロール内で主要な取引先担当者の姓を表示する必要があるとします。 この場合に記述する必要があるのは **ThisItem.PrimaryContact.LastName** だけです。 取引先担当者データ ソースを読み込む必要はありません。 PowerApps はアプリを分析して、どの検索が望ましいかを識別し、プロジェクションに必要なフィールドのみを取り込みます。

