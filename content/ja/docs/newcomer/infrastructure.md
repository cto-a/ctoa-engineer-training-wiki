+++
title="インフラ・DevOps"
description="クラウドインフラやその運用について"
weight=30
+++

## ISUCON

[ISUCON公式Blog](https://isucon.net/)

ISUCONはLINE株式会社が運営窓口となって開催している「お題となるWebサービスを決められたレギュレーションの中で限界まで高速化を図るチューニングバトル」です。

まずはWebアプリケーションのインフラを触ってみるのにISUCONの問題は最適です。理由としては

* アプリケーションの規模が初心者が作るアプリケーションより大きく、業務アプリケーションより小さいくらいの適度なサイズ
* 問題によっては各種クラウドサービスやDockerで起動できるようになっており、動かすハードルが低い

などがあります。

- [ISUCONの過去問にチャレンジするためのシンプルな環境構築 : ISUCON公式Blog](https://isucon.net/archives/54946542.html)
  - @catatsuy: ISUCONの過去問の環境構築がまとまったリンク集
- [達人が教えるWebパフォーマンスチューニング 〜ISUCONから学ぶ高速化の実践：書籍案内｜技術評論社](https://gihyo.jp/book/2022/978-4-297-12846-3)
  - @catatsuy: 執筆しました。初学者はまず問題を解いてみて、付録Aで不足している知識を確認してから読むと読みやすいと思います。ISUCONに直接関係ないインフラや運用についても言及しています
- [tatsujin-web-performance/tatsujin-web-performance: 達人が教えるWebパフォーマンスチューニング〜ISUCONから学ぶ高速化の実践](https://github.com/tatsujin-web-performance/tatsujin-web-performance)
- [catatsuy/private-isu: 社内ISUCON](https://github.com/catatsuy/private-isu)
  - 本の題材で使われた問題

## Linux
- [新しいLinuxの教科書| SBクリエイティブ ](https://www.sbcr.jp/product/4797380941/)
- [O'Reilly Japan - Linuxシステムプログラミング](https://www.oreilly.co.jp/books/9784873113623/)
  - @catatsuy: Linuxカーネル上のファイルの仕組みがどうなっているのか、などLinuxカーネルの動きをしっかり説明してくれる本です。

## ネットワーク

インターネットの仕組みをより深く知る。

- [マスタリングTCP/IP　入門編（第6版）](https://www.ohmsha.co.jp/book/9784274224478/)
  - @catatsuy: TCP/IPと言えばこの本。インフラに興味があれば1度目を通してみるとよいと思います。
- [インフラ／ネットワークエンジニアのためのネットワーク技術＆設計入門 第2版 | SBクリエイティブ](https://www.sbcr.jp/product/4797396805/)
  - @catatsuy: 実際にインフラ構築をしようとすると色々悩むと思います。そういう人におすすめです。
- [ネットワークがよくわかる教科書 | SBクリエイティブ ](https://www.sbcr.jp/product/4797393804/)

Cisco 機器のコマンドや操作方法を知る。

- [ネットワークエンジニアとして](https://www.infraexpert.com/study/)
- [シスコ技術者認定教科書 CCNA 完全合格テキスト&問題集[対応試験]200-301](https://www.shoeisha.co.jp/book/detail/9784798165776)

## CDN

- [Web配信の技術 ―HTTPキャッシュ・リバースプロキシ・CDNを活用する：書籍案内｜技術評論社](https://gihyo.jp/book/2021/978-4-297-11925-6)
  - @catatsuy: CDNの活用方法を徹底的に解説しています。特定のCDNを紹介するのではなく、汎用的な説明なのでCDNを活用するならまずは読みたい本です。

## コンテナ

コンテナ技術について知る。

- [Docker/Kubernetes 実践コンテナ開発入門](https://gihyo.jp/book/2018/978-4-297-10033-9)

## Microsoft Azure

ブラウザ上でWeb三層システムを作りながら言葉や考え方に慣れてみる。

- [作りながら覚えるMicrosoft Azure入門講座（IaaS編）](https://www.udemy.com/course/microsoft-azure-iaas-part/)
