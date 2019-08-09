---
title: ビジネス プロセス フロー内のカスタム コントロール
description: ビジネス プロセス フローでは、豊富なデータのビジュアル化のためのカスタム コントロールがサポートされます
author: KaranSr
ms.reviewer: mkaur
ms.date: 06/26/2019
ms.assetid: 4587bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: karansr
audience: Power user
ms.openlocfilehash: ade2b4e15474b8149478eff68ec93532c4fec355
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756767"
---
# <a name="custom-controls-in-business-process-flows-public-preview"></a><span data-ttu-id="c5502-103">ビジネス プロセス フロー内のカスタム コントロール (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="c5502-103">Custom controls in business process flows (Public Preview)</span></span>

<span data-ttu-id="c5502-104">ビジネス プロセス フローは、ステージとステップの形式で作業を行う手順をガイドする一種のフローです。</span><span class="sxs-lookup"><span data-stu-id="c5502-104">Business process flows are a type of flow that provides a guided way to get work done in the form of stages and steps.</span></span> <span data-ttu-id="c5502-105">ステージは、ユーザーがプロセスのどこにいるかを示します。</span><span class="sxs-lookup"><span data-stu-id="c5502-105">Stages tell users where they are in the process.</span></span> <span data-ttu-id="c5502-106">これらの各ステージでのデータは、Common Data Service のフィールドにバインドされており、これまでは、フィールドの種類 (テキスト ボックス、ドロップダウン リストなど) の既定のビジュアル化だけが許可されていました。</span><span class="sxs-lookup"><span data-stu-id="c5502-106">Data on each of these stages is bound to fields in Common Data Service, and until now, only allowed for default visualizations of the field type (text boxes, drop-down lists, and so on.)</span></span>

<span data-ttu-id="c5502-107">マイクロソフトでは、開発者がこの機能の使用を開始できるようにするテクニカル プレビューを発表しています。</span><span class="sxs-lookup"><span data-stu-id="c5502-107">We are announcing a technical preview that allows developers to get started with this feature.</span></span> <span data-ttu-id="c5502-108">これで、開発者はカスタム コントロールを使用して、スライダー、放射状ノブ、LinkedIn コントロールなどの豊富なビジュアル化をフロー ステップに追加し、ビジネス プロセスのユーザーに魅力的なエクスペリエンスを提供できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c5502-108">Now, developers will be able to use custom controls to add rich visualizations (such as sliders, radial knobs, the LinkedIn control, and more) to flow steps and deliver engaging experiences to users of your business process.</span></span> <span data-ttu-id="c5502-109">このプレビュー バージョンでは、次の方法でこれを設定できます。</span><span class="sxs-lookup"><span data-stu-id="c5502-109">In this version of the preview, you can set this up by:</span></span>

1. <span data-ttu-id="c5502-110">関連するエンティティ フォームでのカスタム コントロールの構成。</span><span class="sxs-lookup"><span data-stu-id="c5502-110">Configuring custom controls on a related entity form.</span></span>
1. <span data-ttu-id="c5502-111">フォーム XML の生成とエクスポート。</span><span class="sxs-lookup"><span data-stu-id="c5502-111">Generating and exporting the form XML.</span></span>
1. <span data-ttu-id="c5502-112">関連エンティティ フォームからフォーム XML へのカスタム コントロール構成のコピー。</span><span class="sxs-lookup"><span data-stu-id="c5502-112">Copying custom control configurations to the form XML from the related entity form.</span></span>
1. <span data-ttu-id="c5502-113">Common Data Service へのカスタマイズのインポート。</span><span class="sxs-lookup"><span data-stu-id="c5502-113">Importing our customizations back into Common Data Service.</span></span>

<span data-ttu-id="c5502-114">完了したら、モデル駆動型アプリでフローをテストし、追加したコントロールを表示できます。</span><span class="sxs-lookup"><span data-stu-id="c5502-114">Once completed, you can test your flow in a Model-driven app and you will be able to see the controls that you added.</span></span>

<span data-ttu-id="c5502-115">![カスタム コントロールの例](media/custom-controls_01.png "カスタム コントロールの例")</span><span class="sxs-lookup"><span data-stu-id="c5502-115">![Example of custom controls](media/custom-controls_01.png "Example of custom controls")</span></span>

<span data-ttu-id="c5502-116">この機能を試すには XML を使用する必要があります。現時点では技術ユーザーだけが使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="c5502-116">Trying this functionality requires working with XML—we recommend that only technical users use it at this time.</span></span> <span data-ttu-id="c5502-117">これを設定する方法の詳細については、こちらの[詳細な手順を示すチュートリアル](https://powerusers.microsoft.com/t5/Microsoft-Flow-Community-Blog/Preview-Custom-Controls-in-Business-Process-Flows/ba-p/263237)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c5502-117">Read more about how to set this up in this [detailed step-by-step walkthrough](https://powerusers.microsoft.com/t5/Microsoft-Flow-Community-Blog/Preview-Custom-Controls-in-Business-Process-Flows/ba-p/263237).</span></span>
