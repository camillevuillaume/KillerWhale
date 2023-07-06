# Killer Whale その他 右手用Build Manual （[左手用](../leftside/8_MISC.md)）

1. [First Page](../README_EN.md)
2. [BASE Unit](../rightside/2_BASE.md)
3. [SIDE Unit](../rightside/3_SIDE_TRACKBALL.md)
4. [TOP Unit](../rightside/4_TOP.md)
5. [ADDITIONAL Unit](../rightside/5_ADD.md)
6. [Assemble](../rightside/6_ASSEMBLE.md)
7. [Customize](../rightside/7_CUSTOM.md)
8. その他
## ファームウェアまとめ（最終更新日: 2023/6/24 18:00）
完成後にファームウェアを入れ替えたくなった場合はこちらからもダウンロード可能です。  
- 単体使用 左右共用キーマップ [tarohayashi_killerwhale_solo_default.uf2
](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.3.1/tarohayashi_killerwhale_solo_default.uf2)
- 左右分割 左手ボール [tarohayashi_killerwhale_duo_ballleft.uf2
](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.3.1/tarohayashi_killerwhale_duo_ballleft.uf2)
- 左右分割 右手ボール [tarohayashi_killerwhale_duo_ballright.uf2
](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.3.1/tarohayashi_killerwhale_duo_ballright.uf2)
- 左右分割 両手ボール [tarohayashi_killerwhale_duo_default.uf2
](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.3.1/tarohayashi_killerwhale_duo_default.uf2)

## VIA用JSONファイル（最終更新日: 2023/6/29 4:00）
- 単体使用向け [killer_whale_solo.json
](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.3.1/killer_whale_solo.json)
- 左右分割向け [killer_whale_duo.json
](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.3/killer_whale_duo.json)

## VIA用キーマップ
- 単体使用左手用キーマップ[solo_left.layout.json](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.4.0/solo_left.layout.json)
- 単体使用右手用キーマップ[solo_right.layout.json](https://github.com/Taro-Hayashi/KillerWhale/releases/download/0.21.4.0/solo_right.layout.json)

### ファームウェアのコード
- https://github.com/Taro-Hayashi/qmk_firmware/tree/tarohayashi/keyboards/tarohayashi/killerwhale/

### Q&A
- 側面/追加ユニットのLEDが光らない
- 側面ユニットのキー以外の機能が動かない
- 分割キーボードでキーマップが左右逆
  - ジャンパーの指定が間違っている可能性があります。  
- ジョイスティックが動かない
  - 左右分割キーボードとして使う場合、ジョイスティックはUSBケーブルを繋いだ側だけが動作します。  
- カーソルがカクつく
  - 左右分割向けのファームウェアで片手のみの利用だとカーソルが飛ぶ現象を確認しています。  単体使用向けのファームウェアをダウンロードしてインストールしてください。
- 何かがおかしい
  - こちらのページの一番下の flash_nuke.uf2 を使うとRaspberry Pi Picoをリセットできるのでお試しください。
    - https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html