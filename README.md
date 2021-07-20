# html2pdf

![GitHub](https://img.shields.io/github/license/Suree33/html2pdf?style=flat-square)

HTMLとCSSを使ってPDFに変換するためのテンプレート。

![image](https://user-images.githubusercontent.com/42645594/126158796-12da7385-4f5b-4b13-ab7b-f82787f4c1bf.png)

## 使い方

### ページ区切り

`<div class="page"></div>` のようにして、 `page` クラスでページを区切ることができる。

### ページのプロパティ

デフォルト: A4、縦向き

#### 紙のサイズ

`<div class="page a4"></div>` のようにして紙のサイズを指定できる。

対応サイズ: A0 ~ A10、B0 ~ B10、Letter、Legal、Tabloid

ただし実際の印刷時は若干大きさが違うので、このプロパティはプレビュー時だけ有効になり、実際に印刷されるときは紙のサイズぴったりになるようになっている。

#### 紙の向き

`<div class="page portrait"></div>` のようにして紙の向きを指定できる

|  向き  | クラス名  |
| :----: | :-------: |
| 縦向き | portrait  |
| 横向き | landscape |

### カスタムCSS

`css/user.scss` にカスタムSCSSを追加できる。

## License
MIT
