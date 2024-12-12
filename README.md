#     M5Core2-Sokoban
## M5Core2ライブラリプロジェクト
M5Core2のSD-Updaterを用いたライブラリ集を構築するプロジェクトの一環として実装されています。

## どんなゲーム？

8bitマシン時代の古くからある、パズルゲームです。

- 中にいる人物を操作して倉庫の中の箱を動かして、箱を目的場所（□）まで全て移動させます。
- 箱は重いため、1つしか押せません。つまり、2つ箱が並ぶと並んだ方向には押すことができません。

オリジナルはM5Stack用プログラムであったので、M5Core2に移植しています。

移植の際、オリジナルは3つのボタンで複数の操作を行うため、複雑なボタン同時押しなどが必要でした。

ここでは、シンプルに十字ボタンのように扱えるようにするため、
- 左ボタンで左
- 右ボタンで右
- 真ん中ボタンで下
- 液晶画面の下の端で上
に移動するように書き換えています。

## M5Stack-SD-Updater対応です

https://github.com/tobozo/M5Stack-SD-Updater 
https://github.com/lovyan03/M5Stack_LovyanLauncher 

# プログラマ

尾和 東/ぽこちゃ技術枠