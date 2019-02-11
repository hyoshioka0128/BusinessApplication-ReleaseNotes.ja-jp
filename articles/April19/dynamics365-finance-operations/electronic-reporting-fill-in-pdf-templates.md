---
title: 電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成
description: 現時点では、PDF テンプレートに入力して PDF 形式のドキュメントを直接生成する方法はありません。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: b9d5fc0b01dfc6b6cb74238cc3aa33f7f06d0750
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210648"
---
#  <a name="electronic-reporting---generate-documents-in-pdf-format-by-filling-in-pdf-templates"></a>電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


電子申告 (ER) の既存機能では、ビジネス ユーザーは、実行時の電子ドキュメント生成のテンプレートとして Microsoft Excel および Microsoft Word のドキュメントを使用して、必要な構成を設計できます。 この機能を使用すると、ビジネス ユーザーは、PDF 形式のレポートを生成するためのテンプレートとして、入力可能な PDF ドキュメントを使用できます。

> [!div class="mx-imgBorder"]
> ![ファイル プレビュー](media/ER-generate-doc-1099-c-preview.png "ファイル プレビュー")

また、ユーザーは設計時に、ER 形式の新しいコンポーネントを生成するそのような入力可能な PDF ドキュメントのフィールドを自動的に発見することもできます。実行時には、PDF テンプレートのこれらのフィールドに入力する必要があります。

> [!div class="mx-imgBorder"]
> ![PDF ページからの更新](media/ER-generate-doc-1099-c-update-from-pdf.png "PDF ページからの更新")

この機能を使用すると、ユーザーは、複数の PDF 文書を生成し、それらを自動的に単一の最終 PDF ドキュメントにマージする、ER 形式を構成することもできます。

> [!div class="mx-imgBorder"]
> ![形式デザイナー](media/ER-generate-doc-1099-c-format-designer.png "形式デザイナーのスクリーンショット")

> [!div class="mx-imgBorder"]
> ![サンプルの 1095-c フォーム](media/ER-generate-doc1099-c-update-output.png "サンプルの 1095-c フォーム")
