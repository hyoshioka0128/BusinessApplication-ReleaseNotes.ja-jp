---
title: "ポータル用の SharePoint ドキュメント管理"
description: "ポータル用の SharePoint ドキュメント管理"
author: sandhangitmsft
manager: ramalingamkrishnan
ms.date: 07/22/2018
ms.assetid: aa14cee1-b121-4c02-8937-13e0717e8fb8
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sandhan
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 318636631f44de9d4991ee0733b502fbed2403fa
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---
#  <a name="manage-sharepoint-documents"></a><span data-ttu-id="2c5d8-103">SharePoint ドキュメントの管理</span><span class="sxs-lookup"><span data-stu-id="2c5d8-103">Manage SharePoint documents</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




<span data-ttu-id="2c5d8-104">この機能は、Dynamics 365 アプリケーションのドキュメント管理機能をポータルに拡張し、一貫性のあるエクスペリエンスを提供すると共に、お客様が既存の SharePoint 資産と Dynamics 365 をドキュメント管理に活用できるようにするものです。</span><span class="sxs-lookup"><span data-stu-id="2c5d8-104">This feature extends document management capabilities of Dynamics 365 applications to portals, providing a consistent experience and allowing customers to leverage their existing investments in SharePoint with Dynamics 365 for document management.</span></span>

<span data-ttu-id="2c5d8-105">エンティティ レコードに関連付けられたドキュメントは SharePoint に格納されるので、ポータル ユーザーがそれらを管理できるようになるだけでなく、SharePoint 独自のシームレスなコラボレーション機能を組織で活用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c5d8-105">Documents associated with entity records can be managed by portal users as they are stored in a SharePoint document library, thus also enabling businesses to leverage the seamless collaboration capabilities offered natively by SharePoint.</span></span>

<span data-ttu-id="2c5d8-106">Dynamics 365 のエンティティを使用して構成された SharePoint Online ドキュメント ライブラリは、ポータル エンティティと Web フォームを通じて表示できます。</span><span class="sxs-lookup"><span data-stu-id="2c5d8-106">SharePoint Online document libraries configured with entities in Dynamics 365 can be surfaced via portal entity and web forms.</span></span> <span data-ttu-id="2c5d8-107">これにより、ポータル ユーザーは以下の操作を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="2c5d8-107">This allows portal users to perform the following actions:</span></span>

## <a name="add-documents"></a><span data-ttu-id="2c5d8-108">ドキュメントを追加する</span><span class="sxs-lookup"><span data-stu-id="2c5d8-108">Add documents</span></span>

<span data-ttu-id="2c5d8-109">![サポート案件レコードにファイルを追加する](media/SP_Portal_Add_Files.png "サポート案件レコードにファイルを追加する")</span><span class="sxs-lookup"><span data-stu-id="2c5d8-109">![Add files to a case record](media/SP_Portal_Add_Files.png "Add files to a case record")</span></span>

## <a name="view-and-download-documents"></a><span data-ttu-id="2c5d8-110">ドキュメントを表示し、ダウンロードする</span><span class="sxs-lookup"><span data-stu-id="2c5d8-110">View and download documents</span></span>

<span data-ttu-id="2c5d8-111">![サポート案件レコードに関連するドキュメントを表示する](media/SP_Portal_View_Files.png "サポート案件レコードに関連するドキュメントを表示する")</span><span class="sxs-lookup"><span data-stu-id="2c5d8-111">![View documents related to case record](media/SP_Portal_View_Files.png "View documents related to case record")</span></span> 

## <a name="create-folder"></a><span data-ttu-id="2c5d8-112">フォルダーを作成する</span><span class="sxs-lookup"><span data-stu-id="2c5d8-112">Create folder</span></span>

<span data-ttu-id="2c5d8-113">![ドキュメント一覧内にサブフォルダーを作成してファイルを整理する](media/SP_Portal_Create_Folder.png "ドキュメント一覧内にサブフォルダーを作成してファイルを整理する")</span><span class="sxs-lookup"><span data-stu-id="2c5d8-113">![Create subfolder within document list to organize files](media/SP_Portal_Create_Folder.png "Create subfolder within document list to organize files")</span></span>

## <a name="delete-document"></a><span data-ttu-id="2c5d8-114">ドキュメントを削除する</span><span class="sxs-lookup"><span data-stu-id="2c5d8-114">Delete document</span></span>

<span data-ttu-id="2c5d8-115">![サポート案件レコードからファイルを削除する](media/SP_Portal_Delete_File.png "サポート案件レコードからファイルを削除する")</span><span class="sxs-lookup"><span data-stu-id="2c5d8-115">![Delete files from a case record](media/SP_Portal_Delete_File.png "Delete files from a case record")</span></span>

<!--
### Who uses this feature
This feature is intended for portal end users, allowing them access to SharePoint documents from portal web pages.
Portal administrators customize the form to display document lists on a portal. Entity permission configuration is used to control actions available to portal end users on files and folders.
### Setup required
This feature requires that document management is set up for [Dynamics 365 with SharePoint Online](https://go.microsoft.com/fwlink/p/?linkid=859386).
-->

## <a name="quick-steps"></a><span data-ttu-id="2c5d8-116">簡単な手順</span><span class="sxs-lookup"><span data-stu-id="2c5d8-116">Quick steps</span></span>

### <a name="configuring-document-list-on-entity-forms"></a><span data-ttu-id="2c5d8-117">エンティティ フォームのドキュメント一覧を構成する</span><span class="sxs-lookup"><span data-stu-id="2c5d8-117">Configuring document list on entity forms</span></span>

<span data-ttu-id="2c5d8-118">![サポート案件エンティティ フォームのドキュメント一覧サブグリッドを構成する](media/SP_Portal_configure_entity_form_doc_location.png "ドキュメントの場所サブグリッドの構成")</span><span class="sxs-lookup"><span data-stu-id="2c5d8-118">![Configure document list subgrid on case entity form](media/SP_Portal_configure_entity_form_doc_location.png "Document location subgrid configuration")</span></span>

### <a name="configuring-permissions-on-document-list"></a><span data-ttu-id="2c5d8-119">ドキュメント一覧に対するアクセス許可を構成する</span><span class="sxs-lookup"><span data-stu-id="2c5d8-119">Configuring permissions on document list</span></span>

<span data-ttu-id="2c5d8-120">![ドキュメント一覧のアクセス許可を構成する](media/SP_Portal_configure_doc_permissions.png "アクセス許可を構成する")</span><span class="sxs-lookup"><span data-stu-id="2c5d8-120">![Configure document list permissions](media/SP_Portal_configure_doc_permissions.png "Configure permissions")</span></span>

<span data-ttu-id="2c5d8-121">アクセス許可ベースのモデルを使用すると、特定の顧客シナリオを対象に、ファイルやフォルダーに対するこれらの操作を管理できます。</span><span class="sxs-lookup"><span data-stu-id="2c5d8-121">A permissions-based model allows controlling these actions on files and folders for specific customer scenarios.</span></span>

<!--
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
Global
-->

## <a name="wed-like-to-thank"></a><span data-ttu-id="2c5d8-122">謝辞</span><span class="sxs-lookup"><span data-stu-id="2c5d8-122">We'd like to thank</span></span>

<span data-ttu-id="2c5d8-123">優先順位付けに役立つ投票とコメントを「[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=d3398770-f9ac-e611-80c2-00155d4616d6)」にお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="2c5d8-123">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=d3398770-f9ac-e611-80c2-00155d4616d6) with votes and comments that helped us prioritize it.</span></span>

