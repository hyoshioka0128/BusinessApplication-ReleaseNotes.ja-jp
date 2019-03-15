---
title: Global Tax Engine でのルックアップ数の削減による税コンフィギュレーションの使いやすさの向上
description: Global Tax Engine のこの機能により、税コンフィギュレーションの使いやすさが向上します。
author: yijialuan
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: riluan
ms.openlocfilehash: 5c17d560216d8de41ced03211bc06db742e9f07d
ms.sourcegitcommit: 365db01dde7ccb5c763d209fedbc715d128b18a6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2019
ms.locfileid: "376829"
---
#  <a name="global-tax-engine-india---improving-tax-configuration-usability-with-reduced-number-of-lookups"></a>Global Tax Engine (インド) - ルックアップ数の削減による税コンフィギュレーションの使いやすさの向上
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

> [!NOTE]
> 現在、GTE はインドでのみ利用可能です。

Global Tax Engine (GTE) で税を構成しているときに、ユーザーは、複数のテーブルを定義して、税率、非控除割合、税コンポーネント、税期間などを検索できます。 実際のビジネスの実践では、ユーザーはルックアップ テーブルを組み合わせてルックアップ テーブル数を減らすことを希望します。たとえば、原産国/地域、消費国/地域、製品タイプなどのデータ モデル プロパティによって、複数の場所で再利用できる税トランザクションの性質が決まります。 このリリースでは、ユーザーは行レベルで文字列タイプのメジャーを追加できます。これはルックアップにすることができます。

![税設定イベント タイプ](media/Tax-setup-tax-event-type.jpg "税設定イベント タイプ")

このメジャーを、レポート作成やレートなどの他のルックアップでさらに使用できます。 

![レポート作成の税設定イベント タイプ](media/Tax-setup-tax-event-type-reporting.jpg "レポート作成の税設定イベント タイプ")

![レートの税設定イベント タイプ](media/Tax-setup-tax-event-type-rate.jpg "レートの税設定イベント タイプ")

ユーザーが維持する必要のあるルックアップの数が大幅に減り、税コンフィギュレーションの使いやすさが向上します。 この行レベルの文字列型の措置は、税務署類ユーザー インターフェイスにも表示されます。 


