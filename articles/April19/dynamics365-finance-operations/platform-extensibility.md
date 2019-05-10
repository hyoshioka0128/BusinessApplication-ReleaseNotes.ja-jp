---
title: プラットフォーム拡張性の機能強化
description: プラットフォーム拡張性の機能強化
author: ChrisGarty
manager: AnnBe
ms.date: 03/19/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: cgarty
audience: developer, customizer
ms.openlocfilehash: cba088fc47a7a8296a7f22011c0fbe8d94116a3f
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225212"
---
# <a name="platform-extensibility-enhancements"></a><span data-ttu-id="b315c-103">プラットフォーム拡張性の機能強化</span><span class="sxs-lookup"><span data-stu-id="b315c-103">Platform extensibility enhancements</span></span>

<span data-ttu-id="b315c-104">Platform update 24 で強化された拡張性機能:</span><span class="sxs-lookup"><span data-stu-id="b315c-104">Enhanced extensibility capabilities in Platform update 24:</span></span>

- <span data-ttu-id="b315c-105">フォーム ボタン コントロールに 'OnClicking' イベントを追加します (参照番号 215644)。</span><span class="sxs-lookup"><span data-stu-id="b315c-105">Add an 'OnClicking' event for form button controls (Ref# 215644).</span></span>

- <span data-ttu-id="b315c-106">フォーム内の種類 (コントロールとデータ ソース) に対するカーネル メソッドのオーバーライドではないメソッドでコマンド チェーン (CoC) が可能です (参照番号 238379)。</span><span class="sxs-lookup"><span data-stu-id="b315c-106">Allow Chain of Command (CoC) on methods that aren't overrides of kernel methods on types inside forms (controls and data sources) (Ref# 238379).</span></span>

- <span data-ttu-id="b315c-107">フォーム拡張機能を使用して参照データソースを追加できます (参照番号 224810)。</span><span class="sxs-lookup"><span data-stu-id="b315c-107">Allow the addition of reference datasources via form extensions (Ref# 224810).</span></span>

- <span data-ttu-id="b315c-108">テーブル リレーションに固定値を設定できます (参照番号 198778)。</span><span class="sxs-lookup"><span data-stu-id="b315c-108">Allow setting a fixed value in a table relation (Ref# 198778).</span></span>

- <span data-ttu-id="b315c-109">拡張機能を使用してフォーム データソースの表示および編集メソッドを追加できます (参照番号 261093)。</span><span class="sxs-lookup"><span data-stu-id="b315c-109">Allow the addition of form datasource display and edit methods via extension (Ref# 261093).</span></span>

- <span data-ttu-id="b315c-110">SysEmailTable.sendMail から SysEmailTable.getMessageBody を抽出し、EventNotificationWorkflow.sendMail で CoC を許可して、送信前に電子メール メッセージにアクセスできます (参照番号 269551、262554)。</span><span class="sxs-lookup"><span data-stu-id="b315c-110">Allow access to email messages before sending by extracting SysEmailTable.getMessageBody from SysEmailTable.sendMail, and by allowing CoC on EventNotificationWorkflow.sendMail (Ref# 269551, 262554).</span></span>

- <span data-ttu-id="b315c-111">新しい SysWorkflowWorkItemHelper クラスを使用して、SysWorkflowWorkItem.createWorkItems で作業項目の作成に影響を与えることができます (参照番号 246996)。</span><span class="sxs-lookup"><span data-stu-id="b315c-111">Enable influencing of the creation of workitems in SysWorkflowWorkItem.createWorkItems via the new SysWorkflowWorkItemHelper class (Ref# 246996).</span></span>

- <span data-ttu-id="b315c-112">NumberSeqScope、NumberSeqDatatype、NumberSequenceTable を変更して、番号順序の拡張性を向上させます (参照番号 262867、259702、245745)。</span><span class="sxs-lookup"><span data-stu-id="b315c-112">Improve extensibility of number sequence through changes to NumberSeqScope, NumberSeqDatatype, NumberSequenceTable (Ref# 262867, 259702, 245745).</span></span>

- <span data-ttu-id="b315c-113">SysChartTitle、PowerBIControlBuild、EventNotificationBatch などのさまざまなクラスの拡張性が向上します (参照番号 280964、280963、275376)。</span><span class="sxs-lookup"><span data-stu-id="b315c-113">Improve extensibility of various classes including SysChartTitle, PowerBIControlBuild, EventNotificationBatch (Ref# 280964, 280963, 275376).</span></span>

<span data-ttu-id="b315c-114">拡張性に関するすべての機能の詳細については、[拡張機能のホーム ページ](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b315c-114">For more information about all extensibility capabilities, see the [Extensibility home page](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>
