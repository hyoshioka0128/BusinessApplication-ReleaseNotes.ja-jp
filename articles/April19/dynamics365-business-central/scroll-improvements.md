---
title: リストのスクロールの改善
description: リストの行を読み込む、スクロールする、ナビゲートするときのエクスペリエンスとパフォーマンスを改善しました。
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: mikebc
audience: end user
ms.openlocfilehash: 67d226d8c57034455b7381998406aac3176fa98a
ms.sourcegitcommit: d38444f318edcbde1d3c922cbf676072b87e5fbb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/02/2019
ms.locfileid: "1447175"
---
#  <a name="improvements-to-scrolling-in-lists"></a><span data-ttu-id="5545f-103">リストのスクロールの改善</span><span class="sxs-lookup"><span data-stu-id="5545f-103">Improvements to scrolling in lists</span></span>
<span data-ttu-id="5545f-104">グリッド パフォーマンス、スクロールおよびキーボード ナビゲーションが向上した Dynamics 365 Business Central のリストで効率的に作業できます。</span><span class="sxs-lookup"><span data-stu-id="5545f-104">Work efficiently in lists in Dynamics 365 Business Central with improved grid performance, scrolling, and keyboard navigation.</span></span>

<span data-ttu-id="5545f-105">バックオフィスのインフォメーション ワーカーは、傾向や異常の分析、データの入力や変更など、リストの操作に多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="5545f-105">Back-office information workers spend significant time working with lists: analyzing trends and anomalies or entering and modifying data.</span></span> <span data-ttu-id="5545f-106">業務データベースが大きくなっても、エクスペリエンスはパフォーマンスを維持し、ユーザーが効率的に作業を続けられるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="5545f-106">As the business database grows, the experience must remain performant and enable users to continue working efficiently.</span></span> 

## <a name="improved-scrolling-and-load-time"></a><span data-ttu-id="5545f-107">スクロールと読み込み時間の向上</span><span class="sxs-lookup"><span data-stu-id="5545f-107">Improved scrolling and load time</span></span>
<span data-ttu-id="5545f-108">リスト内の行の表示方法とデータのフェッチ方法を修正したことで、リストが初めて表示されるまでの時間が短縮され、セル間の移動がスムーズになりました。</span><span class="sxs-lookup"><span data-stu-id="5545f-108">We've rewritten how rows are displayed in a list and how they fetch data, improving the initial display time as well as the snappiness of navigating across cells.</span></span> <span data-ttu-id="5545f-109">ユーザーはキーボードやスクロール バーを使用してリスト内のどこにでも制約なくスクロールできます。「行をさらにフェッチする」のメッセージにより中断が発生することはありません。</span><span class="sxs-lookup"><span data-stu-id="5545f-109">Users can now scroll unhindered to any position in the list using the keyboard or scroll bar, without ever pausing at the "fetching more rows" message.</span></span> <span data-ttu-id="5545f-110">行を快適に読むことができるペースでスクロールすると、スクロール エクスペリエンスはシームレスになります。</span><span class="sxs-lookup"><span data-stu-id="5545f-110">The scrolling experience is seamless when scrolling at a pace where rows can be comfortably read.</span></span> <span data-ttu-id="5545f-111">行は常にオンデマンドで読み込まれ、リストの大きさによってエクスペリエンスが低下しないようにします。</span><span class="sxs-lookup"><span data-stu-id="5545f-111">Rows are always loaded on demand to ensure that larger lists do not degrade the experience.</span></span> <span data-ttu-id="5545f-112">Business Central の 2019 年 4 月の更新プログラムでは、レンガとして表示されたレコードに変更はありません。</span><span class="sxs-lookup"><span data-stu-id="5545f-112">In the April '19 update to Business Central, there is no change to records displayed as bricks.</span></span>

<span data-ttu-id="5545f-113">![リストをゆっくりスクロールしてからすばやくスクロールする](media/scroll-experience2.gif "長いリストをゆっくりスクロールしてからすばやくスクロールする図")</span><span class="sxs-lookup"><span data-stu-id="5545f-113">![Scrolling slowly and then quickly through a list](media/scroll-experience2.gif "Visualization of slow and then fast scroll through a long list of rows")</span></span>

## <a name="improved-keyboard-navigation"></a><span data-ttu-id="5545f-114">キーボード ナビゲーションの向上</span><span class="sxs-lookup"><span data-stu-id="5545f-114">Improved keyboard navigation</span></span>
<span data-ttu-id="5545f-115">キーボードのカーソル キーを使用した次の行までの上下移動がスムーズになり、キーを押したまま制約なしにナビゲートすることもできます。</span><span class="sxs-lookup"><span data-stu-id="5545f-115">Using the keyboard cursor keys to go up or down to the next row is snappy and you can also hold down the keys to navigate unhindered.</span></span> <span data-ttu-id="5545f-116">複数の行を選択すると、遅延が大幅に短縮されます。</span><span class="sxs-lookup"><span data-stu-id="5545f-116">Selecting multiple rows has significantly less delay.</span></span>

## <a name="try-it-now"></a><span data-ttu-id="5545f-117">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="5545f-117">Try it now</span></span>
<span data-ttu-id="5545f-118">[https://businesscentral.dynamics.com/?page=25](https://businesscentral.dynamics.com/?page=25) のオンライン環境にログインして、顧客元帳のエントリなど、より大きなリストの操作を体験してください。</span><span class="sxs-lookup"><span data-stu-id="5545f-118">Experience working with larger lists, such as your customer ledger entries, by signing in to your online environment at [https://businesscentral.dynamics.com/?page=25](https://businesscentral.dynamics.com/?page=25).</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="5545f-119">フィードバック</span><span class="sxs-lookup"><span data-stu-id="5545f-119">Tell us what you think</span></span>
<span data-ttu-id="5545f-120">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="5545f-120">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="5545f-121">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="5545f-121">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
