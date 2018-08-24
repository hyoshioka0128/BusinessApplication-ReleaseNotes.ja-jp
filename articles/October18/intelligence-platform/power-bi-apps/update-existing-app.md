---
title: "AppSource で既存の Power BI アプリを更新する"
description: "AppSource で既存の Power BI アプリを更新する"
author: ezaviv
manager: HaydnR
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: avive
audience: Admin, end user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: a870e8f0d03f19cfd9ba3d93a7bcfce85524d332
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="update-an-existing-power-bi-app-in-appsource"></a>AppSource で既存の Power BI アプリを更新する

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



アプリケーション ライフサイクル管理 (ALM) については、次の機能が提供されます。

- アプリは Power BI ワークスペースをベースとし、追加の設定 (パラメーター) を使用して提供されます。
- アプリには 3 つのリリース レベルがあります: ワークスペース (WIP) --> パッケージ (リリース候補) --> 公開済みアプリ (AppSource を通じてインストールできる、公開済みのコンテンツ) 。
- リリース レベルごとに、1 つのバージョンが保持されます: WIP のワークスペースが 1 つ、パッケージが 1 つ、公開済みアプリが 1 つ。 公開済みアプリを更新するには、パッケージを展開します。 パッケージを展開すると、AppSource の公開済みアプリが上書きされます。
- アプリの作成は、WIP ワークスペースでいつでも続行できます。
- リリース候補を作成する準備ができたら、パッケージを保存します。

