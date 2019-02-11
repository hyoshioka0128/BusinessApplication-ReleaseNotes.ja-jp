---
title: テンプレート アプリ用のセルフサービス ビルダー エクスペリエンス
description: テンプレート アプリの作成者は、アプリをインストールしたユーザーがコンテンツを編集できないようにアプリを構成できます。
author: ezaviv
ms.date: 01/21/2019
ms.reviewer: mihart
ms.topic: article
ms.service: business-applications
ms.author: avive
ms.openlocfilehash: cc6f0b6227250b41c7ae9342ad0742f4a42b324f
ms.sourcegitcommit: 9a31d79f2ae098559c294503984e0d9ddc37c0ad
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2019
ms.locfileid: "210249"
---
# <a name="self-service-builder-experience-for-template-apps"></a>テンプレート アプリ用のセルフサービス ビルダー エクスペリエンス

[!include[business-intelligence banner](../../includes/business-intelligence.md)]

Power BI では、ユーザーがテンプレート アプリ ビルダー モードでテンプレート アプリを作成し、既存のワークスペースを Power BI テンプレート アプリに切り替えることができます。これらのテンプレート アプリは、パッケージ化して他のテナントに展開することができます。 テンプレート アプリ パッケージは、タイプごとに 1 つのアーティファクト (1 つのダッシュボード、1 つのレポート、1 つのデータセット、1 つのデータフロー) で構成されます。 テンプレート アプリの作成者は、アプリをインストールしたユーザーがコンテンツを編集できないようにアプリを構成できます。

このような展開パッケージを使用できるシナリオは複数考えられます。 企業内では、テスト環境、運用前環境、運用環境の間でコンテンツを仕上げていくことができます。 システム インテグレーターの場合は、テンプレート アプリを作成して、データの取り込み中にデータフローの一部として実行される "M" コードをベースに、分析ソリューションを提供することができます。つまり、顧客に独自のインサイトを提供するためのデータセットを取得することができます。
