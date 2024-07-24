# my_mac_setup_with_ansible

ansibleを利用してMacBookの構成を管理するためのリポジトリです。
以下の内容をAnsibleから行います。

- homebrewによるパッケージ管理
- homebrew_caskによるアプリケーション管理
- mas( https://github.com/mas-cli/mas )によるAppStoreからインストールするアプリケーションの管理



## How to use

1. gitとAnsibleをインストールする

```
$ brew install git
$ brew install ansible
```

2. AppStoreへ自身のアカウントでログインする。

3. 本リポジトリをクローンし、playbbok.ymlを実行する。

```
$ git clone https://github.com/yukin520/my_mac_setup_with_ansible.git
```
```
$ cd my_mac_setup_with_ansible
$ ansible-playbook playbook.yml
```

## Other

MACを設定する際のメモ事項もこのリポジトリ上のdocsディレクトリ下で管理する。


