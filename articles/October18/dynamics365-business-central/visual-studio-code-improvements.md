---
title: Visual Studio Code AL エクスペリエンスの向上
description: Visual Studio Code AL エクスペリエンスの改善
author: pborring
manager: edupont04
ms.date: 07/22/2018
ms.topic: article
ms.prod: ''
ms.service: business-applications
ms.technology: ''
ms.author: pborring
audience: developer, customizer
ms.openlocfilehash: 5b1d5c818fb0fafa973ed0e337cd9bb67ad9b137
ms.sourcegitcommit: 0c8ca4eaf47f7f4b83f1b544b910e7cac92bd1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2019
ms.locfileid: "200152"
---
# <a name="improved-visual-studio-code-al-experience"></a>Visual Studio Code AL エクスペリエンスの向上

[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

拡張機能を作成することは、Business Central をカスタマイズするための手段です。 2018 年 10 月リリースでは、開発エクスペリエンスの生産性が強化されたほか、追加の拡張シナリオもサポートされました。

強化されたツールや拡張機能を使用することで、開発者はソリューションの開発やトラブルシューティングを行う際の生産性を高めると共に、拡張機能を通じて顧客のカスタマイズ要件に柔軟に対応できるようになります。

## <a name="cloud-sandbox-with-production-data"></a>運用データを使用したクラウド サンドボックス
クラウド サンドボックスを使用する際 (特にテストやトラブルシューティングを行う際) には、運用データを使用できたほうが望ましい場合がよくあります。 今回のリリースでは、クラウドにバックアップされた運用データの最新のコピーに基づいてクラウド サンドボックスを作成できる機能が追加されます。 運用データで設定されている統合とのクロストークを最小限に抑えるため、これらの統合はサンドボックスの作成時に無効化されます。 管理者ユーザーは、必要な注意を払ったうえで、これらの統合を必要に応じて有効化したり、再構成したりして、クラウド サンドボックスの使用目的に対応することができます。

## <a name="event-discoverability"></a>イベントの見つけやすさ
拡張機能を作成するうえで、イベントのサブスクライブは重要な操作となります。 しかし、特定のユーザー フローでどのイベントが使用できるかを把握することは、多くの開発者にとって共通の課題です。 デバッグは有効な手段ですが、既にサブスクライブされているイベントしか確認できません。 そこで、イベントや拡張ポイントを見つけやすくするために、クライアントに新しいイベント トレーサーが追加されました。 これを使用すると、ユーザー フローを記録して、発生したイベントをリストすることができます。これにより開発者は、イベントのサブスクライバー コードを生成して、AL コードに簡単にコピーできるようになります。

> [!div class="mx-imgBorder"]
> ![イベント トレーサー](media/Event-tracer.png "イベント トレーサー")

また、新しいイベントも多数追加され、より多くの場所での拡張が可能になりました。

## <a name="visual-studio-code-al-extension-enhancements"></a>Visual Studio Code AL Extension の機能強化
バージョニング チェックと下位互換性が提供されたことで、お客様は Visual Studio Code マーケットプレースから AL 言語の拡張機能をインストールし、それを使用してさまざまなプラットフォーム用のソリューションを開発できるようになりました (クラウド サンドボックス、Business Central 2018 年 4 月リリース、Business Central 2018 年 10 月リリース、および今後のバージョンを含む) 。 コンパイラは、接続されたテナントに互換性があることを確認し、新しい app.json プロパティで設定されたターゲット プラットフォームに対してコンパイルを実行します。

また、多数のオブジェクト拡張やファイルを含んだ大規模なプロジェクトを使用する際の、AL 拡張機能の高速性と応答性も改善されました。

## <a name="debugger-enhancements"></a>デバッガーの機能拡張
レガシーの Dynamics NAV デバッガーのように、一般的な Break on Error と Break on Write を使用できるようになりました。 ベース アプリケーション コード内の定義に移動して、ブレークポイントを設定することもできます。

> [!div class="mx-imgBorder"]
> ![ベース アプリケーション コードの定義に移動する (F12)](media/Go-to-definition-F12.gif "ベース アプリケーション コードの定義に移動する (F12)")

## <a name="intellisense-enhancements"></a>IntelliSense の機能拡張
AL 内のすべてのプロパティ (ホバーと IntelliSense の両方) で、関連するオンライン ドキュメントにリダイレクトするためのヘルプ リンクが提供されるようになりました。 また、AL 言語の構成要素に関するドキュメントが自動生成されるようになり、それらをオンライン リファレンス ドキュメントと IntelliSense の両方に使用できるようになったことで、ドキュメントの最新性と統一性を維持できるようになりました。

> [!div class="mx-imgBorder"]
> ![IntelliSense からのヘルプ リンク](media/Help-link-from-IntelliSense.gif "IntelliSense からのヘルプ リンク")

拡張機能での画像プロパティの提示機能では、現在のコンテキストで使用できるものだけが提示されるようになりました。現在のコンテキストで使用できない画像については警告が表示されます。ユーザーは、IntelliSense とホバーを使用して画像をプレビューできます。

> [!div class="mx-imgBorder"]
> ![IntelliSense での画像の選択とプレビュー](media/IntelliSense-Preview-Images.gif "IntelliSense での画像の選択とプレビュー")

## <a name="working-with-permissions"></a>アクセス許可の操作
アクセス許可を操作しやすくするため、クライアントを使用して、アクセス許可セットをアプリケーションからエクスポートし、それらを Visual Studio Code AL Extension にインポートできるようになりました。 拡張機能内のオブジェクト用に使用する新しいアクセス許可ファイルは、Visual Studio Code AL プロジェクト内から生成することもできます。

> [!div class="mx-imgBorder"]
> ![拡張機能オブジェクト用のアクセス許可ファイルを生成するための Visual Studio Code AL コマンド](media/Permissions-AL-command.png "拡張機能オブジェクト用のアクセス許可ファイルを生成するための Visual Studio Code AL コマンド")

## <a name="net-interop"></a>.NET 相互運用機能
オンプレミス展開を対象とした Business Central ソリューションを取り扱う場合に、.NET相互運用機能を AL コード内に追加できるようになりました。 ただしその場合、後からソリューションをクラウドへ移行するには、.NET 相互運用機能を置き換えなければならなくなります。

> [!div class="mx-imgBorder"]
> ![オンプレミス AL 内の .NET 相互運用機能](media/DotNet-interop.png "オンプレミス AL 内の .NET 相互運用機能")

## <a name="translation-enhancements"></a>翻訳の機能強化
特定の文字列が適用されるオブジェクトや要素を記述した新しいコンテキスト情報が、生成後の XLIFF 翻訳ファイルに追加されました。 これにより、文字列が UI のどこに表示されるのかを翻訳者が把握しやすくなり、翻訳の品質が向上します。

> [!div class="mx-imgBorder"]
> ![XLIFF 翻訳ファイルの note タグ](media/xliff-note.png "XLIFF 翻訳ファイルの note タグ")

## <a name="odata-bound-actions-in-al"></a>AL 内での OData バインド アクション
AL 内で、OData にバインドされたアクションを宣言できるようになりました。 これを実現するために、新しい属性と新しい AL 型が導入されました。

```
[ServiceEnabled]
procedure CreateCustomerCopy(var actionContext : WebServiceActionContext)
var
createdCustomerGuid : Guid;
customer : Record Customer;
begin
actionContext.SetObjectType(ObjectType::Page);
actionContext.SetObjectId(Pages::Customer);
actionContext.AddEntityKey(customer.fieldNo(Id), createdCustomerGuid);
actionContext.SetResultCode(WebServiceActionResultCode::Created);
end;
```
<!--
### Who uses this feature
These features are intended for ISV and VAR developers.
## Status
### Availability
Cloud, On-premises
### Regional availability
Globally
-->

## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のため、アイデアを検討したり、提案したり、フィードバックを提供してください。 Business Central フォーラム ([https://aka.ms/businesscentralideas](https://aka.ms/businesscentralideas)) をご利用ください。
