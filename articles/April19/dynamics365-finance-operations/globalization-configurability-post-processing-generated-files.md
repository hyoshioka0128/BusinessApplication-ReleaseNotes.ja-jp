---
title: 電子申告 - 生成されたファイルの後処理
description: 電子申告の後処理機能により、生成されたファイルを処理するための追加機能が可能になります。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: b7894f45c4392977d9dac39b7f845d5078fcd424
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210487"
---
# <a name="electronic-reporting---post-processing-of-generated-files"></a>電子申告 - 生成されたファイルの後処理
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


電子申告の既存の機能により、ビジネス ユーザーは次のことを実行できます。

- 電子ドキュメントのレイアウトを構成する。
- 実行時にドキュメントに入力するデータ ソースを指定する。
- 生成された電子ドキュメントの出力先 (ファイリングとメール送信) を割り当てる。 

この機能がないと、ユーザーは生成されたドキュメントに対する追加の出力先を構成できず、生成されたドキュメントを実行時に完全に変更するためのカスタム変換を適用することができません。 この機能が提供される前は、これを行うには、独自の難しいカスタマイズを作成する必要がありました。 この機能により、ビジネス ユーザーは、Finance and Operations の既存のロジックを再利用し、関連するアプリケーションの機能 (ファイルの暗号化、別の形式への変換、直接印刷など) を使用して、必要な後処理操作を構成できます。
