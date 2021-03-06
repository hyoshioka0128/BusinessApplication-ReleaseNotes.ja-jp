---
title: Azure ワークロード監視用の新しい指標
description: Power BI Embedded のリソース消費を監視し、構成可能なしきい値を超えたときにアクションをトリガーするために、4 つの新しいメトリックが追加されました。
author: Annbe
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 082d21ac-805e-4007-8810-f1838369569c
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: Annbe
audience: Admin
ms.openlocfilehash: b3d24273401dcee8ca67c3552fa42d89aa55f2f3
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200080"
---
#  <a name="new-metrics-for-azure-workload-monitoring"></a>Azure ワークロード監視用の新しい指標

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Power BI のページ付けされたレポートとデータ フローで新しいワークロードを使用できるようになったため、Power BI Embedded のリソースとワークロードの消費を監視して、構成可能なしきい値を超えたときにアクションをトリガーする、3 つの新しいメトリックが追加されます。 新しいメトリックは、リソースでの各ワークロードを反映します。 新しいメトリックは次のとおりです。

- CPU 消費量

- メモリ消費量

- メモリ コミット消費量 (メモリのページングを含む)

開発者は、Azure を使用してしきい値を定義し、アラートを使用して特定のアクションをトリガーできます (たとえば、特定のモニターが定義済みしきい値を超えたらリソースを自動スケールアップするなど)。
