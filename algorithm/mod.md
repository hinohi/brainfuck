# mod
## 概要
divmodeから商を除いたもの。

## アルゴリズム

```bf
ndrXY
n[n->d-[>r+>X]>Yr?[r+[-<d+>]>>Y]Y<<<<n]
```

## 前提メモリ条件

+ n: 被除数
+ d: 除数(2以上)
+ X, Y, r: 0

## 処理後のセル

+ n: 0
+ d: d-n%d
+ r: n%d
+ X, Y: 0
