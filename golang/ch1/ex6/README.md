# 練習問題1.6

SetColorIndexの第３引数を変更して、複数の色でgifを生成

## 内容

線の色をランダムに変更した  
綺麗ではないが、題意は満たした...ハズ

始めの色の宣言は `const` でやろうとしたが、エラーが出てできなかった  
なぜ定数だとダメで、変数だといいのかよく理解できてない

~~~
$ go build main.go
$ ./main > out.gif
~~~