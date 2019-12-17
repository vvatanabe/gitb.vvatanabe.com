+++
title = "Pull Request"
date = ""
author = ""
cover = ""
tags = []
description = ""
showFullContent = false
+++

&emsp;現在のリポジトリに対するBacklogのプルリクエストに関連するコマンドです。

__COMMANDS:__

`gitb pr [-s <STATE>]`

&emsp;現在のリポジトリのプルリクエスト一覧ページを開きます。

`gitb pr show [<PR-ID>]`

&emsp;指定した`<PR-ID>`のプルリクエストのページを開きます。`<PR-ID>`を指定しない時は、現在のブランチに関連したプルリクエストのページを開きます。

`gitb pr add [-b <BASE>]`

&emsp;現在のブランチでプルリクエストを追加するページを開きます。

`gitb pr blame [git blame command options] <PATH>`

&emsp;指定した`<PATH>`の変更に関連するプルリクエストIDを行単位で表示します。`git blame`コマンドのオプションを適用できます。

__OPTIONS:__

`-s, --state <STATE>`

&emsp;STATEでプルリクエストをフィルタリングします。値: "open" (初期値), "closed", "merged", "all".

`-b, --base <BASE>`

&emsp;BASEはプルリクエストのベースとなるブランチ名です。デフォルトは空です。