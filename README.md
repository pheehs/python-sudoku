﻿python-sudoku
-------------

## What's this?
以下の2つの条件に従ってのみ数独を解こうとするプログラムです。
 * 入る数字が1つに絞られる場所は埋める
 * 埋める場所がなかったら、開いている場所の一つで可能性のある数字に仮定して試してみる
 
[wikipediaの数独の解法](http://ja.wikipedia.org/wiki/%E6%95%B0%E7%8B%AC#.E8.A7.A3.E6.B3.95)の項目にあるいわゆる中級以上の手筋は実装してません。
それのせいか、ものすごく時間がかかる問題(原理的にはいつかは解けるはず)もあれば、すぐに解ける問題もあります。
`sample/`以下にネットから適当に拾ってきた数独のサンプルがあります。
`sample2.txt`と`sample4.txt`は解くのに長時間掛かりそうな雰囲気です。
というか作者も解いてません。（面倒なので）
解けたらかかった時間が表示されると思うので教えて下さいー。

//ncursesを初めて使ってみました。
//案外使いやすい。