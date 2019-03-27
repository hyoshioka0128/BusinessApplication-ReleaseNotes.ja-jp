---
title: 統合のためのビジネス イベント
description: 統合のためのビジネス イベント
author: Sunil-Garg
ms.date: 02/12/2019
ms.topic: article
ms.service: business-applications
ms.author: Sunil-Garg
ms.openlocfilehash: ea516d21c62d80a8bdaa54a69ae3c8c8235df63c
ms.sourcegitcommit: 12ea920fd9f3d36860a9d7330d0b0037ff2f7ea5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/12/2019
ms.locfileid: "380216"
---
#  <a name="business-events-for-integrations"></a>統合のためのビジネス イベント  
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





イベントは Finance and Operations 内に存在しますが、それらの使用は以前は Finance and Operations 内に限定されていました。 この新しい機能によって提供されるフレームワークでは、業務プロセスの実行時に Finance and Operations 内の業務プロセスでビジネス イベントをキャプチャし、そのイベントを外部のシステムまたはアプリケーションに送信できます。

これにより、たとえば、発注書の承認によって仕入先組織でのフルフィルメントをすぐにトリガーしたり、損傷部品の受領で仕入先のクレーム プロセスをリアルタイムでトリガーしたりできるようになります。 これらのイベントは業務プロセスのコンテキストで発生するため、これらのイベントは*ビジネス イベント*と呼ばれ、*業務プロセスの統合*を可能にします。

外部の業務プロセスは、Finance and Operations で特定のビジネス イベントをサブスクライブし、発生したときに通知を受けります。 ビジネス イベントは、Finance and Operations コネクタで "トリガ" として使用することもできます。

含まれる予定の機能は次のとおりです。

- ビジネス イベント管理者エクスペリエンス: 必要に応じてビジネス イベントを有効または無効にします
- アプリケーション ビジネス イベント
- ワークフロー ビジネス イベント
- ビジネス イベント フレームワーク: パートナーおよびお客様が定義するイベント
- イベント グリッドに対するエンドポイントのサポート: 統合シナリオ用
- "ビジネス イベント発生時" 用のコネクタ トリガー: Microsoft Flow および LogicApp で使用します。 ユーザーは Finance and Operations で利用可能な特定のビジネス イベントをサブスクライブできるようになります。
