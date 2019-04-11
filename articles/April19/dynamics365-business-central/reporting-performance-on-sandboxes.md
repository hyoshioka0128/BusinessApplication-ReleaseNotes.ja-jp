---
title: サンドボックスでのレポート作成のパフォーマンス
description: サンドボックスでのレポート作成のパフォーマンス
author: KennieNP
ms.reviewer: edupont
ms.date: 02/27/2019
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: kepontop
audience: administrator
ms.openlocfilehash: dfb48bcb8c853eab576dd5a8962e825da5d8c464
ms.sourcegitcommit: b9117e0a006fe421a672a4f6a7fbf0276efbddfa
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/20/2019
ms.locfileid: "878739"
---
# <a name="rdlc-reporting-performance-on-sandboxes"></a><span data-ttu-id="91a29-103">(RDLC) サンドボックスでのレポート作成のパフォーマンス</span><span class="sxs-lookup"><span data-stu-id="91a29-103">(RDLC) Reporting performance on sandboxes</span></span>

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

<span data-ttu-id="91a29-104">Dynamics NAV 2013 R2 の出荷前に、RDLC レポートのランタイムで大きなパフォーマンスのリグレッションが発見されました。</span><span class="sxs-lookup"><span data-stu-id="91a29-104">Before we shipped Dynamics NAV 2013 R2, we discovered a huge performance regression in the runtime for RDLC reports.</span></span> <span data-ttu-id="91a29-105">これは、.NET バージョン 4.0 にアップグレードしたためであり、RDLC レポートをパフォーマンスを低下させることなく機能させるために、レガシ コードのアクセス セキュリティ ポリシーを使用するよう .NET ランタイムを設定する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="91a29-105">This was because we upgraded to .NET version 4.0, and we needed to set the .NET runtime to use legacy code access security policy to make RDLC reports work with no performance degradation.</span></span> <span data-ttu-id="91a29-106">5 年後に、Business Central サンドボックスでのデバッグを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="91a29-106">Fast forward five years, when we enabled debugging in Business Central sandboxes.</span></span> <span data-ttu-id="91a29-107">これには、サンドボックス クラスターでのコード アクセス セキュリティを無効にする必要がありました。</span><span class="sxs-lookup"><span data-stu-id="91a29-107">This required us to disable code access security on sandbox clusters.</span></span> <span data-ttu-id="91a29-108">残念ながら、これにより RDLC レポートのパフォーマンスに関する古いリグレッションが再現しました。</span><span class="sxs-lookup"><span data-stu-id="91a29-108">Unfortunately, this introduced the old regression on RDLC report performance.</span></span> <span data-ttu-id="91a29-109">Business Central の 2019 年 4 月リリースでは、RDLC レポートを別の .NET AppDomain で完全に実行することで、パフォーマンスの問題を解消しました。</span><span class="sxs-lookup"><span data-stu-id="91a29-109">In the Business Central April 2019 release, we got rid of the performance problem by running RDLC reports fully in a different .NET AppDomain.</span></span>

## <a name="solved-memory-leak-in-rdlc-reporting"></a><span data-ttu-id="91a29-110">RDLC レポートでの解決されたメモリ リーク</span><span class="sxs-lookup"><span data-stu-id="91a29-110">Solved memory leak in RDLC reporting</span></span>

<span data-ttu-id="91a29-111">Business Central Server での RDLC の古い実装では、レポート実行時にわずかなメモリ リークが発生していました。</span><span class="sxs-lookup"><span data-stu-id="91a29-111">The old implementation of RDLC in the Business Central server had a small memory leak with report executions.</span></span> <span data-ttu-id="91a29-112">Business Central の 2019 年 4 月リリースでは、レポートに使用される .NET AppDomain を定期的にリサイクルするため、このメモリ リークは発生しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="91a29-112">In the Business Central April '19 release, we no longer have this memory leak, because we regularly recycle the .NET AppDomain that is used for reporting.</span></span>

## <a name="tell-us-what-you-think"></a><span data-ttu-id="91a29-113">フィードバック</span><span class="sxs-lookup"><span data-stu-id="91a29-113">Tell us what you think</span></span>
<span data-ttu-id="91a29-114">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="91a29-114">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="91a29-115">Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="91a29-115">Use the Business Central forum at [https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas).</span></span>
