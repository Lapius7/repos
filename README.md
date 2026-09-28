# Lapius7 のリポジトリ一覧

[Lapius7](https://github.com/Lapius7) の公開リポジトリのまとめ。
CLI ツールはどれも `npm i -g @lapius/<名前>` で入る（Linux / macOS / Windows）。

- [CLI ツール](#cli-ツール)
- [Web サービス・サーバー](#web-サービスサーバー)
- [デスクトップアプリ・ブラウザ拡張](#デスクトップアプリブラウザ拡張)
- [ライブラリ](#ライブラリ)
- [その他](#その他)
- [アーカイブ](#アーカイブ)

## CLI ツール

| リポジトリ | コマンド | 説明 | 言語 | インストール |
|---|---|---|---|---|
| [lapacks](https://github.com/Lapius7/lapacks) | `lapacks` | @lapius の CLI ツール（下の表）をまとめて一覧・インストール・更新・削除する管理 CLI（TUI 付き） | Node.js | `npm i -g @lapius/lapacks` |
| [why](https://github.com/Lapius7/why) | `why` | 失敗したコマンドの原因と対処法を日本語で表示する（オフライン・AI なし） | Go | `npm i -g @lapius/why` |
| [bin-cli](https://github.com/Lapius7/bin-cli) | `bin` | [LapBin](https://bin.lapius7.com) のクライアント。Lapount でログインしてターミナルからコードを共有 | Go | `npm i -g @lapius/bin-cli` |
| [ohatwikeeper-cli](https://github.com/Lapius7/ohatwikeeper-cli) | `ohax` | [おはツイKeeper](https://ohatwikeeper.com/cli) 公式 CLI。プロフィール・推移グラフ・アワードなどをフルカラーで表示 | Go | `npm i -g @lapius/ohatwikeeper-cli` |
| [sca-cli](https://github.com/Lapius7/sca-cli) | `sca` | supabase-chat-app のターミナルクライアント。ルーム作成・チャット・オンライン表示 | Go | `npm i -g @lapius/sca-cli` |
| [dela-cli](https://github.com/Lapius7/dela-cli) | `dela` | ローカルのポートを `https://xxxx.deploy.lapius7.com` で即公開（自前の sish トンネル） | Go | `npm i -g @lapius/dela-cli` |
| [clilap](https://github.com/Lapius7/clilap) | `clilap` | [clilap.org](https://clilap.org) のクライアント。天気・チートシート・DNS・ハッシュなどをターミナルから | Node.js | `npm i -g @lapius/clilap` |
| [laping-lang](https://github.com/Lapius7/laping-lang) | `laping` | Laping (`.lp`) — C で実装した最小構成のプログラミング言語 | C | `npm i -g @lapius/laping-lang` |
| [password-gl](https://github.com/Lapius7/password-gl) | `password-gl` `pgl` | 条件を細かく指定できるパスワード / パスフレーズ生成（要 Python 3.9+） | Python | `npm i -g @lapius/password-gl` |
| [tsbuild](https://github.com/Lapius7/tsbuild) | `tsbuild` | Bun + TypeScript の開発サーバーをホットリロード付きで 1 コマンド起動（要 Python 3.9+） | Python | `npm i -g @lapius/tsbuild` |
| [tssetup](https://github.com/Lapius7/tssetup) | `tssetup` | Bun + TypeScript のフロントエンド環境を 1 コマンドで構築（要 Python 3.9+） | Python | `npm i -g @lapius/tssetup` |
| [go-uuid](https://github.com/Lapius7/go-uuid) | `go-uuid` | アクセスするたびに UUID (v1〜v7) を返す HTTP サーバー（[デモ](https://sandbox.lapius7.com/go-uuid/)） | Go | `npm i -g @lapius/go-uuid` |
| [clilap-codepush](https://github.com/Lapius7/clilap-codepush) | `clilap-codepush` | [codepush.clilap.org](https://codepush.clilap.org) の TUI クライアント | Python | `pip install clilap-codepush` |
| [cli-othello](https://github.com/Lapius7/cli-othello) | `cli-othello` | ターミナルで遊ぶオセロ。5 段階の AI と対戦 | Python | `pip install cli-othello` |

## Web サービス・サーバー

| リポジトリ | 説明 | 言語 |
|---|---|---|
| [clilap](https://github.com/Lapius7/clilap) | `curl clilap.org` で使える開発者向けツール集（天気・チートシート・GitHub・IP・DNS・WHOIS・UUID・Base64 など） | Python |
| [transit.lapius7.com](https://github.com/Lapius7/transit.lapius7.com) | Transit API を使った乗換案内 Web アプリ（[サイト](https://transit.lapius7.com)） | TypeScript |
| [clipshot-server](https://github.com/Lapius7/clipshot-server) | セルフホストの画像アップロードサーバー。ShareX / Gyazo 風のクリップボードアップロードを自前の VPS で | Go |
| [discordwidget-reloader](https://github.com/Lapius7/discordwidget-reloader) | Discord Profile Widgets v2 の同期待ち表示を回避する定期 PATCH コンテナ | Python |

## デスクトップアプリ・ブラウザ拡張

| リポジトリ | 説明 | 言語 |
|---|---|---|
| [clipshot-app](https://github.com/Lapius7/clipshot-app) | clipshot-server 用の Windows トレイクライアント。ホットキーでクリップボードの画像をアップロードし URL をコピー | Go |
| [portality](https://github.com/Lapius7/portality) | 開発者向けのポート / ネットワーク可視化 Windows アプリ（Tauri + React） | TypeScript |
| [YTGrab](https://github.com/Lapius7/YTGrab) | YouTube の動画・音声を細かい設定でダウンロードできる GUI アプリ | Python |
| [ohatwikeeper-extension](https://github.com/Lapius7/ohatwikeeper-extension) | おはツイKeeper のワンクリック登録・統計表示 Chrome 拡張（[紹介](https://ohatwikeeper.com/extensions/oneclick_add/)） | HTML |

## ライブラリ

| リポジトリ | 説明 | 言語 | インストール |
|---|---|---|---|
| [nixparse](https://github.com/Lapius7/nixparse) | `ps` `df` `du` `free` `lsof` `ip` `ss` などの出力を型安全にパース（Zod で実行時検証） | TypeScript | `npm i nixparse` |
| [go-rataliy_lib](https://github.com/Lapius7/go-rataliy_lib) | Go の HTTP レート制限（トークンバケット・スライディング / 固定ウィンドウ、net/http ミドルウェア付き、依存なし） | Go | `go get github.com/Lapius7/go-rataliy_lib` |

## その他

| リポジトリ | 説明 | 言語 |
|---|---|---|
| [ts-othello](https://github.com/Lapius7/ts-othello) | TypeScript の勉強で作ったオセロ | TypeScript |
| [lapius7.github.io](https://github.com/Lapius7/lapius7.github.io) | ポートフォリオサイト（[lapius7.github.io](https://lapius7.github.io)） | HTML |
| [Lapius7](https://github.com/Lapius7/Lapius7) | GitHub プロフィールの README | — |
| [repos](https://github.com/Lapius7/repos) | このページ | — |

## アーカイブ

| リポジトリ | 説明 |
|---|---|
| [pip.kmr1-shorten](https://github.com/Lapius7/pip.kmr1-shorten) | kmr1 API で URL を短縮する CLI |
| [Aviutl-Valorant_CC](https://github.com/Lapius7/Aviutl-Valorant_CC) | AviUtl 用 VALORANT の色調補正（CC）設定 |
