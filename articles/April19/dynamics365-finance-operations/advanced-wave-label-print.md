---
title: 高度なウェーブ ラベル印刷
description: ''
author: Mirzaab
ms.date: 02/12/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
ms.openlocfilehash: 5cb50efd59637d4aca5e989244bcc64ec0acb7ea
ms.sourcegitcommit: 6b5a05bc2ba73d392be45ad6eb5369c6b810ebf0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "390351"
---
# <a name="advanced-wave-label-printing"></a><span data-ttu-id="9bf5b-102">高度なウェーブ ラベル印刷</span><span class="sxs-lookup"><span data-stu-id="9bf5b-102">Advanced wave label printing</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="9bf5b-103">この機能では、新しいウェーブ ステップ法の導入により、Microsoft Dynamics 365 for Finance and Operations でのラベル印刷に対する代替アプローチが提供されます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-103">This functionality offers an alternate approach to label printing in Microsoft Dynamics 365 for Finance and Operations by introducing new wave step method.</span></span> <span data-ttu-id="9bf5b-104">新しい方法では、ウェーブ実行プロセスの間にウェーブ テンプレートから直接ラベルを作成および印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-104">The new method enables creating and printing of the labels directly from the wave template during wave execution process.</span></span> <span data-ttu-id="9bf5b-105">そのため、モバイル デバイスで作業指示書が実行される前に、ラベルを使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-105">Therefore, the labels will be available before the work order is executed on the mobile device.</span></span> <span data-ttu-id="9bf5b-106">これにより、異なる方法でラベルを取り扱うのが望ましいシナリオに対応して、作業者はピッキング後だけでなくピッキング中にも必要なラベルを使用して添付できるようになります。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-106">This handles scenarios where a different approach to label handling is desirable, enabling the worker to use and attach the required labels during picking and not only after picking.</span></span>

<span data-ttu-id="9bf5b-107">この機能では、新しい機能によって印刷されるすべてのラベルに使用するために ZPL ラベル レイアウトが作成される場合に、新しいラベル レイアウト フォームが導入されます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-107">The feature introduces a new Label layout form where ZPL label layouts are created to be used for every label that is printed via the new functionality.</span></span> <span data-ttu-id="9bf5b-108">新しいラベル レイアウトは、ヘッダー、本文、フッターの 3 つのセクションに分かれており、繰り返し構造を持つラベルを印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-108">The new label layout is broken into three sections—header, body, and footer—to allow labels with repeating structure to be printed.</span></span> <span data-ttu-id="9bf5b-109">使用するラベル レイアウトをシステムに指示するラベル テンプレートは、導入される 2 番目のフォームです。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-109">Label templates, which tell the system what label layout to use, is the second form introduced.</span></span> <span data-ttu-id="9bf5b-110">ここでは、ユーザーは、ラベルを印刷するプリンターを指定したり、必要な場合は、一度に複数のプリンターでラベルを印刷したりすることもできます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-110">Here, the user can also specify which printer to print the label at, or if needed, to print labels at multiple printers at once.</span></span> <span data-ttu-id="9bf5b-111">印刷されたラベルの概要をさらに拡張するため、ラベル履歴ページが導入され、この設定で作成されたすべてのラベルの記録が表示されます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-111">To further extend the overview of printed labels, the Label history page is introduced where records of all labels created via this setup are displayed.</span></span>

<span data-ttu-id="9bf5b-112">この設定を使用すると、作業ヘッダーに基づいてラベルを印刷して並べたり、作業ヘッダーごとの切れ目ラベル、コンテナー コンテンツ ラベル、ケース ラベル、その他の類似ラベルを印刷したりできます。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-112">With this setup you can print and collate labels based on work headers, print break labels per work header, container content labels, case labels, and other similar labels.</span></span>

> [!NOTE]
> <span data-ttu-id="9bf5b-113">この機能は、ドキュメント ルーティングによる既存のラベル印刷機能に代わるものではありません。</span><span class="sxs-lookup"><span data-stu-id="9bf5b-113">This functionality does not replace existing label printing functionality via Document routing.</span></span>
