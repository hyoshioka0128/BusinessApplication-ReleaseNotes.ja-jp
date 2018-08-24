---
title: "価格表の日付の有効期間の検証"
description: "検証により、特定の日に対して複数の価格表が有効になっているときに、Project Service の価格の既定設定でエラーが発生するのを回避できます。"
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
ms.openlocfilehash: ebe319f383c161cea41fe8d483206b72f9244de7
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
#   <a name="date-effectivity-validation-on-price-lists"></a>価格表の日付の有効期間の検証

[!include[project-service banner](../../../includes/project-service.md)]





この機能により、特定の日に対して複数の価格表が有効になっているときに、Project Service の価格の既定設定でエラーが発生するのを回避できます。 Project Service では、複数のプロジェクト価格表を見積もり、プロジェクト契約、および組織単位に関連付けることができます。 これは、有効な日付が異なる価格表によって表されるインフレ価格変化を有効にするためです。 

この機能により、システムは価格表のセットアップを検証して、プロジェクトや契約などの 1 つのコンテキストで有効な日付がオーバーラップしていないことを確認します。 また、システムは、見積もりまたは契約での予測に複数の価格期間が含まれる場合、作業に正しく価格を設定できることを確認します。 

