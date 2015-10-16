gulp_starter
====

## Description
Middlemanライクな開発ができるgulpfile。

## Requirement
* node v4.1.0 ~
* bower

## SetUp
### homebrewでnodebrewのインストール

```
brew install nodebrew
```

### nodebrewのパスを通す

`.bashrc`または`.zshrc`など

```
export PATH=$HOME/.nodebrew/current/bin:$PATH
```

```
$ source .bashrc
```

### node.jsのインストール

最新の安定版をインストールします。

```
$ nodebrew install-binary stable
```

### node.jsのバージョンを指定

インストールした最新版を指定します。

```
$ nodebrew use stable
use v4.1.0
```
### node.jsのバージョンを確認

node.jsがつかえるようになっているか確認します。

```
$ node -v
v4.1.0
```

### bowerのインストール

```
npm install -g bower
```

### bowerがインストールされているか確認

```
bower -v
```

## Install

```
$ npm install
$ bower install
```

## Usage

```
$ gulp
$ gulp watch
```

## Contribution

## Licence

MIT

## Author

[KaitoWatanabe](https://github.com/KaitoWatanabe)
