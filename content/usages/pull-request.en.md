+++
title = "Pull Request"
date = ""
author = ""
cover = ""
tags = []
description = ""
showFullContent = false
+++

&emsp;Related to Backlog Pull Requests for the current repository.

__COMMANDS:__

`gitb pr [-s <STATE>]`

&emsp;Open the pull request list page in the current repository.

`gitb pr show`

&emsp;Open the pull request page related to the current branch.

`gitb pr add [-b <BASE>]`

&emsp;Open the page to create pull request with the current branch.

__OPTIONS:__

`-s, --state <STATE>`

&emsp;Filter pull requests by STATE. Values: "open" (default), "closed", "merged", "all".

`-b, --base <BASE>`

&emsp;BASE is base branch name. Default is empty.