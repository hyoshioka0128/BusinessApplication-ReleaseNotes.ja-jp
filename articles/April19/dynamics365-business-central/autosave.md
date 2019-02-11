---
title: 自動保存インジケーター
description: 変更は自動的に保存されます。
author: blazkote
ms.reviewer: edupont
ms.date: 01/21/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: blazkote
audience: end user
ms.openlocfilehash: c6384d9abd667afb170380fd8c564ff2901a3ade
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210306"
---
# <a name="autosave-indicator"></a><span data-ttu-id="c4f02-103">自動保存インジケーター</span><span class="sxs-lookup"><span data-stu-id="c4f02-103">Autosave indicator</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="c4f02-104">Business Central の現在のお客様および Dynamics NAV のお客様は、これらの製品に共通する自動保存の概念をよくご存じでしょう。</span><span class="sxs-lookup"><span data-stu-id="c4f02-104">Current Business Central customers as well as customers of Dynamics NAV are very familiar with the concept of autosave common in our products.</span></span> <span data-ttu-id="c4f02-105">これは非常に好まれ歓迎されている機能ですが、他の ERP システムから移行してきた多くのお客様からは、保存機能を明示的に使用しなくても、データが Business Central に保存されてセキュリティで保護されていることを知らないという声をよく聞きます。</span><span class="sxs-lookup"><span data-stu-id="c4f02-105">This is a very much loved and welcomed feature, but we heard from many of our customers moving from other ERP systems that they are not aware data is saved and secured in Business Central—even without explicitly using any save function.</span></span> <span data-ttu-id="c4f02-106">データが保存されていることを示すスマートな自動保存インジケーターを作成したのは、これらのお客様のためです。</span><span class="sxs-lookup"><span data-stu-id="c4f02-106">It is for those customers that we have built a smart autosave indicator showing when the data is being saved for them.</span></span>  

## <a name="business-value"></a><span data-ttu-id="c4f02-107">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c4f02-107">Business value</span></span>
<span data-ttu-id="c4f02-108">この新しい要素では、バックグラウンドで保存されているカードまたはドキュメントのデータの状態が直接示され、入力された情報がセキュリティで保護されていることが明確に示されます。</span><span class="sxs-lookup"><span data-stu-id="c4f02-108">This new element indicates directly the state of card or document data being saved in the background and provides any user with a clear indication that the entered information is secure.</span></span> 

## <a name="autosave-indicator-appearance"></a><span data-ttu-id="c4f02-109">自動保存インジケーターの外観</span><span class="sxs-lookup"><span data-stu-id="c4f02-109">Autosave indicator appearance</span></span>   
<span data-ttu-id="c4f02-110">インジケーターは画面上のカードの右側に表示され、コンピューターがサーバーと通信してデータを保存していると値が変化します。</span><span class="sxs-lookup"><span data-stu-id="c4f02-110">The indicator is shown on the right side of the card on screen and changes values when the computer communicates with the server and saves the data.</span></span> <span data-ttu-id="c4f02-111">インジケーターは、現在の状態に応じて**保存中**または**保存済**を表示できます。</span><span class="sxs-lookup"><span data-stu-id="c4f02-111">The indicator can display **Saving** or **Saved** depending on current state.</span></span> <span data-ttu-id="c4f02-112">データ検証エラーが発生した場合は、**未保存**も表示されます。</span><span class="sxs-lookup"><span data-stu-id="c4f02-112">In case a data validation error appears, it would also display **Not saved**.</span></span> <span data-ttu-id="c4f02-113">動作中のインジケーターの例を以下に示します。</span><span class="sxs-lookup"><span data-stu-id="c4f02-113">An example of the indicator in action can be seen below:</span></span>

<span data-ttu-id="c4f02-114">![Business Central の新しい自動保存インジケーター](media/autosave.png "自動保存インジケーター")</span><span class="sxs-lookup"><span data-stu-id="c4f02-114">![The new Autosave indicator in Business Central](media/autosave.png "Autosave Indicator")</span></span> 


## <a name="tell-us-what-you-think"></a><span data-ttu-id="c4f02-115">フィードバック</span><span class="sxs-lookup"><span data-stu-id="c4f02-115">Tell us what you think</span></span>
<span data-ttu-id="c4f02-116">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="c4f02-116">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="c4f02-117">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="c4f02-117">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
