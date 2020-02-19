# 基礎プログラミング練習
## はじめに
Rubyをもちいた基礎プログラミング練習！  
以下の問題にチャレンジしてみてください！  
それぞれ別のrubyファイルを作ってね
## BMI計算問題
ファイル名： `bmi.rb`

変数`height`に身長(cm)，  
変数`weight`に体重(kg)  
を代入すると，  
BMIを計算し，BMIの値に対応して「痩せ型」「普通」「肥満」のいずれかを出力するプログラム

BMIは体重を身長(m)の2乗で割ることで計算されます

BMIが18以下の場合「痩せ型」  
25以上の場合「肥満」  
それ以外の場合「普通」  
と出力するプログラムを作ってみましょう！

変数`height`に`178.2`  
変数`weight`に`60.1`を代入したときの出力例：
```
普通
```

## FizzBuzz
ファイル名: `fizzbuzz.rb`

1から30までの数字を順番に出力します  
ただし，3の倍数のときは「fizz」，  
5の倍数のときは「buzz」，
15の倍数のときは「fizzbuzz」  
と出力されるようなプログラムを作りましょう！

出力例：
```
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
16
17
fizz
19
buzz
fizz
22
23
fizz
buzz
26
fizz
28
29
fizzbuzz
```

## 直角三角形問題
ファイル名: `triangle.rb`

変数`height`に整数を代入します

`height`の値の高さの，　　
`*`で直角三角形が出力されるプログラム

`height`に5を代入したときの出力例：
```
*
**
***
****
*****
```

## ピラミッド問題
ファイル名： `pyramid.rb`

変数`height`に整数を代入します

前の，`triangle.rb`からアレンジして，
`height`の値の高さの，
`*`でピラミッドが出力されるプログラム

`height`に5を代入した時の出力例：
```
　　　　　＊
　　　　＊＊＊
　　　＊＊＊＊＊
　　＊＊＊＊＊＊＊
　＊＊＊＊＊＊＊＊＊
```


## 配列の扱いの練習
ファイル名： `array.rb`

変数`colors`を以下のような配列として定義します
```
colors = ['red', 'blue', 'green', 'orange', 'pink', 'purple', 'black', 'white', 'brown']
```

colorsの要素が添字が大きいものから順に出力されるようなプログラム

出力例：
```
brown
white
black
purple
pink
orange
green
blue
red
```