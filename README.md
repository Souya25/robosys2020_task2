# robosys2020_task2
ロボットシステム学の課題2で作成したプログラム

## 動作環境
- Raspberry Pi Raspberry Pi 3 Model B+
- Ubuntu20.04 server
- ROS Noetic

## インストール方法
 `cd ~/catkin_ws/src`
 `git clone https://github.com/Souya25/robosys2020_task2.git`
 

## count.py
1秒間に10回トピック（/count_up）にカウントした値をパブリッシュするプログラム

### 実行方法

`roscore`

別端末で

`rosrun robosys2020_task2 count.py`

## twice.py
/count_upの値をサブスクライブし値を2倍にし/twiceにパブリッシュしターミナルに表示するプログラム

### 実行方法

`roscore`

別端末で

`rosrun robosys2020_task2 count.py`

別端末で

`rosrun robosys2020_task2 twice.py`


## 実行している動画
[Youtube](https://youtu.be/F-ppqREXeew)

