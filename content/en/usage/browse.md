+++
title = "Browse"
date = ""
author = ""
cover = ""
tags = []
description = ""
showFullContent = false
+++

Open other git page (e.g. branch, tree, tag, and more...) in current repository.

__COMMANDS:__

`gitb browse branch`

&emsp;Open the branch list page in the current repository.

`gitb browse tag`

&emsp;Open the tag list page in the current repository.

`gitb browse tree`

&emsp;Open the tree page in the current branch.

`gitb browse history`

&emsp;Open the history page in the current branch.

`gitb browse network`

&emsp;Open the network page in the current branch.

`gitb browse repo`

&emsp;Open the repository list page in the current project.

`gitb browse show　[-l, --line <LINE>] [<PATH>]`

&emsp;Open the corresponding page to given file or directory in current repository.

&emsp;Specify the line to be highlighted by appending `#` to the end of the PATH.

&emsp;&emsp;eg: /foo/bar#5, /foo/bar#5-10

__OPTIONS:__

`-l, --line <LINE>`

&emsp;Highlight the specified line. eg: 5, 5-10