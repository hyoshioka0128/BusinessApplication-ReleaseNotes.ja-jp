---
title: OneDrive for Business の Microsoft Flow 起動パネル
description: OneDrive for Business に、フローを作成するための埋め込み Microsoft Flow エクスペリエンスが備わります
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 07/01/2019
ms.assetid: 3388bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 5a80cef12854d5486bc150033869dfeea06fff5c
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756861"
---
# <a name="onedrive-for-business-flow-launch-panel"></a><span data-ttu-id="414e2-103">OneDrive for Business フロー起動パネル</span><span class="sxs-lookup"><span data-stu-id="414e2-103">OneDrive for Business Flow launch panel</span></span>

<span data-ttu-id="414e2-104">[SharePoint のフロー起動パネル](https://flow.microsoft.com/blog/introducing-flow-launch-panel-in-sharepoint-lists-and-libraries/)と同様に、選択したファイルに対して OneDrive for Business から入力を収集するフローを実行できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="414e2-104">Similar to the [Flow Launch Panel in SharePoint](https://flow.microsoft.com/blog/introducing-flow-launch-panel-in-sharepoint-lists-and-libraries/), you can now run flows on selected files that collect inputs from OneDrive for Business.</span></span> <span data-ttu-id="414e2-105">この機能により、IT 部門によって作成されたフローの場合は特に、フローを実行している人が自分の資格情報を使用できます。</span><span class="sxs-lookup"><span data-stu-id="414e2-105">This feature enables the person running the flow to use their own credentials, which is especially for flows that have been created by an IT department.</span></span> <span data-ttu-id="414e2-106">**承認者**や**メッセージ**などの実行時の入力 (テキスト、ファイル、電子メール、ブール値、数値など) を求めるプロンプトも表示されます。</span><span class="sxs-lookup"><span data-stu-id="414e2-106">They can also get prompts for runtime inputs like **Approver** or **Message**, which can be of type text, file, email, Boolean, or number.</span></span>

<span data-ttu-id="414e2-107">OneDrive for Business から入力を収集するフローを設定するには、**フロー** ボタンを選択してから**フローの作成**を選択します。</span><span class="sxs-lookup"><span data-stu-id="414e2-107">To set up a flow that collects inputs from OneDrive for Business, you can select the **Flow** button and then choose **Create flow**.</span></span> <span data-ttu-id="414e2-108">これにより、いくつかのテンプレートが表示されます。</span><span class="sxs-lookup"><span data-stu-id="414e2-108">This shows you a number of templates.</span></span> <span data-ttu-id="414e2-109">**OneDrive for Business** コネクタの下で**選択したファイルの場合**トリガーを選択することで、Microsoft Flow でフローを空白から作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="414e2-109">You can also create a flow from blank from Microsoft Flow by choosing the **For a selected file** trigger under the **OneDrive for Business** connector:</span></span>

![アクションの選択](media/onedrive-selection-1.png)

<span data-ttu-id="414e2-111">このトリガーを選択した後、**入力の追加**を選択して、フローをトリガーしたユーザーから収集するフィールドを選択できます。</span><span class="sxs-lookup"><span data-stu-id="414e2-111">After you select this trigger you can select **Add an input** to choose the fields to collect from the user who triggered the flow.</span></span>

![入力の追加](media/onedrive-selection-2.png)

<span data-ttu-id="414e2-113">次に、フローにアクションを追加できます。</span><span class="sxs-lookup"><span data-stu-id="414e2-113">Then, you can add actions to your flow.</span></span> <span data-ttu-id="414e2-114">フローに名前を付けて保存すると、OneDrive for Business でファイルを選択した後の**フロー** メニューにそれが表示されます。</span><span class="sxs-lookup"><span data-stu-id="414e2-114">Once you name and save your flow, it shows up in the **Flow** menu after you select a file in OneDrive for Business:</span></span>

![フローの実行](media/onedrive-selection-3.png)


