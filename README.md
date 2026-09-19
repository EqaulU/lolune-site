# tabiato-site

iPhone アプリ **tabiato** の紹介サイト。GitHub Pages で配信している静的サイト。

公開 URL: https://eqaulu.github.io/tabiato-site/

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
| `assets/icon-*.png` | favicon と apple-touch-icon。`app_icon.png` から生成 |
| `.nojekyll` | Jekyll のビルドを無効化し、静的ファイルをそのまま配信する |

ビルド不要。`main` へ push するとそのまま公開される。

画像はアプリ本体のリポジトリ `assets/brand/` からコピーしたもの。ブランド側を変えたら
こちらも入れ替える。ロゴは絵と文字を別ファイルで並べる（アプリの masthead と同じ構成）。
ダークモードでは文字だけを白へ反転させる。絵には反転をかけない（多色のため潰れる）。

## 未了

- `privacy.html` / `support.html` は本文がプレースホルダのまま。App Store 提出前に、
  実際のデータ取扱い・利用 SDK・問い合わせ先に合わせて書き起こす
- App Store のリンクは Coming Soon で止めてある

アプリ本体のリポジトリは別（private）。
