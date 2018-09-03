---
title: "Azure ワークロード監視用の新しいメトリック"
description: "Power BI Embedded のリソース消費を監視し、構成可能なしきい値を超えたときにアクションをトリガーするために、4 つの新しいメトリックが追加されました。"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 082d21ac-805e-4007-8810-f1838369569c
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 38c5ad6fa4ff1160d482cb5d62a7701990bff15a
ms.contentlocale: ja-jp
ms.lasthandoff: 08/15/2018

---
#  <a name="new-metrics-for-azure-workload-monitoring"></a>Azure ワークロード監視用の新しいメトリック

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Power BI のページ付けされたレポートとデータ フローで新しいワークロードを使用できるようになったため、Power BI Embedded のリソースとワークロードの消費を監視して、構成可能なしきい値を超えたときにアクションをトリガーする、3 つの新しいメトリックが追加されます。 新しいメトリックは、リソースでの各ワークロードを反映します。 新しいメトリックは次のとおりです。

•   CPU 消費量 •   メモリ消費量 •   メモリ コミット消費量 (メモリのページングを含む)

開発者は、Azure を使用してしきい値を定義し、アラートを使用して特定のアクションをトリガーできます (たとえば、特定のモニターが定義済みしきい値を超えたらリソースを自動スケールアップするなど)。

