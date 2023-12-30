# リポジトリ　
blizzard003/robosys202x

 
## 概要
このプログラムは、talkerノードとlistenerノードがchatterというトピックでメッセージ（データ）を受け渡すというものである。
人の名前を送ったら、その人の年齢を返すサービスである。
 
## 特徴
各機能を別のプログラムとして実装できる
ノードからノードへトピックという流れを利用してメッセージを渡す 
ノードは複数の「パブリッシャ」や「サブスクライバー」を持てる
 
## 動作環境 
* Ubuntu 20.04 LTS on WSL2
* Ubuntu 22.04 LTS on WSL2
* Ubuntu 22.04 LTS
* ros2・python

ROS２: ロボットアプリケーション開発のためのミドルウェアである。

## 使い方
まず、talkerを先に立ち上げ、
　blizzard03@kasama:~/ros2_ws$ ros2 run mypkg talker

次にlistenerを立ち上げる
　blizzard03@kasama:~/ros2_ws$ ros2 run mypkg listener
その結果、listenerは年齢が受け取れる
 

## 作成者 
* Yuki Kasama
* blizzardyk75@gmail.com
 
## 著作権・ライセンス
・このソフトウェアパッケージは、３条項BSDライセンスの下、再頒布および使用が許可されます。
Ⓒ2023 Yuki Kasama
