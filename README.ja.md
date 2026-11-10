# Taillook / 丸尾 一真

[English](./README.md) · **日本語**

## 職務経験

### 株式会社メンテモ（2025年7月〜現在）

現在はSREとパフォーマンスチューニングを担当しています。

### MIXI（2019年4月〜2025年6月）

XFLAG CONNECTやXFLAG PARKなど、ライブイベントに関わる開発を担当しました。 [MIXIの登壇者紹介](https://mixi.connpass.com/event/232255/)

## 経験した技術

- **クラウド基盤・運用** — Google Cloud、Kubernetes（GKE）、Secret Manager、Cloud Build、Cloud SQL Proxy
- **バックエンド・API** — Go、Ruby on Rails、Rust、Axum、WebSocket、Redis Pub/Sub、OpenAPI Generator
- **Webフロントエンド** — TypeScript、React
- **モバイル開発** — Swift、RxSwift、MVVM、Dart、Flutter、Firebase Authentication

## 主要実績

- RustとAxumで、WebSocket接続をチャンネルごとに管理するサーバーのサンプルを作りました。 [axum-grouping-ws-server](https://github.com/Taillook/axum-grouping-ws-server)
- Goのbcrypt実装をVに移植しました。移植した実装はVの標準ライブラリに取り込まれました。 [vbcrypt](https://github.com/Taillook/vbcrypt)
- 複数の呼び出しが重なっても初期化処理を一度だけ実行できる`sync.Once`をVの標準ライブラリに追加しました。 [V #12722](https://github.com/vlang/v/pull/12722)

## 技術記事

- [OpenAPI GeneratorのカスタムテンプレートでAxumのWebSocketハンドラーを生成する（Zenn）](https://zenn.dev/mixi/articles/f6b7e3e205417b)
- [RustでRedis Pub/Subの購読が静かに切れる問題への対処（Qiita）](https://qiita.com/Taillook/items/6dde2a045c2af85c414b)
- [AxumでRedis Pub/Subを使う（Zenn）](https://zenn.dev/taillook/articles/83b39888c6633d)
- [GKEでGoogle Cloud Secret Managerのシークレットを使う（Qiita）](https://qiita.com/Taillook/items/db3cc8c1ca5f5110b38a)
- [Cloud BuildとCloud SQL ProxyでDBマイグレーションを実行する（Qiita）](https://qiita.com/Taillook/items/d3854620983a00f9445f)
