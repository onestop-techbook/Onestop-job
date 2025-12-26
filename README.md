# ワンストップ職

仕事、生き方に関する色々なところを書いてみませんか？

職業観、仕事の内容、その仕事／職を選んだ理由や経緯、など、界隈のエンジニアを中心とした皆さんの体験を集めたものです。

この内容は、必ずしも一般的に通用するものではありません。むしろ、N=1の話が多くなるでしょう。でも、N=1だって、100本集まればどれかは刺さるはず。(N=1が100本集まっても、N=100にはなりませんが)

ということで、職に関する本書、スタートします。　2025.12.26　おやかた

## 前提

* [Node.js](https://nodejs.org/en/)

## install

```sh
npm i
```

## 本を作成

本を作成するコマンドは `npm run build` と `npm run build:print` です。

```sh:オンラインで使う前提のカラーPDFを作成するコマンド
npm run build
```

```sh:印刷対応の、なるべく白黒に寄せたPDFを作成するコマンド
npm run build:print
```

## プレビュー

```sh
npm run preview
```

## ライセンス

* `src/*` は原稿ファイルと画像ファイルなのでオープンソースとしてのライセンスは付与しません。
* サンプルコードは普通に使っていただいてかまいません
* それ以外のファイルはMIT Licenseのもと使っていただいてかまいません。設定ファイルには筆者の名前や、この本のタイトルなどが書かれいているためご自身の物に書き換えることは忘れないでください。

### 使用しているフォントのライセンス

License: SIL Open Font License, Version 1.1.

* https://github.com/microsoft/cascadia-code
* https://github.com/IBM/plex
* https://github.com/trueroad/HaranoAjiFonts
