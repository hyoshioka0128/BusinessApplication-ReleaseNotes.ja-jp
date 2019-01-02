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
<<<<<<< HEAD
ms.sourcegitcommit: 2ddd4b42d13f15731ed8fd2f46f3376477b2eb3c
ms.openlocfilehash: 471d412ae40cbef021decc560fbc329cfd3fe5d8
ms.contentlocale: ja-jp
ms.lasthandoff: 09/11/2018
=======
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: 471d412ae40cbef021decc560fbc329cfd3fe5d8
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018
>>>>>>> 87e028547d07f7115112632b834c7e86c5555bb3

---
# <a name="update-an-existing-power-bi-app-in-appsource-public-preview"></a>AppSource で既存の Power BI アプリを更新する (パブリック プレビュー)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



アプリケーション ライフサイクル管理 (ALM) については、次の機能が提供されます。

- アプリは Power BI ワークスペースをベースとし、追加の設定 (パラメーター) を使用して提供されます。
- アプリには 3 つのリリース レベルがあります: ワークスペース (WIP) --> パッケージ (リリース候補) --> 公開済みアプリ (AppSource を通じてインストールできる、公開済みのコンテンツ) 。
- リリース レベルごとに、1 つのバージョンが保持されます: WIP のワークスペースが 1 つ、パッケージが 1 つ、公開済みアプリが 1 つ。 公開済みアプリを更新するには、パッケージを展開します。 パッケージを展開すると、AppSource の公開済みアプリが上書きされます。
- アプリの作成は、WIP ワークスペースでいつでも続行できます。
- リリース候補を作成する準備ができたら、パッケージを保存します。

