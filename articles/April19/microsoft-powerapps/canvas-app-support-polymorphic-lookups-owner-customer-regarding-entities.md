---
title: キャンバス アプリによる所有者、顧客、関連エンティティに対するポリモーフィック ルックアップのサポート
description: キャンバス アプリでは、新しいデータ型とヘルパー関数を使用して、タイプセーフな方法で所有者、顧客、関連ポリモーフィック ルックアップ フィールドにアクセスできます。
author: gregli-msft
ms.reviewer: pehecke
ms.date: 07/16/2019
ms.assetid: c186bed6-565e-e911-a973-000d3a1c79c5
ms.topic: article
ms.service: business-applications
ms.author: gregli
audience: Power user
ms.openlocfilehash: 69c85031d5702871f7b96c2490f1dd9f41a9c88a
ms.sourcegitcommit: eed373714b1975b10d4a4e3b186f2116f9b6c06c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/10/2019
ms.locfileid: "1994295"
---
# <a name="canvas-app-support-for-polymorphic-lookups-to-the-owner-customer-and-regarding-entities"></a>キャンバス アプリによる所有者、顧客、関連エンティティに対するポリモーフィック ルックアップのサポート



キャンバス アプリ メーカーは、**所有者**、**顧客**、**関連**エンティティに対するポリモーフィック ルックアップを厳密に型指定された方法で操作できます。 キャンバス アプリの式言語では、これらの参照を操作するために**レコードの参照**データ型と **IsType** および **AsType** 関数を追加しました。 この機能では、**アプリの設定**の下の **CDS のリレーショナル データ、オプション セット、その他の新機能**の設定を有効にする必要があります。これは既定で有効になっています。 

この変更を行う前は、これらのフィールドをブロックしていました。ポリモーフィック ルックアップは Common Data Service で型指定なしで公開され、キャンバス アプリは本質的に厳密に型指定されるためです。 これらのフィールドを操作するには、アプリ メーカーが GUID ID とエンティティ タイプ文字列を管理する必要があり、マイクロソフトでは、これらのフィールドを使用可能にする前に、より優れたエクスペリエンスを提供したいと考えていました。
