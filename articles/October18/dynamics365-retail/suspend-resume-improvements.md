---
title: 中断/再開の改善
description: この機能により、POS でトランザクションを中断および再開するユーザーの機能が向上し、POS 仕訳帳およびバックオフィス トランザクション履歴に監査機能が追加されます。
author: jblucher
manager: AnnBe
ms.date: 10/15/2018
ms.assetid: 7b453328-5b4e-423a-90d9-3069f7cc918f
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: jeffbl
audience: Admin
ms.openlocfilehash: ab2ecf5634c9110f84fafec38fbb48ac6d103299
ms.sourcegitcommit: 44ed9eddd89e00c08da16c86bae997d3110a6e26
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/15/2019
ms.locfileid: "391987"
---
# <a name="suspendresume-improvements"></a>中断/再開の改善


この機能は店舗関係者を対象としています。 ユーザーが POS のトランザクションを一時停止および再開する機能が向上します。 また、この機能により、POS 仕訳帳およびバックオフィス トランザクション履歴に監査機能が追加されます。

この機能は、進行中のトランザクションを中断し、おそらくは店内の別のデバイス/レジスターから後で再開する必要がある、POS レジ係や店員に役立ちます。

## <a name="improvements-and-capabilities"></a>改善点と機能
POS の既存の中断/再開機能は、以下の改善点と機能を含むように強化されています。

### <a name="ability-to-print-a-suspend-transaction-slip"></a>"トランザクションの中断" 伝票を印刷する機能
小売業者はレシート テンプレートを構成できるようになり、トランザクションを中断するたびに POS で伝票を印刷できます。 テンプレートには、ヘッダーおよび明細レベルのトランザクション情報と、固有のレシート番号とバーコードを含めることができます。

### <a name="quickly-recall-suspended-transactions-by-scanning-barcodes"></a>バーコードをスキャンすることで中断したトランザクションをすばやく呼び出す
POS ユーザーは、"トランザクションの中断" 伝票に印刷されたバーコードをスキャンして、トランザクションを迅速かつ簡単に再開できます。

### <a name="view-suspended-transactions-in-the-pos-journal"></a>POS 仕訳帳に中断したトランザクションを表示する
ヘッダーおよび明細レベルの詳細を含む中断されたトランザクション情報は POS 仕訳帳に保存され、追加の店内監査機能を提供します。  

### <a name="view-suspended-transactions-in-back-office-inquiries"></a>バックオフィスの照会で中断されたトランザクションを表示する
中断されたトランザクションのエントリはバックオフィスに複製されて、小売店舗トランザクションの照会に表示されます。 ユーザーは、トランザクションが中断された場所と日時の詳細を見ることができます。 さらに、再開されて完了または無効化されたトランザクションを、元の中断されたトランザクションにリンクすることができます。

### <a name="automatically-void-suspended-transactions-at-the-end-of-each-shift"></a>各シフトの終了時に中断されたトランザクションを自動的に無効にする
小売業者は、中断されたトランザクションが放置されてたまるのを防ぐため、各シフトの終了時に中断されたトランザクションを自動的に無効にするように POS を構成できます。 無効化された各トランザクションは、監査のために、仕訳帳に追加され、バックオフィスに複製されます。

### <a name="ability-to-bulk-select-and-void-suspended-transactions"></a>中断されたトランザクションを一括選択して無効にする機能
シフト終了時に中断されたトランザクションを必要に応じて無効にすることに加え、アクセス許可を持つユーザーは、POS 内から中断されたトランザクションを複数選択して無効にすることができます。 


