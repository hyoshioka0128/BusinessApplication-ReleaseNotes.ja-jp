---
title: ネットワーク プリンターのシステム管理
description: 法人間でネットワーク プリンターを管理するためのシステム管理ツール
author: TJVass
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: TJVass
ms.openlocfilehash: 0478147d5445c43ceaaa35c5d4d53da19ada164f
ms.sourcegitcommit: 1a326997459281936558d131b647fad3a28e5aef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2019
ms.locfileid: "288000"
---
#  <a name="system-management-of-network-printers"></a><span data-ttu-id="41764-103">ネットワーク プリンターのシステム管理</span><span class="sxs-lookup"><span data-stu-id="41764-103">System management of network printers</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]


<span data-ttu-id="41764-104">組織のネットワーク プリンターの管理を担当する管理者向けに、新しいツールが提供されます。</span><span class="sxs-lookup"><span data-stu-id="41764-104">Take advantage of a new tool for administrators to use when tasked with managing network printers for the organization.</span></span> <span data-ttu-id="41764-105">**システム ネットワーク プリンター** ページでは、管理者が単一のビューを使用して、すべての組織の設定を更新したり、ネットワーク プリンターを削除したりできます。</span><span class="sxs-lookup"><span data-stu-id="41764-105">The **System network printers** page allows administrators to update settings and delete network printers across all organizations using a single view.</span></span>  <span data-ttu-id="41764-106">この管理ユーティリティは、Dynamics 365 for Finance and Operations アプリケーション内で使用できるネットワーク プリンター デバイスの構成タスクを簡素化するために設計されています。</span><span class="sxs-lookup"><span data-stu-id="41764-106">This management utility is designed to simplify the task of configuring network printer devices available within Dynamics 365 for Finance and Operations applications.</span></span>

<span data-ttu-id="41764-107">![システム ネットワーク プリンター フォーム](media/system-network-printers-form.png "システム ネットワーク プリンター フォーム")</span><span class="sxs-lookup"><span data-stu-id="41764-107">![System network printers form](media/system-network-printers-form.png "System network printers form")</span></span>

## <a name="common-scenarios"></a><span data-ttu-id="41764-108">一般的なシナリオ</span><span class="sxs-lookup"><span data-stu-id="41764-108">Common scenarios</span></span>

- <span data-ttu-id="41764-109">**システム管理者がネットワーク プリンター インスタンスを削除する必要がある**: これは、ネットワーク プリンターのパスが更新された場合や、ハードウェアが交換された場合によく起こります。</span><span class="sxs-lookup"><span data-stu-id="41764-109">**A system administrator needs to delete a network printer instance**: This is common for cases where the network printer path is updated or hardware has been replaced.</span></span>
- <span data-ttu-id="41764-110">**プリンター キュー内のすべてのドキュメントを削除する必要がある**: 印刷を待機しているサービスによってレンダリングされたドキュメントは、**システム ネットワーク プリンター** ページにあるオプションを使用して削除できます。</span><span class="sxs-lookup"><span data-stu-id="41764-110">**An organization wants to purge all documents in the printer queue**: Documents rendered by the service that are waiting to be printed can be deleted using options available on the **System network printers** page.</span></span>
- <span data-ttu-id="41764-111">**複数の法人に対するネットワーク プリンターの利用可能性をすばやく切り替える**: 単一のビューを使用して、プリンターのプロパティを管理できます (複数の法人に対するプリンターのアクティブ状態など)。</span><span class="sxs-lookup"><span data-stu-id="41764-111">**Quickly toggle availability of network printers for multiple legal entities**: You can manage the printer properties including the active state for a printer in multiple legal entities using a single view.</span></span>
- <span data-ttu-id="41764-112">**複数の法人用のネットワーク プリンターにわかりやすい名前を付ける**: 各法人のユーザーが容易に区別できるよう、プリンターにわかりやすい名前と説明を設定できます。</span><span class="sxs-lookup"><span data-stu-id="41764-112">**Provide friendly names for network printers for multiple legal entities**: You can establish friendly names and descriptions for printers that make sense to the users associated with individual legal entities.</span></span>

<span data-ttu-id="41764-113">これは、アクティブな印刷指示を取り消すための回復ツールであると同時に、法人間をまたいだ組織全体のネットワーク プリンター設定を簡単に管理できるようにするためのツールでもあります。</span><span class="sxs-lookup"><span data-stu-id="41764-113">This is both a recovery tool for cancelling active print instructions and a means of simplifying the task of managing network printer settings across legal entities for the entire organization.</span></span>
