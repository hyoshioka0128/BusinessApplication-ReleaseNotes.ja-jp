---
title: 仕入先請求書のワークフローの状態を回復不能から下書きにリセットする
description: 仕入先請求書が回復不能の場合にそのワークフローの状態をリセットする
author: aprilolson
ms.date: 06/19/2019
ms.reviewer: sericks
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: db0f3366340d2bccfc91dac93435a35f739ce41e
ms.sourcegitcommit: d17c18839d36c91f1e83f4942a43128c4563ec9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1691057"
---
# <a name="reset-workflow-status-for-vendor-invoices-from-unrecoverable-to-draft"></a><span data-ttu-id="b5b4e-103">仕入先請求書のワークフローの状態を回復不能から下書きにリセットする</span><span class="sxs-lookup"><span data-stu-id="b5b4e-103">Reset workflow status for vendor invoices from Unrecoverable to Draft</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="b5b4e-104">システムが中断された場合、ドキュメントは*回復不能*状態になることがあります。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-104">In the case of a system interruption, documents can get into the status of *Unrecoverable*.</span></span> <span data-ttu-id="b5b4e-105">*回復不能*の状態の仕入先請求書が表示される場合、ユーザーはサポートに連絡する必要なしにドキュメントの状態を*下書き*にリセットできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-105">If users see vendor invoices with a status of *Unrecoverable*, they can now reset the document status to *Draft* without having to make a call to Support.</span></span> 

<span data-ttu-id="b5b4e-106">**ワークフロー履歴**ページを使用して、ワークフローの状態を*下書き*にリセットできます。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-106">You can use the **Workflow history** page to reset the workflow status to *Draft*.</span></span> <span data-ttu-id="b5b4e-107">このページは、**仕入先請求書**ページから、または**共通** > **照会** > **ワークフロー**に移動して開くことができます。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-107">You can open this page from the **Vendor invoice** page or by going to **Common** > **Inquires** > **Workflow**.</span></span> <span data-ttu-id="b5b4e-108">ワークフローの状態を*下書き*にリセットするには、**取り消し**を選択します。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-108">To reset the workflow status to *Draft*, select **Recall**.</span></span> <span data-ttu-id="b5b4e-109">**仕入先請求書**または**保留中の仕入先請求書**ページで**取り消し**アクションを選択することでワークフローの状態を**下書き**にリセットすることもできます。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-109">You can also reset the workflow status to **Draft** by selecting the **Recall** action on the **Vendor invoice** or **Pending vendor invoices** page.</span></span> <span data-ttu-id="b5b4e-110">ワークフローの状態が*下書き*にリセットされると、**仕入先請求書**ページで編集可能になります。</span><span class="sxs-lookup"><span data-stu-id="b5b4e-110">After the workflow status is reset to *Draft*, it becomes available for editing on the **Vendor invoice** page.</span></span>
