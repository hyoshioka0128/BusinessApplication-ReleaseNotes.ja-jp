---
title: PowerApps でのシームレスなフロー作成
description: モデル駆動型によるキャンバスベースのアプリケーション コンテキストでフローを作成できます。
author: stepsic-microsoft-com
ms.reviewer: deonhe
ms.date: 06/26/2019
ms.assetid: 6388bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: stepsic
audience: Power user
ms.openlocfilehash: 3b301706341daeb54d4d39f5533a9eb71ee0621b
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756906"
---
# <a name="seamless-flow-creation-in-powerapps"></a>PowerApps でのシームレスなフロー作成

[!include[microsoft-flow banner](../includes/microsoft-flow.md)]

Microsoft Flow は、モデル駆動型によるキャンバスベースの PowerApps でロジックを設計できる、優れたツールです。 コードを記述する代わりに、ポイントアンドクリックのフロー デザイナーを使ってビジネス ロジックを構築することができます。 ユーザーは、ボタン、アクション、データ入力を使って、フローをアプリ内で簡単に実行できます。 これらのフローは、一方向で実行することもできますし、アプリにデータを返してユーザーに情報を表示することもできます。

さらに、ビジネス プロセス フローを使用すれば、ユーザーを常に追跡し、複数のステージで入力されたデータの一貫性を維持することができます。 たとえば、すべてのユーザーに同じ方法で顧客サービス要求を処理させるフローを作成することもできますし、注文の送信前に承認を要求するフローを作成することもできます。

Microsoft Flow では、ビジネス プロセス フローとインスタント フローの両方を、モデル駆動型によるキャンバスベースのアプリケーション コンテキストで構築できる、シームレスなオーサリング エクスペリエンスを実現しています。 ユーザーは、コマンド バーで **フロー** を選択するだけで、PowerApps Studio 内から高度なフロー作成を行うことができます。 フロー作成をいったんやめても、アプリのコンテキスト内なので、簡単に作成を続行することができます。より本格的にフローを設計したい場合は、新しいタブを開いてフル機能のフロー デザイナーで作業することもできます。もちろん、それまでの作業内容は維持されます。

![PowerApps キャンバス スタジオ内での作成](media/SeamlessFlowcreationinPowerApps-1.png "PowerApps キャンバス スタジオ内での作成")

作成のエクスペリエンスが改善されるだけでなく、機能面でも重要な改善点がいくつかあります。

- **複雑なデータ型を簡単に定義できる**: インスタント フローを使用して、PowerApps で作成されたアプリにデータを返す場合に、JSON 形式を理解していなくても、複雑なデータ型 (ネストしたテーブルやレコードなど) を簡単に定義できるようになりました。
- **フローをデータ ギャラリーにバインドできる**: フローをオンデマンドで呼び出すだけでなく、フローを使用してギャラリー内のデータを追加することも可能になりました。たとえば、SQL でストアド プロシージャを呼び出して、そのデータを返すこともできます。
