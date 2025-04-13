# mac

## plantuml を vs code でうまく表示されない場合

vs code で plantuml extension を入れたけど下記のようなエラーになる。

```
java.io.IOException: Cannot run program "/opt/local/bin/dot": error=2, No such file or directory
```

```
brew install dot
```
はダメで、下記を入れる。

```
brew install graphviz
```

<https://github.com/sitoolkit/sit-cv/blob/develop/README.md>

※javaも前もってinstallしている。

同じ内容のqiitaがあった。
<https://qiita.com/tomokei5634/items/48ce7b61c76238ce7d5a>

## code . ように vs code 起動

コマンドパレットを開く(cmd+shift+p)
"Shell Command: Install 'code' command in PATH"を選択
<https://qiita.com/noto_web/items/eb5d6a904c459b8c6dea>

## for coding, off caps lock, etc...

システム設定 > キーボード > キーボード > 修飾キー > Caps Lock - アクションなし

システム設定 > キーボード > ユーザ辞書 > 
英字入力中にスペルを自動変換をoff
文頭を自動的に大文字にするをoff
スペルチェック > KoreanとEnglishをoff

スマート引用符とスマートダッシュを使用をoff
https://torazuka.hatenablog.com/entry/20140724/smart

## off windows minimalize effect

defaults write com.apple.dock mineffect -string scale


初期日本語の mac folder 名を英語に変更
https://qiita.com/narikei/items/60cdedf0efb616dd0bcd

```
rm ~/Applications/.localized
rm ~/Documents/.localized
rm ~/Downloads/.localized
rm ~/Desktop/.localized
rm ~/Public/.localized
rm ~/Pictures/.localized
rm ~/Music/.localized
rm ~/Movies/.localized
rm ~/Library/.localized

rm /Applications/.localized
```

only python3 is installed.

install python2

https://zenn.dev/satokazur222/articles/66568417b291d8

```
brew install java
```

show hidden files
```
~/Documents % defaults write com.apple.Finder AppleShowAllFiles true
~/Documents % killall Finder
```



