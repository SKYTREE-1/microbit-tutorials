# micro:bit × NeoPixel（4球 I型）チュートリアル# micro:bit × NeoPixel（8球 I型）チュートリアル
```package
neopixel=github:microsoft/pxt-neopixel
keypad=github:lioujj/pxt-keypad
```

## 光る！カラフル・ライトバーをつくろう@showdialog
この活動では、「カラフル・ライトバーをつくろう」で学習したLEDとkeypad を組み合わせて、指定した色に切り替えるプログラムを作ってみよう」

<!--![メインイメージ(https://www.kodai.uec.ac.jp/sk/make-code/np/img_neopixel.png)-->

---

## 1. 接続しよう@showdialog

まず、テープLED と keypad を micro:bit に接続しましょう。

**配線1**
- micro:bit → テープLED（NeoPixel）  
  - 3V → +5V
  - P12 → DIN
  - GND → GND

👉 接続部分を上にして左から+5V, DIN, GND。（黄色の線は信号、赤/白はモジュールごとに違うので注意‼）。  

![配線図１](https://www.kodai.uec.ac.jp/sk/make-code/np/img_wiring_uecsc.png)
  写真では、真ん中の線（DIN）をP0に接続するように書いてありますが、P12に接続してください。

## 1. 接続しよう@showdialog

まず、テープLED と keypad を micro:bit に接続しましょう。

**配線1**
- micro:bit → テープLED（NeoPixel）  
  - 3V → +5V
  - P12 → DIN
  - GND → GND

👉 接続部分を上にして左から+5V, DIN, GND。（黄色の線は信号、赤/白はモジュールごとに違うので注意‼）。  

![配線図１](https://www.kodai.uec.ac.jp/sk/make-code/np/img_wiring_uecsc2.png)
  写真では、真ん中の線（DIN）をP0に接続するように書いてありますが、P12に接続してください。
  

---
