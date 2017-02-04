# Photoshop Duotoneの作成方法

このような画像を作る

![Before](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/0_before.jpg)

![After](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/0_after.png)

### サンプル
[サンプルファイルはこちら](https://github.com/ryo24/PhotoshopDuotoneExplain/tree/master/exampleFiles)

このレポジトリのexampleFilesディレクトリに格納されています。


### 学習要素
- 画像の切り抜き
- クイック選択ツール
- レイヤー
- グラデーションマップ
- 文字ツール


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
クイック選択ツールはaltキーを押している間は*マイナスモード*になるので、ミスして選択した部分はマイナスモードで削除する

![クイック選択ツール](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/3_quickchoice.png)

![選択結果](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/3.1_choceedAnimal.png)

### 新規レイヤーとして切り抜きの実行

選択範囲を元に、切り抜きレイヤーを作成する。
ここで始めてレイヤーという考え方を体験する。

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4_makeLayer.png)

レイヤーパネルにて、目のボタンをクリックすることで、背景の非表示を行う。

![切り抜きが終わった状態](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4_LayerInvisible.gif)



## 3. 塗りつぶしレイヤーの作成
背景が透明になっているので、塗りつぶしレイヤーで背景を入れる。

後ほど、グラデーションマップをかけるので白色で作成。
（黒色にしてもよい）

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4.2_singleLayer.png)

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/4.3lion_layerChange.gif)

## 4. レイヤー順序の交換

レイヤーは上から順番に表示される。塗りつぶしレイヤーが上になっている場合は、動物が出てこないので、レイヤーをドラッグ&ドロップして順番を入れ替える

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/6_layerListChange.gif)

## 5. グラデーションマップの作成

新規調整レイヤーから、グラデーションマップを作成する。グラデーションマップの設定は「紫、オレンジ」。

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/8_gradationMap.png)


グラデーションマップレイヤーを作成したら、*[属性]->カラーバー*をクリックして、グラデーションエディーパネルを開く。明るめの色であったほうが、WebのDuotoneに近くなるので、必要なら調整する。
カラーバー下部の■をクリックすれば変更が可能。

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/8.1_lion_gradationMap.gif)

## 6. 文字ツールで文字の挿入

文字ツールと移動ツールを紹介する。

文字の作成は文字ツールを利用し、作成後の移動などは移動ツールを利用する。
Duotoneでは、文字色は白がわかりやすい。
（グラデーションマップの下に入れると文字色にもグラデーションがつく）

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/9_textTool.png)

文字を入れるとこのようになる。

![After](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/0_after.png)

---


## 番外編Tips集

### 背景をグラデーションにする
背景の塗りつぶしレイヤーを作成時に、ベタ塗りではなく、グラデーション塗りつぶしに変更する

![](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/tips1_makeGradationBackground.gif)

完成イメージ

![完成イメージ](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/tips1_lion_CMinput.png)


### [WIP]境界線の調整で切り抜き名人

スマート半径を利用して、ぼかしをかけることで、Duotoneにしたときの切り抜いた感はかなりなくなる

![境界は内側に作るとよりよい](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/tips2_edgeAdjust.gif)

完成図はこちら

![完成イメージ](https://github.com/ryo24/PhotoshopDuotoneExplain/blob/master/images/tips2_layerAdjustComp.png)


### [WIP]おしゃれなカラーは今あるポスターからKulerで抜き出せ！

1. Webでkulerを開く
2. カラーを参考にしたいDuotoneの画像をD&D
3. カラーが自動抜き出しされる
4. 画像モードからカラー指定モードにして、#のやつをコピー

### [WIP]吹き出しを作るとよりセリフっぽくなる？？

1. 角丸長方形と多角形ツールから三角形を利用して吹き出しを作る
2. 大きさを調整したいときはメニューにある編集 -> 変形 -> 拡大縮小から調整を行う