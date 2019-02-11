---
title: ブラジル向けの構成可能な E-Invoice (NF-e と NFS-e)
description: この機能により、NF-e および NFS-e の E-Invoice を構成できます。
author: sndray
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: sndray
ms.openlocfilehash: bb95c9c25f0efde4925a17f335e018a40b435b12
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210481"
---
#  <a name="configurable-e-invoices-for-brazil-nf-e-and-nfs-e"></a><span data-ttu-id="85078-103">ブラジル向けの構成可能な E-Invoice (NF-e と NFS-e)</span><span class="sxs-lookup"><span data-stu-id="85078-103">Configurable e-invoices for Brazil (NF-e and NFS-e)</span></span> 
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="85078-104">SEFAZ とも呼ばれるブラジルの税務当局は、電子請求のためにすべての企業が順守しなければならない電子通信標準を定義しました。</span><span class="sxs-lookup"><span data-stu-id="85078-104">The Brazil tax authority, also known as SEFAZ, defined an electronic communication standard that all companies must adhere to for e-invoicing.</span></span> <span data-ttu-id="85078-105">ブラジルのローカライズでは、Nota Fiscal Eletrônica (NF-e または NFS-e) を生成して、2 者間の品目またはサービスの移動を登録できます。</span><span class="sxs-lookup"><span data-stu-id="85078-105">In the Brazilian localization, you can generate a Nota Fiscal Eletrônica (NF-e or NFS-e) to register the movement of items or services between two parties.</span></span> <span data-ttu-id="85078-106">生成された会計文書は、XML メッセージでデジタル署名された NF-e として Secretaria da Fazenda (SEFAZ) に送信できます。</span><span class="sxs-lookup"><span data-stu-id="85078-106">The generated fiscal document can be submitted as the digitally signed NF-e to the Secretaria da Fazenda (SEFAZ) in an XML message.</span></span> <span data-ttu-id="85078-107">NF-e のプロセスには次のステップが含まれます。</span><span class="sxs-lookup"><span data-stu-id="85078-107">The NF-e process includes the following steps:</span></span>

1. <span data-ttu-id="85078-108">会計施設は会計ドキュメントを転記します。</span><span class="sxs-lookup"><span data-stu-id="85078-108">The fiscal establishment posts a fiscal document.</span></span>
2. <span data-ttu-id="85078-109">NF-e のエクスポートまたはインポート プロセスで、転記された会計ドキュメントが検出されて、指定された形式の XML メッセージが生成されます。</span><span class="sxs-lookup"><span data-stu-id="85078-109">The NF-e export or import process detects the posted fiscal document and generates an XML message in the specified format.</span></span> <span data-ttu-id="85078-110">NF-e ごとに個別の XML メッセージが生成されます。</span><span class="sxs-lookup"><span data-stu-id="85078-110">A separate XML message is generated for each NF-e.</span></span> <span data-ttu-id="85078-111">XML メッセージが SEFAZ に送信されます。</span><span class="sxs-lookup"><span data-stu-id="85078-111">The XML message is transmitted to SEFAZ.</span></span>
3. <span data-ttu-id="85078-112">SEFAZ は XML メッセージを処理し、各 NF-e に対してプロトコルとステータスを返します。</span><span class="sxs-lookup"><span data-stu-id="85078-112">SEFAZ processes the XML message and returns a protocol and status for each NF-e.</span></span>

<span data-ttu-id="85078-113">SEFAZ から NF-e のステータスを受け取ったら、承認、取消、ドキュメントの訂正と再送信など、さまざまな一連の操作を実行できます。</span><span class="sxs-lookup"><span data-stu-id="85078-113">Upon the status receipt of the NF-e from SEFAZ, you can perform different sets of actions, like approval, cancellation or correction and resending of the document.</span></span>

<span data-ttu-id="85078-114">ブラジルの NF-e については頻繁に法律が変更されており、NFS-e の要件は計画的に変更されます。</span><span class="sxs-lookup"><span data-stu-id="85078-114">Brazilian NF-e is subject to frequent law changes and there are planned changes in requirements for NFS-e.</span></span> <span data-ttu-id="85078-115">この機能により両方とも完全に構成可能になるため、Microsoft は規制の更新をすばやくリリースでき、パートナーと顧客は必要に応じてコードを変更することなく統合とエクスポート/インポート形式をカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="85078-115">This feature will make both fully configurable, so it will be quicker for Microsoft to release regulatory updates and for partners and customers to customize integrations and export/import formats, if required, without code changes.</span></span> <span data-ttu-id="85078-116">さらに、構成可能な E-Invoice を使用すると、パートナーはブラジルのサポートされていない州、都市、および業種のローカライズ対象を簡単に拡大できます。</span><span class="sxs-lookup"><span data-stu-id="85078-116">In addition, configurable e-invoices will make it simpler for partners to extend localization coverage for non-supported states, cities, and verticals in Brazil.</span></span>

<span data-ttu-id="85078-117">NF-e と NFS-e の両方の構成可能性の目標は、電子メッセージングとの統合および電子報告機能の使用によって達成される予定です。</span><span class="sxs-lookup"><span data-stu-id="85078-117">Configurability goals both for NF-e and NFS-e are planned to be met through integration with Electronic messaging and using Electronic Reporting capabilities.</span></span> 

<span data-ttu-id="85078-118">**メッセージ処理アクションの例**</span><span class="sxs-lookup"><span data-stu-id="85078-118">**Message processing actions example**</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="85078-119">![電子メッセージング - メッセージ処理アクション](media/Configurable_EM_1.png "電子メッセージング - メッセージ処理アクション")</span><span class="sxs-lookup"><span data-stu-id="85078-119">![Electronic messaging - Message processing actions](media/Configurable_EM_1.png "Electronic messaging - Message processing actions")</span></span>

> [!NOTE]
> <span data-ttu-id="85078-120">この機能は、既存の構成不可能な NF-e および NFS-e の機能の一部を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="85078-120">This feature will replace some parts of already existing non-configurable NF-e and NFS-e functionality.</span></span> <span data-ttu-id="85078-121">新しい機能と更新されたユーザー エクスペリエンスの導入により、古い機能は廃止され、対応するコードは将来のアップデートで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="85078-121">With introduction of the new feature and updated user experience, the old feature will be deprecated and corresponding code will be removed in a future update.</span></span>
