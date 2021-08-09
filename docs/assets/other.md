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
    - 実はこの文書もGitHubActionsとこのCLIツールを利用することで自動生成しています。
    - npmで1000以上DLされました！
  - [pigeon](https://github.com/CasheeeewNuts/pigeon)
    - **!!!開発中!!! 念のため、動作検証は行わないでください。**
    - Windows, macOS, Linuxのマルチプラットフォームに利用できる電子書籍リーダー
    - 技術スタックは Electron + React(with material-ui) + Next.js + TypeScript

### 社内的な活動
- Dockerによる開発環境の統一
  - 私が入社してすぐの頃は開発環境が整備されておらず、個人個人のPCにインストールされた実行環境のバージョン違いによって、開発に新しいメンバーが参加するのに
  - 時間が１〜２日程度かかるなど、大きな支障をきたしていました。そこで、個人的に業務外で学んでいたDockerに目をつけて、これを導入する施策をとりました。
  - 
