---
title: 従来の Common Data Service ワークフローと同等の自動フロー
description: このリリースでは、従来の非同期 Common Data Service ワークフローでサポートされていたすべてのシナリオを、自動フローで実現できるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/30/2019
ms.assetid: fb86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: e2c91d3a6cfd40f4f9735771fa08e3d59507beaf
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445823"
---
# <a name="automated-flow-parity-with-classic-common-data-service-workflows"></a>従来の Common Data Service ワークフローと同等の自動フロー

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

今後、既存の従来の Common Data Service ワークフロー (以前は Dynamics 365 for Customer Engagement ワークフローと呼ばれていました) は、自動フローによって置き換えられます。 このリリースでは、従来の非同期 Common Data Service ワークフローでサポートされていたすべてのシナリオを、自動フローで実現できるようになりました。 アクションのサポートやバッチ処理のサポートなど、いくつかの機能がリリース ノートの他の部分で説明されています。 自動フローの新機能の一覧を次に示します。

- **トリガーにフィルターを提供する**: 自動フローをトリガーするレコードを正確に制御できます。 トリガーをフローの途中に含めることで、それらをフローの内部の**待機状態**として利用できます。
- **として実行**機能: CDS for Apps によってトリガーされる自動フローは、フローの所有者によって定義されたアカウントで、またはトリガーの原因になった変更を実行したユーザーの ID によって、実行できます。
- **失敗したアクションからフローを再開する**: アクションでフローが失敗した場合、作成者はエラーを修復した後そのアクションからフローを再開できます。
- **複数のトリガー タイプのサポート**: フローを、自動 (システム内のイベントによってトリガーされる) と即時 (オンデマンドでトリガーされる) の両方に同時にできるようになりました。
- **他のフローを呼び出す**: フローでは、他のフローを呼び出してパラメーターを渡すことができるようになりました。

最後に、お客様に対して移行ガイダンスも提供されていますが、現時点では自動移行はありません。
