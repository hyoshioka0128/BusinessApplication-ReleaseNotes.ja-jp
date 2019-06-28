---
title: 空白状態で小切手を作成する機能をオフにする
description: 空白状態で小切手を作成する機能をオフにする
author: aprilolson
ms.date: 06/12/2019
ms.reviewer: sericks
ms.topic: article
ms.service: business-applications
ms.author: aolson
ms.openlocfilehash: a19eeabd0d6a2024f7a978e864805610044bdac4
ms.sourcegitcommit: 54ade0d34315b507974a3b0b3953f59f80cb5ce8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/12/2019
ms.locfileid: "1625796"
---
#  <a name="turn-off-the-ability-to-create-checks-with-blank-status"></a><span data-ttu-id="a1359-103">空白状態で小切手を作成する機能をオフにする</span><span class="sxs-lookup"><span data-stu-id="a1359-103">Turn off the ability to create checks with Blank status</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

<span data-ttu-id="a1359-104">この機能は、支払い生成中に印刷される空白の小切手の数を指定する機能を無効にします。</span><span class="sxs-lookup"><span data-stu-id="a1359-104">This feature will turn off the ability to specify the number of blank checks to be printed during payment generation.</span></span> <span data-ttu-id="a1359-105">空白の小切手は、たとえば、破損していて支払いに使用できない小切手を記録するために使用します。</span><span class="sxs-lookup"><span data-stu-id="a1359-105">An example of blank check usage is to record a check that has been damaged and cannot be used for payment.</span></span> <span data-ttu-id="a1359-106">空白の状態で小切手を作成した後、それを削除したりシステムで再利用したりすることはできません。</span><span class="sxs-lookup"><span data-stu-id="a1359-106">After a check has been created with a Blank status, it cannot be deleted or reused in the system.</span></span> <span data-ttu-id="a1359-107">この機能の利点は、使用できない無駄な小切手の在庫につながる可能性があるデータ入力エラーを防ぐことです。</span><span class="sxs-lookup"><span data-stu-id="a1359-107">The benefit of this feature is prevention of data entry errors that could result in unusable, wasted check stock.</span></span>
