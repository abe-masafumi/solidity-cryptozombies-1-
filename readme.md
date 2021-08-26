https://github.com/github/linguist/blob/master/lib/linguist/languages.yml
> シンタックスハイライトが効かない（泣）
# Solidity
<img src="home.png">

# 記述方法
-  1:バージョンの指定
> ページの一番上には必ずバージョンの指定をする  
```sol
pragma solidity ^0.4.19;
```

- contractの指定
> jsでいうclassのこと？骨組み・約束　みたいな意味   
> 使用例:  
```sol
contract HelloWorld {
---この中に処理を記入---
}
```

- 状態変数の定義
>  状態変数はコントラクト内に永遠に保管され続けるもの  
> データベース）に書き込むようなものだと思って良い。  

> よく使う状態変数  
> uint => 符号なし整数のデータ型  
> 使用例:  
```sol
uint dnaDigits = 16;
```

> 他にもこんな演算があるよ  
```sol
加算（足し算）: x + y
減算（引き算）: x - y
乗算（掛け算）: x * y
除算（割り算）: x / y
剰余（余り）: x % y
```
> Solidityは指数演算子もサポートしている。(例 "xのy乗"、 x^y)  
```sol
uint x = 5 ** 2; // 5^2 = 25 と同様
```

- 構造体
> 構造体(struct)は複数のプロパティを持つ複雑なデータ型を作成することができる  
> Class構文みたいなイメージ？  
> 使用例:    
```sol
struct Person {
  uint age;
  string name;
}
```
- 配列
> 固定長配列と可変長配列がある  
```sol
// 2要素の固定長の配列の場合：
uint[2] fixedArray;
// 別の固定長配列の例。5つの文字列を格納できる：
string[5] stringArray;
// 可変長配列 - 決まったサイズはないので、格納し続けることができるぞ：
uint[] dynamicArray;
```






