# Killer Whale ビルドガイド

1. スタートページ（このページ）
2. [ベースユニットの組み立て](左手用/ベースユニット.md)
3. [追加ユニットの組み立て](左手用/追加ユニット.md)
5. [側面ユニットの組み立て](左手用/側面ユニット.md)
6. [天面ユニットの組み立て](左手用/天面ユニット.md)
7. [カスタマイズ](左手用/カスタマイズ.md)

![完成図](img/IMG_.jpeg)  
大きな袋の中にスイッチプレートと5つの袋が入っています。キット以外に以下の部品が必要です。  
![袋](img/IMG_.jpeg)   

## キット以外に必要なもの
![追加パーツ](img/IMG_.jpeg)  
|部品名|数||
|-|-|-|
|[キースイッチ](https://shop.yushakobo.jp/collections/all-switches)|27|Cherry MX互換|
|[キーキャップ](https://shop.yushakobo.jp/collections/keycaps)|27|Cherry MX互換|
|[Raspberry Pi Pico](https://shop.yushakobo.jp/products/raspberry-pi-pico)|1|W、Type-C版も可|
|[USBケーブル](https://shop.yushakobo.jp/products/usb-cable-micro-b-0-8m)|1||

### オプション
![オプション](img/IMG_.jpeg)  
|部品名|数||
|-|-|-|
|LED（[SK6812MINI-E](https://shop.yushakobo.jp/products/sk6812mini-e-10)）|32|発光させられますが難易度が上がります|
|[コンスルー20ピン](https://shop.yushakobo.jp/products/31?variant=40815840067745)|2|Raspberry Pi Picoをつけ外しできるようになります|
|TRSケーブル、[TRRSケーブル](https://shop.yushakobo.jp/products/trrs_cable)|1|2台を接続できます|

### 必要な工具
![工具](img/IMG_.jpeg)  
|工具名|
|-|
|はんだごて|
|はんだ|
|ニッパー|
|カッター（デザインナイフ）|
|やすり（棒、紙）|
|+の精密ドライバー|
|ナットをしめるもの（ラジオペンチ、M2スパナ）|

## 準備
### ファームウェアを書き込む
製作の前にRaspberry Pi Picoをキーボードとして使えるようにします。
こちらのファイルをダウンロードしてください。  
 - []

Raspberry Pi PicoのBOOTSELボタン押しながらUSBケーブルでPCと接続すると、RPI-RP2というUSBメモリとして認識されます。  
![](img/IMG_3493.jpeg)   
![](img/rpi.jpg)   
ダウンロードしたファイルをそこにドラッグ&ドロップしてドライブが消えたら成功です。  
書き込みが終わったら一旦USBケーブルは外します。  

### スイッチプレートの切り離し
スイッチプレートは繋がった状態で入っていて、切り離して使います。
![スイッチプレート全体、文字](img/IMG_.jpeg)  
カッターで切れ目を入れ、折って切り離します。
![カッター](img/IMG_.jpeg)  
断面は棒やすりや、平らな面に敷いた紙やすりで綺麗にします。
![やすり](img/IMG_.jpeg)  

### 左右を決める
キットを左右どちらで作るか決めてベースユニットの組み立てに進んでください。
- [ベースユニット 左手用](左手用/ベースユニット.md)
- [ベースユニット 右手用](右手用/ベースユニット.md)

左右のビルドガイドの違いは写真だけです。
