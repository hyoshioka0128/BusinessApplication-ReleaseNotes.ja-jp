---
title: Retail 更新プログラムの配信
description: Retail 更新プログラムの配信
author: ReneeW-CPub
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: renwe
ms.openlocfilehash: 055445904c2b344b5862a56001b044e4cd0cd7d6
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1224840"
---
#  <a name="retail-broadcast-updates"></a><span data-ttu-id="74420-103">Retail 更新プログラムの配信</span><span class="sxs-lookup"><span data-stu-id="74420-103">Retail broadcast updates</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


<span data-ttu-id="74420-104">シームレスかつ自動的な更新は、SaaS (Software as a Service) ソリューションの重要な要素です。</span><span class="sxs-lookup"><span data-stu-id="74420-104">Seamless and automatic updates are a key element of any software as a service (SaaS) solution.</span></span> <span data-ttu-id="74420-105">従来のオンプレミス ソリューションから最新のクラウド運用型 SaaS ソリューションへの進化の中で、Commerce Runtime (CRT)、チャネル データベース、販売時点情報管理などの Retail の主なコンポーネントのすべてに対する革新的なロックダウンを含め、大幅な進歩を遂げました。また同時に、(Microsoft の顧客による各統合のブロックを解除する直接的なフィードバックに基づいて) 特定の拡張ポイントの開発に多大な投資を行いました。</span><span class="sxs-lookup"><span data-stu-id="74420-105">In our evolution from a legacy on-premises solution to a modern cloud-operated SaaS solution, we’ve made considerable strides, including progressive lockdown (with regard to invasive customizations) of all key Retail components, including Commerce Runtime (CRT), Channel Database, Point of Sale, and at the same time invested considerably in developing specific extension points (based on direct feedback to unblock each of our customer implementations).</span></span> <span data-ttu-id="74420-106">顧客の環境に対する Microsoft の更新プログラムの適用の際に、顧客側のカスタマイズによりコードをマージする必要がなくなるところまで到達しました。</span><span class="sxs-lookup"><span data-stu-id="74420-106">We are now at a point where Microsoft updates to a customer environment can be applied with no need for code merge with a customer's customization.</span></span> <span data-ttu-id="74420-107">ただし、顧客からは依然として更新プログラムの展開を明示的に開始することが期待されています。</span><span class="sxs-lookup"><span data-stu-id="74420-107">Customers, however, are still expected to explicitly initiate update deployment.</span></span> <span data-ttu-id="74420-108">この機能は物事を次のレベルに引き上げ、更新プログラムを顧客の環境に自動的に適用します。</span><span class="sxs-lookup"><span data-stu-id="74420-108">This feature takes things to the next level and automatically applies the updates in customer environments.</span></span> 

## <a name="business-value"></a><span data-ttu-id="74420-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="74420-109">Business value</span></span>
<span data-ttu-id="74420-110">小売業者が最新の情報に通じていることは、すべての利害関係者に利益をもたらします。</span><span class="sxs-lookup"><span data-stu-id="74420-110">Keeping retailers up to date has benefits for all stakeholders.</span></span> <span data-ttu-id="74420-111">小売業者は、基本的な機能 (可用性、信頼性、パフォーマンス、セキュリティ) に加えて、製品内の機能革新において Microsoft が提供する最新の機能強化から恩恵を受けています。</span><span class="sxs-lookup"><span data-stu-id="74420-111">Retailers benefit from the latest improvements from Microsoft, across the fundamentals (availability, reliability, performance, and security) as well as functional innovations in the product.</span></span> <span data-ttu-id="74420-112">それらは以前に別の小売業者の環境で発見され修正された問題の影響を受けることは少なく、それによって業務の混乱を招く予測可能な問題の発生を回避できます。</span><span class="sxs-lookup"><span data-stu-id="74420-112">They are much less likely to be affected by issues that have previously been discovered and fixed in other retailers' environments and thereby avoid preventable disruptions to their business.</span></span>

## <a name="feature-description"></a><span data-ttu-id="74420-113">機能の説明</span><span class="sxs-lookup"><span data-stu-id="74420-113">Feature description</span></span>
<span data-ttu-id="74420-114">この機能はクラウドでホストされている Retail のコンポーネントを自動更新します。</span><span class="sxs-lookup"><span data-stu-id="74420-114">This feature will auto-update cloud-hosted Retail components.</span></span> <span data-ttu-id="74420-115">更新プログラムは各公開ラウンドにわたって段階的に展開され、小売業者はそれらが本番環境に展開される前に本番前環境の変化を検証できます。</span><span class="sxs-lookup"><span data-stu-id="74420-115">Updates will be rolled out in a staged fashion across various exposure rings and allow retailers to validate the changes in preproduction environments before these get rolled out to their production environments.</span></span> <span data-ttu-id="74420-116">小売業者はリグレッション テストに 30 日をかけ、本番前環境でのテスト中にリグレッションやその他の影響が発見された場合は、本番環境への更新プログラムの提供を最大で 90 日遅らせることができます。</span><span class="sxs-lookup"><span data-stu-id="74420-116">Retailers will have 30 days for regression testing and the ability to delay updates in production by up to 90 days, in case of any regressions or other impacts discovered during testing in the preproduction environment.</span></span>
