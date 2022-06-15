# Azure 標準化ガイドライン

## Azure 標準化ガイドラインとは

Azure 標準化ガイドライン (以下、本書と記載) とは、Microsoft Azure を利用するにあたり、具体的なプラットフォーム/サービス設計の指針となるテンプレートを提供することを目的に作成されたものです。本書は、可能な限り 「ベスト プラクティス」 としての実例をベースに記載していますが、本書を利用する組織の体制や構築するシステム要件に応じてテーラリングして利用されることを前提としています。  
本書を初めて利用する際は、「0 章 はじめに 1. Azure 標準化ガイドラインとは」をご参照の上、活用ください。

## ガイドラインのダウンロード

Azure 標準化ガイドラインのファイルは Release からダウンロードできます。いくつかの章ごとに zip 形式でまとまっています。なお、0 章はすべての zip ファイルに含まれています。

## ガイドラインの構成

本書は、次のように 7 章で構成されています。

|章|節|タイトル|
|:--:|:--:|--------|
|0||はじめに|
||1|Azure 標準化ガイドラインとは|
|1||システム全体方式設計|
||1|ビジネス SLA 設定|
||2|IaaS／PaaS 選択方式|
||3|コスト管理／最適化|
||4|プロジェクト評価／レビュー|
||5|ネーミング ルール|
||6|サブスクリプション管理|
||7|ネットワーク構成|
||8|データベースとストレージの構成|
|2||アプリケーション方式設計|
||1|言語の選択とフレームワーク|
||2|アプリケーション パフォーマンス|
||3|可用性／冗長性|
||4|エラー ハンドリング|
||5|アプリケーション セキュリティ|
||6|DevOps（CI／CD）|
||7|API 管理|
||8|フェールソフト|
|3||品質管理|
||1|テスト／検証|
|4||セキュリティ方式設計|
||1|クラウド セキュリティ|
||2|監査ポリシー／ガバナンス|
||3|ID／アクセス権|
|5||高信頼性設計|
||1|レジリエンシー|
|6||運用方式設計|
||1|障害復旧|
||2|バックアップ／リストア|
||3|監視|
||4|インシデント管理|
||5|サービス リクエスト|
||6|クラウド メンテナンス|
|7||構成管理|
||1|変更管理|
||2|キャパシティ管理|
||3|ソースコード管理|

## 制限事項

本書の使用においては、次の制限、制約をご理解の上、活用ください。

+ 目的外利用の禁止  
本書は Microsoft Azure 上において、システムやソリューションの円滑かつ安全な構築に資することを目的に作成されています。この目的に反する利用はお断りいたします。
+ フィードバック  
本書の記載内容へのコメントやフィードバックをいただけます場合は、担当の日本マイクロソフト社員にご連絡ください。なお、個別質問への回答やフィードバックへの対応はお約束できないことを、ご了承いただけますようお願い申し上げます。
+ 公式情報の確認  
本書は日本マイクロソフトの有志のエンジニアによって、現場での経験を加えて執筆されたものです。そのため、この記載内容は Microsoft として公式に表明されたものではなく、日本マイクロソフトおよび米国 Microsoft Corporation は一切の責任を負いません。また、本書の記載内容について Azure サポートへお問い合わせいただいても、回答することはできません。  
Microsoft Azure の公式情報については、Azure のドキュメントをご確認ください。
+ 免責  
本書の記載内容によって発生したいかなる損害についても、日本マイクロソフトおよび米国 Microsoft Corporation は一切の責任を負いません。

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
