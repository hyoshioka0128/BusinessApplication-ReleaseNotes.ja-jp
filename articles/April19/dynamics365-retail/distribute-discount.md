---
title: 明細行間に割引を分散する
description: 最安値組み合わせ割引のために明細行間に割引を分散させます
author: ReneeW-CPub
ms.date: 05/21/2019
ms.topic: article
ms.service: business-applications
ms.author: shajain
ms.openlocfilehash: 2d6d642fc799748799259ede89cd040cf11f7842
ms.sourcegitcommit: cab3880e061232d8975a39a1fb6952556bd55274
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "1595039"
---
#  <a name="distribute-discount-across-lines-for-least-expensive-discounts"></a>最安値割引のために明細行間に割引を分散させる
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]


## <a name="business-value"></a>ビジネス バリュー

今日の小売業者は、顧客に製品を購入させるために複数の種類のプロモーションを行っています。 しかし、顧客は購入した商品の一部または全部を返品することがあります。 一般に、返品された商品は高い割引で販売されるため、小売業者の収益に大きな影響を与えます。 返品による損失を減らすことができる改善は、小売業者にとって非常に有益です。

## <a name="feature-description"></a>機能の説明

Dynamics 365 for Retail では、カートに入っている他の品目に依存する多くの割引がサポートされています。たとえば、数量、組み合わせ、しきい値などの割引です。 ほとんどの場合、適用可能な割引はすべての割引明細行に比例的に分散されます。 ただし、"最安値組み合わせ" 割引の場合は、割引は最も安い明細行にのみ適用されます。 たとえば、"2 つ買えば 1 つ無料" では、最も安い品目は無料になり、カートには他の 2 つの品目の全額が表示されます。 顧客が全額品目を両方とも返品した場合、顧客は 3 番目の品目を無料で入手することになり、小売業者にとっての損失となります。 この機能を使用すると、小売業者はオプションで該当するすべての明細行に割引を分散できるため、返品による損失を減らすことができます。 この機能は、**小売パラメーター** ページの**割引**タブにある**最安値割引の割引を分散させる**パラメーターをオンにすることで有効にできます。
