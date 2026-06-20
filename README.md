# KATAPATA site starter

KATAPATAを本格的なサイトとして分けていくための、静的サイトスターターです。

## 構成

- `index.html`：入口 / ENTER
- `about.html`：はじめに / KATAPATAとは
- `tools/index.html`：原型作成ツール・型紙作成ツールの分岐
- `tools/sloper/index.html`：原型作成ツール入口
- `tools/sloper/app/katapata.html`：KATAPATA本体の置き場
- `tools/pattern/index.html`：型紙作成ツール入口
- `guide/index.html`：使い方
- `examples/index.html`：使用例
- `blog/index.html`：ブログ一覧
- `pricing/index.html`：料金・出力
- `help/index.html`：FAQ
- `assets/css/site.css`：サイト共通CSS
- `assets/js/site.js`：サイト共通JS

## KATAPATA本体の差し替え

現在の `tools/sloper/app/katapata.html` は仮のプレースホルダーです。
最新のKATAPATA単体HTMLを `katapata.html` という名前にして、ここへ上書きしてください。

いきなり製図ロジックを分割せず、まずはサイト外側だけを分ける方針です。
