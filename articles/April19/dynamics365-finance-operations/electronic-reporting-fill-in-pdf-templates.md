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
ms.sourcegitcommit: 560c1b626b40ff3c51450183b6201cfc589b49e3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/22/2019
ms.locfileid: "890852"
---
#  <a name="electronic-reporting---generate-documents-in-pdf-format-by-filling-in-pdf-templates"></a><span data-ttu-id="6dbad-103">電子申告 - PDF テンプレートに記入することによる PDF 形式での文書生成</span><span class="sxs-lookup"><span data-stu-id="6dbad-103">Electronic reporting - Generate documents in PDF format by filling in PDF templates</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="6dbad-104">電子申告 (ER) の既存機能では、ビジネス ユーザーは、実行時の電子ドキュメント生成のテンプレートとして Microsoft Excel および Microsoft Word のドキュメントを使用して、必要な構成を設計できます。</span><span class="sxs-lookup"><span data-stu-id="6dbad-104">Existing functionality in electronic reporting (ER) allows business users to design necessary configurations using Microsoft Excel and Microsoft Word documents as templates of electronic documents generating at run time.</span></span> <span data-ttu-id="6dbad-105">この機能を使用すると、ビジネス ユーザーは、PDF 形式のレポートを生成するためのテンプレートとして、入力可能な PDF ドキュメントを使用できます。</span><span class="sxs-lookup"><span data-stu-id="6dbad-105">This feature allows business users to use a fillable PDF document as a template for generation of reports in PDF format.</span></span>

<span data-ttu-id="6dbad-106">![ファイル プレビュー](media/ER-generate-doc-1099-c-preview.png "ファイル プレビュー")</span><span class="sxs-lookup"><span data-stu-id="6dbad-106">![File preview](media/ER-generate-doc-1099-c-preview.png "File preview")</span></span>

<span data-ttu-id="6dbad-107">設計時に PDF を構成済みの ER 形式にインポートして、検出された入力が必要なフィールドに対してその ER 形式の新しい要素を自動的に生成できます。</span><span class="sxs-lookup"><span data-stu-id="6dbad-107">You can import the PDF at design time to a configured ER format which automatically generates new elements of this ER format for discovered fields that need to be filled in.</span></span> <span data-ttu-id="6dbad-108">ER 形式の生成された要素へのバインディングを追加することで、この ER 形式の実行によって PDF テンプレートの必要なフィールドに入力できるようになります。</span><span class="sxs-lookup"><span data-stu-id="6dbad-108">By adding bindings to generated elements of an ER format, you can fill in necessary fields of the PDF template by running this ER format.</span></span>

<span data-ttu-id="6dbad-109">![PDF ページからの更新](media/ER-generate-doc-1099-c-update-from-pdf.png "PDF ページからの更新")</span><span class="sxs-lookup"><span data-stu-id="6dbad-109">![Update from PDF page](media/ER-generate-doc-1099-c-update-from-pdf.png "Update from PDF page")</span></span>

<span data-ttu-id="6dbad-110">ユーザーはこの機能を使用して、複数の PDF 文書を生成してそれらを自動的に単一の最終 PDF ドキュメントにマージする ER 形式を構成することもできます。</span><span class="sxs-lookup"><span data-stu-id="6dbad-110">This feature also enables users to configure an ER format generating multiple PDF documents and automatically merging them into a single, final PDF document.</span></span>

<span data-ttu-id="6dbad-111">![形式デザイナー](media/ER-generate-doc-1099-c-format-designer.png "形式デザイナーのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="6dbad-111">![Format designer](media/ER-generate-doc-1099-c-format-designer.png "Format designer screenshot")</span></span>

<span data-ttu-id="6dbad-112">![サンプルの 1095-C フォーム](media/ER-generate-doc1099-c-update-output.png "サンプルの 1095-C フォーム")</span><span class="sxs-lookup"><span data-stu-id="6dbad-112">![Sample 1095-C form](media/ER-generate-doc1099-c-update-output.png "Sample 1095-C form")</span></span>
