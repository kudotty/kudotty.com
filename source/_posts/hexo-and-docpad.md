---
title: 静的サイトジェネレーターを、拡張性重視でひたすら比較検討したら、HexoとDocPadの二択だった
banner: http://i.imgur.com/QAre4k8.png
categories:
  - 静的サイトジェネレーター
tags:
  - 静的サイトジェネレーター
  - Hexo
  - DocPad
  - Node.js
date: 2016-07-19 17:19:15
---
[StaticGen \- Top Open\-Source Static Site Generators](https://www.staticgen.com/)を上から7段目、28コぐらいを徹底的に調べた結果、HexoとDocPadの２つに絞り込んだ。
- [Hexo \- fast, simple & powerful blog framework](https://hexo.io/)
- [DocPad \- Streamlined Web Development](http://docpad.org/)

## まずは、Hexoを使ってブログを構築してみた
[![Hexo](http://i.imgur.com/35jOjbk.png)](https://hexo.io/)

Hexo公式の[テーマ一覧](https://hexo.io/themes/)を全てチェックした結果、「使える」テーマは以下のページと同意見だった。

[hexoでblogを書くためのオススメtheme\(テーマ\)一覧 \- tea Photography](https://tea3.github.io/p/hexo-blog-theme-16/)

## Hexoテーマはこの、Icarusをチョイスしカスタマイズ
[![Hexoテーマ Icarus](http://i.imgur.com/wMuHZym.png)](https://github.com/ppoffice/hexo-theme-icarus)

## Hexoの使い方は、以下のページがしっかりとわかりやすく書いてあると思う
[Hexo コマンド\|Akanetrip](http://hatobane.github.io/hexo/hexo-command/)
[Hexo 設定ファイル\|Akanetrip](http://hatobane.github.io/hexo/Hexo-config/)

## DocPadも実際に触ってみた
- DocPadでは、テーマではなくスケルトン。パッケージやリポジトリが自動インストールされる
- docpad run起動時のスケルトンの選択肢が20前後あるが、どれもどうもピンとこない
- スケルトン自動インストール直後の表示が崩れてる
- Unsupportedなスケルトンは、自動インストールでエラーが出たりする
  
つまり、DocPadはスケルトンを使わずスクラッチでやれってことなんだろう。

## 結論。やりたいことがブログであればHexo。ブログ以外を作りたくてプラグインに惚れればDocPad
DocPadプラグインの全リスト
[npm \- packages with keyword ‘docpad-plugin’](https://www.npmjs.com/browse/keyword/docpad-plugin)
  
{% youtube EqdRW3I7CIc %}
