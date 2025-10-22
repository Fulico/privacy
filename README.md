# プライバシーポリシー管理リポジトリ

このリポジトリは、あなたが開発・公開する全アプリのプライバシーポリシーを一元管理し、GitHub Pages で公開するためのものです。

## ディレクトリ構成

index.html            ... アプリ一覧＆各ポリシーへのリンク（リポジトリ直下）
privacy/
├── glycolog.html      ... Glycologのプライバシーポリシー

templates/
└── template.html      ... プライバシーポリシー雛形（新規アプリ追加用）

## 公開方法
GitHub Pagesで `index.html` または `privacy/` ディレクトリを公開対象に設定してください。公開後は以下の形式のURLで各アプリのポリシーに直接リンクできます。

例: https://ユーザー名.github.io/privacy/glycolog.html

新しいアプリを追加する場合は、同様に `privacy/アプリ名.html` としてファイルを追加し、index.htmlへもリンクを追記します。
雛形は`templates/template.html`を複製・編集して利用してください。
