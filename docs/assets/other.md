## 業務外における活動

### OSS
- OSSアプリケーションの翻訳
  - [learnGitBranching](https://github.com/pcottle/learnGitBranching/pull/850)
- 自作ツールの公開
  - [route53-ipv4-pusher](https://github.com/CasheeeewNuts/route53-ipv4-pusher)
    - AWS Route53を利用したDDNSアプリケーション
    - これを利用することで、固定IPアドレスをプロパイダと契約しなくても、手軽にドメインを取得して自宅サーバーを公開できます。
  - [md-bundler](https://github.com/CasheeeewNuts/md-bundler)
    - MarkDown形式のテキストファイルを一つのファイルにまとめるツール。
    - 実はこの文書もGitHubActionsと、このCLIツールを利用することで自動生成しています。
    - npmで1000回以上DLされました！
  - [pigeon](https://github.com/CasheeeewNuts/pigeon)
    - **!!!開発中!!! 動作検証は行わないでください。**
    - Windows, macOS, Linuxのマルチプラットフォームに利用できる電子書籍リーダー
    - 技術スタックは Electron + React(with material-ui) + Next.js + TypeScript

### 社内的な活動
- Dockerによる開発環境の統一
  - 私が入社してすぐの頃は開発環境が整備されておらず、個人個人のPCにインストールされた実行環境のバージョン違いによって開発に新しいメンバーが参加するのに
  １〜２日程度かかるなど、大きな支障をきたしていました。そこで個人的に業務外で学んでいたDockerに目をつけてこれを導入する施策をとりました。
  結果、開発環境構築のコストが大幅に削減され、30分から1時間程度で開発環境の準備ができるようになりました。
- 社内勉強会の企画・運営
  - 自分自身の学習と、知識・知見を共有して開発がより効率的になることを目的に勉強会を行っていました。以下はこれまでに開催した勉強会の一部です.
    - Laravelのハンズオン（全4回）
    - Dockerのハンズオン（全4回）
    - 新しい開発環境の使い方（全2回）
    - PHPの機能にフォーカスしたOOP(class, abstract class, interface, trait)（全4回）
    - 保守性の高いコードの書き方（全2回）
    - ブラウザでサイトが表示されるまでの詳細・それを考慮したパフォーマンス改善(全2回)
    - インラインJSの問題点と改善方法・webpackの使い方(全2回)
    - プロトコル・ネットワーク・Linuxの基礎(全3回)
- 開発業務の効率化
  - EC2におけるデプロイ手順の一部をシェルスクリプトなどで置き換えて自動化など
    - [参考：　デプロイの際のApacheへの設定を自動化](https://gist.github.com/CasheeeewNuts/7c92baa8e36c761483609f5a4f7c81bc)

### その他
- 愛用しているjetbrains製IDEのバグ・イシューレポート
  - [参考:　過去に報告したバグ](https://youtrack.jetbrains.com/issue/WI-60394)
