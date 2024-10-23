# シングルケースデザイン（SCD）における反転法のグラフ作成

ここでは、Pythonのseabornライブラリを使用して、ABAデザインまたはABABデザインなどの反転法のグラフを作成するコードを作成しました。以下に、実際に作成されるグラフやその作成手順を記載していますので、良かったら使ってください。

## 出来上がるグラフ

例えばこのようなグラフを作ることができます。

- ↓サンプルグラフ⓵（ABAデザイン）

![サンプルグラフ](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/aba.png)

- ↓サンプルグラフ⓶（ABABデザイン）

![サンプルグラフ](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/abab.png)

- ↓サンプルグラフ⓷（ABCBCデザイン）
ちょっと特殊なこのようなデザインにも対応しています。

![サンプルグラフ](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/abcbc.png)

## 使い方手順

1. **データの準備**: グラフで使用するCSVファイルを用意してください。CSVファイルは、エクセルで作成した表データの保存時にCSV形式を選ぶだけでも可能です。
行や列ついては、以下のファイルの形式に沿って入力してください。

- [サンプルグラフ⓵のCSVファイル](https://github.com/PT-Araisan/scd-abab-graph/blob/main/detaset/aba.csv)

- [サンプルグラフ⓶のCSVファイル](https://github.com/PT-Araisan/scd-abab-graph/blob/main/detaset/abab.csv)

- [サンプルグラフ⓷のCSVファイル](https://github.com/PT-Araisan/scd-abab-graph/blob/main/detaset/abcbc.csv)

サンプルグラフのCSVファイルは赤丸の場所からダウンロードできます。

![画像１](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/demo1.png)



- 次に、後で使うので、↓こちらのファイルを押してから
- [Pythonコードのファイル](https://github.com/PT-Araisan/scd-abab-graph/blob/main/main.ipynb)

- この赤丸の場所を押してmain.ipynbというファイルをダウンロードしておいてください。
![画像３](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/demo2.png)

2. **Google colaboratoryの利用**: 次にこちらのツールを使います。今回の作業は無料で可能。

- [Google colabのサイトへ行きます）](https://colab.research.google.com/?hl=ja)
Googleアカウントが必要です。

- そして↓アップロードを押す。
![画像４](https://github.com/PT-Araisan/scd-mltbs-graph/blob/main/assets/demo2.png)
もしくはファイルのタブから『ノートブックをアップロード』を押す。

- さっきダウンロードしたmain.ipynbをアップロードしてください。

すると、↓このような画面になります。そこで

- ⓵を押すと⓶が出てきます。少し時間がかかることがあります。５秒くらい。

- ⓶を押して、グラフを作りたいCSVファイルをアップロードしてください。

![画像４](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/demo4.png)


- 最後に、↓の画像の'hoge.csv'のところを、自分がアップロードしたファイルの名前に変更して、上の赤丸の△ボタンを押します。Ctrl + Enterでもいいです。
![画像５](https://github.com/PT-Araisan/scd-abab-graph/blob/main/assets/demo3.png)

3. **グラフが表示されたら、右クリックで画像を保存してください**


## 補足事項

- 多層ベースライン法の検定や効果量の計算は、[『Rではじめるシングルケースデザイン』（藤巻 峻・山田 剛史　著）](https://ratik.org/9955/907438227/)を参考にすることをお勧めします。そちらでは解析パッケージをダウンロードすることができ、RStudioを活用して簡単にランダマイゼーション検定やTau-Uなども算出できます。

## お問い合わせ

何か質問や要望があれば、[Twitter の DM](https://x.com/Pt96442837Pt) からお気軽にお知らせください。

