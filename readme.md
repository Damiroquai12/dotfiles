# name

dotfiles for Mac(Apple Silicon)

## description
Mac (Apple Silicon)購入,ファクトリーリセット後にすぐに開発できる環境を整えるためのファイルとする。

## command

```
$ curl -o - https://raw.githubusercontent.com/Damiroquai12/dotfiles/master/install | sh
$ source ~/.zshrc

```
## other
[starship_文字化けを修正]
- starshipのフォントが文字化けしている場合フォントをインストール
$ git clone --branch=master --depth 1 https://github.com/ryanoasis/nerd-fonts.git
$ cd nerd-fonts

# 好きなフォントをインストール
./install.sh #好きなフォントを指定 e.g. $ ./install.sh Hack

# 不要になったファイルを削除
cd ..
rm -rf nerd-fonts

[starship_アイコンの変更]
//starship.tomlでの作業
e.g.ラインの改行をしない
下記を追加
add_newline = false

他にも色々あるので、下記を参照しカスタマイズ
https://starship.rs/config/#prompt

## link
Homebrew: https://brew.sh/
Starship: https://starship.rs/
nerd-fonts: https://github.com/ryanoasis/nerd-fonts

