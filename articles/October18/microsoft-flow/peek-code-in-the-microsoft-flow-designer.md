---
title: Microsoft Flow デザイナーでのコードのプレビュー
description: Microsoft Flow デザイナーでアクションの JSON コードをプレビューします
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 02/04/2019
ms.assetid: c4ffc9c8-c521-e911-a966-000d3a1d531d
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 55f39e856c798c7e8406cc2ba64680012288819c
ms.sourcegitcommit: 60c89801f3a5a65e4961c14877fb34f3752b9311
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2019
ms.locfileid: "391317"
---
# <a name="peek-code-in-the-microsoft-flow-designer"></a><span data-ttu-id="c1042-103">Microsoft Flow デザイナーでのコードのプレビュー</span><span class="sxs-lookup"><span data-stu-id="c1042-103">Peek code in the Microsoft Flow designer</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="c1042-104">多くの異なる入力がある大きなアクションを実行している場合、フローからコネクタに送信される内容を正確に理解するのが難しい場合があります。</span><span class="sxs-lookup"><span data-stu-id="c1042-104">If you have a large action with many different inputs, sometimes it can be difficult to understand exactly what will be sent to the Connector from your flow.</span></span> <span data-ttu-id="c1042-105">Flow デザイナーのすべてのトリガーとアクションの `...` メニューに、新しい**コードのプレビュー** オプションが追加されています。</span><span class="sxs-lookup"><span data-stu-id="c1042-105">We have added a new **Peek code** option in the `...` menu of all triggers and actions in the Flow designer.</span></span> 

<span data-ttu-id="c1042-106">![コードのプレビュー メニュー項目](media/peek_code_01.png "コードのプレビュー メニュー項目")</span><span class="sxs-lookup"><span data-stu-id="c1042-106">![Peek code menu item](media/peek_code_01.png "Peek code menu item")</span></span>

<span data-ttu-id="c1042-107">このオプションを選択すると、アクションの完全な JSON 表現が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c1042-107">When you select this option, you will see the full JSON representation of an action.</span></span> <span data-ttu-id="c1042-108">これには、アクションへのすべての入力 (直接入力したテキストなど) および使用されている式が含まれます。</span><span class="sxs-lookup"><span data-stu-id="c1042-108">This includes all of the inputs to the action, such as the text you entered directly, and expressions used.</span></span> <span data-ttu-id="c1042-109">たとえば、ここで式を選択して、動的コンテンツ式エディターに貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="c1042-109">For example, you can select expressions here and paste them into the Dynamic Content expression editor.</span></span> <span data-ttu-id="c1042-110">これはまた、期待するデータがフロー内に存在することを確認するための方法にもなります。</span><span class="sxs-lookup"><span data-stu-id="c1042-110">This can also give you a way to verify that exactly the data you expect is present in the flow.</span></span>

<span data-ttu-id="c1042-111">![コード プレビュー ビュー](media/peek_code_02.png "コード プレビュー ビュー")</span><span class="sxs-lookup"><span data-stu-id="c1042-111">![Peek code view](media/peek_code_02.png "Peek code view")</span></span>

<span data-ttu-id="c1042-112">通常のアクション ビューに戻るには、アクションの下部にある**完了**を選択します。</span><span class="sxs-lookup"><span data-stu-id="c1042-112">Select **Done** at the bottom of the action to return to the normal action view.</span></span>
