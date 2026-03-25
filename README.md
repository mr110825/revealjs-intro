# revealjs-intro

HTML・CSS・Bootstrapで学ぶreveal.jsスライド作成入門

## 概要

[reveal.js](https://revealjs.com/) を使って、HTML・CSSでプレゼンテーションスライドを作成するハンズオン教材です。

## ディレクトリ構成

```
01-setup/       ステップ1: CDN + 最小構成
02-html/        ステップ2: HTML基礎（タグを学びながらスライド作成）
03-css/         ステップ3: CSS基礎（スライドの見た目をカスタマイズ）
04-bootstrap/   ステップ4: Bootstrap（クラスを付けるだけでデザイン適用）
```

各ディレクトリの `index.html` をブラウザで開くと、その段階のスライドを確認できます。

## 使い方

1. このリポジトリをクローン
   ```bash
   git clone https://github.com/mr110825/revealjs-intro.git
   ```
2. 任意のステップの `index.html` をブラウザで開く
3. スピーカーノートを使う場合は、VSCode Live Server 等のローカルサーバー経由で開き、`S` キーを押す

## 各ステップで学べること

### ステップ1: セットアップ
- reveal.js の CDN 読み込み
- 最小構成（`div.reveal > div.slides > section`）
- `Reveal.initialize()` による初期化

### ステップ2: HTML基礎
- スピーカーノート（Notes プラグイン）
- 見出し・段落（`h1`〜`h2`, `p`）
- 箇条書き（`ul`/`ol`, `li`）
- リンク・画像（`a`, `img`）
- テキスト強調（`strong`, `em`）
- コード表示（`code`, `pre`）
- 引用（`blockquote`）
- 段階表示（`class="fragment"`）
- 背景色変更（`data-background-color`）
- 縦スライド（`section` のネスト）

### ステップ3: CSS基礎
- `<style>` タグによるCSS記述
- セレクタ（要素・クラス・ID）
- 色・フォント系プロパティ（`color`, `font-size`, `font-weight`, `text-align`）
- 背景・余白系プロパティ（`background-color`, `padding`, `margin`, `border`）
- Box Model（DevTools で確認）
- Flexbox（`display: flex`）
- reveal.js テーマ切り替え
- 擬似クラス（`:hover`）
- Google Fonts 読み込み

### ステップ4: Bootstrap
- Bootstrap CDN 読み込み
- グリッドシステム（`container` / `row` / `col`）
- ボタン（`btn`）
- カード（`card`）
- バッジ（`badge`）
- アラート（`alert`）
- ユーティリティクラス（`text-center`, `p-2`, `mb-3`, `rounded`）

## 関連記事

- [HTML/CSS入門をreveal.jsスライド作りで実践する](https://zenn.dev/mr110825/scraps/afbe68a87a68ad) - このリポジトリの内容をZenn Scrapで解説しています

## 参考リンク

- [reveal.js 公式サイト](https://revealjs.com/)
- [MDN Web Docs](https://developer.mozilla.org/ja/)
- [Bootstrap 公式](https://getbootstrap.com/)
- [Google Fonts](https://fonts.google.com/)
