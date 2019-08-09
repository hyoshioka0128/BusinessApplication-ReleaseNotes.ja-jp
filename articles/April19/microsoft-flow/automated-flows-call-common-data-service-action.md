---
title: 自動フローであらゆる Common Data Service アクションを呼び出すことが可能
description: Common Data Service で使用できるすべてのアクションを自動フローで呼び出すことができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: fd86bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: c4b6807481fba7fb07b337aa8cbbd13af5374bcd
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756778"
---
# <a name="automated-flows-can-call-any-common-data-service-action"></a><span data-ttu-id="c7fd2-103">自動フローであらゆる Common Data Service アクションを呼び出すことが可能</span><span class="sxs-lookup"><span data-stu-id="c7fd2-103">Automated flows can call any Common Data Service action</span></span>

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="c7fd2-104">Common Data Service のワークフローと同等のものにする作業の一貫として、Common Data Service で使用可能なすべてのアクションを自動フローで呼び出すことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c7fd2-104">As a part of reaching parity with the Common Data Service Workflows, automated flows can now call all actions that are available in Common Data Service.</span></span> <span data-ttu-id="c7fd2-105">これには、販売注文の遂行から Excel ファイルのエクスポートまでのすべてが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c7fd2-105">This includes everything from fulfilling a sales order to exporting an Excel file.</span></span> <span data-ttu-id="c7fd2-106">アクションは、レコードの作成や更新など、データベースに副作用を与える可能性がある操作を表します。</span><span class="sxs-lookup"><span data-stu-id="c7fd2-106">Actions represent operations that might have side effects in the database, such as creating or updating records.</span></span> <span data-ttu-id="c7fd2-107">アクションは、パラメーターを必要としたり、値を返したりする場合があり、特定のレコードと関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="c7fd2-107">An Action might require parameters and might return a value, and can be associated with certain records.</span></span>

<span data-ttu-id="c7fd2-108">![Common Data Service のアクションを呼び出すフロー](media/PerformActionInCDS-1.png "Common Data Service のアクションを呼び出すフロー")</span><span class="sxs-lookup"><span data-stu-id="c7fd2-108">![Flow calling Common Data Service actions](media/PerformActionInCDS-1.png "Flow calling Common Data Service actions")</span></span>

<span data-ttu-id="c7fd2-109">このようなアクションとしては、**すぐに使える SDK メッセージ**、**プロセスとカスタム アクション**、さらには**カスタム ワークフローア クティビティ**などがあります。</span><span class="sxs-lookup"><span data-stu-id="c7fd2-109">These actions include the **out-of-box SDK messages**, **process and custom actions**, and even **custom workflow activities**.</span></span>
