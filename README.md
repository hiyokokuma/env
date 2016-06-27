# OS X Provisioning

Ansibleで環境構築

## Run

```
$ git clone http~=
$ cd provisioning
$ make
```

## 対応していること

1. ansibleのインストール
1. brewのインストール
1. brewによるアプリのインストール
1. brew-caskによるアプリのインストール
1. `defaults`コマンドによるMacの設定自動化
1. zshの設定
1. vimの設定
1. gitの設定
1. sshの設定
1. xcodeのプラグインパッケージマネージャのインストール


## ディレクトリ構成

```
provisioning ❯❯❯ tree -L 1
.
├── Context.sh
├── InstallAnsible.sh
├── Makefile
├── PlayAnsible.sh
├── README.md
└── provisioning/
```
