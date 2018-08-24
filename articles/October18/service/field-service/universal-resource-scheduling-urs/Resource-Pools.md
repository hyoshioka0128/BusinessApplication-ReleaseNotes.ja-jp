---
title: "リソース プール"
description: "リソース プールを使用すると、スケジュール担当者は、実際に作業を実行するリソースを決定する必要なしに、汎用プールに作業を予約できます。"
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 8450e5278a3b84e410ad73c3635ff94a20d32812
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

#  <a name="resource-pools"></a>リソース プール

[!include[field-service banner](../../../includes/field-service.md)]



リソースをリソース プールに関連付けて、スケジュール担当者が、実際に作業を実行するリソースを決定する必要なしに、汎用プールに要件を予約できるようにします。

# <a name="why"></a>理由

- 特定のリソースを強制的に事前予約することを回避し、代わりに "リソース プール" を予約してオーバーコミットを防ぎます。
- 中央のスケジュール担当者には詳細を隠し、ローカル リソース マネージャーに詳細を任すことができます。
- 特定のリソースはまだ指名できず、プールのキャパシティが設定されてリソースは後で指名されます。 すべてのリソースが指名されたかのようにプールのキャパシティを設定できるので、スケジュール担当者は引き続きスケジュールできます (キャパシティ管理)。
- キャンセルを予想して予約超過を意図的に有効にします。

# <a name="what"></a>対象

- リソース プールは、設備のプール、取引先企業/取引先担当者/ユーザーのプール、または備品プールのいずれかです。 プールは、同種のリソースのセットにすることが意図されています。
- プール メンバーは、有効日に永久または一時的にプールに割り当てることができます。
- 必要に応じてプール メンバーから全体的なプール キャパシティを取得します。

> *リソース プールでのサポートが計画されていないオンサイト要件*

> [!div class="mx-imgBorder"]
> ![](media/ResourcePools.png "リソース プールのシナリオ")
<!-- picture -->

*リソース プールのシナリオ*

