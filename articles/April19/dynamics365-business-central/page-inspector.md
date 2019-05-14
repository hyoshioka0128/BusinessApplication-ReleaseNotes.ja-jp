---
title: ページの検査 (以前の「このページについて」)
description: ページおよびページの部分を調べて、データの問題をトラブルシューティングしたり、基になっているデータ モデルを理解したりします。 ページ インスペクターは、現在のレコード、フィルター、およびページに影響を与えている拡張機能についての情報を明らかにします。 以前は「このページについて」、それより前は「ズーム」と呼ばれていました。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: developer, end user, customizer
ms.openlocfilehash: d8af1ee4d372faed46e51a13db6f51d4c6ffd275
ms.sourcegitcommit: d38444f318edcbde1d3c922cbf676072b87e5fbb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/02/2019
ms.locfileid: "1447186"
---
# <a name="page-inspection-formerly-about-this-page"></a><span data-ttu-id="4b0ff-105">ページの検査 (以前の*このページについて*)</span><span class="sxs-lookup"><span data-stu-id="4b0ff-105">Page inspection (formerly *About This Page*)</span></span>
<span data-ttu-id="4b0ff-106">ビジネス データまたは機能構成のエラーのトラブルシューティングを行うときは、多くの場合、ページに表示されているもの以外の追加レベルの分析情報が必要です。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-106">Troubleshooting errors in business data or feature configuration often requires an additional level of insight beyond what is shown on the page.</span></span> <span data-ttu-id="4b0ff-107">パワー ユーザーとサポート スタッフは、ページ (またはページ内の部分) を調べて、ページに表示されていないフィールドなど、現在のレコードの内容全体を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-107">Power users and support staff can now inspect any page (or the page parts within a page), revealing the entire contents of the current record including fields that are not shown on the page.</span></span>

<span data-ttu-id="4b0ff-108">![アイテム情報ボックスの検査](media/page-inspector.png "情報ボックスの 1 つが検査されているアイテム カードの横にあるページの検査ウィンドウ")</span><span class="sxs-lookup"><span data-stu-id="4b0ff-108">![Inspecting an Item factbox](media/page-inspector.png "The page inspection pane alongside an Item card where one of the factboxes is being inspected")</span></span>

## <a name="getting-started"></a><span data-ttu-id="4b0ff-109">作業の開始</span><span class="sxs-lookup"><span data-stu-id="4b0ff-109">Getting started</span></span>
<span data-ttu-id="4b0ff-110">デスクトップ ブラウザーまたは Windows デスクトップ アプリで現在表示しているページの検査を開始するには、トップ メニューから**検査**を選択するか、またはキーボード ショートカット **Ctrl + Alt + F1** を使用します。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-110">Start inspecting the page you are currently viewing in the desktop browser or Windows desktop app by choosing  **Inspect** from the top menu or use the **Ctrl+Alt+F1** keyboard shortcut.</span></span>

## <a name="an-evolution-of-the-toolset"></a><span data-ttu-id="4b0ff-111">ツールセットの進化</span><span class="sxs-lookup"><span data-stu-id="4b0ff-111">An evolution of the toolset</span></span>
<span data-ttu-id="4b0ff-112">Microsoft Dynamics NAV での前身 (一般的に "このページについて" と呼ばれていたもの) とは異なり、ページの検査は、イマーシブで高度にインタラクティブであり、ポイント アンド クリック操作によって、ページ自体の操作を中断することなくページの横に情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-112">Unlike its predecessor in Microsoft Dynamics NAV, commonly known as "About this Page," page inspection is an immersive and highly interactive, point-and-click experience that conveniently displays information alongside your page without interrupting how you interact with the page itself.</span></span> <span data-ttu-id="4b0ff-113">検査対象についての正確な情報の明確さが向上したこととは別に、ページや基になっているテーブルに影響を与えている拡張機能を表示し、それらの拡張機能によって追加されたページやフィールドを知ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-113">Apart from the improved clarity on precisely what you are inspecting, you can now view which extensions affect the page and/or underlying table, and learn which pages and fields were added by those extensions.</span></span>

## <a name="feature-highlights"></a><span data-ttu-id="4b0ff-114">主な機能</span><span class="sxs-lookup"><span data-stu-id="4b0ff-114">Feature highlights</span></span>
<span data-ttu-id="4b0ff-115">調べているページに応じて、以下の一部または全部が表示されます。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-115">Depending on the page you are inspecting, some or all of the following is displayed:</span></span>

- <span data-ttu-id="4b0ff-116">ページまたはページの部分の名前と識別子。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-116">The page or page part name and identifier.</span></span>
- <span data-ttu-id="4b0ff-117">基になっているテーブルの名前と識別子。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-117">The underlying table name and identifier.</span></span>
- <span data-ttu-id="4b0ff-118">キャプション、値、フィールド識別子、主キー インジケーター、およびそれらを追加した拡張機能など、現在のレコードのテーブル フィールドのセット全体。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-118">The entire set of table fields for the current record, including their caption, value, field identifier, primary key indicator, and which extension has introduced them.</span></span>
- <span data-ttu-id="4b0ff-119">ページまたは基になっているテーブルを拡張する拡張機能。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-119">Which extensions extend the page or the underlying table.</span></span>
- <span data-ttu-id="4b0ff-120">テーブルに現在適用されているフィルター。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-120">Which filters are currently applied to the table.</span></span>


## <a name="try-it-now"></a><span data-ttu-id="4b0ff-121">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="4b0ff-121">Try it now</span></span>
<span data-ttu-id="4b0ff-122">[https://businesscentral.dynamics.com/?page=30](https://businesscentral.dynamics.com/?page=30) のオンライン環境にサインインして、提供している品目の 1 つに関する全レコード データを調べます。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-122">Inspect the full record data for one of the items that you offer, by signing in to your online environment at [https://businesscentral.dynamics.com/?page=30](https://businesscentral.dynamics.com/?page=30).</span></span>

## <a name="resources"></a><span data-ttu-id="4b0ff-123">リソース</span><span class="sxs-lookup"><span data-stu-id="4b0ff-123">Resources</span></span>
[<span data-ttu-id="4b0ff-124">ページの検査</span><span class="sxs-lookup"><span data-stu-id="4b0ff-124">Inspecting pages</span></span>](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-inspecting-pages)<br>  
[<span data-ttu-id="4b0ff-125">キーボード ショートカット</span><span class="sxs-lookup"><span data-stu-id="4b0ff-125">Keyboard Shortcuts</span></span>](https://aka.ms/bckeys)  

## <a name="tell-us-what-you-think"></a><span data-ttu-id="4b0ff-126">フィードバック</span><span class="sxs-lookup"><span data-stu-id="4b0ff-126">Tell us what you think</span></span>
<span data-ttu-id="4b0ff-127">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-127">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="4b0ff-128">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="4b0ff-128">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
