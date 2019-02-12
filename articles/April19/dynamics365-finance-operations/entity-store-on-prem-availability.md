---
title: オンプレミス展開でのエンティティ格納のサポート
description: Dynamics 365 for Finance and Operations オンプレミスで利用可能なエンティティ格納
author: MilindaV2
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: MilindaV2
ms.openlocfilehash: 958aff6631f41ce990b21cc2a12ab0643e0e2421
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210579"
---
#  <a name="entity-store-support-for-on-premises-deployments"></a>オンプレミス展開でのエンティティ格納のサポート
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


[エンティティ格納](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/power-bi-integration-entity-store)は、管理者またはパワー ユーザーのステージで、レポート作成および分析のために測定値を専用のデータ ストアに集約できる運用データ ストアです。 お客様は、Microsoft Power BI DirectQuery のモデルをエンティティ格納と共に使用して、大量のデータに対する大容量でほぼリアルタイムの分析レポートを作成できます。 トランザクション ストアからのデータはリアルタイムで同期され、エンティティ格納で利用できるようになります。

エンティティ格納は、バージョン 10.0 以降のすべてのお客様が、オンプレミス用に定義されてほぼリアルタイムで同期されるすべての既定の集計で利用できます。 オンプレミスのお客様は、エンティティ格納に対して作成された既成のレポートを使用し、自分の Power BI サブスクリプションに展開することができます。 ただし、オンプレミス展開には分析ワークスペースは含まれません。 
