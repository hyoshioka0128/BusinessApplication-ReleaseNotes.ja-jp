---
title: SAP 変数
description: DirectQuery を介した SAP BW 変数と SAP HANA 変数へのインポートまたは接続のサポートを追加します。
author: AdamDWilson
ms.date: 01/21/2019
ms.reviewer: mihart
ms.topic: article
ms.service: business-applications
ms.author: adamw
ms.openlocfilehash: 42b72b4c0f3a74c35cf350eb04075226519e4538
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225134"
---
# <a name="support-for-sap-variables"></a><span data-ttu-id="03edc-103">SAP 変数のサポート</span><span class="sxs-lookup"><span data-stu-id="03edc-103">Support for SAP variables</span></span>

[!include[business-intelligence banner](../../includes/business-intelligence.md)]

<span data-ttu-id="03edc-104">Power BI は、SAP Business Warehouse (BW) と SAP HANA の両方への接続をサポートします。</span><span class="sxs-lookup"><span data-stu-id="03edc-104">Power BI supports connecting to both SAP Business Warehouse (BW) and SAP HANA.</span></span>
<span data-ttu-id="03edc-105">通常、使用されている SAP BW オブジェクトや SAP HANA オブジェクトには変数やパラメーターが定義されています。</span><span class="sxs-lookup"><span data-stu-id="03edc-105">It is commonly the case that the SAP BW or SAP HANA objects being used have variables or parameters defined on them.</span></span> <span data-ttu-id="03edc-106">たとえば、SAP BW Infocube や SAP HANA の分析ビューで国や年に対して変数が定義されていると、利用できるデータが選択した国や年に限定されます。</span><span class="sxs-lookup"><span data-stu-id="03edc-106">For example, an SAP BW Infocube or SAP HANA Analytical View might have variables defined for country and year that restrict the data available to the selected country or year.</span></span> <span data-ttu-id="03edc-107">このような変数は、SAP BW や SAP HANA のソースで必須またはオプションのいずれかに定義されている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="03edc-107">Such variables might be defined as either required or optional in the SAP BW or SAP HANA source.</span></span> <span data-ttu-id="03edc-108">パラメーターの例として、計算に使用される税率を決定する TaxRate というパラメーターが挙げられます。</span><span class="sxs-lookup"><span data-stu-id="03edc-108">An example of a parameter might be TaxRate, which determines the TaxRate that will be used in calculations.</span></span>

<span data-ttu-id="03edc-109">Power BI Desktop は、データをインポートするときと DirectQuery を使用して接続するときに、このような SAP BW と SAP HANA の両方の変数とパラメーターに対するサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="03edc-109">Power BI Desktop will add support for such variables and parameters, for both SAP BW and SAP HANA, when importing the data and when connecting using DirectQuery.</span></span> <span data-ttu-id="03edc-110">これにより、レポート作成者が国や年などの値を設定することで、レポートに表示されるデータを選択した国や年に限定できます。</span><span class="sxs-lookup"><span data-stu-id="03edc-110">This allows the report author to set the values, such as the country and year to be used, that then restricts the data shown in the report to the selection made.</span></span> <span data-ttu-id="03edc-111">レポート作成者は最初の接続時に値を設定し、必要に応じて後で選択内容を変更できます。</span><span class="sxs-lookup"><span data-stu-id="03edc-111">The report author sets the values upon first connecting and can then change the selections later if required.</span></span>

<span data-ttu-id="03edc-112">レポートが Power BI サービスに発行された後は、そのレポートで選択した内容は Power BI サービスでは変更できません。</span><span class="sxs-lookup"><span data-stu-id="03edc-112">After the report is published to the Power BI service, it is not possible to change the selections made for the report in the Power BI service.</span></span>
<span data-ttu-id="03edc-113">その結果、レポートを開いたすべてのユーザーに、レポート作成者が選択した内容が反映された同じデータが表示されます。</span><span class="sxs-lookup"><span data-stu-id="03edc-113">As a result, all users who open the report would see the same data, reflecting the selections made by the report author.</span></span>

<span data-ttu-id="03edc-114">DirectQuery を使用するレポートについては、そのレポートを開いたユーザー自身が変数やパラメーターを選択できる機能を追加することで改善します。</span><span class="sxs-lookup"><span data-stu-id="03edc-114">For reports that use DirectQuery, we will be improving this by adding the ability for the users who open the report to make their own selection of these variables and parameters.</span></span> <span data-ttu-id="03edc-115">たとえば、あるレポートを 1 人のユーザーは 2018 年のフランスのデータを表示できる一方で、もう一方のユーザーは同じレポートの 2017 年の米国のデータを表示できます。</span><span class="sxs-lookup"><span data-stu-id="03edc-115">For example, a user opening a report might choose to see data for France/2018, while another user opening the same report might choose to see USA/2017.</span></span> <span data-ttu-id="03edc-116">選択は最新のスライサーのように行うことが可能で、各ユーザーが選択した内容は記憶され、次にそのレポートを開いたときに再利用されます。</span><span class="sxs-lookup"><span data-stu-id="03edc-116">The choices made by each user will be remembered and reused when they next open the report, much like slicer selections are today.</span></span>

[!include[feedback](../includes/service-feedback.md)]