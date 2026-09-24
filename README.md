# lolune-site

iPhone アプリ **lolune** の紹介サイト。GitHub Pages で配信している静的サイト。

公開 URL: https://eqaulu.github.io/lolune-site/

## 構成

| ファイル | 内容 |
|---|---|
| `index.html` | トップページ（LP） |
| `privacy.html` | プライバシーポリシー |
| `support.html` | サポート |
| `style.css` | 全ページ共通のスタイル |
| `assets/logo-mark.png` | ロゴの絵。アプリ本体の `assets/brand/logo_mark.png` と同じもの |
| `assets/logo-wordmark.png` | ロゴの文字。同じく `logo_wordmark.png` |
| `assets/hero.png` | トップのヒーロー画像。`app_icon_squared.png` |
| `assets/icon-16.png` / `icon-32.png` / `icon-180.png` | favicon と apple-touch-icon。`app_icon.png` から生成 |
| `.nojekyll` | Jekyll のビルドを無効化し、静的ファイルをそのまま配信する |

ビルド不要。`main` へ push するとそのまま公開される。

画像はアプリ本体のリポジトリ `assets/brand/` からコピーしたもの。ブランド側を変えたら
こちらも入れ替える。ロゴは絵と文字を別ファイルで並べる（アプリの masthead と同じ構成）。
ダークモードでは文字だけを白へ反転させる。絵には反転をかけない（多色のため潰れる）。

`privacy.html` / `support.html` はトップと同じヘッダー・フッターを持つ。表組みなど
共通スタイルに無い分だけ、各ページの `<style>` で足している。

## 本文の出どころ

`privacy.html` の本文は、アプリ本体のリポジトリの `PRIVACY_POLICY.md` が正本。
実装を変えたらそちらを直し、このページへ反映する。二重管理にしない。

問い合わせ先は `loluneapp@gmail.com`。プライバシーポリシーとサポートの両方で同じものを使う。

## App Store

2026-09-23 に公開した。

- https://apps.apple.com/jp/app/lolune/id6814073570

トップの App Store ボタンはここへ繋いである。バージョンを上げても URL は変わらない。

アプリ本体のリポジトリは別（private）。
