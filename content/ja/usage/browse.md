+++
title = "Browse"
date = ""
author = ""
cover = ""
tags = []
description = ""
showFullContent = false
+++

現在のリポジトリに関するGitページ（ブランチ、ツリー、タグ等）を開きます。

__COMMANDS:__

`gitb browse branch`

&emsp;現在のリポジトリのブランチ一覧ページを開きます。

`gitb browse tag`

&emsp;現在のリポジトリのタグ一覧ページを開きます。

`gitb browse tree`

&emsp;現在のブランチのツリーページを開きます。

`gitb browse history`

&emsp;現在のブランチの履歴ページを開きます。

`gitb browse network`

&emsp;現在のブランチのネットワークページを開きます。

`gitb browse repo`

&emsp;現在のプロジェクトのリポジトリ一覧ページを開きます。

`gitb browse show　[-l, --line <LINE>] [<PATH>]`

&emsp;現在のリポジトリで指定されたファイルやディレクトリに対応するページを開きます。

&emsp;PATHの末尾に`#`を付与してハイライトしたい行を指定できます。

&emsp;&emsp;例: /foo/bar#5, /foo/bar#5-10

__OPTIONS:__

`-l, --line <LINE>`

&emsp;LINEで指定した行をハイライトします。 例: 5, 5-10