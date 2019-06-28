---
title: スケジューリング機能
description: スケジューリング
author: dgittler
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: dgittler
ms.reviewer: shellyha
ms.openlocfilehash: c0fef0a5704f73eb2d2a444d2d607ab01355bc63
ms.sourcegitcommit: 738a9a637dcc50b6ac52d47433e684ea61cedd52
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/07/2019
ms.locfileid: "1623898"
---
#  <a name="scheduling-capabilities"></a>スケジューリング機能
[!include[dynamics365-field-service banner](../../includes/dynamics365-field-service.md)]


この記事では、2019 年 4 月リリースの新しいスケジューリング機能について説明します。

## <a name="support-for-greater-than-1-resource-capacity"></a>複数のリソース キャパシティのサポート

場合によっては、すべてのリソースが同じように生産的とは限りません。 たとえば、経験豊富な技術者は 2 台の自転車を同時に修理できますが、経験の浅い技術者は一度に 1 台の自転車しか作業できない可能性があります。 このようなケースに対応するために、リソース スケジュール最適化は 1 を超えるキャパシティでリソースをスケジュールできるようになりました。


## <a name="support-for-matches-resource-role-constraints"></a>"リソースの種類に一致する" 制約のサポート

組織は要件に対するリソース ロールを定義できるようになりました。オプティマイザーは、一致したリソース ロールを持つリソースに予約を割り当てると同時に、他の定義済み制約を満たします。

## <a name="support-for-must-choose-resource-constraints"></a>"リソースの選択が必要" 制約のサポート

特定のリソースを常に重要な顧客に派遣するなど、企業は顧客との間に特別な契約を結ぶことがあります。 新しい**リソースの選択が必要**制約では、企業が要件に対するリソースの基本設定を定義できます。 オプティマイザーは、他の定義済み制約も満たしながら、**リソースの選択が必要**リストでリソースに予約を割り当てます。

## <a name="optimization-objective-for-as-soon-as-possible-asap"></a>「できるだけ早く (ASAP)」の最適化目標 

たまに (作業指示書などで) リソースのキャパシティがリソースの需要を超えることがあります。 そのような状況において、リソースの予定を完全に埋めてしまうか、緊急時や予定外の作業に備えてリソースを残しておくか、経営上の判断を求められます。

2019 年 4 月のリリースでは、「できるだけ早く (ASAP)」という新しい目標が設定できるようになります。これにより、組織は他のスケジューリングの目標を選択して再度ランク付けすることで、一部のリソースを余裕を持って残しておくか、1 日の予定をすべて埋めてしまうか、バランスを取ることができます。
