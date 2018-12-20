---
title: "IP アドレスからポータルへのアクセスの制限"
description: "許可される IP 範囲を定義することで、ポータルのアクセスを一部のユーザーのみに制限します"
author: dileeps
manager: rycu
ms.date: 11/20/2018
ms.assetid: 143d1e32-f70e-478c-b8c1-d25b37782653
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: dileeps
ms.reviewer: shjais
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: e35bcf943f7257d057015b8535340025f4e76c30
ms.openlocfilehash: 6b7345e5634d97068be3e91c6a981b8ab2bc132a
ms.contentlocale: ja-jp
ms.lasthandoff: 11/21/2018

---
# <a name="restrict-portal-access-by-ip-address"></a>IP アドレスからポータルへのアクセスの制限

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




セキュリティは、アプリケーションの重要な考慮事項であり、Dynamics 365 ポータルなどの外部に接続するアプリケーションにとってはより重要になります。 このリリースの一部として、お客様がポータルへのアクセスを特定の IP アドレスからのアクセスに制限できる機能を追加します。 これは、自社ポータルへのアクセスを社内ネットワークなどの固定の場所からのアクセスに制限しようとしている組織に役立ちます。 また、不正な構成が原因でデータがリークされることがないようにしたい、現在開発段階のお客様にも役立ちます。

この機能は、ポータルへのアクセスを許可される IP アドレスの一覧を管理者が定義できるようにします。 許可リストには、個々の IP アドレスまたはサブネット マスクによって定義された IP アドレスの範囲を含めることができます。 ポータルに対する要求が任意のユーザーから生成されると、そのユーザーの IP アドレスが許可リストに照らして評価されます。 IP アドレスがリストにない場合、ポータルは HTTP 403 状態コードで応答します。

<!--
### Who uses this feature
This feature is intended for administrators who are managing portals.
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

## <a name="resources"></a>リソース

[IP アドレスからポータルへのアクセスの制限](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/portals/ip-address-restrict)

