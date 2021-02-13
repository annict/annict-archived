<p align="center"><a href="https://annict.com" target="_blank" rel="noopener"><img src="https://user-images.githubusercontent.com/56767/56467671-fdd6ea80-645c-11e9-9056-a5d3fd5739e6.png" width="130" /></a></p>

# Annict (アニクト)

[Annict](https://annict.jp) は、見たアニメを記録したり友達に共有したりできるアニメ視聴記録サービスです。

このリポジトリはIssue管理をしたり開発で使用する雑多なファイルを管理するためのもので、実際の開発は以下のリポジトリで行っています。

- [annict-api](https://github.com/kiraka-net/annict-api) (:construction: 準備中)
  - サービス内で使用している内部APIや、[Annict Developers](https://developers.annict.jp/) で一般公開しているWeb APIを提供しています
  - 元々Annictはこのリポジトリしか無いモノリシックなRailsアプリだったので、現状Web API以外にもサイト内の大半のページのHTMLはこのRailsアプリが返しています
- [annict-web](https://github.com/kiraka-net/annict-web) (:construction: 準備中)
  - Webブラウザ向けのUIを提供します
  - annict-api のHTMLを返す部分をこのリポジトリに切り出し始めています

## 開発に参加する

### 新機能、改善案やバグの話など

開発に関するもろもろのやり取りは以下で行っています。

- [GitHub Issues](https://github.com/kiraka-net/annict/issues)
- [Discord](https://discord.gg/PVJRUKP)

やることの優先度や、今何をやっているかは [GitHub Projects](https://github.com/orgs/kiraka-net/projects/1) で管理しています。

### セキュリティに関する報告

hello@annict.com までメールをください。
Twitterなど、第三者が閲覧できる場所に投稿しないでもらえるとありがたいです。

### 開発環境を作る

あとで書く。

## ライセンス

Copyright 2014-2021 Annict

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
