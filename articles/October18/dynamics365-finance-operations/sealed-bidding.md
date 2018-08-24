---
title: "封緘された入札"
description: "封緘された入札"
author: ShylaThompson
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 2405e676929ee3a49bce634b83c744f138fe401a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="sealed-bidding"></a>封緘された入札 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



見積依頼機能は、封緘された入札をサポートするように強化されました。 仕入先は、仕入先コラボレーション インターフェイスの専用フォームを通じて、.pdf の添付ファイルを含んだ入札を入力し、送信することができます。 入札は、調達担当者がアクセスできる RFQ のコンテキストでは表示されません。 入札は暗号化されて保存されます。 仕入先連絡先として登録されていて、かつ必要なロールのアクセス許可を持っている連絡担当者だけが、開封前の入札にアクセスできます。 有効期限が切れると、調達担当者が入札を開封できるようになり、その時点で、RFQ のコンテキスト内から仕入先の入札を表示できるようになります。 入札に対して有効期限内に行われたユーザー操作 (読み取りや書き込みを伴う操作) は、監査目的でログに記録され、その情報は入札の開封時に仕入先と調達担当者に開示されます。  

