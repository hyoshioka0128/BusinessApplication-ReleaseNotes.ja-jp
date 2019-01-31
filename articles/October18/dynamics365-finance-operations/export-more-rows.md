---
title: Excel への最大 100 万行のエクスポート
description: ユーザーは、これまでより大きいデータセットを Excel にエクスポートできます
author: jasongre
manager: AnnBe
ms.date: 12/03/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jasongre
audience: admin, end user, IT pro
ms.openlocfilehash: 32cc85cd4f8688edba0cb2dbaf47c21db8550fa9
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199278"
---
# <a name="export-up-to-1-million-rows-to-excel"></a>Excel への最大 100 万行のエクスポート

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Excel へのエクスポート機能では、Finance and Operations のグリッドから最大 100 万行をエクスポートできるように構成できるようになり、以前の 10,000 行の制限から大幅に増加しました。 既定では、エクスポートの制限は 50,000 行に設定されていますが、**クライアント パフォーマンス オプション** ページで、システム管理者はエクスポートの上限を 100 万行まで調整できます。  

Finance and Operations で Excel にエクスポートできるデータセットが大きくなったため、Excel へのエクスポート機能のユーザー エクスペリエンスに対して 2 つの調整が加えられました。

-    エクスポートの間に表示される新しいダイアログでは、ユーザーにフィードバックと進行状況が提供されます。 また、このダイアログでは、ユーザーはいつでもエクスポートを停止し、それまでにエクスポートされたデータを含むファイルを取得することができます。 エクスポートの速度はデータセットによって異なり、エクスポートされる行数、グリッドの列数、表示方法の有無 (計算列)、グリッド内のディメンション フィールドの有無に依存します。 この機能は、Platform update 22 で利用できます。

      > [!div class="mx-imgBorder"]
      > ![エクスポート進行状況のダイアログ](media/largeExport.png  "エクスポート進行状況のダイアログ")

-  エクスポートの完了後、ユーザーは、エクスポート完了通知をアクション センターで受け取ります。 この通知には、エクスポートされたデータを含む Excel ファイルをダウンロードするためのリンクが含まれます。 リンクと通知には、エクスポートが完了してからおよそ 3 日間アクセスできます。 この機能は、Platform update 23 で利用できます。     

詳細については、「[Office 統合のトラブルシューティング](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/office-integration/office-integration-troubleshooting)」を参照してください。

