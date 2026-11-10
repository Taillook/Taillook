# Taillook / 丸尾 一真

[English](./README.md) · **日本語**

## 職務経験

### 株式会社メンテモ（2025年7月〜現在）

現在はSREとパフォーマンスチューニングを担当しています。

### MIXI（2019年4月〜2025年6月）

XFLAG CONNECTやXFLAG PARKなど、ライブイベントに関わる開発を担当しました。 [MIXIの登壇者紹介](https://mixi.connpass.com/event/232255/)

## 経験した技術

- **クラウド基盤・運用** — Google CloudとKubernetes（GKE）。Secret ManagerでGKEのシークレットを管理し、Cloud BuildとCloud SQL Proxyでデプロイ時のDBマイグレーションを実行しました。 [Cloud BuildでのDBマイグレーション](https://qiita.com/Taillook/items/d3854620983a00f9445f)
- **バックエンド・API** — Go、Ruby on Rails、Rust（Axum）。WebSocketサーバーやRedis Pub/Subの実装例、OpenAPI Generatorを使ったAxumのハンドラー生成を公開しています。 [AxumでのRedis Pub/Sub](https://zenn.dev/taillook/articles/83b39888c6633d)
- **Webフロントエンド** — TypeScript、React。
- **モバイル開発** — SwiftとRxSwift、DartとFlutter。MVVM構成のiOSサンプルと、Firebase Authenticationを使ったFlutterのログインサンプルを実装しました。 [SwiftのMVVMサンプル](https://github.com/Taillook/SwiftMVVMSample) · [Flutterのログインサンプル](https://github.com/Taillook/FlutterFirebaseAuthSample)

## 主要実績

- RustとAxumで、WebSocket接続をチャンネルごとに管理するサーバーのサンプルを作りました。 [axum-grouping-ws-server](https://github.com/Taillook/axum-grouping-ws-server)
- Goのbcrypt実装をVに移植しました。移植した実装はVの標準ライブラリに取り込まれました。 [vbcrypt](https://github.com/Taillook/vbcrypt)
- 複数の呼び出しが重なっても初期化処理を一度だけ実行できる`sync.Once`をVの標準ライブラリに追加しました。 [V #12722](https://github.com/vlang/v/pull/12722)

## 技術記事

- [OpenAPI GeneratorのカスタムテンプレートでAxumのWebSocketハンドラーを生成する（Zenn）](https://zenn.dev/mixi/articles/f6b7e3e205417b)
- [GKEでGoogle Cloud Secret Managerのシークレットを使う（Qiita）](https://qiita.com/Taillook/items/db3cc8c1ca5f5110b38a)

## GitHubでの活動

[![公開情報に基づくGitHub活動の統計](https://github-stats-extended.vercel.app/api?username=Taillook&theme=monokai&show_icons=true&include_all_commits=true&locale=ja)](https://github.com/Taillook)

[![公開リポジトリの使用言語](https://github-stats-extended.vercel.app/api/top-langs/?username=Taillook&theme=monokai&layout=compact&langs_count=10&locale=ja)](https://github.com/Taillook)
