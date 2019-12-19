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

__Bash, Zsh__

```bash
function git(){
  gitb "$@"
}
```

__Fish__

```fish
function git
  gitb $argv
end
```