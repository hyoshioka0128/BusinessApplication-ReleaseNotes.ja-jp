---
title: 開発者ツールとアプリケーション ライフサイクルの管理
description: Finance and Operations と Retail の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの VM の利用可能性を通して簡単かつ確実に行うことができます。
author: robadawy
ms.date: 06/24/2019
ms.topic: article
ms.service: business-applications
ms.author: robadawy
ms.openlocfilehash: d515148e3a4848101762bd2f08276b271aa2a5e2
ms.sourcegitcommit: 0ea5527b0231308498194bb834c920749b8aae06
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/25/2019
ms.locfileid: "1703027"
---
#  <a name="developer-tools-and-application-lifecycle-management"></a>開発者ツールとアプリケーション ライフサイクルの管理
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





Unified Operations (Finance and Operations、Retail) の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの仮想マシン (VM) の利用可能性を通して簡単かつ確実に行うことができます。 この機能は優れていますが、顧客やパートナーにとっては、開発チームが拡大したときに、または複数のアプリケーションや同じアプリケーションの複数のバージョンを開発するときに、多くの開発環境を管理する必要があるため、コストがかかることがわかっています。 さらに、当社の自動ビルド フレームワークも (Azure DevOps に加えて) 同様の VM に依存しており、Lifecycle Services (LCS) やサンドボックス環境へのビルドの自動展開は提供されていません。

Unified Operations 開発ツール、アプリケーション メタデータ、およびプラットフォームは、同じ環境で複数のアプリケーションを開発できるように、標準モジュールにコンポーネント化されています。 これにより、ステージは事前構成された VM において開発ツールの依存関係を削除するように設定され、ローカル コンピュータでの開発エクスペリエンスが向上します。

さらに、ビルド自動化フレームワークは VM を必要とせず、Azure DevOps のビルド機能のみに依存します。 リリース候補であるビルドを、LCS およびサンドボックス クラウド環境に自動的に展開できます。

更新: 2019 年 4 月 1 日のリリースに間に合うように、Visual Studio Marketplace には Finance and Operations カスタム ビルド (AOT デプロイ可能パッケージ) をアップロードおよびデプロイするための Azure DevOps タスクが含まれるようになりました。 詳細および関連するお知らせについては、[Dynamics 365 for Finance and Operations での開発とカスタマイズに関するインサイダーのヒント](https://community.dynamics.com/365/financeandoperations/b/newdynamicsax)のブログを参照してください。
