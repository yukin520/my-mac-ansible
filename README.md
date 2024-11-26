# my-mac-ansible

MacBookの構成を管理するためのリポジトリです。
次の内容をAnsibleから行います。

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
$ git clone https://github.com/yukin520/my-mac-ansible.git
```
```
$ cd my_mac_setup_with_ansible
$ ansible-playbook playbook.yml
```

## Other

Macを設定する際のメモもこのリポジトリ上のdocsディレクトリ下で管理したい。


