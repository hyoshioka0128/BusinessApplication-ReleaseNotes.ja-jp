---
title: 電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成
description: 現時点では、PDF テンプレートに入力して PDF 形式のドキュメントを直接生成する方法はありません。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: 6242a9b8e896ad9352792689f23fc9d4437a2a8b
ms.sourcegitcommit: 3c1c87393de3c81395a981f7eea040c5ee62ab45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "285231"
---
#  <a name="electronic-reporting---generate-documents-in-pdf-format-by-filling-in-pdf-templates"></a>電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


電子申告 (ER) の既存機能では、ビジネス ユーザーは、実行時の電子ドキュメント生成のテンプレートとして Microsoft Excel および Microsoft Word のドキュメントを使用して、必要な構成を設計できます。 この機能を使用すると、ビジネス ユーザーは、PDF 形式のレポートを生成するためのテンプレートとして、入力可能な PDF ドキュメントを使用できます。

![ファイル プレビュー](media/ER-generate-doc-1099-c-preview.png "ファイル プレビュー")

また、ユーザーは設計時に、ER 形式の新しいコンポーネントを生成するそのような入力可能な PDF ドキュメントのフィールドを自動的に発見することもできます。実行時には、PDF テンプレートのこれらのフィールドに入力する必要があります。

![PDF ページからの更新](media/ER-generate-doc-1099-c-update-from-pdf.png "PDF ページからの更新")

この機能を使用すると、ユーザーは、複数の PDF 文書を生成し、それらを自動的に単一の最終 PDF ドキュメントにマージする、ER 形式を構成することもできます。

![形式デザイナー](media/ER-generate-doc-1099-c-format-designer.png "形式デザイナーのスクリーンショット")

![サンプルの 1095-C フォーム](media/ER-generate-doc1099-c-update-output.png "サンプルの 1095-C フォーム")
