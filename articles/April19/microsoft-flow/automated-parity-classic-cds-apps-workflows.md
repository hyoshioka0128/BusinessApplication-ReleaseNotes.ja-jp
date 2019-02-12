---
title: 従来の CDS for Apps ワークフローと同等の自動フロー
description: このリリースでは、従来の非同期 CDS for Apps ワークフローでサポートされていたすべてのシナリオを、自動フローで実現できるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 3d7e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: f4969f2ba0f4b091230585c115600a9e1349c094
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210901"
---
# <a name="automated-flow-parity-with-classic-cds-for-apps-workflows"></a>従来の CDS for Apps ワークフローと同等の自動フロー


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

時間の経過とともに、既存の従来の Common Data Service (CDS) for Apps ワークフローは自動フローに置き換えられていきます。 このリリースでは、従来の非同期 CDS for Apps ワークフローでサポートされていたすべてのシナリオを、自動フローで実現できるようになりました。 アクションのサポートやバッチ処理のサポートなど、いくつかの機能がリリース ノートの他の部分で説明されています。 自動フローの新機能の一覧を次に示します。

- **トリガーにフィルターを提供する**: 自動フローをトリガーするレコードを正確に制御できます。 トリガーをフローの途中に含めることで、それらをフローの内部の**待機状態**として利用できます。
- **として実行**機能: CDS for Apps によってトリガーされる自動フローは、フローの所有者によって定義されたアカウントで、またはトリガーの原因になった変更を実行したユーザーの ID によって、実行できます。
- **失敗したアクションからフローを再開する**: アクションでフローが失敗した場合、作成者はエラーを修復した後そのアクションからフローを再開できます。
- **複数のトリガー タイプのサポート**: フローを、自動 (システム内のイベントによってトリガーされる) と即時 (オンデマンドでトリガーされる) の両方に同時にできるようになりました。
- **他のフローを呼び出す**: フローでは、他のフローを呼び出してパラメーターを渡すことができるようになりました。

最後に、お客様に対して移行ガイダンスも提供されていますが、現時点では自動移行はありません。
