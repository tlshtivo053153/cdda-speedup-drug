# 加速薬MOD
Cataclysm: Dark Days Ahead の開発版向けMOD。
加速薬というアイテムでクラフトやスキル上げなどの単調な作業を省力する。

## インストール

1. Githubのページにある `Code -> Download ZIP` からダウンロードする。
2. `mods` フォルダを `data/mods` または `mods` にコピーする。
3. 世界生成時のMODリストから `[基本]->[様々な追加]->[追加 - 加速薬]` を選択。

## 概要
加速薬というアイテムを追加する。
このアイテムは、いくつか種類があり
クラフト速度やスキル成長を早める効果、体力などを回復する効果がある。
ただし、使用後のペナルティで一定の時間が経過するようになっている。

このMODの目的は、現実世界で時間のかかる作業の短縮である。
クラフト、スキル上げ、熟練上げなどに作業感を感じることがあると思う。
通常の長時間作業では、
作業が終わるまでの間に食事や睡眠を繰り返す必要がある。
このMODを使うことで、単調な作業を省略できる。

このMODでは加速薬を作るのに保存食を使い、
加速薬の効果が切れると時間が経過する。
食料と時間というリソースを消費して、
ゲームバランスをあまり損ねないようにしている。

このMODで追加するアイテムの名前は、
`アイテム名 [SD]` と末尾に `[SD]` をつけている。
これは、検索のしやすさを考えてつけた。

## 加速薬
加速薬には `クラフト加速薬`, `学習加速薬`, `回復加速薬` の3種類ある。
`クラフト加速薬` と `学習加速薬` には、それぞれ `日`, `週`, `月`, `年` の4種類ある。
`回復加速薬` には `弱`, `中`, `強` の3種類ある。

`クラフト加速薬` は、クラフト速度と読書速度を上げる。
時間のかかるクラフトの短縮や、
クラフトで上がるスキル上げに使う。

`学習加速薬` は、スキル成長率と読書速度を上げる。
戦闘スキルや熟練上げに使う。

`回復加速薬`は、HPや苦痛の回復、睡眠不足の解消、泥酔からの回復効果がある。

加速薬の `日` は効果時間が切れると、時間が1日経過する。
同様に、`週`, `月`, `年` も効果時間が切れると、
時間が7日, 30日, 365日経過する。
上昇速度の倍率は、経過する時間などから決めている。

### 作り方
加速薬を作るためには `メガカロリー粉末` という中間アイテムを
作り、それを素材にして作る。
`メガカロリー粉末` の材料は、乾燥肉や穀粉、酒類などの保存食である。

### 使用時の仕様について
加速薬は同時に2種類のバフを付けることはできない。
すでに加速薬を使用している時に、
別の加速薬を使用しても、その効果は無視される。
また、同じ種類の加速薬を使用した場合も、
効果の重ねがけはできない。

### 効果時間の確認
`[` キーで変異メニューを出して、特質を選択することで
残り時間を表示できる。
