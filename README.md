# Taillook / Kazuma Maruo

**English** · [日本語](./README.ja.md)

## Experience

### Mentemo (Jul 2025 – Present)

I currently work on site reliability engineering (SRE) and performance tuning.

### MIXI (Apr 2019 – Jun 2025)

I worked on software for live events, including XFLAG CONNECT and XFLAG PARK. [MIXI speaker profile (Japanese)](https://mixi.connpass.com/event/232255/)

## Technologies

- **Cloud infrastructure and operations** — Google Cloud, Kubernetes (GKE), Secret Manager, Cloud Build, Cloud SQL Proxy
- **Backend and APIs** — Go, Ruby on Rails, Rust, Axum, WebSocket, Redis Pub/Sub, OpenAPI Generator
- **Web frontend** — TypeScript, React
- **Mobile development** — Swift, RxSwift, MVVM, Dart, Flutter, Firebase Authentication

## Key Achievements

- Built an example Rust server with Axum that groups WebSocket connections by channel. [axum-grouping-ws-server](https://github.com/Taillook/axum-grouping-ws-server)
- Ported Go's bcrypt implementation to V. The port became part of V's standard library. [vbcrypt](https://github.com/Taillook/vbcrypt)
- Added `sync.Once` to V's standard library to run initialization once across concurrent calls. [V #12722](https://github.com/vlang/v/pull/12722)

## Technical Writing

- [Generating Axum WebSocket handlers with a custom OpenAPI Generator template (Zenn, Japanese)](https://zenn.dev/mixi/articles/f6b7e3e205417b)
- [Handling silent Redis Pub/Sub subscription drops in Rust (Qiita, Japanese)](https://qiita.com/Taillook/items/6dde2a045c2af85c414b)
- [Using Redis Pub/Sub with Axum (Zenn, Japanese)](https://zenn.dev/taillook/articles/83b39888c6633d)
- [Using Google Cloud Secret Manager with GKE (Qiita, Japanese)](https://qiita.com/Taillook/items/db3cc8c1ca5f5110b38a)
- [Running database migrations with Cloud Build and Cloud SQL Proxy (Qiita, Japanese)](https://qiita.com/Taillook/items/d3854620983a00f9445f)
