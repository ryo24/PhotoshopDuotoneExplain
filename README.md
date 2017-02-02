# Photoshop Duotoneの作成方法

### 学習要素
- 画像の切り抜き
- クイック選択ツール
- レイヤー
- グラデーションマップ
- 文字ツール

### サンプル
[サンプルファイルはこちら](https://github.com/ryo24/PhotoshopDuotoneExplain/tree/master/exampleFiles)

## 0. 画像の検索

注意点

1. 画像のサイズは大きなものをダウンロード（500px以上推奨）
2. 切り抜きのために、背景と境界が分かれているものを選ぶ

![検索オプション](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/0_search_size.jpg)


## 1. 画像を開く→別名保存

画像を開いたら、まずはフォトショップの画像形式"psd"で保存を行う。

![別名で保存](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/2.1_saveas.png)

![Photoshopを選択](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/2.2_choicephotoshop.png)


## 2. クイック選択ツールで選択→レイヤーで切り抜き

### クイック選択ツールで選択範囲を決定
クイック選択ツールはaltキーを押している間は”マイナスモード”になるので、ミスして選択した部分はマイナスモードで削除する

![クイック選択ツール](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/3_quickchoice.png)

### 新規レイヤーとして切り抜きの実行

確認まで行う。ここで始めてレイヤーという考え方を知る。

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4_makeLayer.png)

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4.3rion_layerChange.gif)


## 3. 塗りつぶしレイヤーの作成
背景が透明になっているので、塗りつぶしレイヤーで背景を入れる。
後ほど、グラデーションマップをかけるので白色で作成。
（黒色にしてもよい）

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4.2_singleLayer.png)

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4.1_rion_layer.gif)

## 4. レイヤー順序の交換

レイヤーは上から順番に表示される。塗りつぶしレイヤーが上になっている場合は、動物が出てこないので、レイヤーをドラッグ&ドロップして順番を入れ替える

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/6_layerListChange.gif)

## 5. グラデーションマップの作成

作成するグラデーションマップは「紫、オレンジ」。

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/8_gradationMap.png)


グラデーションマップレイヤーを作成したら、[属性]->カラー部分をクリックして、グラデーションエディーパネルを開く。明るめの色であったほうが、WebのDuotoneに近くなるので、必要なら調整する。
カラーバー下部の■をクリックすれば変更が可能。

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/8.1_rion_gradationMap.gif)

## 6. 文字ツールで文字の挿入

文字ツールと移動ツールを紹介する。
Duotoneでは、文字色は白がわかりやすい。
（グラデーションマップの下に入れると文字色にもグラデーションがつく）

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/9_textTool.png)

---


## 番外編Tips集

### 背景をグラデーションにする
背景の塗りつぶしレイヤーを作成じに、ベタ塗りではなく、グラデーション塗りつぶしに変更する

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/tips1_makeGradationBackground.gif)

完成イメージ
![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/tips1_rion_CMinput.png)
