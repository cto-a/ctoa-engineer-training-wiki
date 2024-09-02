# 日本CTO協会エンジニア育成WG Wiki

## Overview
本Wikiは、日本CTO協会のエンジニア育成WGを中心に作成しているエンジニア育成のサポートとなる教材リストとなります。
対象として、エンジニアを育成する側のCTOやEMの方々、また学ぼうとされるソフトウェアエンジニアの方を想定。

## Requirement
- [Go](https://go.dev/doc/install)
- CMS
    - [Hugo](https://gohugo.io/)
- template
    - [Docsy](https://www.docsy.dev/)

## Usage
```
# run dev server
$ hugo serve
```

## Deployment
GitHub Pagesにて公開しています。
https://cto-a.github.io/ctoa-engineer-training-wiki/

## Contents
現状、下記構成でコンテンツを作成しています。

```
content/ja/
├── _index.html
├── docs
│   ├── _index.md
│   ├── about ... Wiki自体について
│   │   ├── _index.md
│   │   ├── contributing.md
│   │   ├── contributors.md
│   │   └── howtouse.md
│   ├── entry ... ソフトウェア・エンジニアリング入門者向け
│   │   └── _index.md
│   └── newcomer ... 職業エンジニアを目指す方・新入社員の方向け
│       ├── _index.md
│       ├── backend.md
│       ├── database.md
│       ├── frontend.md
│       ├── infrastructure.md
│       ├── machine_learning.md
│       ├── mindset.md
│       ├── nativeapp.md
│       ├── people_management.md
│       ├── process.md
│       ├── product_management.md
│       └── security.md
└── howtouse ... 本Wikiの利用方法
    └── _index.html

```

