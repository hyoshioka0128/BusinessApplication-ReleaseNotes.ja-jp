---
title: "プロジェクトでの複数通貨の原価価格表の解決"
description: "プロジェクトでの複数通貨の原価価格表の解決"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: bac9c35f91f43541a6597feb3973c9bf40fe1a44
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a>プロジェクトでの複数通貨の原価価格表の解決 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service は、プロジェクトを所有する組織単位の通貨を価格表の通貨と一致させることで、プロジェクトの原価率の価格表を解決します。 価格表に複数通貨の価格がある場合、1 つのマスター価格表に複数通貨の原価率行があり、この価格表がすべてのプロジェクトでグローバルに使用されることが予想されます。 

その状況では、価格表のヘッダーの通貨を使用したプロジェクトの原価価格表の解決が機能しなくなります。 この機能では、プロジェクトの原価価格表の既定の解決を設定するように構成できます。 使用可能なオプションは、プロジェクトのコスト通貨を現在機能している価格表のヘッダーと一致させるか、ヘッダー通貨に関係なく、グローバルに管理されている価格表を使用することです。  



