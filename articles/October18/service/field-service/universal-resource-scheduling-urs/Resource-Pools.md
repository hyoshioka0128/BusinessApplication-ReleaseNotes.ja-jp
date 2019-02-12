---
title: リソース プール
description: リソース プールを使用すると、スケジュール担当者は、実際に作業を実行するリソースを決定する必要なしに、汎用プールに作業を予約できます。
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: c2b7fc7a136622d5fa38aae44d97e98c720fed8e
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288106"
---
#  <a name="resource-pools"></a>リソース プール

[!include[field-service banner](../../../includes/field-service.md)]



リソースをリソース プールに関連付けて、スケジュール担当者が、実際に作業を実行するリソースを決定する必要なしに、汎用プールに要件を予約できるようにします。

## <a name="why"></a>理由

- 特定のリソースを強制的に事前予約することを回避し、代わりに "リソース プール" を予約してオーバーコミットを防ぎます。
- 中央のスケジュール担当者には詳細を隠し、ローカル リソース マネージャーに詳細を任すことができます。
- 特定のリソースはまだ指名できず、プールのキャパシティが設定されてリソースは後で指名されます。 すべてのリソースが指名されたかのようにプールのキャパシティを設定できるので、スケジュール担当者は引き続きスケジュールできます (キャパシティ管理)。
- キャンセルを予想して予約超過を意図的に有効にします。

## <a name="what"></a>対象

- リソース プールは、設備のプール、取引先企業/取引先担当者/ユーザーのプール、または備品プールのいずれかです。 プールは、同種のリソースのセットにすることが意図されています。
- プール メンバーは、有効日に永久または一時的にプールに割り当てることができます。
- 必要に応じてプール メンバーから全体的なプール キャパシティを取得します。 </br>

  (リソース プールでのサポートが計画されていないオンサイト要件。)

  ![リソース プールのシナリオ](media/ResourcePools.png "リソース プールのシナリオ")
  
  *リソース プールのシナリオ*
