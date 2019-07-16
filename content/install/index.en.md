---
title: "Install"
date: ""
draft: false
---

　`gitb`をインストールする方法を解説します。

# Homebrew

&emsp;MacOSで使用可能なパッケージマネージャであるHomebrewでインストールできます。

``` bash
$ brew tap vvatanabe/gitb
$ brew install gitb
```

# Snap

&emsp;Debian系のOSで使用可能なパッケージマネージャであるSnapでインストールできます。

``` bash
$ sudo snap install --classic gitb
```

# Go

&emsp;`go get`コマンドでもインストールできます。

``` bash
$ go get github.com/vvatanabe/gitb
```

# Github Release Page

&emsp;ビルド済のバイナリはGitHubの[リリースページ](https://github.com/vvatanabe/gitb/releases)からOS毎にダウンロードできます。ダウンロード後、パスが通ったディレクトリに配置してください。