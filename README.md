# my_mac_setup_with_ansible

ansibleを利用してMacBookの構成を管理するためのリポジトリです。
以下の内容を行います。

- homebrewによるパッケージ管理
- homebrew_caskによるアプリケーション管理
- mas( https://github.com/mas-cli/mas )によるAppStoreからインストールするアプリケーションの管理


## prerequirement

1. homebrewをインストール後、gitとAnsibleをインストールする

```
$ brew install git
$ brew install ansible
```

2. AppStoreへ自身のアカウントでログインする。


## how to use

```
$ git clone https://github.com/Yuki0520-ba/my_mac_setup_with_ansible.git
$
$ amnsible-playbook playbook.yml
```