# mac

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



