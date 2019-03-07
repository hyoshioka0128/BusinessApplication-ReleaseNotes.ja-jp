---
title: Common Data Service for Apps のキャンバス アプリで多対一リレーションシップを簡単に操作
description: 手動で参加または検索する必要がありません。 PowerApps は多対一リレーションシップを自動で拡張するため、必要な情報はすぐそこにあります。
author: gregli-msft
ms.reviewer: anneta
ms.date: 02/04/2019
ms.assetid: 421c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: gregli
audience: Power user
ms.openlocfilehash: b683d839ba3c8ceeb575cc9cb3f977cc6d6357ca
ms.sourcegitcommit: b0c22af04369d4d8d0d0a5d67c06d26b3474ceb6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/11/2019
ms.locfileid: "379449"
---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a>Common Data Service for Apps のキャンバス アプリで多対一リレーションシップを簡単に操作




リレーショナル データの活用はほとんどのビジネス アプリケーションで鍵となります。 とはいえ、必要な情報を取り込み、外部キーを組み込み、プロジェクションを制御するクエリを記述するのは面倒な場合があります。

この機能により、キャンバス アプリ開発者が Common Data Service (CDS) for Apps を使うときに、作業が簡単になります。 たとえば、CDS for Apps の標準モデルには、取引先担当者エンティティを示す PrimaryContact を参照する取引先企業エンティティがあります。 仮に、ギャラリー コントロール内で主要な取引先担当者の姓を表示する必要があるとします。 この場合に記述する必要があるのは **ThisItem.PrimaryContact.LastName** だけです。 取引先担当者データ ソースを読み込む必要はありません。 PowerApps はアプリを分析して、どの検索が望ましいかを識別し、プロジェクションに必要なフィールドのみを取り込みます。