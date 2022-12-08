# ROS2を用いての、ノード間の連携

![test](https://github.com/souta-pqr/mypkg/actions/workflows/test.yml/badge.svg)

## 何をするためのソフトか
* ノード間でのデータが送受信ができていることを確認するためもの。

## 動作確認済み環境
* ubuntu 22.04

## 起動する手順
* `git clone <リポジトリのURL>`

## 簡単な使い方
* 'ros2 run mypkg talker' と 'ros2 run mypkg listener' を二つの端末を立ち上げて、行う。
	*実行結果(延々と続くため、最初の3行を表示している)
    →[INFO] [1670533199.245508900] [listener]: Listen: 0
      [INFO] [1670533199.736696900] [listener]: Listen: 1
      [INFO] [1670533200.236635100] [listener]: Listen: 2

## LICENSE・使用しているコードについて
* このソフトウェアパッケージは、3条項ライセンスの下、再頒布および使用が許可されます。
* このパッケージのコードは、下記のスライド( CC-BY-SA 4.0 by Ryuichi Ueda) のものを、本人の許可を得て自身の著作としたものです。
    *[ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Souta Kobori	
