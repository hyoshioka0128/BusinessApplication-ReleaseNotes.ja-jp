---
title: AppSource で既存の Power BI アプリを更新する
description: AppSource で既存の Power BI アプリを更新する
author: ezaviv
manager: HaydnR
ms.date: 07/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: avive
audience: Admin, end user
ms.openlocfilehash: a4b1086ff6a80c3e4e847536d8d0bfbe48794abd
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "199010"
---
# <a name="update-an-existing-power-bi-app-in-appsource"></a>AppSource で既存の Power BI アプリを更新する

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



アプリケーション ライフサイクル管理 (ALM) については、次の機能が提供されます。

- アプリは Power BI ワークスペースをベースとし、追加の設定 (パラメーター) を使用して提供されます。
- アプリには 3 つのリリース レベルがあります: ワークスペース (WIP) --> パッケージ (リリース候補) --> 公開済みアプリ (AppSource を通じてインストールできる、公開済みのコンテンツ) 。
- リリース レベルごとに、1 つのバージョンが保持されます: WIP のワークスペースが 1 つ、パッケージが 1 つ、公開済みアプリが 1 つ。 公開済みアプリを更新するには、パッケージを展開します。 パッケージを展開すると、AppSource の公開済みアプリが上書きされます。
- アプリの作成は、WIP ワークスペースでいつでも続行できます。
- リリース候補を作成する準備ができたら、パッケージを保存します。
