---
title: "コストのロール価格明細のリソース単位通貨"
description: "リソース時間の原価率をリソース単位の通貨で表現できるようになりました"
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
ms.openlocfilehash: a40e2adff4c8ca26094dddb8bcc9bd6f8fadaacb
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#  <a name="resourcing-unit-currency-on-role-price-lines-for-cost"></a>コストのロール価格明細のリソース単位通貨 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service では、価格表ヘッダーで指定された、価格表あたり 1 つの通貨のみ許可されます。 リソース価格の価格表明細に、価格表ヘッダーで指定されているものと同じ通貨があります。 ただし、国をまたがるすべての事業部に対して一元化された価格を持つ、グローバルに活動しているプロジェクト サービス企業の場合、販売またはコストが発生する通貨ごとに価格表を設定する必要があるデータ中心のセットアップが必要な場合があります。 

この機能を使用すると、Project Service は価格表ヘッダーの通貨とは異なるリソース価格の明細行レベル通貨に対応できます。 価格表ヘッダー上の通貨は、リソース価格明細で既定として使用されます。 このようにして、より一元的な価格設定を望む大規模なグローバル企業は、多くの通貨でリソース価格を指定する 1 つのグローバル価格表を操作できます。 これにより、各リソース単位によって管理される価格が 1 つのマスター価格表としてまとめられるシナリオも可能になります。

依然として価格表あたり 1 つの通貨を使用することもできます。これは、より分権的な価格設定に対応する企業や、リソースの換算価格を追跡する企業にとってメリットがあります。 これは、価格表のリソース価格が価格表ヘッダーの通貨に従うようにカスタマイズできます。

![複数通貨での価格表明細があるコストの価格表](media/Resourcing-unit-currency-on-pricelist.png "複数通貨での価格表明細があるコストの価格表")
<!-- Picture 2 -->

