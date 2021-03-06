# 解いて学ぼうデザインパターン!

## 趣旨

なんでこれ作ろうと思ったか、あとで改めて書く。要約(お気持ち)を書いておく。

演習を楽しく解く(競プロっぽく) -> 愚直に解く -> 演習が変わったら(変更・拡張)？ 
-> デザインパターンを適用する ->　演習が変わったら(変更・拡張)？ -> あら問題がシンプル！ -> 設計が美しい!(と体験してもらう)

という感じで、一度演習を解いたら終わり、では無く演習が抱える問題の本質を読み解いて、
そこで初めてデザインパターンの有用性を理解してもらおうかなと。

## 形式

- 演習のテンプレートや解答は、Ruby 2.0 以降を使う
    - 純粋なオブジェクト指向で、オブジェクトの定義のみに専念できる(全ての演算子はメソッド、staticな世界が無い。)
    - オブジェクト指向における基本パターンは用意されている(アクセサ、モジュール等。)
- 演習がどのパターンかは、解答で明かされる
    - 固定概念に囚われず、演習を自分の思いつく手法で解ける
      (このパターンだから、このオブジェクトを用意しよう、とならない。上級者でも楽しく！)
- Unitテストにより正答を判断する(実際に開発時にUnitテストを使う重要性も感じて欲しいので)

## 演習一覧

上で説明したとおり、パターン名は伏せて単なるシーケンスにしました。
どこまで解いて、どれがどのパターンだったかは、各人で、オリジナルマップを管理しましょう！(それ自体が学習に繋がるはず)

| Execise | Template | Answer |
|:--------|:---------|:-------|
| [Ex01](ex/ex01.md "Ex01") | [A](https://github.com/ababup1192/design_pattern_exercise_ex01_template/tree/ex01-a "A") [B](https://github.com/ababup1192/design_pattern_exercise_ex01_template/tree/ex01-b "B")  [C](https://github.com/ababup1192/design_pattern_exercise_ex01_template/tree/ex01-c "C") | [A](https://github.com/ababup1192/design_pattern_exercise_ex01_ans/tree/ex01-a "A") [B](https://github.com/ababup1192/design_pattern_exercise_ex01_ans/tree/ex01-b "B") [C](https://github.com/ababup1192/design_pattern_exercise_ex01_ans/tree/ex01-c "C")|
