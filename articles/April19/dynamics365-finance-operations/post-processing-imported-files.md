---
title: 電子申告 - インポートされたファイルの後処理
description: 電子申告のインポート機能は、フォルダーを使用して次に処理するファイル セットを取得します。
author: NickSelin
ms.date: 01/21/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: nselin
ms.openlocfilehash: ed68377e31862e792b5cdf3e4ee98b7bb3dcca4e
ms.sourcegitcommit: 3c1c87393de3c81395a981f7eea040c5ee62ab45
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "285019"
---
#  <a name="electronic-reporting---post-processing-of-imported-files"></a><span data-ttu-id="949ed-103">電子申告 - インポートされたファイルの後処理</span><span class="sxs-lookup"><span data-stu-id="949ed-103">Electronic reporting - Post-processing of imported files</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="949ed-104">電子申告 (ER) のインポート機能は、SharePoint のフォルダーを使用して次に処理するファイル セットを取得します。</span><span class="sxs-lookup"><span data-stu-id="949ed-104">Import functionality in electronic reporting (ER) uses SharePoint folders to get the next set of files for processing.</span></span> <span data-ttu-id="949ed-105">現在のところ、処理されたファイルを自動的に管理する手順はありません。たとえば、正常に処理されたファイルは自動的に SharePoint のソース フォルダーから削除され、別の場所に移動することはできません。</span><span class="sxs-lookup"><span data-stu-id="949ed-105">As of now, there is no automatic procedure to manage processed files; for example, successfully processed files are automatically deleted from a SharePoint source folder and can’t be moved to another location.</span></span> <span data-ttu-id="949ed-106">これにより、手動での作業が追加で発生し、エラーを招く可能性があります。</span><span class="sxs-lookup"><span data-stu-id="949ed-106">It results in additional manual work and potential errors.</span></span> <span data-ttu-id="949ed-107">この機能はこの手順を自動化し、後処理のアクションを構成できます。</span><span class="sxs-lookup"><span data-stu-id="949ed-107">This feature automates this procedure and allows configuring of the post-processing actions.</span></span> <span data-ttu-id="949ed-108">ER の形式のソース設定を変更することで、ユーザーは次のアクションを構成できます。</span><span class="sxs-lookup"><span data-stu-id="949ed-108">By changing source settings of an ER format, the user can configure the following actions:</span></span>

- <span data-ttu-id="949ed-109">正常に処理されたファイルの場合:</span><span class="sxs-lookup"><span data-stu-id="949ed-109">For successfully processed files:</span></span>
  - <span data-ttu-id="949ed-110">ファイルを SharePoint のソース フォルダーから削除する</span><span class="sxs-lookup"><span data-stu-id="949ed-110">Delete files from the source SharePoint folder</span></span>
  - <span data-ttu-id="949ed-111">ファイルを SharePoint の別のフォルダーに移動する</span><span class="sxs-lookup"><span data-stu-id="949ed-111">Move files to another SharePoint folder</span></span>
- <span data-ttu-id="949ed-112">警告ありで処理されたファイルの場合:</span><span class="sxs-lookup"><span data-stu-id="949ed-112">For processed-with-warning files:</span></span>
  - <span data-ttu-id="949ed-113">ファイルを SharePoint のソース フォルダーに保持する</span><span class="sxs-lookup"><span data-stu-id="949ed-113">Keep files in the source SharePoint folder</span></span>
  - <span data-ttu-id="949ed-114">ファイルを SharePoint の別のフォルダーに移動する</span><span class="sxs-lookup"><span data-stu-id="949ed-114">Move files to another SharePoint folder</span></span>
- <span data-ttu-id="949ed-115">失敗したファイルの場合:</span><span class="sxs-lookup"><span data-stu-id="949ed-115">For failed files:</span></span>
  - <span data-ttu-id="949ed-116">ファイルを SharePoint のソース フォルダーに保持する</span><span class="sxs-lookup"><span data-stu-id="949ed-116">Keep files in the source SharePoint folder</span></span>
  - <span data-ttu-id="949ed-117">ファイルを SharePoint の別のフォルダーに移動する</span><span class="sxs-lookup"><span data-stu-id="949ed-117">Move files to another SharePoint folder</span></span>

<span data-ttu-id="949ed-118">![SharePoint のソース設定](media/ER-post-process.png "SharePoint のソース設定")</span><span class="sxs-lookup"><span data-stu-id="949ed-118">![SharePoint source settings](media/ER-post-process.png "SharePoint source settings")</span></span>  
