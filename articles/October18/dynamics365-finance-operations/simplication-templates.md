---
title: 構成可能なテンプレートによる簡略化
description: 構成可能なテンプレートによる簡略化
author: Annbe
manager: AnnBe
ms.date: 09/06/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: end-user
ms.openlocfilehash: b6a9664c7dee1e53db19eaf6ea09f30073f255ea
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199301"
---
#  <a name="simplification-through-configurable-templates"></a>構成可能なテンプレートによる簡略化 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

お客様は、構成可能な顧客請求書やその他の外部レポート形式を使用することで、時間とコストを節約することができます。 各形式では、事前印刷用紙や普通紙にドキュメントを印刷するためのオプションが提供されます。 構成可能なテンプレートを使用すると、請求書や顧客取引明細書を X++ コードや SQL Server Reporting Services (SSRS) で変更する必要性をなくしたり、最小限に減らすことができます。 2018 年 10 月リリースでは、構成可能なテンプレートは自由書式の請求書でのみ使用できます。 テンプレートは、既存の自由書式請求書から作成することもできますし、新しい請求書の作成時に新規作成することもできます。 今後の更新プログラムでは、顧客請求書、取引明細書、およびその他の外部ドキュメント用に、構成可能なテンプレートの数を増やしていく予定です。

> [!NOTE]
> 2018 年 10 月リリースでは、パブリック レビューに使用した自由書式の請求書テンプレートのサンプル構成と、それがベースとするデータ モデル (顧客請求書モデル) が廃止され、使用できなくなりました。

![構成可能な自由書式の請求書の例](media/configurablefti.png "構成可能な自由書式の請求書の例")
