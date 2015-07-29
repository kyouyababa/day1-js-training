#day1

##JavaScriptとは何か
* ウェブブラウザではHTMLや画像を表示することしかできなかったが、JavaScriptでプログラムを実行することで様々な描画が行えるようになった
* JavaとJavaScriptはまったくの別物なので、JavaScriptをJavaとは略さないように

##変数について - p.26
* var による変数宣言、省略の仕方
* 変数への文字列値、数値の代入
* 定義した変数の変換（加減乗除など）
* 定義されていない変数の扱い

##定数について - p.28
* 定数の取り扱い

##関数について - p.29
* function を使った関数の定義、return の仕方
* 関数リテラル
* 無名関数、関数名を持った関数 - いずれも var で定義できる

##オブジェクトについて - p.32
* プロパティ（名前と値）の集合としてのオブジェクト
* オブジェクトリテラルとして定義
* 識別子、文字列値、数値などからプロパティを定義できる
* オブジェクトであるプロパティ値には foo.bar のようにドットで連結し演算できる
* プロパティへのアクセスはブラケット[]演算子でも可能

##new式　- p.35
* オブジェクトを明示的に生成する場合は new 式を用いる
* new Date();
* new Object();

##配列 - p.37
* 順序を持った値のまとまりを Array クラスのインスタンスとして定義し、演算や取り出しが可能
``` javascript
var array = [1,2,3,4,5];
```
* arr[] 型で任意の値を取り出すことができる

##文字列型 - p.41
* エスケープシーケンスについて知る
* 演算結果は連結となる
* 数値と同様、Unicode準拠で比較ができる
* String.prototype オブジェクトのプロパティを使って様々な操作が可能

##数値型 - p.50
* 数値リテラルの取り扱い
* 明示的に16進数で取り扱ったり、乗数を定義することも可能
* 浮動小数点による演算のため、あくまでも近似値であることに注意
* 数値ではないものを数値として扱おうとするとNaN型を返す

##演算子 - p.96
* 演算子を用いて計算ができる。
* 詳細は当該頁を参照。
* その他のプログラミング言語やCSSなどと同様、判定・優先の順序や規則があるので注意

##文字列と数値の変換 - p.63
* 以下の関数を使うことにより、文字列を数値化できる
* Number
* parseInt, parseFloat
* 関数を使わずに、以下のように文字列値を数値化することもできる
* '123' - 0
* +'123'
* 以下の関数を使うことにより、数値を文字列に変換できる
* String
* 関数を使わずに、以下のように数値を文字列化することもできる
* '123'+''

##boolean型 - p.57
* true と false で値の真偽値を判定する型をいう
###boolean型の型変換 - p.67
* 各種演算子を用いて比較ができる。
* 以下は、javascriptの公理として false になる
* 0
* NaN
* null
* undefined
* ''
* オブジェクト型は、すでに定義され具体的な中身を持つので、常に true となる

##null型、undefined型 - p.60
* 定義だけされ、具体的な中身がない値はnull型を返す
* そもそも定義されていないものについてはundefined型を返す
