---
title: "インストール"
date: ""
draft: false
---

&emsp;`gitb`をインストールする方法を解説します。サポートするOSはWindows、MacOS、そしてLinuxです。

# Homebrew

&emsp;MacOSで使用可能なパッケージマネージャであるHomebrewでインストールできます。

```bash
brew tap vvatanabe/gitb
brew install gitb
```

# Go

&emsp;Go言語(go1.12+)をインストールしていれば、`go get`コマンドでもインストールできます。

``` bash
go get github.com/vvatanabe/gitb
```

# GitHub Release Page

&emsp;ビルド済のバイナリはGitHubの[リリースページ](https://github.com/vvatanabe/gitb/releases)からOS毎にダウンロードできます。ダウンロード後、パスが通ったディレクトリに配置してください。