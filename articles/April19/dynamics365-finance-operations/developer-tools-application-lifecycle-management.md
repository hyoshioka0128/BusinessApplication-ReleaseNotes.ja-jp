---
title: 開発者ツールとアプリケーション ライフサイクルの管理
description: Finance and Operations と Retail の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの VM の利用可能性を通して簡単かつ確実に行うことができます。
author: robadawy
ms.date: 01/21/2019
ms.topic: article
ms.service: business-applications
ms.author: robadawy
ms.openlocfilehash: cfdca7166381ea517ec88f0a1ebb2a15662a4802
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225152"
---
#  <a name="developer-tools-and-application-lifecycle-management"></a>開発者ツールとアプリケーション ライフサイクルの管理
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]





Unified Operations (Finance and Operations、Retail) の開発環境の設定は、すぐに使用できるクラウドおよびオンプレミスの仮想マシン (VM) の利用可能性を通して簡単かつ確実に行うことができます。 この機能は優れていますが、顧客やパートナーにとっては、開発チームが拡大したときに、または複数のアプリケーションや同じアプリケーションの複数のバージョンを開発するときに、多くの開発環境を管理する必要があるため、コストがかかることがわかっています。 さらに、当社の自動ビルド フレームワークも (Azure DevOps に加えて) 同様の VM に依存しており、Lifecycle Services (LCS) やサンドボックス環境へのビルドの自動展開は提供されていません。

Unified Operations 開発ツール、アプリケーション メタデータ、およびプラットフォームは、同じ環境で複数のアプリケーションを開発できるように、標準モジュールにコンポーネント化されています。 これにより、ステージは事前構成された VM において開発ツールの依存関係を削除するように設定され、ローカル コンピュータでの開発エクスペリエンスが向上します。

さらに、ビルド自動化フレームワークは VM を必要とせず、Azure DevOps のビルド機能のみに依存します。 リリース候補であるビルドを、LCS およびサンドボックス クラウド環境に自動的に展開できます。

新しいお客様の場合、LCS の事前構成済み開発環境 (VM) はお客様の Azure サブスクリプションでホストされ、Microsoft によって管理されることはありません。 これらの環境を実行するコストを削減するため、新しい LCS 機能が導入されます。 Microsoft によって管理される Tier-1 環境 (現在は開発/テスト環境) は、テストおよび構成環境のみとなり (RDP アクセスは不可)、他の種類のクラウド環境と同じアーキテクチャになります。
