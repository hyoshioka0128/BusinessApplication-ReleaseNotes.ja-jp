---
title: アラブ首長国連邦用の VAT 報告機能
description: アラブ首長国連邦用の VAT 報告機能
author: AdamTrukawka
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: atrukawk
audience: end-user
ms.openlocfilehash: 8c7a861abccfc1aa959a4eaa2244148022ed6fb6
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199702"
---
# <a name="vat-reporting-functionality-for-united-arab-emirates"></a><span data-ttu-id="064aa-103">アラブ首長国連邦用の VAT 報告機能</span><span class="sxs-lookup"><span data-stu-id="064aa-103">VAT reporting functionality for United Arab Emirates</span></span>

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="064aa-104">アラブ首長国連邦では、2018 年 1 月 1 日に付加価値税 (VAT) が導入されました。</span><span class="sxs-lookup"><span data-stu-id="064aa-104">Value added tax (VAT) was introduced in the United Arab Emirates on January 1, 2018.</span></span> <span data-ttu-id="064aa-105">発布された法令 (Federal Decree Law No.</span><span class="sxs-lookup"><span data-stu-id="064aa-105">The issued Federal Decree Law No.</span></span> <span data-ttu-id="064aa-106">(8) of 2017 on Value Added Tax) では、税の範囲、税率、納税義務、およびあらゆるケースにおける商品やサービスの供給について概要が示されています。</span><span class="sxs-lookup"><span data-stu-id="064aa-106">(8) of 2017 on Value Added Tax outlines the tax scope, rate, responsibility for tax, and supply of goods and services in all cases.</span></span> <span data-ttu-id="064aa-107">VAT に関する法令の詳細については、[アラブ首長国連邦の税務当局サイト](https://government.ae/en/information-and-services/finance-and-investment/taxation/valueaddedtaxvat)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="064aa-107">For more details on VAT regulations, see [Federal Tax Authorities of United Arab Emirates](https://government.ae/en/information-and-services/finance-and-investment/taxation/valueaddedtaxvat).</span></span>

<span data-ttu-id="064aa-108">Microsoft Dynamics 365 for Finance and Operations の 2018 年 10 月リリースを使用しているお客様は、アラブ首長国連邦法での VAT 報告に関連する UAE 専用の機能を使用して、UAE の法人を構成できます。</span><span class="sxs-lookup"><span data-stu-id="064aa-108">Customers using the October '18 release of Microsoft Dynamics 365 for Finance and Operations will be able to configure the UAE legal entity with country-specific functionality related to VAT reporting in the country.</span></span>

<span data-ttu-id="064aa-109">次の機能は、VAT 報告の要件に従い、UAE 専用の強化機能として UAE ローカライズに追加されたものです。</span><span class="sxs-lookup"><span data-stu-id="064aa-109">The following country-specific enhancements have been added to UAE localization to align with the requirements of VAT reporting:</span></span>

- <span data-ttu-id="064aa-110">法人構成が拡張され、VAT 報告書に必要な追加フィールドが加えられました。</span><span class="sxs-lookup"><span data-stu-id="064aa-110">Legal entity configuration has been extended with additional fields required in VAT reports.</span></span>
- <span data-ttu-id="064aa-111">VAT の逆請求機能が ARE のコンテキスト用に有効化され、GCC 領域での課税対象となる国内業務を適切に記録できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="064aa-111">VAT reverse charge functionality has been enabled for ARE country context to properly record taxable domestic operations within GCC territory.</span></span>
- <span data-ttu-id="064aa-112">UAE 専用の売上請求書と訂正票の出力レイアウトが追加され、追加の列と VAT 集計情報を出力できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="064aa-112">UAE country-specific sales invoice and credit notes printout layouts have been added with additional columns and VAT summary information.</span></span>
- <span data-ttu-id="064aa-113">UAE 用の売上請求書と訂正票は、2 つの言語で出力されます (ar-AE アラビア語とユーザー インターフェイス言語)。</span><span class="sxs-lookup"><span data-stu-id="064aa-113">Sales invoice and credit notes for UAE are printing in two languages, including ar-AE Arabic and user interface language.</span></span>
- <span data-ttu-id="064aa-114">VAT 納税申告書は、e-TAX FTA ポータルへのアップロードに対応した電子ファイル形式で出力されます。</span><span class="sxs-lookup"><span data-stu-id="064aa-114">VAT return declaration report is printed to electronic file format ready for uploading to the e-TAX FTA portal.</span></span>
- <span data-ttu-id="064aa-115">標準監査ファイル機能は、UAE のローカル機能と共有されます。</span><span class="sxs-lookup"><span data-stu-id="064aa-115">Standard audit file functionality has been shared with UAE local functionality.</span></span> <span data-ttu-id="064aa-116">FTA VAT 監査ファイル (FAF) は、税務当局の要件に従って必要な CSV 形式にエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="064aa-116">Required by Federal Tax Authorities, FTA VAT audit file (FAF) can be exported accordingly to required CSV format.</span></span>

<span data-ttu-id="064aa-117">UAE で業務を運営するすべての企業は、事業所得、コスト、および関連する VAT 課税額を正確に文書化し、定期的な VAT 報告書を税務当局に送付する義務があります。</span><span class="sxs-lookup"><span data-stu-id="064aa-117">All companies in UAE are responsible for carefully documenting their business income, costs, and associated VAT charges and sending regular VAT reports to federal tax authorities.</span></span> <span data-ttu-id="064aa-118">VAT 報告機能は、Dynamics 365 for Finance and Operations のすべてのお客様によって導入されます。</span><span class="sxs-lookup"><span data-stu-id="064aa-118">The VAT reporting functionality will be adopted by all customers of Dynamics 365 for Finance and Operations.</span></span>

