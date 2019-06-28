---
title: 埋め込み IoT の機能強化
description: 2019 年 4 月リリースでの埋め込み IoT の機能強化
author: VivianFSandCFS
ms.author: kyley
ms.reviewer: shellyha
ms.date: 04/09/2019
ms.topic: article
ms.service: business-applications
ms.openlocfilehash: af2631408884554fd6512d0ea05acf33f3c06f39
ms.sourcegitcommit: d099a82effbb96a7079a9d088ee40847fa8d7a7f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/03/2019
ms.locfileid: "1616193"
---
#  <a name="embedded-iot"></a>埋め込み IoT
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]

この記事では、2019 年 4 月リリースでの埋め込み IoT 機能に対する機能強化について説明します。

## <a name="embedded-iot-visualizations"></a>埋め込み IoT の視覚化
IoT アラートを受け取った後は、アラートを診断する必要があります。 Azure IoT からの測定データは、フィールド サービスに関連付けて使用することができます。 

-   アラートを理解するための最初のステップは、資産またはデバイスの現在の状態です。 複数の測定値と調整可能な時間枠を表示する機能を備えた現在のハートビートが表示されます。 これにより、デバイスで何が起こっているのかがリアルタイムでわかります。

-   次のレベルの分析は、資産からの測定値の履歴と傾向を見ることです。 これは、孤立したイベント、またはパターンやトレンドの一部であるイベントがあるかどうかを理解するのに役立ちます。 これには調整可能なタイム スケールが含まれます。 履歴ビューには、資産の最近の修復履歴も含まれます。 これは修復、イベント、傾向との関係を理解するのに役立ちます。


この情報は、次のようなコンテキストでのビジュアル化でプレビューとして利用できるようになります。

| サポート案件または作業指示書 | アラート | 資産 | モバイル |
|----------------------------|-----------------------------|----------------------------|---------------------------------|
| 現在および最近の履歴 | 現在および最近の履歴 | 現在および最近の履歴 | Field Service モバイル アプリ内 |
| 関連する修復履歴 | 似たデバイスでのビュー | 似た資産でのビュー | 現在および最近の履歴 |



## <a name="device-commands"></a>デバイスのコマンド

アラートを診断すると、デバイスにコマンドを送信することでアラートを解決できる場合があります。 Field Service アプリケーションには、デバイスを分類し、そのカテゴリ内のデバイスに送信できるコマンドを定義する機能が含まれています。
コマンドは、Field Service で発行し (手動または自動)、IoT Central によってデバイス上で実行できます。

コマンド ペイロードは、フロー (Microsoft Flow テンプレートに基づく) を使用して Field Service アプリケーションから IoT Central に送信されます。 コマンドを送信した後は、IoT の視覚化を使用して結果を監視できます。

![IoT の視覚化](media/embedded-iot-remotecommands.png "IoT の視覚化")

## <a name="connected-field-service-solution-in-field-service-75-release"></a>Field Service 7.5 リリースの Connected Field Service ソリューション
これまで Field Service バージョン 7.5 を使用していたお客様にとって、Connected Field Service と IoT ソリューションのインストールは Microsoft AppSource での追加ステップでした。 このリリースでは、Connected Field Service と IoT ソリューションを Field Service ソリューションに含めることでこの余分なステップを削除し、お客様が IoT 機能を簡単にオンボードして展開時間を短縮できるようにします。
