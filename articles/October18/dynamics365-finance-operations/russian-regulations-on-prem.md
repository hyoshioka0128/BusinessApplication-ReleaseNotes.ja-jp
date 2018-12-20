---
title: "ロシア語ローカライズ"
description: "Microsoft Dynamics 365 for Finance and Operations では、ロシアで必須の規制要件がサポートされるようになりました (オンプレミス展開の場合のみ)。"
author: Anasyash
manager: AnnBe
ms.reviewer: shylaw
ms.date: 11/13/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: anasyash
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 188a8a4a4e31001537ccdd38d349df16f7eb8193
ms.openlocfilehash: c20573f5f4b0ab295ca5b7d0b33e93ad45d77a00
ms.contentlocale: ja-jp
ms.lasthandoff: 12/06/2018

---

# <a name="russian-localization"></a>ロシア語ローカライズ

Microsoft Dynamics 365 for Finance and Operations では、2018 年 10 月時点でロシア語のローカライズがサポートされています。 ロシア語以外のテナントを持つお客様はロシアの住所を持つ法人を作成することができ、それによってロシア語ローカライズ機能を有効にすることができます。また、お客様はロシア語ローカライズ機能の実装の検討を開始することができます。

## <a name="october-18-features"></a>2018 年 10 月の機能

ロシア語版の 2018 年 10 月リリースには、次の機能領域が含まれています。 

- 買掛金勘定と売掛金勘定
- [前貸し保有者](https://docs.microsoft.com/en-us/dynamics365/unified-operations/financials/localizations/rus-advance-holders) 
- [銀行](https://docs.microsoft.com/en-us/dynamics365/unified-operations/financials/localizations/rus-local-settings-requisites-bank-module)
- 現金
- クライアント銀行インターフェイスの輸出部分 
- [固定資産](https://docs.microsoft.com/en-us/dynamics365/unified-operations/financials/localizations/rus-fixed-asset-acquisition) 
- 一般会計と一般会計報告 
- 財務報告の電子レポート 
- 在庫 
- アドレス/FIAS  
- VAT 
- 現金移動、商品移動、定格費用、繰延経費、為替差異、WIP の分野における利益税登録

## <a name="monthly-planned-features"></a>月次で計画されている機能

次のロシア語ローカライズ機能は、2018 年 10 月 1 日リリースの月次更新での一般提供が予定されています。 

|月|機能|
|----------------------|-------------|
|2018 年 11 月| - サードパーティのその他の請求<br></br>- 電子形式の VAT 申告|
|2018 年 12 月|- クライアント銀行インターフェイスの輸入部分<br></br> - 在庫管理<br></br> &nbsp;&nbsp;&nbsp;&nbsp;- 寄託 <br></br>   &nbsp;&nbsp;&nbsp;&nbsp;- 輸送中の商品<br></br>   &nbsp;&nbsp;&nbsp;&nbsp;- オプションの移動オーダーの転記<br></br> &nbsp;&nbsp;&nbsp;&nbsp;- 在庫所有者<br></br> - 資産分野の利益税登録<br></br> - 電子形式での VAT 登録|
|2019 年 1 月|- キャッシュ フロー管理<br></br> - 次の分野の利益税登録:<br></br>   &nbsp;&nbsp;&nbsp;&nbsp;- 売掛金勘定の貸方<br></br>   &nbsp;&nbsp;&nbsp;&nbsp;- 買掛金勘定の負債<br></br>   &nbsp;&nbsp;&nbsp;&nbsp;- その他の収入と支出<br></br>|
|2019 年 2 月|- 加工業者のローカライズ|
|2019 年 3 月|- 電子形式の会計申告<br></br>- 電子形式の利益税申告<br></br>- 運送税の登録と電子形式の申告<br></br>- 土地税の登録と電子形式の申告<br></br>- 評価税の登録と電子形式の申告<br></br>- 商品の輸入での電子形式の間接税申告<br></br>- 電子形式でのアルコール販売申告<br></br>- アルコール販売の仕訳帳<br></br>|


## <a name="frequently-asked-questions-about-the-russian-localization-availability"></a>ロシア語ローカライズの利用可能性に関してよく寄せられる質問

### <a name="when-will-the-cloud-deployment-option-of-dynamics-365-for-finance-and-operations-be-generally-available-for-russia"></a>Dynamics 365 for Finance and Operations のクラウド展開オプションはロシアでいつ一般提供されますか?

マイクロソフトは、2018 年の暦年の終わりまでにクラウド展開オプションをロシアで一般提供する予定です。  

ロシアでクラウドを "ライブに移行" するためには、お客様がロシアの個人データ ローカライズ法を遵守する必要があります。 Federal Law No. 242-FZ の修正 (2015 年 9 月 1 日に発効) は、ロシア市民の "個人データ" を収集するロシアのデータ "事業者" にデータ ローカライズ要件を課しています。 これらの事業者は、その個人データをロシア以外の地域に転送する前に、そのデータの "収集、記録、体系化、蓄積、保存、訂正 (更新と変更)、抽出" がロシアにあるデータベースで行われるようにする必要があります。 ロシア向けにクラウド展開を実装しているお客様は、Russian Federal Law No.  242-FZ の修正を遵守するために、個人データを海外に転送する前にデータをローカルに格納できるようにするソリューションを提供しているローカル パートナーと協力する必要があります。 


### <a name="when-will-the-on-premises-deployment-option-of-dynamics-365-for-finance-and-operations-be-generally-available-for-russia"></a>Dynamics 365 for Finance and Operations のオンプレミス展開オプションはロシアでいつ一般提供されますか?

マイクロソフトは、2018 年の暦年の終わりまでにオンプレミス展開オプションをロシアで一般提供する予定です。


### <a name="will-the-russian-retail-localization-and-russian-payroll-be-released-within-the-october-18-release-timeframe"></a>ロシア語 Retail ローカライズとロシア語の給与は 2018 年 10 月リリース期間内にリリースされる予定ですか?

ロシア語 Retail ローカライズとロシア語の給与は、2018 年 10 月リリース期間 (2018 年 10 月から 2019 年 3 月) には利用可能になりません。 ロシア語 Retail ローカライズとロシア語の給与の計画は、計画が確定した時点でリリース ノートに掲載されます。

詳細については、[ロシア語ローカライズのヘルプ コンテンツ](https://docs.microsoft.com/en-us/dynamics365/unified-operations/financials/localizations/russia)を参照してください。

