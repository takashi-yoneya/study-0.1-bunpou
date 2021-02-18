# Python基本構文の学習用
この課題は初学者さん用に基礎文法の理解度チェックするためのものです。<BR>
ある程度理解している方は飛ばしてもかまいません。

## １ 変数の使い方
変数を使って、「ねずこ」と「ぜんいつ」 は仲間ですとprint文を使って表示させてみよう<BR>
なお、ねずこをname1、ぜんいつをname2として定義してください。

## ２ if文の使い方
１のソースを改造して、name2が敵キャラの「むざん」だった場合に<BR>
仲間ではありませんと表示させてみよう。

## ３ 配列の使い方
以下の配列に対して、キャラクター「ぜんいつ」を追加してみよう。
appendを使うことで追加できます。
name=["たんじろう","ぎゆう","ねずこ","むざん"]

## ４ for文の使い方
３のソースコードで使用したnameのキャラクターをfor文を使って<BR>
１行に１キャラクター表示してみよう

## ５　関数の使い方
関数を１つ作ってみましょう。<BR>
関数化したら、関数を呼び出して結果が表示されることを確認してみよう。

## ６ 引数を使う関数の使い方
以下のようにhikisuuの部分が引数です。引数は関数の外から変数を関数内に渡すことができます。\n
このような引数を使う関数を作成してみよう。<BR>

def test(hikisuu):<BR>

【仕様】<BR>
関数名：なんでも良い<BR>
引数：キャラクターの名前を格納する変数<BR>
関数で行う処理：キャラクターのリスト（３、４で使ったもの）の中に、<BR>
引数で入力されたキャラクター名が存在するか確認して結果をprint文で表示させる<BR>
例）引数が「ぎゆう」→nmaeにぎゆうが存在する→ぎゆうは含まれますと表示
