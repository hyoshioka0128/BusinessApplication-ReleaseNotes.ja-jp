---
title: テーマの適用と変更
description: レポートのテーマを使用すると、会社の色や季節の色など、レポート全体に配色テーマを適用できます。
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: c44d4deb-6158-4658-9171-7fa813e438cf
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: cb0e85612f1da966bb75db8e19075c712a9f2fd7
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199394"
---
# <a name="api-to-apply-and-change-report-themes-in-power-bi-embedded"></a><span data-ttu-id="9835c-103">Power BI Embedded でレポートのテーマを適用および変更するための API</span><span class="sxs-lookup"><span data-stu-id="9835c-103">API to apply and change report themes in Power BI Embedded</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




<span data-ttu-id="9835c-104">この新機能を使うと、アプリケーションで API を呼び出し、セッション レベルで埋め込みオブジェクトにレポート テーマを適用したり変更したりできます。</span><span class="sxs-lookup"><span data-stu-id="9835c-104">This new capability allows applications to call an API to apply and change report themes for embedded objects on a session level.</span></span> <span data-ttu-id="9835c-105">レポートのテーマを使用すると、会社の色や季節の色など、レポート全体に配色テーマを適用できます。</span><span class="sxs-lookup"><span data-stu-id="9835c-105">With report themes, you can apply a color theme to an entire report, such as corporate colors, or seasonal coloring.</span></span> <span data-ttu-id="9835c-106">レポート テーマを適用すると、レポートのすべてのビジュアルが指定したテーマの色を使うようになります。</span><span class="sxs-lookup"><span data-stu-id="9835c-106">When you apply a report theme, all visuals in your report use the colors from your selected theme.</span></span>

<span data-ttu-id="9835c-107">![](media/apply-change-themes-1.png "レポート テーマを適用する")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="9835c-107">![](media/apply-change-themes-1.png "Apply report themes")
<!-- picture --></span></span>


<span data-ttu-id="9835c-108">レポート テーマの適用には JSON ファイルが必要で、このファイルを Power BI Desktop にインポートしてレポートに適用できます。</span><span class="sxs-lookup"><span data-stu-id="9835c-108">Applying a report theme requires a JSON file, which you can import into the Power BI Desktop and apply to your report.</span></span> 
