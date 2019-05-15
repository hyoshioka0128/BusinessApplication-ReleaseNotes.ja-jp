---
title: 高度なウェーブ ラベル印刷
description: ''
author: Mirzaab
ms.date: 02/12/2019
ms.reviewer: shylaw
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
ms.openlocfilehash: 5cb50efd59637d4aca5e989244bcc64ec0acb7ea
ms.sourcegitcommit: 921dde7a25596a81c049162eee650d7a2009f17d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2019
ms.locfileid: "1225190"
---
# <a name="advanced-wave-label-printing"></a>高度なウェーブ ラベル印刷

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

この機能では、新しいウェーブ ステップ法の導入により、Microsoft Dynamics 365 for Finance and Operations でのラベル印刷に対する代替アプローチが提供されます。 新しい方法では、ウェーブ実行プロセスの間にウェーブ テンプレートから直接ラベルを作成および印刷することができます。 そのため、モバイル デバイスで作業指示書が実行される前に、ラベルを使用できるようになります。 これにより、異なる方法でラベルを取り扱うのが望ましいシナリオに対応して、作業者はピッキング後だけでなくピッキング中にも必要なラベルを使用して添付できるようになります。

この機能では、新しい機能によって印刷されるすべてのラベルに使用するために ZPL ラベル レイアウトが作成される場合に、新しいラベル レイアウト フォームが導入されます。 新しいラベル レイアウトは、ヘッダー、本文、フッターの 3 つのセクションに分かれており、繰り返し構造を持つラベルを印刷することができます。 使用するラベル レイアウトをシステムに指示するラベル テンプレートは、導入される 2 番目のフォームです。 ここでは、ユーザーは、ラベルを印刷するプリンターを指定したり、必要な場合は、一度に複数のプリンターでラベルを印刷したりすることもできます。 印刷されたラベルの概要をさらに拡張するため、ラベル履歴ページが導入され、この設定で作成されたすべてのラベルの記録が表示されます。

この設定を使用すると、作業ヘッダーに基づいてラベルを印刷して並べたり、作業ヘッダーごとの切れ目ラベル、コンテナー コンテンツ ラベル、ケース ラベル、その他の類似ラベルを印刷したりできます。

> [!NOTE]
> この機能は、ドキュメント ルーティングによる既存のラベル印刷機能に代わるものではありません。
