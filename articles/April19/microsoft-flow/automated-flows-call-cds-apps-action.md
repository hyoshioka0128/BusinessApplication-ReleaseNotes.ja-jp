---
title: 自動フローで CDS for Apps のすべてのアクションを呼び出すことが可能
description: Common Data Service for Apps で使用できるすべてのアクションを、自動フローで呼び出すことができるようになりました。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 01/08/2019
ms.assetid: 177458cb-f6c4-e811-a971-000d3a137208
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 5f2a18b8b4e45e42b89faacc6021ed8d0ef24670
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210461"
---
# <a name="automated-flows-can-call-any-cds-for-apps-action"></a><span data-ttu-id="52be3-103">自動フローで CDS for Apps のすべてのアクションを呼び出すことが可能</span><span class="sxs-lookup"><span data-stu-id="52be3-103">Automated flows can call any CDS for Apps action</span></span>


[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

<span data-ttu-id="52be3-104">従来の Common Data Service (CDS) for Apps のワークフローと同等のものにする作業の一貫として、CDS for Apps で使用可能なすべてのアクションを自動フローで呼び出すことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="52be3-104">As a part of reaching parity with the Classic Common Data Service (CDS) for Apps Workflows, automated flows can now call all actions that are available in CDS for Apps.</span></span> <span data-ttu-id="52be3-105">これには、販売注文の遂行から Excel ファイルのエクスポートまでのすべてが含まれます。</span><span class="sxs-lookup"><span data-stu-id="52be3-105">This includes everything from fulfilling a sales order to exporting an Excel file.</span></span> <span data-ttu-id="52be3-106">アクションは、レコードの作成や更新など、データベースに副作用を与える可能性がある操作を表します。</span><span class="sxs-lookup"><span data-stu-id="52be3-106">Actions represent operations that might have side effects in the database, such as creating or updating records.</span></span> <span data-ttu-id="52be3-107">アクションは、パラメーターを必要としたり、値を返したりする場合があり、特定のレコードと関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="52be3-107">An Action might require parameters and might return a value, and can be associated with certain records.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="52be3-108">![CDS のアクションを呼び出すフロー](media/PerformActionInCDS-1.png "CDS のアクションを呼び出すフロー")</span><span class="sxs-lookup"><span data-stu-id="52be3-108">![Flow calling CDS actions](media/PerformActionInCDS-1.png "Flow calling CDS actions")</span></span>

<span data-ttu-id="52be3-109">このようなアクションとしては、**すぐに使える SDK メッセージ**、**プロセスとカスタム アクション**、さらには**カスタム ワークフローア クティビティ**などがあります。</span><span class="sxs-lookup"><span data-stu-id="52be3-109">These actions include the **out-of-box SDK messages**, **process and custom actions**, and even **custom workflow activities**.</span></span>
