# raspi-smell-sensor

## 背景
- 鼻が悪いので赤ちゃんのうんちにきづけない...  
- ラズパイでうんちをけんちできるのではないか？  
    →ラズパイ+臭気センサを使ってみる


## 用意するもの
- [Raspberry Pi Zero WH](https://akizukidenshi.com/catalog/g/g112958/)
- [ADRSZOD ゼロワン 臭気センサ拡張基板](https://bit-trade-one.co.jp/adrszod/)
- sandiskのSDカード
- ラズパイ用の電源


## ラズパイの設定
1. [こちら](https://www.raspberrypi.com/software/)よりimagerを取得
1. "CHOOSE DEVICE"で"RASPBERRY PI ZERO"を選択
1. osは"RASPBERRY PI OS(32-BIT)"を選択
1. "would you like to apply OS customization settings?"と出るのでやっておく
    1. 一般: ホスト名やwifi設定をあらかじめやっておく  
        ＊5Ghzのwifiは最初に設定しても使えないので注意(詳細は[こちら](https://qiita.com/ymktmk/items/424a34191585db25bdab))
    1. サービス: sshを有効化しておく
1. 書き込みを実行→結構時間かかる
1. sdをラズパイにさす+電源もさす→ラズパイのライトが光る
1. 



## 参考
- [Raspberry Pi 4 5GHzのWi-Fiに接続する](https://qiita.com/ymktmk/items/424a34191585db25bdab)