---
title: 電子申告 - 生成されたファイルの後処理
description: 電子申告の後処理機能により、生成されたファイルを処理するための追加機能が可能になります。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: b7894f45c4392977d9dac39b7f845d5078fcd424
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225188"
---
# <a name="electronic-reporting---post-processing-of-generated-files"></a><span data-ttu-id="d559a-103">電子申告 - 生成されたファイルの後処理</span><span class="sxs-lookup"><span data-stu-id="d559a-103">Electronic reporting - Post-processing of generated files</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="d559a-104">電子申告の既存の機能により、ビジネス ユーザーは次のことを実行できます。</span><span class="sxs-lookup"><span data-stu-id="d559a-104">Existing functionality in electronic reporting allows business users to do the following:</span></span>

- <span data-ttu-id="d559a-105">電子ドキュメントのレイアウトを構成する。</span><span class="sxs-lookup"><span data-stu-id="d559a-105">Configure the layout of an electronic document.</span></span>
- <span data-ttu-id="d559a-106">実行時にドキュメントに入力するデータ ソースを指定する。</span><span class="sxs-lookup"><span data-stu-id="d559a-106">Specify data sources to fill in the document at run time.</span></span>
- <span data-ttu-id="d559a-107">生成された電子ドキュメントの出力先 (ファイリングとメール送信) を割り当てる。</span><span class="sxs-lookup"><span data-stu-id="d559a-107">Assign destinations (filing and emailing) for the generated electronic document.</span></span> 

<span data-ttu-id="d559a-108">この機能がないと、ユーザーは生成されたドキュメントに対する追加の出力先を構成できず、生成されたドキュメントを実行時に完全に変更するためのカスタム変換を適用することができません。</span><span class="sxs-lookup"><span data-stu-id="d559a-108">Without this feature, the user can't configure additional destinations for the generated document and can’t apply custom transformations to entirely modify the generated document at run time.</span></span> <span data-ttu-id="d559a-109">この機能が提供される前は、これを行うには、独自の難しいカスタマイズを作成する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="d559a-109">To get this functionality before this feature, you had to create a unique and difficult customization.</span></span> <span data-ttu-id="d559a-110">この機能により、ビジネス ユーザーは、Finance and Operations の既存のロジックを再利用し、関連するアプリケーションの機能 (ファイルの暗号化、別の形式への変換、直接印刷など) を使用して、必要な後処理操作を構成できます。</span><span class="sxs-lookup"><span data-stu-id="d559a-110">This feature gives more power to business users and allows configuring the required post-processing actions by reusing existing logic of Finance and Operations as well as the functionality of surrounding applications (files encryption, conversion to another format, direct printing, and so on).</span></span>
