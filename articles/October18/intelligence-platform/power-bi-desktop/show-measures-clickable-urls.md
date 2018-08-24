---
title: "メジャーをクリック可能な URL として表示する"
description: "メジャーを使用して、レポートから他の Web アドレスに移動するためのハイパーリンクを定義できます。"
author: MI77
manager: kimani
ms.date: 6/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: end user, developer, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 0ae8e309078c1aea0a4b24abe8eb4b253db34b29
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="show-measures-as-clickable-urls"></a>メジャーをクリック可能な URL として表示する

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

エンド ユーザーは、レポート間を移動したり、レポートから他のアプリケーションに移動しながらも、参照しているデータのコンテキストを維持できる、簡単な方法を求めています。 メジャーを使用すれば、移動のための URL を生成したり、レポートやアプリケーション間を簡単に移動するためのハイパーリンクを表示することができます。

DAX メジャーを使用すれば、レポート内でのデータ選択に対応するフィルター付きで URL を返すことができます。 これは、テーブルやマトリックス ビジュアル内でハイパーリンクとして表示できるため、ユーザーの選択に基づいて動的に調整できます。 エンド ユーザーは、このリンクをクリックすることで、目的のレポートを新しいタブで開くことができます。

次に示すのは DAX メジャーの例です。

`Link = “http://app.powerbi.com/Report/GUID/&filter=Table1/Category eq “ & SELECTEDVALUE(Products[Category])`

<!--
### Who uses this feature
This feature is intended for end users, developers, citizen developers, customizers, business analysts, and IT pros. No additional setup is required.
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

