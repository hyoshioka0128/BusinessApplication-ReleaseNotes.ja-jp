---
title: "構成の移行"
description: "環境の間で Dynamics 365 Portal の構成を移行します"
author: sandhangitmsft
manager: ramalingamkrishnan
ms.date: 7/22/2018
ms.assetid: f454a2d3-c047-4a57-8a9f-7ddf38781971
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sandhan
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 7e0954b5f4a23af4780aa48b1b609c68fc7ae6e3
ms.openlocfilehash: 589c266f81868780f660f9c174dc5538728174ef
ms.contentlocale: ja-jp
ms.lasthandoff: 09/20/2018

---
# <a name="configuration-migration"></a>構成の移行

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]

ポータルの開発には、ポータルのエンド ユーザーに望ましいエクスペリエンスを実現するための複数の構成とカスタマイズが含まれます。 複数の環境でポータルの構成を管理するために必要な時間と作業を軽減するため、[Configuration Migration SDK ツール](https://technet.microsoft.com/library/dn647421.aspx)で動作する構成移行用のスキーマが公開されています。

ポータル カスタマイズ担当者はさまざまな方法を使用し、その 1 つとして、Configuration Migration SDK ツールがさまざまな環境 (一般的には開発、テスト、運用) に構成を移動するためのスキーマ ファイルを一から作成することが含まれます。 スキーマを一から作成すると時間がかかり、そのために一部のデータしか移行できないことがあり、エラーも発生しやすくなります。

Configuration Migration SDK ツールのすべての機能をこのスキーマで使用して、ポータルの構成を管理できます。

 - **スキーマの作成**: ツールで用意されている標準的な方法を使用して、実装に合わせてスキーマを調整することができます。 スキーマ ファイルをツールに読み込んで変更し、構成移行のニーズに適するようにエンティティや属性などを追加、削除、変更できます。
 - **データのエクスポート**: スキーマ ファイルを使用して環境から .zip ファイルにデータをエクスポートし、バックアップ、ソース管理、またはターゲット環境へのインポートに使用します。
 - **データのインポート**: エクスポートされたデータを使用して、ターゲット環境にインポートします。

ポータル構成を移行する方法については、詳細なドキュメント「[Dynamics 365 Portal の構成を移行する](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/migrate-portal-configuration)」を参照してください

<!--
### Who uses this feature
This feature is intended for administrators and customizers who need to migrate their portal configuration between environments.
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
Global
-->

## <a name="wed-like-to-thank"></a>謝辞

優先順位付けに役立つ投票とコメントを[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c)にお送りいただき、ありがとうございました。


