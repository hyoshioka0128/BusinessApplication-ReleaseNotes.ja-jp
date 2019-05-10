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
# <a name="update-hardware-station-merchant-properties-at-runtime"></a>実行時にハードウェア ステーションのマーチャント プロパティを更新する

[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

## <a name="business-value"></a>ビジネス バリュー

スケーラビリティを向上させるためのより広範な取り組みの一環として、特定の Retail コンポーネントの "サイレント" インストールおよびアップグレードをサポートするための作業が行われています。 ハードウェア ステーションの場合、これは設定に関連する特定の側面を変更する必要があることを意味します。 具体的に言うと、現在のハードウェア ステーションのインストーラーには、ハードウェア ステーションのマーチャント プロパティを設定する構成ユーティリティが含まれています。 このユーティリティは、ハードウェア ステーションのプロパティの更新が必要になるたびに、Azure Active Directory (Azure AD) ユーザーによって物理的に実行される必要があります。 このプロセスはスケールされず、アップグレードを困難にする可能性があります。 
 
## <a name="feature-description"></a>機能の説明

この機能は、マーチャント プロパティの設定プロセスを MPOS ランタイムに移動することにより、ハードウェア ステーションのインストールとマーチャント プロパティの更新をヘッドレスで実行できるようにします。 マーチャント プロパティ設定ユーティリティはハードウェア ステーションのインストーラーに含まれなくなり、Azure AD ユーザーは、スタンドアロンのインターネット インフォメーション サービス (IIS) ハードウェア ステーションのマーチャント プロパティを更新または設定するためにこのユーティリティを実行する必要がなくなります。 代わりに、Modern Point of Sale (MPOS) のサインインおよびアクティブ化の間にマーチャント プロパティが確認されます。 ハードウェア ステーションで見つかったものよりも新しいマーチャント プロパティが小売サーバーにある場合は、新しいマーチャント プロパティがハードウェア ステーションに送信されます。 このプロセス全体は、販売時点管理 (POS) ユーザーには見えません。  
