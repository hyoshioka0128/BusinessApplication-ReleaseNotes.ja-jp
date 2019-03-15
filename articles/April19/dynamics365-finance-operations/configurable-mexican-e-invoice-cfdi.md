---
title: メキシコ向けの構成可能な E-Invoice (CFDI)
description: メキシコ向けの構成可能な E-Invoice (CFDI)
author: mrolecki
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
ms.openlocfilehash: 46ef36a76ebb8c4e9a8e47389a667871ffbbd488
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288190"
---
#  <a name="configurable-mexican-e-invoice-cfdi"></a>メキシコ向けの構成可能な E-Invoice (CFDI) 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


メキシコでの電子請求には、Comprobantes fiscales digitales por internet (CFDI) 電子請求書フォーマットが必要です。 電子請求書は、組織がメキシコの税務当局 Servicio de Administración Tributaria (SAT) に提出する、合法的に承認されたデジタル納税領収書です。 

CFDI は、SAT が要求する形式で電子請求書を生成するための現在の方法です。 この方法では、請求書はデジタル署名サービス プロバイダー (PAC) によって検証および認定されます。 CFDI 方式を使用して電子請求書を生成する前に、組織は承認された PAC への Web サービス接続を設定する必要があります。 CFDI 方式の場合、Finance and Operations から PAC に XML メッセージを送信します。 PAC によって各請求書が検証され、フォリオ番号が割り当てられてから、サービス税務当局によって提供されるデジタル スタンプが組み込まれます。 PAC による承認プロセスが完了すると、組織は承認された XML メッセージを受け取り、請求書を XML または PDF 形式で顧客に送信できます。 印刷可能な CFDI フォームの例:

![印刷可能な CFDI フォーム](media/Configurable_CFDI_1.png "印刷可能な CFDI フォーム")

PAC Web サービスとの統合は、メキシコ向けローカライズの一部ではありません。 それとは別に、CFDI は最近頻繁に行われる法律変更の対象となっており、印刷可能な CFDI フォームをカスタマイズする需要が高まっています。 この機能によってそれが完全に構成可能になるため、PAC Web サービスとの統合および規制に関する更新のリリースが容易になります。 パートナーおよび顧客向けのエクスペリエンスが向上し、コードを変更することなく、必要に応じて、統合、エクスポートとインポートの形式、および印刷可能なフォームをカスタマイズできるようになります。

構成可能性の目標は、電子メッセージングとの統合および電子報告機能の使用によって達成される予定です。 

**メッセージ処理アクションの例**

![電子メッセージング - メッセージ処理アクション](media/Configurable_EM_1.png "電子メッセージング - メッセージ処理アクション")

> [!NOTE]
> この機能は、既存の構成不可能な CFDI の機能の一部を置き換えます。 新しい機能と更新されたユーザー エクスペリエンスの導入により、古い機能は廃止され、対応するコードは将来のアップデートで削除される予定です。  
