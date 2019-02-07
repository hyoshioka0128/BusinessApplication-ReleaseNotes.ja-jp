---
title: CFS - IoT Central との統合
description: 統合の最初のフェーズでは、統合ソリューションの焦点は Flow によるものです。
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: ce0f2e97-8ded-4530-9c50-fc82ce4a6171
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: e8ce65283cef98e7cc78aa121d0bc13520e50fb4
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "287025"
---
#  <a name="cfs---integration-with-iot-central"></a>CFS - IoT Central との統合

[!include[field-service banner](../../../includes/field-service.md)]




統合の最初のフェーズでは、統合ソリューションの焦点は Microsoft Flow によるものです。 これは、IoT Central から Connected Field Service への一方向の通信です。 IoT Central によるリモート デバイスの監視では、IoT Central で定義されているしきい値を測定値が超えると、CFS でアラートを生成するアクションがトリガーされます。 フィールド サービス マネージャーは、顧客の資産やインシデントの種類などの条件に基づいて、これらのアラートをグループ化できます。

![強化された IoT Central 統合](media/enhanced-iot-central-integration-1.png "強化された IoT Central 統合")
<!-- picture -->


2018 年 10 月のリリースでは、技術者はサイトにいるときに、IoT Central の状態に応じた少数のオプションで、IoT デバイスから分析情報を取得して対応できます。

-   IoT Central のデバイス状態と測定のビジュアルを、Field Service モバイル アプリケーション内に直接埋め込みます。
-   IoT Central からの利用統計情報を Azure BLOB に格納し、埋め込まれた Power BI でデータを視覚化できるようにします。
-   技術者は Field Service モバイル アプリケーションから IoT Central にコマンドを送信できます。
