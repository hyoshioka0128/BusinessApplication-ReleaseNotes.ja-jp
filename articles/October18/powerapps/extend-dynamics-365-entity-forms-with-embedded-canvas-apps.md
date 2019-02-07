---
title: 埋め込みキャンバス アプリによる Dynamics 365 エンティティ フォームの拡張
description: 任意の Sales、Service、Marketing、またはカスタム エンティティ フォームにキャンバス アプリを埋め込んで、わずかなコーディングによる豊富なカスタマイズのほか、200 以上のデータ ソースをフル活用できます。
author: aneesmsft
ms.reviewer: anneta
ms.date: 01/11/2019
ms.assetid: 131c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: aneesa
audience: Power user
ms.openlocfilehash: 8977c6e0cf0c9f41e799649c000d00ab1d644e0a
ms.sourcegitcommit: abbfbdaff6d71a53e5dd36fecb6673080c49e5d6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/26/2019
ms.locfileid: "289549"
---
# <a name="extend-dynamics-365-entity-forms-with-embedded-canvas-apps-public-preview"></a><span data-ttu-id="ed80e-103">埋め込みキャンバス アプリによる Dynamics 365 エンティティ フォームの拡張 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="ed80e-103">Extend Dynamics 365 entity forms with embedded canvas apps (Public Preview)</span></span>




<span data-ttu-id="ed80e-104">キャンバス アプリにより、アプリ開発者はわずかなコーディングによるカスタマイズ機能を通じて豊富な美しいユーザー エクスペリエンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="ed80e-104">Canvas apps enable app makers to deliver a rich, pixel-perfect user experience via low-code customization capabilities.</span></span> <span data-ttu-id="ed80e-105">また、幅広いクラウド サービス (Office 365 や SharePoint) およびオンプレミス データ ソース (ゲートウェイ経由) を始めとする 200 以上のデータ ソースへの接続に対応しています。</span><span class="sxs-lookup"><span data-stu-id="ed80e-105">They also support connecting to more than 200 data sources including a range of cloud services (such as Office 365 and SharePoint) as well as on-premises data sources (via a gateway).</span></span> <span data-ttu-id="ed80e-106">アプリ開発者は、モデル駆動型フォームにキャンバス アプリを埋め込むことで、これらの機能をモデル駆動型アプリに直接もたらすことができます。</span><span class="sxs-lookup"><span data-stu-id="ed80e-106">Now app makers can bring these capabilities directly into their model-driven apps by embedding canvas apps in their model-driven forms.</span></span> 
 
<span data-ttu-id="ed80e-107">アプリ開発者は、カスタム コントロールを追加するのと同じように、キャンバス アプリをモデル駆動型フォームに埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="ed80e-107">App makers can embed canvas apps in their model-driven forms just like they add custom controls.</span></span> <span data-ttu-id="ed80e-108">モデル駆動型フォームでは、現在のレコード、関連レコード、関連レコード セットのデータ コンテキストを埋め込みキャンバス アプリに渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="ed80e-108">Model-driven forms can also pass data context of the current record, a related record, or a set of related records to an embedded canvas app.</span></span> <span data-ttu-id="ed80e-109">この機能により、アプリ開発者は、豊富なコンテキスト セクション、グリッド、その他のコンポーネントに加え、Common Data Service for Apps のデータを表示するビジュアル、さらには幅広い外部データ ソースを作成できます。</span><span class="sxs-lookup"><span data-stu-id="ed80e-109">This functionality empowers app makers to create rich, contextual sections, grids, and other components, as well as visualizations that display data from Common Data Service for Apps and a wide array of external data sources.</span></span>

<span data-ttu-id="ed80e-110">この機能は、統一インターフェイスでのみ使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="ed80e-110">This feature will be available on Unified Interface only.</span></span> <span data-ttu-id="ed80e-111">プレビュー リリースでは、埋め込みキャンバス アプリのブラウザー ベースの読み取り専用サポートが有効になります。</span><span class="sxs-lookup"><span data-stu-id="ed80e-111">The preview release will enable browser-based, read-only support for the embedded canvas apps.</span></span> <span data-ttu-id="ed80e-112">将来のリリースでは、モバイル デバイスのサポートと、埋め込みキャンバス アプリの編集サポートが有効になります。</span><span class="sxs-lookup"><span data-stu-id="ed80e-112">A future release will enable support for mobile devices and edit support for the embedded canvas apps.</span></span>