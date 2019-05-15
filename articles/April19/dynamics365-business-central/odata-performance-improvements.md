---
title: OData のパフォーマンスの向上
description: OData のパフォーマンスの向上
author: KennieNP
ms.reviewer: jswymer
ms.date: 03/18/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: 5e27b1884dc9a3f57043e01a239c05b38c5a995d
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224918"
---
# <a name="odata-performance-improvements"></a>OData のパフォーマンスの向上

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

テレメトリにより、Business Central Server の OData スタックが最適に機能していないことがわかりました。 まず第一に、OData の $top クエリ オプションが SQL Server クエリの TOP 句に渡されていなかったため、データベースには $top クエリ オプションのメリットがありませんでした。 第二に、合計の多くの OData クエリでは、Business Central Server の OData スタックで定義されている既定の 1,000 行よりはるかに多くの行が返されることがわかりました。 そのため、既定の行数を 20,000 に変更しました。

## <a name="odata-resource-constraints"></a>OData リソースの制約

また、テレメトリから、少数のテナントが Business Central クラスター上で適正な量を超えるリソースを使用していることもわかりました。 そのため、サーバーでの OData の同時呼び出し数を制限し、使用されるリソースのテナントごとのガバナンスも制御する設定が、Business Central Server の OData スタックに実装されました。

以下の新しいサーバー設定が追加されています。

|  |  |
|--|--|
|ODataServicesOperationTimeout|サーバー インスタンスが単一の OData 要求に割り当てることができる最大時間を指定します。 |
|ODataMaxConnections|サーバー インスタンスでの同時 OData 要求の最大数を指定します (すべてのテナントに対して)。|
|ODataMaxConnectionsPerTenant|テナントごとの同時 OData 要求の最大数を指定します。|

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
