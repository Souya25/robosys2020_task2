# robosys2020_task2

## count.py
1秒間に10回トピック（/count_up）にカウントした値をパブリッシュするプログラム

### 実行方法

`roscore`

別端末で

`rosrun robosys2020_task2 count.py`

## count.py
/count_upの値をサブスクライブし値を2倍にし/twiceにパブリッシュしターミナルに表示するプログラム

### 実行方法

`roscore`

別端末で

`rosrun robosys2020_task2 count.py`
別端末で

`rosrun robosys2020_task2 twice.py`




