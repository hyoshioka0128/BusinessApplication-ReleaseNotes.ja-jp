---
title: ビジネス プロセス フロー内のカスタム コントロール
description: ビジネス プロセス フローでは、豊富なデータのビジュアル化のためのカスタム コントロールがサポートされます
author: KaranSr
ms.reviewer: mkaur
ms.date: 06/26/2019
ms.assetid: 4587bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: karansr
audience: Power user
ms.openlocfilehash: ade2b4e15474b8149478eff68ec93532c4fec355
ms.sourcegitcommit: 13a94b4173f5b62040e0eb13b7dffe7a901e3b29
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "1756767"
---
# <a name="custom-controls-in-business-process-flows-public-preview"></a>ビジネス プロセス フロー内のカスタム コントロール (パブリック プレビュー)

ビジネス プロセス フローは、ステージとステップの形式で作業を行う手順をガイドする一種のフローです。 ステージは、ユーザーがプロセスのどこにいるかを示します。 これらの各ステージでのデータは、Common Data Service のフィールドにバインドされており、これまでは、フィールドの種類 (テキスト ボックス、ドロップダウン リストなど) の既定のビジュアル化だけが許可されていました。

マイクロソフトでは、開発者がこの機能の使用を開始できるようにするテクニカル プレビューを発表しています。 これで、開発者はカスタム コントロールを使用して、スライダー、放射状ノブ、LinkedIn コントロールなどの豊富なビジュアル化をフロー ステップに追加し、ビジネス プロセスのユーザーに魅力的なエクスペリエンスを提供できるようになります。 このプレビュー バージョンでは、次の方法でこれを設定できます。

1. 関連するエンティティ フォームでのカスタム コントロールの構成。
1. フォーム XML の生成とエクスポート。
1. 関連エンティティ フォームからフォーム XML へのカスタム コントロール構成のコピー。
1. Common Data Service へのカスタマイズのインポート。

完了したら、モデル駆動型アプリでフローをテストし、追加したコントロールを表示できます。

![カスタム コントロールの例](media/custom-controls_01.png "カスタム コントロールの例")

この機能を試すには XML を使用する必要があります。現時点では技術ユーザーだけが使用することをお勧めします。 これを設定する方法の詳細については、こちらの[詳細な手順を示すチュートリアル](https://powerusers.microsoft.com/t5/Microsoft-Flow-Community-Blog/Preview-Custom-Controls-in-Business-Process-Flows/ba-p/263237)をご覧ください。
