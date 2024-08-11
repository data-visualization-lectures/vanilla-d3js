# Vanilla D3.js



## データのインポート

ヴァージョン3、4、5〜7のそれぞれでインポート方法が異なる。

- data_import_v5-7
- data_import_v4
- data_import_v3


### v5〜v7における方法

Promiseを使用する。

- [data_import_v5-7](data_import_v5-7)


### v4における方法

d3.queue()を使用する。

- [data_import_v4](data_import_v4)

### v3における方法

queue.jsを使用する。

- [data_import_v3](data_import_v3)



## スケール変換

ヴァージョン3、4〜7のそれぞれでインポート方法が異なる。
サンプルファイルは、データのインポートに合わせて三種類用意している。

- scale_v5-7
- scale_v4
- scale_v3

### v4〜7における方法

d3.scaleLinear()、d3.scaleOrdinal()などの構文。

- [scale_v5-7](scale_v5-7)
- [scale_v4](scale_v4)

### v3における方法

d3.scale.linear()、d3.scale.ordinal()などの構文。

- [scale_v3](scale_v3)