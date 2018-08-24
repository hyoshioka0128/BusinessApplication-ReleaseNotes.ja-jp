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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: dc40b9862dcb8c4e8eeb12168ab8497bc131c000
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a>プロジェクトでの複数通貨の原価価格表の解決 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service は、プロジェクトを所有する組織単位の通貨を価格表の通貨と一致させることで、プロジェクトの原価率の価格表を解決します。 価格表に複数通貨の価格がある場合、1 つのマスター価格表に複数通貨の原価率行があり、この価格表がすべてのプロジェクトでグローバルに使用されることが予想されます。 

その状況では、価格表のヘッダーの通貨を使用したプロジェクトの原価価格表の解決が機能しなくなります。 この機能では、プロジェクトの原価価格表の既定の解決を設定するように構成できます。 使用可能なオプションは、プロジェクトのコスト通貨を現在機能している価格表のヘッダーと一致させるか、ヘッダー通貨に関係なく、グローバルに管理されている価格表を使用することです。  



