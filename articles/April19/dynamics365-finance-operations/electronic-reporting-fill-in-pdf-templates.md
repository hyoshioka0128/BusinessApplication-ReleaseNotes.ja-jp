---
title: 電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成
description: 現時点では、PDF テンプレートに入力して PDF 形式のドキュメントを直接生成する方法はありません。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: c6ec6fbcd8a295325ce88eb81ef6b906a58b2a7b
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225017"
---
#  <a name="electronic-reporting---generate-documents-in-pdf-format-by-filling-in-pdf-templates"></a>電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


電子申告 (ER) の既存機能では、ビジネス ユーザーは、実行時の電子ドキュメント生成のテンプレートとして Microsoft Excel および Microsoft Word のドキュメントを使用して、必要な構成を設計できます。 この機能を使用すると、ビジネス ユーザーは、PDF 形式のレポートを生成するためのテンプレートとして、入力可能な PDF ドキュメントを使用できます。

![ファイル プレビュー](media/ER-generate-doc-1099-c-preview.png "ファイル プレビュー")

設計時に PDF を構成済みの ER 形式にインポートして、検出された入力が必要なフィールドに対してその ER 形式の新しい要素を自動的に生成できます。 ER 形式の生成された要素へのバインディングを追加することで、この ER 形式の実行によって PDF テンプレートの必要なフィールドに入力できるようになります。

![PDF ページからの更新](media/ER-generate-doc-1099-c-update-from-pdf.png "PDF ページからの更新")

ユーザーはこの機能を使用して、複数の PDF 文書を生成してそれらを自動的に単一の最終 PDF ドキュメントにマージする ER 形式を構成することもできます。

![形式デザイナー](media/ER-generate-doc-1099-c-format-designer.png "形式デザイナーのスクリーンショット")

![サンプルの 1095-C フォーム](media/ER-generate-doc1099-c-update-output.png "サンプルの 1095-C フォーム")
