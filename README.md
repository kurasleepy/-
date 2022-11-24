# -１．作ったゲームの説明
Pythonで作ったコネクトフォー
・頑張ったところ　
通信の実装。TCP通信でクライアントとサーバで分けてみた。
・改善するべき点　
勝利判定が力技すぎる。応用が利かない。
通信してるのに画面が１P,２Pで分かれてないのが難点。
書き終わる前に次の番が押すと描画終了前に次の処理になってしまう。タイマーで入力制限を入れるべき

２．チキンレースゲーム
初心者本に有ったゲームを改善したもの。スマホ向け。
Unityの使い方を知るために作ったので独自性がない。
頑張ったところ
逆走の制限。シーンの遷移の実装。Textの実装
改善すべき点
あんまりおもしろくない。頭を使う感じでも技を使う感じでもない。時速表記とか足すと多少まし。
グラフィックが差し替えしかしてないからモーションとか足したほうが良い

3.マルチ五目並べ
普通は白黒しかない碁石を色を増やしてマルチ対戦可能にしたもの。
当初は拾ってきた五目並べから改造してたが結局全部書き直した。
囲碁が小さいころから好きだけど、難しいとか言われて誰もやってくれないのでとっつきやすいように色々工夫していきたい。
これを元に囲碁の石が置けるかどうかの判定ができるようにするのが最終目標。
頑張ったところ
勝利判定　盤が大きくなっても判定が機能するようにした。
石を置いたときにエフェクトを出してちょっとカッコよくした
上から見る分にはいい感じに碁盤ができた
改善点
ターン回しのコードがもう少しきれいにかけていいと思う。
