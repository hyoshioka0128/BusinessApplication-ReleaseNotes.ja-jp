---
title: 電子メール、HTML、PDF からの構造化データの抽出
description: ユーザーが電子メール、HTML ファイル、PDF からコンテンツを解析できる新しいインテリジェンス機能を、Microsoft Flow に統合しました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/14/2019
ms.assetid: 8987bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: d88a104b105a5bb017a140a26d03125036cde842
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445426"
---
# <a name="extract-structured-data-from-emails-html-and-pdf-public-preview"></a><span data-ttu-id="1dc06-103">電子メール、HTML、PDF からの構造化データの抽出 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="1dc06-103">Extract structured data from emails, HTML, and PDF (Public Preview)</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="1dc06-104">ユーザーが電子メール、HTML ファイル、PDF からコンテンツを解析できる新しいインテリジェンス機能を、Microsoft Flow に統合しました。</span><span class="sxs-lookup"><span data-stu-id="1dc06-104">We have integrated new intelligence features into Microsoft Flow that allow users to parse content from email, HTML files, and PDFs.</span></span> <span data-ttu-id="1dc06-105">これにより、ユーザーはフロー内のロジックを駆動し、ダウンストリームのコネクタで使用できる、構造化データを取得できます。</span><span class="sxs-lookup"><span data-stu-id="1dc06-105">This allows users to retrieve structured data that can drive logic in a flow and be used in downstream connectors.</span></span>

<span data-ttu-id="1dc06-106">従来、電子メールの処理が</span><span class="sxs-lookup"><span data-stu-id="1dc06-106">Historically, working with email is the No.</span></span> <span data-ttu-id="1dc06-107">自動化フローで最もよく発生するタスクです。</span><span class="sxs-lookup"><span data-stu-id="1dc06-107">1 task that happens with Automated Flows.</span></span> <span data-ttu-id="1dc06-108">ただし、電子メールの本文の内容を解析および推論する機能は非常に限られています。</span><span class="sxs-lookup"><span data-stu-id="1dc06-108">However, our ability to parse and reason over the content of the body of an email has been extremely limited.</span></span> <span data-ttu-id="1dc06-109">ユーザーは 1 日に何百もの電子メールを受け取る可能性があり、それらに迅速に応答できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="1dc06-109">Users can receive hundreds of emails in a day and need to be able to respond to them quickly.</span></span> <span data-ttu-id="1dc06-110">Microsoft Flow のインテリジェンス機能では、電子メールの本文からでもコンテンツを抽出することができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1dc06-110">Now, with the intelligence features in Microsoft Flow, it’s possible to extract content even from the body of an email.</span></span> <span data-ttu-id="1dc06-111">ユーザーは、次の操作を実行できます。</span><span class="sxs-lookup"><span data-stu-id="1dc06-111">Users can now:</span></span>

- <span data-ttu-id="1dc06-112">電子メールに含まれる**テーブル**を抽出します。</span><span class="sxs-lookup"><span data-stu-id="1dc06-112">Extract **tables** contained in emails.</span></span> <span data-ttu-id="1dc06-113">たとえば、仕入先価格表などです。</span><span class="sxs-lookup"><span data-stu-id="1dc06-113">For example: vendor price lists.</span></span>
- <span data-ttu-id="1dc06-114">HTML/テキスト ドキュメントから**特定のエンティティ**を抽出します。</span><span class="sxs-lookup"><span data-stu-id="1dc06-114">Extract **specific entities** from an HTML/text document.</span></span> <span data-ttu-id="1dc06-115">たとえば、サービス インシデントから ID とステータスを抽出します。</span><span class="sxs-lookup"><span data-stu-id="1dc06-115">For example: extract ID and status from a service incident.</span></span>
- <span data-ttu-id="1dc06-116">電子メールに**繰り返しパターン**が含まれる場合、そのすべてのインスタンスを抽出します。</span><span class="sxs-lookup"><span data-stu-id="1dc06-116">If email contains a **repeating pattern**, extract all the instances of it.</span></span> <span data-ttu-id="1dc06-117">たとえば、複数の区間がある航空券などです。</span><span class="sxs-lookup"><span data-stu-id="1dc06-117">For example: flight tickets with multiple legs.</span></span>

<span data-ttu-id="1dc06-118">ユーザーは 1 つ以上のドキュメントまたは電子メールの例から必要なコンテンツを選択するだけでよく、将来同じ特性を持つドキュメントからそのコンテンツが抽出されます。</span><span class="sxs-lookup"><span data-stu-id="1dc06-118">All you do is select the content you want from one or more example documents or emails, and then in the future that content will be extracted on future documents that have the same characteristics.</span></span>

<span data-ttu-id="1dc06-119">![電子メール抽出の設定](media/EmailExtraction-1.png "電子メール抽出の設定")</span><span class="sxs-lookup"><span data-stu-id="1dc06-119">![Configuring email extraction](media/EmailExtraction-1.png "Configuring email extraction")</span></span>
