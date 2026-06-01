# AGENTS.md — kklab-taiyaki-deepseekv4-flash

## 概要

名古屋たい焼き「金鯱堂」の単一ページランディングサイト。純粋な HTML + CSS（インライン）のみ。ビルド・パッケージ管理・テスト・リンター・型チェックは一切なし。

## 構造

- `index.html` — 単一ファイルのランディングページ（CSS 内蔵）
- `README.md` — ドキュメント
- `LICENSE` — MIT

## デプロイ

- GitHub Pages: `https://katzkawai.github.io/kklab-taiyaki-deepseekv4-flash/`
- `main` ブランチに push すると GitHub Actions（設定なし）の Pages が自動反映
- ルート (`/`) から配信、gh-pages ブランチ不使用

## 開発コマンド

ビルド・サーバー・テスト類は存在しない。編集後は `git add -A && git commit -m "..." && git push` でデプロイ完了。

## 画像

全画像は `images.unsplash.com` の外部 URL を直接参照。ローカル画像アセットなし。

## 運用注意

- 内容の修正は `index.html` のみ編集すればよい
- インライン CSS のため、スタイル変更も `index.html` 内で完結
