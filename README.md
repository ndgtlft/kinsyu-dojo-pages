# 禁酒道場 GitHub Pages

禁酒道場のApp Store公開に向けた静的サイトです。GitHub Pagesでそのまま公開できるよう、HTMLとCSSのみで構成しています。

## ファイル構成

```text
.
├── index.html
├── styles.css
├── support/
│   └── index.html
├── privacy/
│   └── index.html
└── terms/
    └── index.html
```

## ページ

- `/` トップページ
- `/support/` 問い合わせページ
- `/privacy/` プライバシーポリシー
- `/terms/` 利用規約

## App Store Connectへ入力するURL例

公開URLは未定です。GitHubユーザー名 `ndgtlft`、リポジトリ名 `kinsyu-dojo-pages` でGitHub Pagesを公開する場合、想定URLは以下です。

- サポートURL：`https://ndgtlft.github.io/kinsyu-dojo-pages/support/`
- プライバシーポリシーURL：`https://ndgtlft.github.io/kinsyu-dojo-pages/privacy/`
- 利用規約URL：`https://ndgtlft.github.io/kinsyu-dojo-pages/terms/`

独自ドメインを使う場合は、上記のドメイン部分を差し替えてください。

## 差し替えが必要な項目

- 公開URL
  - GitHub Pages公開後、必要に応じてREADME内のURL例を正式URLへ変更

## 実装メモ

- JavaScriptは使用していません。
- 外部ライブラリは使用していません。
- 各ページに `lang="ja"`、`charset="UTF-8"`、`meta viewport` を設定しています。
- 共通スタイルは `styles.css` にまとめています。
