---
title: "Dynamics 365 for Field Service との統合 - 在庫とプロジェクト"
description: "Dynamics 365 for Field Service との統合 - 在庫とプロジェクト"
author: Annbe
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: Annbe
audience: Admin, developer, end-user
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 3f6dc2e145bc06a060ac8b79d7401375b21908ef
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="integration-with-dynamics-365-for-field-service--inventory-and-projects"></a>Dynamics 365 for Field Service との統合 - 在庫とプロジェクト

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



CDS データ統合との統合は、Field Service 活動が Dynamics 365 for Finance and Operations の外部で行われるシナリオをサポートするために提供されます。

このフェーズでは、Finance and Operations からの在庫情報の分析情報をフィールド技術者に提供して、フィールド技術者が在庫レベルの更新と材料の移動を行えるようにすることに重点を置きます。 さらに、販売した製品をインストールまたは保守する企業では、プロジェクトから統合を利用して営業およびサービス プロセス全体をより適切に制御および可視化できるというメリットがあります。

以下のデータを統合する機能です。

-   ウェアハウス情報
-   手持在庫情報
-   在庫移動
-   在庫調整
-   Dynamics 365 for Field Service 作業指示書と接続された Dynamics 365 for Finance and Operations プロジェクト

CDS データ インテグレーターはカスタマイズ可能なプロジェクトを使用してデータを同期します。
標準テンプレートを使用して、カスタム統合プロジェクトを作成できます。このプロジェクトでは、追加の標準およびカスタム フィールドおよびエンティティをマップして統合を調整し、特定のビジネス ニーズを満たすことができます。 フィールド サービスの統合は、既存の見込顧客の現金化機能を基に構築されます。

