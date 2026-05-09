# 禁酒道場 GitHub Pages

禁酒道場のApp Store公開に向けた静的サイトです。GitHub Pagesでそのまま公開できるよう、HTMLとCSSのみで構成しています。

## ファイル構成

```text
.
├── index.html
├── favicon.svg
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

## 公開URL

https://ndgtlft.github.io/kinsyu-dojo-pages/

## App Store Connectへ入力するURL

- サポートURL：`https://ndgtlft.github.io/kinsyu-dojo-pages/support/`
- プライバシーポリシーURL：`https://ndgtlft.github.io/kinsyu-dojo-pages/privacy/`
- 利用規約URL：`https://ndgtlft.github.io/kinsyu-dojo-pages/terms/`

独自ドメインを使う場合は、上記のドメイン部分を差し替えてください。

## 現在の設定

- 開発者名：Yasuyuki Arata
- 問い合わせ先メールアドレス：nadegatadev@gmail.com
- 最終更新日：2026/5/9

## 実装メモ

- JavaScriptは使用していません。
- 外部ライブラリは使用していません。
- 各ページに `lang="ja"`、`charset="UTF-8"`、`meta viewport`、`canonical`、`favicon` を設定しています。
- 共通スタイルは `styles.css` にまとめています。
- キーボード操作向けのスキップリンクとフォーカス表示を設定しています。
