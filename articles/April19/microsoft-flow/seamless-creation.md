---
title: PowerApps でのシームレスなフロー作成
description: モデル駆動型によるキャンバスベースのアプリケーション コンテキストでフローを作成できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 04/14/2019
ms.assetid: 6388bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 26ad87c60190a8591f6e4a303b4c71c618624218
ms.sourcegitcommit: 2a74fca6d58a1a6abe2c19cac21deae64d5fd8af
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2019
ms.locfileid: "1445273"
---
# <a name="seamless-flow-creation-in-powerapps"></a><span data-ttu-id="e3d8c-103">PowerApps でのシームレスなフロー作成</span><span class="sxs-lookup"><span data-stu-id="e3d8c-103">Seamless flow creation in PowerApps</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="e3d8c-104">Microsoft Flow は、モデル駆動型によるキャンバスベースの PowerApps でロジックを設計できる、優れたツールです。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-104">Microsoft Flow is the best way to design logic for your model-driven and canvas-based PowerApps.</span></span> <span data-ttu-id="e3d8c-105">コードを記述する代わりに、ポイントアンドクリックのフロー デザイナーを使ってビジネス ロジックを構築することができます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-105">Instead of writing code, you can use the point-and-click flow designer to build out your business logic.</span></span> <span data-ttu-id="e3d8c-106">ユーザーは、ボタン、アクション、データ入力を使って、フローをアプリ内で簡単に実行できます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-106">Easily run flows in your app with buttons, actions, and data inputs.</span></span> <span data-ttu-id="e3d8c-107">これらのフローは、一方向で実行することもできますし、アプリにデータを返してユーザーに情報を表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-107">These flows can fire-and-forget, or return data back to your app to display information to the user.</span></span>

<span data-ttu-id="e3d8c-108">さらに、ビジネス プロセス フローを使用すれば、ユーザーを常に追跡し、複数のステージで入力されたデータの一貫性を維持することができます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-108">Moreover, with business process flows, you can keep users on track and ensure data consistency regardless of where it's entered across multiple stages.</span></span> <span data-ttu-id="e3d8c-109">たとえば、すべてのユーザーに同じ方法で顧客サービス要求を処理させるフローを作成することもできますし、注文の送信前に承認を要求するフローを作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-109">For example, you can create a flow to have everyone handle customer service requests the same way, or to require approvals before submitting an order.</span></span>

<span data-ttu-id="e3d8c-110">Microsoft Flow では、ビジネス プロセス フローとインスタント フローの両方を、モデル駆動型によるキャンバスベースのアプリケーション コンテキストで構築できる、シームレスなオーサリング エクスペリエンスを実現しています。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-110">Now, we are providing a seamless authoring experience for building flows—both business process flows and instant flows—in the context of model-driven and canvas-based apps.</span></span> <span data-ttu-id="e3d8c-111">ユーザーは、コマンド バーで **フロー** を選択するだけで、PowerApps Studio 内から高度なフロー作成を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-111">All you do is select **Flow** in the command bar and you’ll have the full flow authoring experience right inside the PowerApps studio.</span></span> <span data-ttu-id="e3d8c-112">フロー作成をいったんやめても、アプリのコンテキスト内なので、簡単に作成を続行することができます。より本格的にフローを設計したい場合は、新しいタブを開いてフル機能のフロー デザイナーで作業することもできます。もちろん、それまでの作業内容は維持されます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-112">Once you’re done working on your flow, you’re still in context of your app, so you can easily continue working on building it out. If you ever want more real-estate to design your flows, you can pop out to a new tab to work in the full Flow designer, and your flow will be preserved.</span></span>

<span data-ttu-id="e3d8c-113">![PowerApps キャンバス スタジオ内での作成](media/SeamlessFlowcreationinPowerApps-1.png "PowerApps キャンバス スタジオ内での作成")</span><span class="sxs-lookup"><span data-stu-id="e3d8c-113">![Create inside PowerApps canvas studio](media/SeamlessFlowcreationinPowerApps-1.png "Create inside PowerApps canvas studio")</span></span>

<span data-ttu-id="e3d8c-114">作成のエクスペリエンスが改善されるだけでなく、機能面でも重要な改善点がいくつかあります。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-114">Beyond just improving the authoring experience, there are these key, functional improvements:</span></span>

- <span data-ttu-id="e3d8c-115">**複雑なデータ型を簡単に定義できる**: インスタント フローを使用して、PowerApps で作成されたアプリにデータを返す場合に、JSON 形式を理解していなくても、複雑なデータ型 (ネストしたテーブルやレコードなど) を簡単に定義できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-115">**Easily define complex data types**: When you use an instant flow to return data to a PowerApps-created app, you can now easily define complex data types (such as nested tables and records), rather than having to understand JSON format.</span></span>
- <span data-ttu-id="e3d8c-116">**フローをデータ ギャラリーにバインドできる**: フローをオンデマンドで呼び出すだけでなく、フローを使用してギャラリー内のデータを追加することも可能になりました。たとえば、SQL でストアド プロシージャを呼び出して、そのデータを返すこともできます。</span><span class="sxs-lookup"><span data-stu-id="e3d8c-116">**Bind flows to a data gallery**: In addition to invoking a flow on demand, you can now use flows to populate data in a gallery—for example, by calling a stored procedure in SQL and returning that data.</span></span>
