---
title: データ損失防止の強化
description: データ損失防止には、データ分類とデータ フローの方向を適用する機能が追加されました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/14/2019
ms.assetid: 4f87bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 2dc044217588e834640044282627e6d0b3aa7e39
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445452"
---
# <a name="data-loss-prevention-enhancements"></a>データ損失防止の強化

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

データ損失防止 (DLP) ポリシーを使用すると、組織はコネクタをビジネス データ グループと非ビジネス データ グループにグループ化できます。 これにより、組織は*ビジネス* データ ソースだけを含むフローを構築し、ビジネス データが非ビジネス データ ソースに漏れるのを防ぐことができます。 一般的な例は、*自分の SharePoint データが Twitter に送られて欲しくない*ような場合です。

これらの機能に加えて、ユーザーからはデータの分類とデータ フローの方向を尊重する機能の要望がありました。 これをサポートすることで、ブロックするシナリオを細かく指定できるので、作成されるフローの数が増えます。

たとえば、多くの環境では、Twitter は*非ビジネス*に分類され、SharePoint は*ビジネス*に分類されます。 現在のモデルでは、これはユーザーがセンチメント分析データを収集してそれを SharePoint リスト (イベントおよびフィードバック収集に関して製品チームに非常に役立つもの) に格納できないことを意味します。

DLP に対する新しい機能強化により、これが可能になります。 これについては、2 つの重要な側面があります。

- 1 つ目は、管理者はデータがコネクタ間を移動できる方向を選択できるようになりました。 たとえば、組織によっては Twitter のデータがフローに入るのは問題なくても、そのデータがフローから Twitter に送られるのは望ましくない場合があります。
- 2 つ目は、設計時と実行時の両方においてデータの分類が Microsoft Flow によって適用されます。 たとえば、機密性の高い SharePoint サイトからデータを取得して、パブリックの SharePoint サイトに送信することはできません。 一方、パブリック サイトからデータを取得して高機密性サイトに移動することはできます。
