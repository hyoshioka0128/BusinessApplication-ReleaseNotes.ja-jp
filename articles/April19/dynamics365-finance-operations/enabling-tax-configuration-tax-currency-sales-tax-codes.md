---
title: Global Tax Engine での税通貨と消費税コードによる税コンフィギュレーションの有効化
description: この機能のリリースにより、ユーザーは、ルックアップ テーブルで税コンポーネントの税通貨を定義することができます。 ユーザーは、税設定で消費税コードを保守し、ルックアップ テーブル内の消費税コードに税コンポーネントをマップし、これらの消費税コードの期間およびレポート コードを保守することもできます。
author: yijialuan
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: riluan
ms.openlocfilehash: e25b3e8f5db704e1ecdb41e1d8ea5842e7246427
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225296"
---
#  <a name="global-tax-engine-india---enabling-tax-configuration-with-tax-currency-and-sales-tax-codes"></a>Global Tax Engine (インド) - 税通貨と消費税コードによる税コンフィギュレーションの有効化 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

> [!NOTE]
> 現在、Global Tax Engine はインドでのみ利用可能です。

消費税コードは、Global Tax Engine (GTE) と Dynamics 365 for Finance and Operations を統合するために必須の設定です。 以前は、税コンフィギュレーションを同期するときに GTE によって税コンポーネントと同じ名前の消費税コードが作成され、自動作成の消費税コードには会計通貨が使用されていました。 

世界中で複数の税を登録している企業では、異なる国で使用されている税コンポーネントに対して異なる税通貨を維持する必要があります。 この機能のリリースにより、ユーザーは、税設定で消費税コードを保守し、ルック アップテーブル内の消費税コードに税コンポーネントをマップし、これらの消費税コードの税通貨と決済期間を維持できます。

![税設定レポート](media/Tax-setup-Reporting.jpg "税設定レポート")

税設定では、GTE はマッピングされた消費税コード、税通貨、および決済期間を使用して税取引を転記します。

![税設定レポートで転記された消費税](media/Tax-setup-Reporting-Posted-Sales-tax.jpg "税設定レポートで転記された消費税")


