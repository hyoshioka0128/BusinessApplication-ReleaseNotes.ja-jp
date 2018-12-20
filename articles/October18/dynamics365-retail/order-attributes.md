---
title: "注文属性"
description: "注文属性フレームワークの拡張。"
author: mugunthanm
manager: AnnBe
ms.date: 11/29/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mumani
audience: admin
ms.translationtype: HT
ms.sourcegitcommit: ba1e0a919b45697fd78e54e462b89f37cc8880b5
ms.openlocfilehash: 9909513e4885c6c185a58c09b66e5389bceca87b
ms.contentlocale: ja-jp
ms.lasthandoff: 11/30/2018

---


# <a name="order-attributes"></a><span data-ttu-id="edb11-103">注文属性</span><span class="sxs-lookup"><span data-stu-id="edb11-103">Order attributes</span></span>

<span data-ttu-id="edb11-104">現金持ち帰り (C&C) トランザクションと顧客注文の属性値を POS (販売時点管理) から直接表示し、更新するように注文属性フレームワークを機能強化しました。</span><span class="sxs-lookup"><span data-stu-id="edb11-104">We enhanced the order attribute framework to show and update the attribute values for the cash and carry (C&C) transaction and customer order directly from the point of sale (POS).</span></span> <span data-ttu-id="edb11-105">前回のリリースでは、さまざまなシナリオ用の属性をサポートするように CRT フレームワークを機能強化しましたが、値を設定するために POS で使用できる UI はなく、拡張機能で UI を構築し、CRT から手動で読み取って更新する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="edb11-105">In the last release, we enhanced the CRT framework to support attributes for different scenarios, but there was no UI available in POS to set the values, and extensions have to build the UI and read and update from CRT manually.</span></span> <span data-ttu-id="edb11-106">この新機能により、開発者は本社の画面レイアウト デザイナーで属性パネルを構成し、POS でそのパネルにアクセスして C&C トランザクションと顧客注文の両方の属性値を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="edb11-106">With this new feature, developers can configure the attribute panel in the headquarters screen layout designer and access it in POS to set the attribute values for both a C&C transaction and a customer order.</span></span> 

<span data-ttu-id="edb11-107">C&C トランザクションまたは顧客注文の追加データを取得して表示する必要があるカスタム シナリオがある場合は、この機能を追加コードなしで使用できます。</span><span class="sxs-lookup"><span data-stu-id="edb11-107">If there are custom scenarios where it is required to capture and show additional data for C&C transaction or customer order, this feature can be used without any additional code.</span></span> <span data-ttu-id="edb11-108">さらに、CRT または POS の追加のビジネス ロジック用にカスタマイズすることもできます。</span><span class="sxs-lookup"><span data-stu-id="edb11-108">In addition, it can be customized for any additional business logic in CRT or POS.</span></span> <span data-ttu-id="edb11-109">これまで、シナリオ開発者は、コマース本部、CDX、CRT、RS、チャネル DB、POS に関与してこれらを変更する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="edb11-109">Previously to do this, scenario developers had to be involved and modify Commerce headquarters, CDX, CRT, RS, channel DB, and POS.</span></span> <span data-ttu-id="edb11-110">現在は、構成主導型のアプローチでこれを行うことができ、任意のビジネス ユーザーがこの作業を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="edb11-110">Now this can be done through a configuration-driven approach, and any business user can do this.</span></span> <span data-ttu-id="edb11-111">ビジネス ロジックを変更するには、開発者のペルソナが必要です。</span><span class="sxs-lookup"><span data-stu-id="edb11-111">To modify the business logic, the developer persona is required.</span></span> 

<span data-ttu-id="edb11-112">この初期バージョンでは、属性の型として**文字列**だけがサポートされますが、将来のバージョンでは他の型の属性もサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="edb11-112">This initial version supports only the **String** attribute type, but future versions will support other attribute types.</span></span> <span data-ttu-id="edb11-113">データをマスター テーブルから取得し、そのデータに X++ での複雑な検索ロジックとコア ビジネス ロジックが必要な場合は、拡張機能プロパティを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="edb11-113">If you want the data to come from the master table, and that data involves complex search logic and core business logic in X++, you should use extension properties.</span></span>

<span data-ttu-id="edb11-114">最低限のビジネス ロジックを持つ新しいフィールドを C&C トランザクション、顧客注文、またはコール センター注文に追加する場合や、POS または小売用バックオフィスに情報を取り込む場合は、注文属性を使用します。</span><span class="sxs-lookup"><span data-stu-id="edb11-114">If you want to add new fields with minimum business logic to C&C transactions, customer orders, or call center orders, and if you want to capture the information in the POS or retail headquarters, use order attributes.</span></span> <span data-ttu-id="edb11-115">以前は、POS での C&C トランザクション (トランザクション ヘッダーまたは行) または顧客注文に新しいフィールドを追加するには、小売用バックオフィスとチャネル データベースに新しい拡張テーブルを作成してから、さまざまな画面や操作を処理するために CRT および POS コードにインライン変更を行う必要がありました。</span><span class="sxs-lookup"><span data-stu-id="edb11-115">Previously, to add a new field to a C&C transaction (transaction header or lines) or a customer order in the POS, you had to create a new extension table in Retail headquarters and the channel database, and then make inline changes to CRT and POS code to handle the various screens and operations.</span></span> <span data-ttu-id="edb11-116">チャネル データベースと小売用バックオフィスの間でデータを同期するように Commerce Data Exchange を構成する必要もありました。</span><span class="sxs-lookup"><span data-stu-id="edb11-116">You also had to configure Commerce Data Exchange to synchronize the data between the channel database and Retail headquarters.</span></span> <span data-ttu-id="edb11-117">顧客属性により、コードを記述したりカスタム拡張テーブルを作成したりすることなく、構成を通じてこれらすべてのアクションを実行できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="edb11-117">Customer attributes now let you complete all these actions through configuration without writing any code or creating custom extension tables.</span></span> <span data-ttu-id="edb11-118">(コア ビジネス ロジックと POS UI は依然として作成する必要があります)。</span><span class="sxs-lookup"><span data-stu-id="edb11-118">(You still need to create the core business logic and the POS UI).</span></span>

<span data-ttu-id="edb11-119">機能の詳細については、「[注文属性](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/order-attributes)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="edb11-119">For the full feature details, refer to [Order attributes](https://docs.microsoft.com/en-us/dynamics365/unified-operations/retail/dev-itpro/order-attributes).</span></span>


