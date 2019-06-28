---
title: Common Data Service コネクタで環境を選択する
description: Common Data Service コネクタで環境を選択する
author: aorth
ms.reviewer: anneta
ms.date: 05/17/2019
ms.assetid: dbb2b284-2c65-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: aorth
audience: Power user
ms.openlocfilehash: a0e216b0e830165995b810217a393aa1c2b4802f
ms.sourcegitcommit: 6c1c9ed9328a3b6194ebc4741d0beeef0ef435f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/23/2019
ms.locfileid: "1605798"
---
# <a name="select-an-environment-with-the-common-data-service-connector"></a>Common Data Service コネクタで環境を選択する

[!include[microsoft-powerapps banner](../includes/microsoft-powerapps.md)]

キャンバス アプリの作成者は、Common Data Service で 1 つ以上のエンティティに接続するときに環境を選択できます。 この変更の前は、作成者はキャンバス アプリが展開された環境内のエンティティにだけ接続できました。 現在の環境は、単一の環境で構築されて実行されるアプリ、または開発と運用のために環境を移行されるアプリに役立ちます。 この機能を使用すると、アプリ作成者は特定の環境を選択でき、これはアプリ内の別の既存環境を参照するのに役立ちます。 この場合、アプリが別の環境に移行されても、データ ソースは変化しません。

![環境を変更する](media/cds-change-environment.png "環境を変更する")

![環境を選択する](media/cds-select-environment.png "環境を選択する")
