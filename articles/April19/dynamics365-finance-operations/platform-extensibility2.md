---
title: プラットフォーム拡張性の機能強化ウェーブ 2
description: プラットフォーム拡張性の機能強化ウェーブ 2
author: ChrisGarty
manager: AnnBe
ms.date: 02/25/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: cgarty
audience: developer, customizer
ms.openlocfilehash: b5f080c19c7d62aa004fb4e9dad962fffc2ef5bd
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225244"
---
# <a name="platform-extensibility-enhancements-wave-2"></a><span data-ttu-id="afb22-103">プラットフォーム拡張性の機能強化ウェーブ 2</span><span class="sxs-lookup"><span data-stu-id="afb22-103">Platform extensibility enhancements wave 2</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="afb22-104">プラットフォーム更新プログラム 25 で強化された拡張性機能:</span><span class="sxs-lookup"><span data-stu-id="afb22-104">Enhanced extensibility capabilities in Platform update 25:</span></span>

- <span data-ttu-id="afb22-105">InternalUseOnlyAttribute メソッドのコマンド チェーン (CoC) をエラーから警告にダウングレードします (参照番号 289075)。</span><span class="sxs-lookup"><span data-stu-id="afb22-105">Downgrade Chain of Command (CoC) on an InternalUseOnlyAttribute method from an error to a warning (Ref# 289075).</span></span> <span data-ttu-id="afb22-106">InternalUseOnlyAttribute の詳細については、「[拡張性に関するよく寄せられる質問](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/app-sealing-faq)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="afb22-106">For more information about the InternalUseOnlyAttribute, see the [Extensibility FAQ](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/app-sealing-faq).</span></span>

- <span data-ttu-id="afb22-107">拡張機能を使用してクエリに 'order by' フィールドを追加できます (参照番号 198811)。</span><span class="sxs-lookup"><span data-stu-id="afb22-107">Enable adding 'order by' fields into a query via extension (Ref# 198811).</span></span>

- <span data-ttu-id="afb22-108">拡張機能を使用して追加された兄弟フォーム コントロールのスタイル プロパティ値の既定値の設定が向上します (参照番号 198824)。</span><span class="sxs-lookup"><span data-stu-id="afb22-108">Improve defaulting of style property values on sibling form controls added via extension (Ref# 198824).</span></span>

- <span data-ttu-id="afb22-109">EDT の DisplayHeight を変更できます (参照番号 247167)。</span><span class="sxs-lookup"><span data-stu-id="afb22-109">Allow changing DisplayHeight on EDTs (Ref# 247167).</span></span>

- <span data-ttu-id="afb22-110">formHasMethod 関数が ExtentionOf クラスのメソッドに対して機能するようになります (参照番号 199220)。</span><span class="sxs-lookup"><span data-stu-id="afb22-110">Enable function formHasMethod to work for methods in an ExtentionOf class (Ref# 199220).</span></span>

- <span data-ttu-id="afb22-111">CoS を介してカスタム ボタンを追加できるように、SysSystemDefinedButtons.addButtonsToActionPane メソッドを protected に調整します (参照番号 272356)。</span><span class="sxs-lookup"><span data-stu-id="afb22-111">Adjust the SysSystemDefinedButtons.addButtonsToActionPane method to protected to allow addition of custom buttons via CoC (Ref# 272356).</span></span>

- <span data-ttu-id="afb22-112">CoC を介した重要部分のターゲット設定を可能にするために、NumberSequenceDetails.updateFormat、EventContextDrillDown.drillDown、SysEmailTable.showEmailBody からメソッドを抽出しました (参照番号 270780、278611、269568)。</span><span class="sxs-lookup"><span data-stu-id="afb22-112">Extracted methods from NumberSequenceDetails.updateFormat, EventContextDrillDown.drillDown, SysEmailTable.showEmailBody to allow targeting of key pieces via CoC (Ref# 270780, 278611, 269568).</span></span>

- <span data-ttu-id="afb22-113">ワークフロー電子メールの書式設定を可能にするために、finalFormatMessageText デリゲートを WorkflowDocumentField.substitutePlaceholderAsUser に追加します (参照番号 262556)。</span><span class="sxs-lookup"><span data-stu-id="afb22-113">Add finalFormatMessageText delegate to WorkflowDocumentField.substitutePlaceholderAsUser to allow formatting of workflow emails (Ref# 262556).</span></span>

- <span data-ttu-id="afb22-114">CoC ターゲット設定を可能にするために、NumberSeqScope.getParameterValue を protected に変更します (参照番号 262866)。</span><span class="sxs-lookup"><span data-stu-id="afb22-114">Change NumberSeqScope.getParameterValue to protected to allow for CoC targeting (Ref# 262866).</span></span>

- <span data-ttu-id="afb22-115">拡張性を提供するために SysPickList にクラス変数 parmTxt を追加します (参照番号 235796)。</span><span class="sxs-lookup"><span data-stu-id="afb22-115">Add class variable parmTxt to SysPickList to provide extensibility (Ref# 235796).</span></span>

- <span data-ttu-id="afb22-116">CoC ターゲット設定を可能にするために、WorkflowDocIsQueueEnabledAttribute から InternalUseOnlyAttribute を削除します (参照番号 264119)。</span><span class="sxs-lookup"><span data-stu-id="afb22-116">Remove InternalUseOnlyAttribute from WorkflowDocIsQueueEnabledAttribute to allow for CoC targeting (Ref# 264119).</span></span>

- <span data-ttu-id="afb22-117">SysEmailDistributor に initializeMessageBuilder メソッドを追加して、送信前に電子メールにアクセスできるようにします (参照番号 256434)。</span><span class="sxs-lookup"><span data-stu-id="afb22-117">Add initializeMessageBuilder method to SysEmailDistributor to provide access to emails prior to sending (Ref# 256434).</span></span>

<span data-ttu-id="afb22-118">拡張性に関するすべての機能の詳細については、[拡張機能のホーム ページ](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="afb22-118">For more information about all extensibility capabilities, see the [Extensibility home page](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).</span></span>
