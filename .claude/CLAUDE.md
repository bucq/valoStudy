# プロジェクト

## 概要
本プロジェクトはFPSゲームのVALORANT関するコーチングyoutube動画検索サイトです。

## ディレクトリ構成
.
├── README.md
├── apps
│   ├── admin_studio //管理者用アプリ
│   └── public. //公開用メインアプリ
├── biome.json
├── doc //プロジェクトドキュメント
│   ├── architecture.md
│   ├── er.md
│   ├── overview.md
│   └── usecase.md
├── knip.json
├── lefthook.yml
├── node_modules
│   ├── @biomejs
│   ├── knip -> .pnpm/knip@5.86.0_@types+node@25.3.1_typescript@5.9.3/node_modules/knip
│   └── lefthook -> .pnpm/lefthook@1.13.6/node_modules/lefthook
├── package.json
├── packages
│   └── valorant
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
└── scripts
    ├── get-channel-id.mjs
    └── get-channel-id.ts

## 基本ルール

コード変更後、doc/を確認しコードと差分があればそれに合わせてdoc/内のドキュメントを変更してください。

