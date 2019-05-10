---
title: エージェント固有の構成のキャッシュ
description: エージェント固有の構成のキャッシュについて説明します。
keywords: ''
ms.date: 03/12/2019
ms.service:
- business-applications
ms.topic: article
ms.assetid: AF34A5B0-7F0D-4DBD-9B83-258CC1FB3B23
author: DeepapMS
ms.author: deepap
ms.openlocfilehash: 304d402ab127cc2c66748013412fee0e0088fc08
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225385"
---
# <a name="cache-specific-configurations-for-agents"></a>エージェント固有の構成のキャッシュ
[!include[unified-service-desk banner](../../../includes/unified-service-desk.md)]
クライアント キャッシュ機能で [構成キャッシュのバージョン] オプションを使用すると、すべての構成を取得せずに、変更を加えられた構成を Customer Engagement サーバーからエージェントのデスクトップに取得することができます。

組織に複数の部署があり、それぞれの部署にロールに基づいてエージェントが追加された構成が存在する場合があります。 これらの構成のいずれかに変更を加えた場合、[構成キャッシュのバージョン] 機能を使用すると、変更を加えた構成のみをダウンロードできます。

また、他の構成に割り当てられているエージェントがクライアント アプリケーションにサインインするときは、この機能を使用すると構成がダウンロードされないため、Unified Service Desk の起動時のパフォーマンスが向上します。 この機能は、組織が実稼働ユーザーに影響を与えずにパイロット構成を変更したい場合に、Unified Service Desk のアプリケーション ライフサイクル管理を改善するのにも役立ちます。
