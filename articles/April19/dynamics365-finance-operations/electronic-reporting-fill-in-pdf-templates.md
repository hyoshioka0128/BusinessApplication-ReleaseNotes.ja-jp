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
#  <a name="electronic-reporting---generate-documents-in-pdf-format-by-filling-in-pdf-templates"></a><span data-ttu-id="3a972-103">電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成</span><span class="sxs-lookup"><span data-stu-id="3a972-103">Electronic reporting - Generate documents in PDF format by filling in PDF templates</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="3a972-104">電子申告 (ER) の既存機能では、ビジネス ユーザーは、実行時の電子ドキュメント生成のテンプレートとして Microsoft Excel および Microsoft Word のドキュメントを使用して、必要な構成を設計できます。</span><span class="sxs-lookup"><span data-stu-id="3a972-104">Existing functionality in electronic reporting (ER) allows business users to design necessary configurations using Microsoft Excel and Microsoft Word documents as templates of electronic documents generating at run time.</span></span> <span data-ttu-id="3a972-105">この機能を使用すると、ビジネス ユーザーは、PDF 形式のレポートを生成するためのテンプレートとして、入力可能な PDF ドキュメントを使用できます。</span><span class="sxs-lookup"><span data-stu-id="3a972-105">This feature allows business users to use a fillable PDF document as a template for generation of reports in PDF format.</span></span>

<span data-ttu-id="3a972-106">![ファイル プレビュー](media/ER-generate-doc-1099-c-preview.png "ファイル プレビュー")</span><span class="sxs-lookup"><span data-stu-id="3a972-106">![File preview](media/ER-generate-doc-1099-c-preview.png "File preview")</span></span>

<span data-ttu-id="3a972-107">また、ユーザーは設計時に、ER 形式の新しいコンポーネントを生成するそのような入力可能な PDF ドキュメントのフィールドを自動的に発見することもできます。実行時には、PDF テンプレートのこれらのフィールドに入力する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3a972-107">It also allows users to automatically discover fields of such fillable PDF document generating new components of an ER format at design time that are necessary to fill in these fields of a PDF template at run time.</span></span>

<span data-ttu-id="3a972-108">![PDF ページからの更新](media/ER-generate-doc-1099-c-update-from-pdf.png "PDF ページからの更新")</span><span class="sxs-lookup"><span data-stu-id="3a972-108">![Update from PDF page](media/ER-generate-doc-1099-c-update-from-pdf.png "Update from PDF page")</span></span>

<span data-ttu-id="3a972-109">この機能を使用すると、ユーザーは、複数の PDF 文書を生成し、それらを自動的に単一の最終 PDF ドキュメントにマージする、ER 形式を構成することもできます。</span><span class="sxs-lookup"><span data-stu-id="3a972-109">This feature also enables users to configure an ER format generating multiple PDF documents and automatically merging them into a single, final PDF document.</span></span>

<span data-ttu-id="3a972-110">![形式デザイナー](media/ER-generate-doc-1099-c-format-designer.png "形式デザイナーのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="3a972-110">![Format designer](media/ER-generate-doc-1099-c-format-designer.png "Format designer screenshot")</span></span>

<span data-ttu-id="3a972-111">![サンプルの 1095-C フォーム](media/ER-generate-doc1099-c-update-output.png "サンプルの 1095-C フォーム")</span><span class="sxs-lookup"><span data-stu-id="3a972-111">![Sample 1095-C form](media/ER-generate-doc1099-c-update-output.png "Sample 1095-C form")</span></span>
