データ構造
===

## Stack

Goでパッケージ化してみた(対して意味はない)
逆ポーランド記法は、Stackの問題としてはいい問題だと思った。
あと感じたのは、Perlの配列/リストに関する関数でpushとpopがあったのを思い出した。
流石に、基本的なデータ構造はわざわざ定義しなくても使えるということと、Stackを知ったことでpopとかpushという操作の名前で何をしてるのかがわかるようになったかな。

## Queue

思ったより時間かけすぎてるから、自分でコードは書かない。
この辺りも、基本的なすぎるデータ構造で自分で実装する必要はないんだと思われ。
ただ、問題でリングバッファ使ってenqueue、dequeueをO(1)でやっているのは新しい知見だった。
ポインタとか使わないリスト世代だから、ポインタを循環させるとかいう発想が出てこないんだろう。

## 連結リスト
ちょっとややこしくなってきた。
普段はなんの意識もせずにリストは使ってるけれど、データを動的に変化させるにはテクニックが必要だということですね。

## まとめ

あえて実装はしたけれど、実際はよく使われるから標準ライブラリに入ってる。
面白いと思ったのは、vectorとlistでどちらも可変長配列を扱うが、要素の挿入・削除にO(n)とO(1)と計算時間の差があること。
vectorは[]で要素にアクセスできつが、listはできないしね。

