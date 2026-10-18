# 2画面比較プレイヤー

2本の動画を並べて、コマ送り・スロー・同期再生・実寸の定規で見比べる、スポーツ動画向けのプレイヤーです。

- 紹介ページ（GitHub Pages）: このリポジトリの Pages のURL
- Windows 版のダウンロード: [Releases](../../releases/latest) の `DualViewPlayer-setup.zip`
- ブラウザ版: `app/index.html`

## ファイル構成

| パス | 内容 |
|---|---|
| `index.html` | 紹介ページ本体（使い方ガイド・更新情報・ダウンロード） |
| `img/` | 紹介ページの画面写真 |
| `app/index.html` | ブラウザ版プレイヤー |
| `download/DualViewPlayer-setup.zip` | Windows 版セットアップ（Releases が使えないときの予備） |

## 更新のしかた

1. `index.html` の「更新情報」にある `<article>` をコピーして先頭に追加し、版番号・日付・内容を書き換える。
2. Releases で新しいリリース（例 `v1.0.1`）を作り、`DualViewPlayer-setup.zip` を **同じファイル名で** 添付する。
   ダウンロードボタンのURLは `releases/latest/download/DualViewPlayer-setup.zip` で固定なので、リンクは変わりません。

## 同梱ソフトウェア

Electron（MIT License）／ FFmpeg（GPL v3）。Windows 版のセットアップ時に公式の配布元から取得します。
