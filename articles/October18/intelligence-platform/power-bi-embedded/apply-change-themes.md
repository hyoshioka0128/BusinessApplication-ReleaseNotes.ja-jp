---
title: "テーマの適用と変更"
description: "レポートのテーマを使用すると、会社の色や季節の色など、レポート全体に配色テーマを適用できます。"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: c44d4deb-6158-4658-9171-7fa813e438cf
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 62a44aa1eeb8959f7f51e9a6dbe34941159b1b16
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="api-to-apply-and-change-report-themes-in-power-bi-embedded"></a><span data-ttu-id="f698a-103">Power BI Embedded でレポートのテーマを適用および変更するための API</span><span class="sxs-lookup"><span data-stu-id="f698a-103">API to apply and change report themes in Power BI Embedded</span></span>


[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="f698a-104">この新機能を使うと、アプリケーションで API を呼び出し、セッション レベルで埋め込みオブジェクトにレポート テーマを適用したり変更したりできます。</span><span class="sxs-lookup"><span data-stu-id="f698a-104">This new capability allows applications to call an API to apply and change report themes for embedded objects on a session level.</span></span> <span data-ttu-id="f698a-105">レポートのテーマを使用すると、会社の色や季節の色など、レポート全体に配色テーマを適用できます。</span><span class="sxs-lookup"><span data-stu-id="f698a-105">With report themes, you can apply a color theme to an entire report, such as corporate colors, or seasonal coloring.</span></span> <span data-ttu-id="f698a-106">レポート テーマを適用すると、レポートのすべてのビジュアルが指定したテーマの色を使うようになります。</span><span class="sxs-lookup"><span data-stu-id="f698a-106">When you apply a report theme, all visuals in your report use the colors from your selected theme.</span></span>

<span data-ttu-id="f698a-107">![](media/apply-change-themes-1.png "レポート テーマを適用する")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="f698a-107">![](media/apply-change-themes-1.png "Apply report themes")
<!-- picture --></span></span>


<span data-ttu-id="f698a-108">レポート テーマの適用には JSON ファイルが必要で、このファイルを Power BI Desktop にインポートしてレポートに適用できます。</span><span class="sxs-lookup"><span data-stu-id="f698a-108">Applying a report theme requires a JSON file, which you can import into the Power BI Desktop and apply to your report.</span></span> 

