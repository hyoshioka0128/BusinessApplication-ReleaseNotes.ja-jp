---
title: "サードパーティ クライアント接続と監視のための XMLA エンドポイント"
description: 
author: adamw
manager: PaBenj
ms.date: 12/05/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: HaydnR
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 6b6290afd87b7786a135a154041de9416f0dbc7f
ms.openlocfilehash: d2df7d981542e668d164b2e0ecc6ae93e4987b77
ms.contentlocale: ja-jp
ms.lasthandoff: 12/05/2018

---
# <a name="xmla-endpoint-for-third-party-client-connectivity-and-monitoring-public-preview"></a>サードパーティ クライアント接続と監視のための XMLA エンドポイント (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

Power BI サービス内のデータセットに対して XMLA プロトコルがサポートされたことで、お客様はこれまで以上に柔軟な方法で、BI 展開を提供および管理できるようになります。 XMLA は SQL Server Analysis Services や Azure Analysis Services のモデル管理に使用されるのと同じプロトコルなので、さまざまな Microsoft ツールやサードパーティ ツールが有効になります。

XMLA エンドポイントにより、分析、デバッグ、監視のためにサードパーティ アプリケーションから Power BI データセットへの読み取り専用接続のみが許可されます。

将来のリリースでは書き込みアクセスが許可されるので、スクリプトやアプリケーションから、データセットの管理や更新をプログラムによって行えるようになります。 これにより、Power BI データセットのモデル化、ライフサイクル管理、操作のシナリオが可能になります。 Analysis Services の表形式モデリング機能がサポートされます。

