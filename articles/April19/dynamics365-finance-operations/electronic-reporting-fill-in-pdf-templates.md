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
#  <a name="electronic-reporting---generate-documents-in-pdf-format-by-filling-in-pdf-templates"></a><span data-ttu-id="c8b9b-103">電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成</span><span class="sxs-lookup"><span data-stu-id="c8b9b-103">Electronic reporting - Generate documents in PDF format by filling in PDF templates</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="c8b9b-104">電子申告 (ER) の既存機能では、ビジネス ユーザーは、実行時の電子ドキュメント生成のテンプレートとして Microsoft Excel および Microsoft Word のドキュメントを使用して、必要な構成を設計できます。</span><span class="sxs-lookup"><span data-stu-id="c8b9b-104">Existing functionality in electronic reporting (ER) allows business users to design necessary configurations using Microsoft Excel and Microsoft Word documents as templates of electronic documents generating at run time.</span></span> <span data-ttu-id="c8b9b-105">この機能を使用すると、ビジネス ユーザーは、PDF 形式のレポートを生成するためのテンプレートとして、入力可能な PDF ドキュメントを使用できます。</span><span class="sxs-lookup"><span data-stu-id="c8b9b-105">This feature allows business users to use a fillable PDF document as a template for generation of reports in PDF format.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="c8b9b-106">![ファイル プレビュー](media/ER-generate-doc-1099-c-preview.png "ファイル プレビュー")</span><span class="sxs-lookup"><span data-stu-id="c8b9b-106">![File preview](media/ER-generate-doc-1099-c-preview.png "File preview")</span></span>

<span data-ttu-id="c8b9b-107">また、ユーザーは設計時に、ER 形式の新しいコンポーネントを生成するそのような入力可能な PDF ドキュメントのフィールドを自動的に発見することもできます。実行時には、PDF テンプレートのこれらのフィールドに入力する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c8b9b-107">It also allows users to automatically discover fields of such fillable PDF document generating new components of an ER format at design time that are necessary to fill in these fields of a PDF template at run time.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="c8b9b-108">![PDF ページからの更新](media/ER-generate-doc-1099-c-update-from-pdf.png "PDF ページからの更新")</span><span class="sxs-lookup"><span data-stu-id="c8b9b-108">![Update from PDF page](media/ER-generate-doc-1099-c-update-from-pdf.png "Update from PDF page")</span></span>

<span data-ttu-id="c8b9b-109">この機能を使用すると、ユーザーは、複数の PDF 文書を生成し、それらを自動的に単一の最終 PDF ドキュメントにマージする、ER 形式を構成することもできます。</span><span class="sxs-lookup"><span data-stu-id="c8b9b-109">This feature also enables users to configure an ER format generating multiple PDF documents and automatically merging them into a single, final PDF document.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="c8b9b-110">![形式デザイナー](media/ER-generate-doc-1099-c-format-designer.png "形式デザイナーのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="c8b9b-110">![Format designer](media/ER-generate-doc-1099-c-format-designer.png "Format designer screenshot")</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="c8b9b-111">![サンプルの 1095-c フォーム](media/ER-generate-doc1099-c-update-output.png "サンプルの 1095-c フォーム")</span><span class="sxs-lookup"><span data-stu-id="c8b9b-111">![Sample 1095-c form](media/ER-generate-doc1099-c-update-output.png "Sample 1095-c form")</span></span>
