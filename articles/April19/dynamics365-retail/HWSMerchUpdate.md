---
title: 実行時にハードウェア ステーションのマーチャント プロパティを更新する
description: エンタープライズ環境でハードウェア ステーションを管理しやすくするための変更の概要。
author: rubendel
ms.date: 05/01/2019
ms.assetid: 8cf8e242-945a-45b3-9b88-7d7b960314ba
ms.topic: article
ms.service: business-applications
ms.author: rubendel
ms.reviewer: josaw
ms.openlocfilehash: b703e408bcfc6c0cb28711072b0d45777f29edd7
ms.sourcegitcommit: 7fc1e31dbcdd6afe3b8447803a8e63d77d796e7e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/01/2019
ms.locfileid: "1446541"
---
# <a name="update-hardware-station-merchant-properties-at-runtime"></a><span data-ttu-id="4f02c-103">実行時にハードウェア ステーションのマーチャント プロパティを更新する</span><span class="sxs-lookup"><span data-stu-id="4f02c-103">Update hardware station merchant properties at runtime</span></span>

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

## <a name="business-value"></a><span data-ttu-id="4f02c-104">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4f02c-104">Business value</span></span>

<span data-ttu-id="4f02c-105">スケーラビリティを向上させるためのより広範な取り組みの一環として、特定の Retail コンポーネントの "サイレント" インストールおよびアップグレードをサポートするための作業が行われています。</span><span class="sxs-lookup"><span data-stu-id="4f02c-105">As part of wider efforts to improve scalability, work is being done to support "silent" install and upgrade for certain Retail components.</span></span> <span data-ttu-id="4f02c-106">ハードウェア ステーションの場合、これは設定に関連する特定の側面を変更する必要があることを意味します。</span><span class="sxs-lookup"><span data-stu-id="4f02c-106">For the hardware station, this means certain aspects related to configuration must change.</span></span> <span data-ttu-id="4f02c-107">具体的に言うと、現在のハードウェア ステーションのインストーラーには、ハードウェア ステーションのマーチャント プロパティを設定する構成ユーティリティが含まれています。</span><span class="sxs-lookup"><span data-stu-id="4f02c-107">Specifically, the current hardware station installer includes a configuration utility that sets merchant properties for the hardware station.</span></span> <span data-ttu-id="4f02c-108">このユーティリティは、ハードウェア ステーションのプロパティの更新が必要になるたびに、Azure Active Directory (Azure AD) ユーザーによって物理的に実行される必要があります。</span><span class="sxs-lookup"><span data-stu-id="4f02c-108">This utility must be physcially run by an Azure Active Directory (Azure AD) user every time hardware station properties need an update.</span></span> <span data-ttu-id="4f02c-109">このプロセスはスケールされず、アップグレードを困難にする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4f02c-109">This process does not scale and can make upgrades difficult.</span></span> 
 
## <a name="feature-description"></a><span data-ttu-id="4f02c-110">機能の説明</span><span class="sxs-lookup"><span data-stu-id="4f02c-110">Feature description</span></span>

<span data-ttu-id="4f02c-111">この機能は、マーチャント プロパティの設定プロセスを MPOS ランタイムに移動することにより、ハードウェア ステーションのインストールとマーチャント プロパティの更新をヘッドレスで実行できるようにします。</span><span class="sxs-lookup"><span data-stu-id="4f02c-111">This feature enables headless hardware station installation and merchant properties updates by moving the process of setting merchant properties to MPOS runtime.</span></span> <span data-ttu-id="4f02c-112">マーチャント プロパティ設定ユーティリティはハードウェア ステーションのインストーラーに含まれなくなり、Azure AD ユーザーは、スタンドアロンのインターネット インフォメーション サービス (IIS) ハードウェア ステーションのマーチャント プロパティを更新または設定するためにこのユーティリティを実行する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="4f02c-112">The merchant properties configuration utility will no longer be part of the hardware station installer, so an Azure AD user will not have to run the utility to update or set merchant properties for a standalone Internet Information Services (IIS) hardware station.</span></span> <span data-ttu-id="4f02c-113">代わりに、Modern Point of Sale (MPOS) のサインインおよびアクティブ化の間にマーチャント プロパティが確認されます。</span><span class="sxs-lookup"><span data-stu-id="4f02c-113">Instead, during Modern Point of Sale (MPOS) sign-in and activation, the merchant properties will be checked.</span></span> <span data-ttu-id="4f02c-114">ハードウェア ステーションで見つかったものよりも新しいマーチャント プロパティが小売サーバーにある場合は、新しいマーチャント プロパティがハードウェア ステーションに送信されます。</span><span class="sxs-lookup"><span data-stu-id="4f02c-114">If the retail server has newer merchant properties than those found on the hardware station, the new merchant properties will be sent to the hardware station.</span></span> <span data-ttu-id="4f02c-115">このプロセス全体は、販売時点管理 (POS) ユーザーには見えません。</span><span class="sxs-lookup"><span data-stu-id="4f02c-115">This entire process will be transparent to the Point of Sale (POS) user.</span></span>  
