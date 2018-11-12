---
title: "財務、営業、購買の拡張"
description: "財務、営業、購買機能が向上しました。"
author: bnielse
manager: edupont04
ms.date: 10/16/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: bnielse
audience: developer, admin, end user, customizer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: d65d9c6f9cae75ea7d7934a95b3a9f67a9e10fe3
ms.openlocfilehash: a925806da0b2b1828f55d5fe4cfb10b06d40a91c
ms.contentlocale: ja-jp
ms.lasthandoff: 10/26/2018

---

# <a name="enhancements-to-finance-sales-and-purchasing"></a>財務、営業、購買の拡張

[!include[banner](../../includes/banner.md)]

## <a name="non-inventory-items"></a>非在庫品目

Business Central では、非在庫品目 (購入または販売できるが在庫品目として保持しない品目) がサポートされるようになりました。

*例: オフィス消耗品、製造/サービス シナリオでの金属 (kg 単位で購入し、単位で消費)、イチゴを路上販売する農家。*

非在庫品目では、価格/割引構造、数量単位、既定の仕入先と追加仕入先、詳細説明、交換品目、税目番号などの品目機能を利用できますが、在庫数量と金額の追跡は不要です。 非在庫品目では、以下の機能がサポートされます。

* 営業
* 購買
* 作業消費
* サービス消費
* アセンブリ消費
* 生産消費

詳細: [https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-about-item-types](https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-about-item-types)  

## <a name="blocked-items-hidden-in-lookups"></a>ルックアップで非表示になっているブロックされた品目

時間の経過と共に、使用されないブロックされた品目が数千になることがあります。 しかし、販売ドキュメントに品目を追加する際に、これらは依然としてルックアップに表示されます。 そのため品目の一覧が長くなりすぎて、販売できる品目が混乱することになります。

10 月のリリースでは、ブロックされた品目は複数の仕訳帳とドキュメントのルックアップで非表示になります。

詳細: https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-how-block-items

## <a name="block-items-from-sales-and-purchasing"></a>販売と購買からの品目のブロック

特定の品目に対して許可される取引をより柔軟に指定できます。 品目が販売明細行または購買注文明細行に入力されないようにしたり、その品目がどの取引でも転記されないようにブロックしたりできます。

詳細: https://docs.microsoft.com/en-us/dynamics365/business-central/inventory-how-block-items

## <a name="updated-reports-layout"></a>更新されたレポート レイアウト

頻繁に使用されるレポートは、レイアウトが更新され、よりモダンな外観になっています。  

|レポート ID|名前|
|---------|----|
|1|勘定科目表|
|2|一般仕訳帳 - テスト|
|3|G/L 登録|
|4|詳細な試算表|
|5|売掛金/買掛金|
|6|試算表|
|8|予算|
|9|試算表/予算|
|25|会計スケジュール|
|38|期間別試算表|
|101|顧客 - 一覧|
|103|顧客登録|
|107|顧客 - 受注の概要|
|108|顧客 - 受注の詳細|
|111|顧客 - 上位 10 リスト|
|112|販売統計|
|113|顧客/品目販売|
|114|営業担当者 - 販売統計|
|119|顧客 - 販売リスト|
|120|指定の期間に達している売掛金勘定|
|129|顧客 - 試算表|
|309|仕入先 - 購買リスト|
|321|仕入先 - 現在までの残高|
|329|仕入先 - 試算表|
|715|価格表|
|720|品目/仕入先カタログ|
|1001|在庫評価|
|5605|固定資産 - 簿価額 01|
|5871|品目 - 作成可能 (タイムライン)|
|5872|BOM 原価共有配分|

## <a name="standard-sales-and-purchase-codes-improvements"></a>標準販売および購入コードの改善

同様の情報を持つ販売明細行と購買注文明細行を頻繁に作成する必要がある場合は、定期補充注文など、定期的な販売および購買ドキュメントに挿入できる標準明細を設定できます。 10 月のリリースでは、ユーザーは異なる販売または購買ドキュメントを作成する際に、標準の販売コードまたは購買コードの入力方法を指定できます。

詳細: https://docs.microsoft.com/en-us/dynamics365/business-central/sales-how-work-standard-lines

## <a name="fixed-assets-appreciation-posting-available-through-purchase-invoice"></a>購買請求書を通じて利用できる固定資産評価の転記

現在のリリースでは、ユーザーは固定資産 (FA) の価値上昇を簡単に登録することができます。 "FA 転記タイプ" フィールドは、これをサポートするために仕入請求書の [増加] の種類で拡張されています。 したがって、一般的な仕訳を使用して個別の取引を転記する必要なしに、適切な FA 転記タイプを使用して購買請求書を転記することによって、保守だけでなく固定資産の増加も文書化できるようになりました。

## <a name="multiple-interest-rates-finance-charge-terms"></a>複数の金利 (利息条件)

利息条件に複数の期間別金利のサポートを追加。 現在のリリースでは、利息条件とアラーム条件を支払遅延のペナルティとして作成するときに、複数の金利を指定して、異なる期間の異なる金利からペナルティ料金を計算することもできます。  

## <a name="vat-reconciliation-report-country-consolidation"></a>VAT 調整レポート (国の連結)

VAT 調整は、VAT 還付が税務当局に提出されるたびに、通常は会計士によって行われます。 W1 バージョンには何年もの間 VAT と G/L の関係がありましたが、それを利用している特定の機能はありません。 確立された関係に基づいて G/L エントリと VAT エントリを調整する機能を追加しました。

## <a name="archiving-of-blanket-orders-and-document-line-tracking"></a>一括発注のアーカイブとドキュメント明細行追跡

アーカイブ機能を整理し、一括発注を含むように拡張しました。 また、追跡を改善したので、ユーザーは注文またはアーカイブされた注文から一括発注を検索することができ、その逆も可能です。

詳細: https://docs.microsoft.com/en-us/dynamics365/business-central/across-how-to-archive-documents  
https://docs.microsoft.com/en-us/dynamics365/business-central/across-how-to-track-document-lines

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。 Business Central フォーラム (https://aka.ms/businesscentralideas) をご利用ください。

