---
title: 価格表の日付の有効期間の検証
description: 検証により、特定の日に対して複数の価格表が有効になっているときに、Project Service の価格の既定設定でエラーが発生するのを回避できます。
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.openlocfilehash: 45118e9b8562da5b617c2ad1e983ffddc466259c
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200116"
---
#   <a name="date-effectivity-validation-on-price-lists"></a>価格表の日付の有効期間の検証

[!include[project-service banner](../../../includes/project-service.md)]





この機能により、特定の日に対して複数の価格表が有効になっているときに、Project Service の価格の既定設定でエラーが発生するのを回避できます。 Project Service では、複数のプロジェクト価格表を見積もり、プロジェクト契約、および組織単位に関連付けることができます。 これは、有効な日付が異なる価格表によって表されるインフレ価格変化を有効にするためです。 

この機能により、システムは価格表のセットアップを検証して、プロジェクトや契約などの 1 つのコンテキストで有効な日付がオーバーラップしていないことを確認します。 また、システムは、見積もりまたは契約での予測に複数の価格期間が含まれる場合、作業に正しく価格を設定できることを確認します。 
