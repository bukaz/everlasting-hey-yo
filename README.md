# 俺 everlasting-hey-yo

AWS にインフラ構築してるとサンプルアプリが欲しくなるわけで、トリさんの [everlasting-hey-yo](https://github.com/toricls/everlasting-hey-yo) を自分の都合がいいようにあれこれするレポジトリです。


### 追加オプション

#### `INTERVAL_SEC`: "Hey, Yo!" 間隔 (sec) を指定する

```shell
$ docker run -e TIMESTAMP=1 -e INTERVAL_SEC=5 bukaz/everlasting-hey-yo
2021-02-20T18:38:25+0000 Hey, Yo!
2021-02-20T18:38:30+0000 Hey, Yo!
2021-02-20T18:38:35+0000 Hey, Yo!
...
```

#### `ONE_TIME_HEY_YO`: 一回だけ "Hey, Yo!" して終了する

```
$ docker run -e ONE_TIME_HEY_YO=1 bukaz/everlasting-hey-yo
Hey, Yo!
Bye.
```
