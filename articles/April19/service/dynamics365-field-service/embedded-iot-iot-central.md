---
title: IoT Central による埋め込み IoT の機能強化
description: IoT Central による埋め込み IoT の 2019 年 4 月リリースでの機能強化
author: VivianFSandCFS
ms.author: kyley
ms.reviewer: shellyha
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: e812c65c1c5a749155425a25bc0e0f7f5a6e9cd3
ms.sourcegitcommit: 3c1c87393de3c81395a981f7eea040c5ee62ab45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "285154"
---
#  <a name="embedded-iot-with-iot-central"></a>埋め込み IoT (IoT Central)
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]

この記事では、2019 年 4 月リリースでの埋め込み IoT 機能に対する機能強化について説明します。

## <a name="embedded-iot-visualizations"></a>埋め込み IoT の視覚化
IoT アラートを受け取った後は、アラートを診断する必要があります。 IoT Central からの測定データは、Field Service に関連付けて使用することができます。 

-   アラートを理解するための最初のステップは、資産またはデバイスの現在の状態です。 複数の測定値と調整可能な時間枠を表示する機能を備えた現在のハートビートが表示されます。 これにより、デバイスで何が起こっているのかがリアルタイムでわかります。

-   次のレベルの分析は、資産からの測定値の履歴と傾向を見ることです。 これは、孤立したイベント、またはパターンやトレンドの一部であるイベントがあるかどうかを理解するのに役立ちます。 これには調整可能なタイム スケールが含まれます。 履歴ビューには、資産の最近の修復履歴も含まれます。 これは修復、イベント、傾向との関係を理解するのに役立ちます。

-   分析のもう 1 つの分野は、類似の資産/デバイスとの比較です。 たとえば、同じカテゴリー内の他の資産に対する同じ測定値を見てみます。
    これは、正常な状態をよりよく理解し、関連する資産/デバイスで同様のイベントまたは傾向が発生しているかどうかを判断するのに役立ちます。

この情報は、次のようなコンテキストでの視覚化で利用できます。

| サポート案件または作業指示書 | アラート | 資産 | モバイル |
|----------------------------|-----------------------------|----------------------------|---------------------------------|
| 現在および最近の履歴 | 現在および最近の履歴 | 現在および最近の履歴 | Field Service モバイル アプリ内 |
| 関連する修復履歴 | 似たデバイスでのビュー | 似た資産でのビュー | 現在および最近の履歴 |


![埋め込まれた IoT ビジュアル化](media/embedded-iot-visualization.png "埋め込まれた IoT ビジュアル化")

## <a name="device-commands"></a>デバイスのコマンド

アラートを診断すると、デバイスにコマンドを送信することでアラートを解決できる場合があります。 Field Service アプリケーションには、デバイスを分類し、そのカテゴリ内のデバイスに送信できるコマンドを定義する機能が含まれています。
コマンドは、Field Service で発行し (手動または自動)、IoT Central によってデバイス上で実行できます。

コマンド ペイロードは、フロー (Microsoft Flow テンプレートに基づく) を使用して Field Service アプリケーションから IoT Central に送信されます。 コマンドを送信した後は、IoT の視覚化を使用して結果を監視できます。

![IoT の視覚化](media/embedded-iot-remotecommands.png "IoT の視覚化")

## <a name="device-provisioning"></a>デバイスのプロビジョニング
IoT Central デバイスと Field Service デバイスまたは資産との間のマッピングは、Field Service アカウントへの適切なマッピングなど、埋め込み IoT 機能を使用するために重要です。

デバイス、資産、またはアカウントの同期マッピング機能を、IoT Central 統合の一部として使用できます。
