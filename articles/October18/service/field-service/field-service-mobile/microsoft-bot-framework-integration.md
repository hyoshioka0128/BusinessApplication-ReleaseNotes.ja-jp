---
title: Microsoft Bot Framework 統合
description: Microsoft Bot Framework 統合
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: f98775be-f51b-4aaa-86ba-bf14dfaf54d4
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: 0b8e452a7fbe1e1f21d6ce27b6d7fa8631d84da8
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199537"
---
#  <a name="microsoft-bot-framework-integration"></a><span data-ttu-id="388b2-103">Microsoft Bot Framework 統合</span><span class="sxs-lookup"><span data-stu-id="388b2-103">Microsoft Bot Framework integration</span></span>

[!include[field-service banner](../../../includes/field-service.md)]




<span data-ttu-id="388b2-104">ほとんどのフィールド サービス作業には、特定の職務に対して繰り返される一連の同じ手順 (出張の作業指示書の状態の更新、作業指示書の指示を開く、作業指示書のサービス タスクの表示など) があります。</span><span class="sxs-lookup"><span data-stu-id="388b2-104">Most field service work involves a set of the same steps that are repeated on any given job: update the status of a work order to traveling, open the directions for a work order, view the service tasks for a work order, and so on.</span></span> <span data-ttu-id="388b2-105">これらのタスクは、技術者にモバイル アプリケーションでのクリックを要求する代わりに会話やハンズフリーのエクスペリエンスにすることで能率化できます。</span><span class="sxs-lookup"><span data-stu-id="388b2-105">These tasks can be streamlined through conversational and even hands-free experiences as opposed to requiring technicians to click through a mobile application.</span></span> 

<span data-ttu-id="388b2-106">Microsoft では、Microsoft Bot Framework で開発したボットをモバイル アプリで公開したり、Dynamics とのインターフェイスをとるボット コードをテンプレート化して、技術者が作業をより迅速に完了するために使用できる独自のボットをすばやく稼働状態にしたりする機能を提供しています。</span><span class="sxs-lookup"><span data-stu-id="388b2-106">We now provide the ability to surface a bot developed with the Microsoft Bot Framework in our mobile app as well as template bot code interfacing with Dynamics to get your own bots up and running quickly for use by technicians to get their work done faster.</span></span> <span data-ttu-id="388b2-107">Dynamics 365 CE 組織に対するボットの認証は Microsoft が処理するので、ユーザー認証を 2 回行う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="388b2-107">We handle the authentication of your bot to your Dynamics 365 CE organization so that there is no need to have the user authenticate twice.</span></span>


