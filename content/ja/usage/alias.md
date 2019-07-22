+++
title = "Alias"
date = ""
author = ""
cover = ""
tags = []
description = ""
showFullContent = false
+++

`gitb <command>`を`git <command>`として使いたい場合は、.XXXrc（.bashrc、.zshrc、config.fish）に以下のエイリアスを書いてください。

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