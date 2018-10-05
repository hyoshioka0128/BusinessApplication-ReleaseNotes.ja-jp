---
title: "グローバリゼーション - 構成可能性の強化"
description: "このトピックでは、電子レポートおよびグローバリゼーション税エンジンでの強化された構成可能性について説明します。"
author: yijialuan
manager: sshvedov
ms.date: 09/07/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: riluan
audience: Admin, developer, end-user
ms.translationtype: HT
ms.sourcegitcommit: 82ebd0def3ad9a394a1764eb77a8e2ece04f5048
ms.openlocfilehash: 34b2a3e3f30b9d6be72b7bfefb30f887661d1c04
ms.contentlocale: ja-jp
ms.lasthandoff: 09/07/2018

---

# <a name="globalization--enhanced-configurability"></a><span data-ttu-id="258c7-103">グローバリゼーション - 構成可能性の強化</span><span class="sxs-lookup"><span data-stu-id="258c7-103">Globalization – enhanced configurability</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="258c7-104">機能の構成可能性により、パートナーや顧客はコーディングしないで拡張とカスタマイズを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="258c7-104">Configurability of features lets partners and customers do extensions and customizations without coding.</span></span> <span data-ttu-id="258c7-105">構成可能性の広さと深さの両方について拡張を続けており、この領域では次の新機能を追加しました。</span><span class="sxs-lookup"><span data-stu-id="258c7-105">We continue to extend both the depth and the breadth of configurability and added the following new capabilities in this area:</span></span>

- <span data-ttu-id="258c7-106">構成の静的検証と動的パフォーマンス ルール。</span><span class="sxs-lookup"><span data-stu-id="258c7-106">Static validations and dynamic performance rules for configuration.</span></span> <span data-ttu-id="258c7-107">この機能は、パートナーまたは顧客が構成をカスタマイズするときのパフォーマンス低下を防ぎ、カスタマイズの間にユーザーにガイドを提供します。</span><span class="sxs-lookup"><span data-stu-id="258c7-107">This feature prevents performance degradation when partners or customers customize configurations and guide users while doing such customizations.</span></span>
- <span data-ttu-id="258c7-108">タスク ガイドで定義されているベースラインに対する、電子レポート書式設定実行の自動比較。Microsoft、パートナー、顧客に自動テスト機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="258c7-108">Automatic comparison of electronic reporting format executions with baselines defined in task guides, which provides us and our partners and customers with automatic test capabilities.</span></span> <span data-ttu-id="258c7-109">これらのテストの対象は、エンジニアではなくビジネス ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="258c7-109">These tests focus on business users rather than engineers.</span></span>
- <span data-ttu-id="258c7-110">電子レポートの計算式での相対パス。</span><span class="sxs-lookup"><span data-stu-id="258c7-110">Relative paths in electronic reporting formulas.</span></span> <span data-ttu-id="258c7-111">この機能は、似た構造の別のデータ エンティティまたは XML ノードに切り替える必要がある場合に、書式設定をすばやく再マップできます。</span><span class="sxs-lookup"><span data-stu-id="258c7-111">This feature allows quick remapping of the format if you need to switch to another data entity or XML node with a similar structure.</span></span>
- <span data-ttu-id="258c7-112">世界中の顧客やパートナーがローカル要件に合わせて簡単に変更できる、既成の構成可能な無料のテキスト請求書テンプレート。</span><span class="sxs-lookup"><span data-stu-id="258c7-112">Out-of-the-box configurable free text invoice templates that customers and partners around the globe can easily modify to meet their local requirements.</span></span>
- <span data-ttu-id="258c7-113">1 つの課税対象文書セットを異なるバージョンの Finance and Operations で共有できるようにする、課税対象文書からの個別のモデル マッピング。</span><span class="sxs-lookup"><span data-stu-id="258c7-113">Separated model mapping from taxable documents, so that one set of taxable documents can be shared by different Finance and Operations versions.</span></span>
- <span data-ttu-id="258c7-114">税文書の税コンポーネントを参照した税通貨の構成。</span><span class="sxs-lookup"><span data-stu-id="258c7-114">Enable configuring tax currency by lookups on the tax component in tax documents.</span></span> <span data-ttu-id="258c7-115">これは、異なる国で複数の税登録を行っている企業で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="258c7-115">This is useful for companies with multiple tax registrations in different countries.</span></span> <span data-ttu-id="258c7-116">これにより、異なる国で使用される税金で異なる通貨を使用できます。</span><span class="sxs-lookup"><span data-stu-id="258c7-116">This enables the use of different currencies for taxes that are used in different countries.</span></span>
- <span data-ttu-id="258c7-117">税計算のための線形方程式ソルバー。</span><span class="sxs-lookup"><span data-stu-id="258c7-117">Linear equations solver for tax calculation.</span></span> <span data-ttu-id="258c7-118">ユーザーが線形方程式を使用して税計算式を作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="258c7-118">This requires users to create tax calculation formulas with linear equations.</span></span> <span data-ttu-id="258c7-119">結果として、税計算のパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="258c7-119">The result will be performance improvements in tax calculation.</span></span>
- <span data-ttu-id="258c7-120">税務書類での税措置の表示を構成できます。</span><span class="sxs-lookup"><span data-stu-id="258c7-120">Enable configuring the visibility of tax measures in tax documents.</span></span> <span data-ttu-id="258c7-121">税式で使用される中間的な税措置の一部は、Dynamics 365 Finance and Operations の税務書類ページに表示する必要がありません。これらの税措置は非表示にすることができます。</span><span class="sxs-lookup"><span data-stu-id="258c7-121">Tax formulas may use some intermediate tax measures that do not need to be shown on the Tax document page in Dynamics 365 Finance and Operations, so it is possible to hide these tax measures.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="258c7-122">![税務書類での税措置の表示の構成](../../media/Configure-tax-measure-visibility.png)</span><span class="sxs-lookup"><span data-stu-id="258c7-122">![Configure the visibility of tax measures in tax documents](../../media/Configure-tax-measure-visibility.png)</span></span>

