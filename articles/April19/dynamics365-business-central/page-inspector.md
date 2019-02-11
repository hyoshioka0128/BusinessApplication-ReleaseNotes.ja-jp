---
title: ページの検査
description: ページおよびページの部分を調べて、データの問題をトラブルシューティングしたり、基になっているデータ モデルを理解したりします。 ページ インスペクターは、現在のレコード、フィルター、およびページに影響を与えている拡張機能についての情報を明らかにします。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: 00ff20da44081218a0560d278f98afbfb64e8e80
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210295"
---
# <a name="page-inspection"></a><span data-ttu-id="8cbd7-104">ページの検査</span><span class="sxs-lookup"><span data-stu-id="8cbd7-104">Page inspection</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="8cbd7-105">ビジネス データまたは機能構成のエラーのトラブルシューティングを行うときは、多くの場合、ページに表示されているもの以外の追加レベルの分析情報が必要です。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-105">Troubleshooting errors in business data or feature configuration often requires an additional level of insight beyond what is shown on the page.</span></span> <span data-ttu-id="8cbd7-106">パワー ユーザーとサポート スタッフは、ページまたはページ内の部分を調べて、ページに表示されていないフィールドなど、現在のレコードの内容全体を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-106">Power users and support staff can now inspect any page or the page parts within a page, revealing the entire contents of the current record including fields that are not shown on the page.</span></span>

<!--
> ![Inspecting a Sales Order factbox](media/inspect-factbox.png "The page inspection pane alongside a sales order where one of the factboxes is being inspected.")
-->

## <a name="getting-started"></a><span data-ttu-id="8cbd7-107">作業の開始</span><span class="sxs-lookup"><span data-stu-id="8cbd7-107">Getting started</span></span>
<span data-ttu-id="8cbd7-108">デスクトップ ブラウザーまたは Windows デスクトップ アプリで現在表示しているページの検査を開始するには、トップ メニューから**検査**を選択するか、またはキーボード ショートカット **Ctrl + Alt + F1** を使用します。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-108">Start inspecting the page you are currently viewing in the desktop browser or Windows desktop app by choosing  **Inspect** from the top menu or use the **Ctrl+Alt+F1** keyboard shortcut.</span></span>

## <a name="an-evolution-of-the-toolset"></a><span data-ttu-id="8cbd7-109">ツールセットの進化</span><span class="sxs-lookup"><span data-stu-id="8cbd7-109">An evolution of the toolset</span></span>
<span data-ttu-id="8cbd7-110">Microsoft Dynamics NAV での前身 (一般的に "このページについて" と呼ばれていたもの) とは異なり、ページの検査は、イマーシブで高度にインタラクティブであり、ポイント アンド クリック操作によって、ページ自体の操作を中断することなくページの横に情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-110">Unlike its predecessor in Microsoft Dynamics NAV, commonly known as "About this Page," page inspection is an immersive and highly interactive, point-and-click experience that conveniently displays information alongside your page without interrupting how you interact with the page itself.</span></span> <span data-ttu-id="8cbd7-111">検査対象についての正確な情報の明確さが向上したこととは別に、ページや基になっているテーブルに影響を与えている拡張機能を表示し、それらの拡張機能によって追加されたページやフィールドを知ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-111">Apart from the improved clarity on precisely what you are inspecting, you can now view which extensions affect the page and/or underlying table, and learn which pages and fields were added by those extensions.</span></span>

## <a name="feature-highlights"></a><span data-ttu-id="8cbd7-112">主な機能</span><span class="sxs-lookup"><span data-stu-id="8cbd7-112">Feature highlights</span></span>
<span data-ttu-id="8cbd7-113">調べているページに応じて、以下の一部または全部が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-113">Depending on the page you are inspecting, some or all of the following is displayed:</span></span>

- <span data-ttu-id="8cbd7-114">ページまたはページの部分の名前と識別子。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-114">The page or page part name and identifier.</span></span>
- <span data-ttu-id="8cbd7-115">基になっているテーブルの名前と識別子。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-115">The underlying table name and identifier.</span></span>
- <span data-ttu-id="8cbd7-116">キャプション、値、フィールド識別子、主キー インジケーター、およびそれらを追加した拡張機能など、現在のレコードのテーブル フィールドのセット全体。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-116">The entire set of table fields for the current record, including their caption, value, field identifier, primary key indicator, and which extension has introduced them.</span></span>
- <span data-ttu-id="8cbd7-117">ページまたは基になっているテーブルを拡張する拡張機能。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-117">Which extensions extend the page or the underlying table.</span></span>
- <span data-ttu-id="8cbd7-118">テーブルに現在適用されているフィルター。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-118">Which filters are currently applied to the table.</span></span>


<!--
 
## Try it now
Inspect the full record data for one of the products or services that you offer, by signing in to your online environment at https://businesscentral.dynamics.com/?page=30

## Resources
Inspecting pages
FAQ about inspecting pages
Keyboard Shortcuts

-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="8cbd7-119">フィードバック</span><span class="sxs-lookup"><span data-stu-id="8cbd7-119">Tell us what you think</span></span>
<span data-ttu-id="8cbd7-120">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-120">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="8cbd7-121">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="8cbd7-121">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
