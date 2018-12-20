---
title: "CFS - IoT Central との統合"
description: "統合の最初のフェーズでは、統合ソリューションの焦点は Flow によるものです。"
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: ce0f2e97-8ded-4530-9c50-fc82ce4a6171
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 564b2b697e5130b078dc81d04f3541919e4f1b8a
ms.openlocfilehash: d91fbd5c75ed887be6180470680719c2c47ad47b
ms.contentlocale: ja-jp
ms.lasthandoff: 11/08/2018

---
#  <a name="cfs---integration-with-iot-central"></a>CFS - IoT Central との統合

[!include[field-service banner](../../../includes/field-service.md)]




統合の最初のフェーズでは、統合ソリューションの焦点は Microsoft Flow によるものです。 これは、IoT Central から Connected Field Service への一方向の通信です。 IoT Central によるリモート デバイスの監視では、IoT Central で定義されているしきい値を測定値が超えると、CFS でアラートを生成するアクションがトリガーされます。 フィールド サービス マネージャーは、顧客の資産やインシデントの種類などの条件に基づいて、これらのアラートをグループ化できます。

> [!div class="mx-imgBorder"]
> ![強化された IoT Central 統合](media/enhanced-iot-central-integration-1.png "強化された IoT Central 統合")
<!-- picture -->


2018 年 10 月のリリースでは、技術者はサイトにいるときに、IoT Central の状態に応じた少数のオプションで、IoT デバイスから分析情報を取得して対応できます。

-   IoT Central のデバイス状態と測定のビジュアルを、Field Service Mobile アプリケーション内に直接埋め込みます。
-   IoT Central からの利用統計情報を Azure BLOB に格納し、埋め込まれた Power BI でデータを視覚化できるようにします。
-   技術者は Field Service Mobile アプリケーションから IoT Central にコマンドを送信できます。

