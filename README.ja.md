[English](./README.md) / 日本語

# これはなに？
MacでOptionキーを押しながら英字を入力した際に記号が入力されないようにするレイアウトファイルです。
例えば自分のMacではA + Optionキーで`å`という記号が入力されますが、こうした挙動が起こらないようにしたものです。

# 使い方
1. [specialCharsDisabled.bundle.zip](https://github.com/nemolize/disable-alt-symbols-in-mac/blob/master/specialCharsDisabled.bundle.zip?raw=true) をダウンロードして展開。
2. `specialCharsDisabled.bundle` を `~/Library/Keyboard Layouts`にコピーする。
2. キーボード設定を開く。
3. `+` ボタンをクリックして英語を選択する。
4. `specialChartsDisabled`を選択して追加する。
5. 入力ソースを`specialChartsDisabled`に変更する。
6. Optionキーを押しながら文字を入力して、記号が入力されないことを確認する  
(注: 効果がない場合は入力ソースを確認するか、再起動を試してください。)

![screenshot](https://github.com/nemolize/disable-alt-symbols-in-mac/blob/master/screenshot.png?raw=true)

## Thanks
This layout file is created with [Ukelele](http://software.sil.org/ukelele/)