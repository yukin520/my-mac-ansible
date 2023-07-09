
# mmeo 

## 追加設定

### oh my zshのインストール

ターミナルの表示を手間をかけることなくカスタマイズするため、oh my zshをインストールする。  
インストール後、テーマをagnosterへ変更する。

[参考](https://ohmyz.sh/)

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

併せてPowerlineに対応したfontを取得し、設定する。

```
cd ~
git clone https://github.com/powerline/fonts
cd fonts 
./install.sh
cd ..
rm -rf fonts
```