---
title: ブラジル向けの構成可能な E-Invoice (NF-e と NFS-e)
description: この機能により、NF-e および NFS-e の E-Invoice を構成できます。
author: sndray
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: sndray
ms.openlocfilehash: 7831e7930423cd809019e16919a7bfb4f3dd116d
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224970"
---
#  <a name="configurable-e-invoices-for-brazil-nf-e-and-nfs-e"></a>ブラジル向けの構成可能な E-Invoice (NF-e と NFS-e) 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


SEFAZ とも呼ばれるブラジルの税務当局は、電子請求のためにすべての企業が順守しなければならない電子通信標準を定義しました。 ブラジルのローカライズでは、Nota Fiscal Eletrônica (NF-e または NFS-e) を生成して、2 者間の品目またはサービスの移動を登録できます。 生成された会計文書は、XML メッセージでデジタル署名された NF-e として Secretaria da Fazenda (SEFAZ) に送信できます。 NF-e のプロセスには次のステップが含まれます。

1. 会計施設は会計ドキュメントを転記します。
2. NF-e のエクスポートまたはインポート プロセスで、転記された会計ドキュメントが検出されて、指定された形式の XML メッセージが生成されます。 NF-e ごとに個別の XML メッセージが生成されます。 XML メッセージが SEFAZ に送信されます。
3. SEFAZ は XML メッセージを処理し、各 NF-e に対してプロトコルとステータスを返します。

SEFAZ から NF-e のステータスを受け取ったら、承認、取消、ドキュメントの訂正と再送信など、さまざまな一連の操作を実行できます。

ブラジルの NF-e については頻繁に法律が変更されており、NFS-e の要件は計画的に変更されます。 この機能により両方とも完全に構成可能になるため、Microsoft は規制の更新をすばやくリリースでき、パートナーと顧客は必要に応じてコードを変更することなく統合とエクスポート/インポート形式をカスタマイズできます。 さらに、構成可能な E-Invoice を使用すると、パートナーはブラジルのサポートされていない州、都市、および業種のローカライズ対象を簡単に拡大できます。

NF-e と NFS-e の両方の構成可能性の目標は、電子メッセージングとの統合および電子報告機能の使用によって達成される予定です。 

**メッセージ処理アクションの例**

![電子メッセージング - メッセージ処理アクション](media/Configurable_EM_1.png "電子メッセージング - メッセージ処理アクション")

> [!NOTE]
> この機能は、既存の構成不可能な NF-e および NFS-e の機能の一部を置き換えます。 新しい機能と更新されたユーザー エクスペリエンスの導入により、古い機能は廃止され、対応するコードは将来のアップデートで削除される予定です。
