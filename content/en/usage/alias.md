+++
title = "Alias"
date = ""
author = ""
cover = ""
tags = []
description = ""
showFullContent = false
+++

Please write an alias to .XXXrc (.bashrc, .zshrc, config.fish) if you want to use `gitb <command>` as `git <command>`.

__Bash__

```bash
eval "$(gitb alias -s)"
```

__Zsh__

```zsh
function git(){gitb "$@"}
```

__Fish__

```fish
function git
  gitb $argv
end
```