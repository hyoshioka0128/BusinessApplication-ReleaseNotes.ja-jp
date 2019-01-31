---
title: Microsoft Flow ボタン入力の機能拡張
description: 作成者がボタンの入力をより細かく制御できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/02/2019
ms.assetid: 537e446a-cf73-e811-a967-000d3a18c047
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 36e8aae6b6ab247e08d9d24094479470285bb094
ms.sourcegitcommit: 851bbbbeaac02e33829dfbf5f6f8e4055acf0822
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "203705"
---
# <a name="flow-button-input-enhancements"></a><span data-ttu-id="64786-103">Flow ボタン入力の機能拡張</span><span class="sxs-lookup"><span data-stu-id="64786-103">Flow button input enhancements</span></span>




<span data-ttu-id="64786-104">ボタンを 1 回タップするだけで実行できることをだれもが望む多くの反復的なタスクがあります。</span><span class="sxs-lookup"><span data-stu-id="64786-104">There are many repetitive tasks that we all wish we could run with just a tap of a button.</span></span> <span data-ttu-id="64786-105">たとえば、毎日のチーム同期に参加するよう通知するためにチームに迅速に電子メールを送信する必要がある場合や、その日はそれ以上チェックインが予定されていないことが通知された後に新しい Visual Studio Online ビルドを開始することが必要な場合があります。</span><span class="sxs-lookup"><span data-stu-id="64786-105">For example, you might need to quickly email your team to remind them to join the daily team sync, or you might want to start a new Visual Studio Online build after you've been notified that no more check-ins are planned for the day.</span></span> <span data-ttu-id="64786-106">ボタン フローを使用すると、モバイル デバイスのボタンをタップするだけでこれらのタスクやその他のタスクを実行できます。</span><span class="sxs-lookup"><span data-stu-id="64786-106">Button flows allow you to accomplish these and other tasks simply by tapping a button on your mobile device.</span></span>

<span data-ttu-id="64786-107">ボタンの初期リリースでは、ボタンはテキストのような基本的な入力を受け取ることができました。</span><span class="sxs-lookup"><span data-stu-id="64786-107">With the initial release of buttons, a button could receive basic input like text.</span></span> <span data-ttu-id="64786-108">しかし、[このアイデア](https://powerusers.microsoft.com/t5/Flow-Ideas/Create-multiple-input-types-for-buttons/idi-p/33695)でカバーされているように、充実したデータをボタン フローに渡すことが求められてきました。</span><span class="sxs-lookup"><span data-stu-id="64786-108">However, as covered by [this idea](https://powerusers.microsoft.com/t5/Flow-Ideas/Create-multiple-input-types-for-buttons/idi-p/33695), you have asked to be able to pass richer data to button flows.</span></span> <span data-ttu-id="64786-109">これに対応して、ボタン フローに以下のすべての種類のデータを要求できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="64786-109">We've listened, and now you can ask for all the following types of data for a button flow:</span></span>

- <span data-ttu-id="64786-110">テキスト</span><span class="sxs-lookup"><span data-stu-id="64786-110">Text</span></span>
- <span data-ttu-id="64786-111">ドロップダウン (ラジオ ボタンなど)</span><span class="sxs-lookup"><span data-stu-id="64786-111">Drop-downs (like radio buttons)</span></span>
- <span data-ttu-id="64786-112">電子メール アドレス</span><span class="sxs-lookup"><span data-stu-id="64786-112">Email address</span></span>
- <span data-ttu-id="64786-113">ファイル (携帯電話上の写真など)</span><span class="sxs-lookup"><span data-stu-id="64786-113">File (for example, a photo on your phone)</span></span>
- <span data-ttu-id="64786-114">[はい] または [いいえ] のチェック ボックス</span><span class="sxs-lookup"><span data-stu-id="64786-114">Yes or No check box</span></span>
- <span data-ttu-id="64786-115">数値</span><span class="sxs-lookup"><span data-stu-id="64786-115">Number</span></span>
- <span data-ttu-id="64786-116">日付 (カレンダー ピッカー付き)</span><span class="sxs-lookup"><span data-stu-id="64786-116">Date (with a calendar picker)</span></span>

<span data-ttu-id="64786-117">![入力の追加](media/flow-button-enhancements-1.png "入力の追加")</span><span class="sxs-lookup"><span data-stu-id="64786-117">![Add an input](media/flow-button-enhancements-1.png "Add an input")</span></span>

<span data-ttu-id="64786-118">さらに、一部の入力を必須として指定し、他の入力を省略可能として指定することができます。</span><span class="sxs-lookup"><span data-stu-id="64786-118">Additionally, you might want to designate some inputs as required and others as optional.</span></span> <span data-ttu-id="64786-119">これは各入力フィールドのアクション メニュー (右側にある **...** ボタン) から行うことができます。</span><span class="sxs-lookup"><span data-stu-id="64786-119">That's now possible from the action menu (the **...** button at the right side) on each input field.</span></span> <span data-ttu-id="64786-120">ボタンあたり 5 入力の制限も引き上げました。</span><span class="sxs-lookup"><span data-stu-id="64786-120">We have also raised the limit of five inputs per button.</span></span>

<span data-ttu-id="64786-121">![入力を省略可能にする](media/flow-button-enhancements-2.png "入力を省略可能にする")</span><span class="sxs-lookup"><span data-stu-id="64786-121">![Make input optional](media/flow-button-enhancements-2.png "Make input optional")</span></span>

