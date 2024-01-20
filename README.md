# 本リポジトリについて
本リポジトリは、江崎貴裕著『指標・特徴量の設計から始める データ可視化学入門 データを洞察につなげる技術』（ソシム）のサンプルコードを公開するためのリポジトリです。

- 動作確認は MATLAB R2023b で実施しています。
- 各サンプルコードは markdown 版 (md、閲覧用) と MATLAB スクリプト版 (mlx) を用意しています。後者は MATLAB で実行できます。
- MATLAB Online で開く場合は MathWorks アカウントでのログインが必要です。
- markdown は export 関数で mlx ファイルから直接生成しています。

例:

```matlab
export('chapter6_2.mlx',Format='markdown',EmbedImages=false)
```

## 

- 筆者による Python コード[tkEzaki/data_visualization](https://github.com/tkEzaki/data_visualization)
- Rによる実装 [https://morimotoosamu.github.io/data_visualization/](https://morimotoosamu.github.io/data_visualization/)


# ご利用に際して　

- 各章の図版を作成するためのコードが各フォルダに入っています。各 MATLAB ファイルは独立して動くようになっているので、個別に取り出して実行できます。
- 本書の中で用いられている図版と厳密に同じ図にはならないことに注意してください。

# コード一覧

以下のリンクをクリックすると MATLAB Online にファイルをクローンして開くことができます（ライセンス不要ですが MathWorks アカウントを作成する必要があります。）
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization)

章ごとに開く場合はそれぞれのリンクをクリックしてください。

|  Chapter (link to markdown) |  Open in MATLAB Online  |
| ---- | ---- |
| 1.1 [データを可視化するということ](chapter1/chapter1_1.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter1/chapter1_1.mlx) |
| 1.2 [可視化の効果を考える](chapter1/chapter1_2.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter1/chapter1_2.mlx) |
| 1.3 [可視化で読み取れるロジック](chapter1/chapter1_2.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter1/chapter1_3.mlx) |
| 2.1 [数量と図形の大きさを紐付る](chapter2/chapter2_1.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter2/chapter2_1.mlx) |
| 2.2 [大きさを比較する](chapter2/chapter2_2.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter2/chapter2_2.mlx) |
| 2.3 [標本を視えるようにする](chapter2/chapter2_3.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter2/chapter2_3.mlx) |
| 3.1 [分布の特徴をとらえる](chapter3/chapter3_1.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter3/chapter3_1.mlx) |
| 3.2 [線で特徴をとらえる](chapter3/chapter3_3.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter3/chapter3_2.mlx) |
| 3.3 [２変数の関係をとらえる](chapter3/chapter3_3.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter3/chapter3_3.mlx) |
| 4.1 [三つ以上の変数の可視化](chapter4/chapter4_1.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter4/chapter4_1.mlx) |
| 4.2 [ネットワークをとらえる](chapter4/chapter4_2.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter4/chapter4_2.mlx) |
| 4.3 [「まとめる」可視化](chapter4/chapter4_3.md) | [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter4/chapter4_3.mlx) |
| 5.1 [分布と統計量](chapter5/chapter5_1.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter5/chapter5_1.mlx) |
| 5.2 [ばらつきをとらえる](chapter5/chapter5_2.md)　|  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter5/chapter5_2.mlx) |
| 5.3 [分布の形をとらえる](chapter5/chapter5_3.md)　|  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter5/chapter5_3.mlx) |
| 6.1 [「近いか遠いか」をとらえる](chapter6/chapter6_1.md)　|  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter6/chapter6_1.mlx) |
| 6.2 [分布同士の距離を測る](chapter6/chapter6_2.md)　|  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter6/chapter6_2.mlx) |
| 6.3 [ペアになった分布間の距離指標](chapter6/chapter6_3.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter6/chapter6_3.mlx) |
| 6.4 [「つながり」をとらえる](chapter6/chapter6_4.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter6/chapter6_4.mlx) |
| 7.1 時間的なパターンをとらえる　| （準備中） |
| 7.2 空間データのパターンをとらえる　| （準備中） |
| 7.3 ネットワークのパターンをとらえる　| （準備中） |
| 8.1 [効果的な可視化のテクニック](chapter8/chapter8_1.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter8/chapter8_1.mlx) |
| 8.2 [指標化から可視化の戦略を考える](chapter8/chapter8_2.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter8/chapter8_2.mlx) |
| 8.3 [可視化されたデータの解釈学](chapter8/chapter8_3.md)　| [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=minoue-xx/MATLAB-example-for-An-Introduction-to-Data-Visualization&file=/chapter8/chapter8_3.mlx) |

## License
MIT

## Todo list

- 図 1.2.3 重要なつながりだけ抜き出す
- 図 1.2.4 全体の関係性パターンを見つける
- 図 1.2.5 様々なデータの並べ方, 日本の地図プロット
- 図 2.1.3 ツリーマップによるグループ情報の付与
- 図 2.3.2 様々な標本の可視化, バイオリンプロット
- 図 4.1.3 変数ごとに個別に可視化する方法, バイオリンプロット
- 図 4.2.4 様々なレイアウトによるネットワーク描画
- 図 4.3.1 クラスターマップによるデータの可視化
- 図 4.3.3 様々なクラスタリング手法
- 図 4.3.4 多変数をペアプロットで見る, データ生成
- 図 4.3.6 画像データの次元削減, MDS, UMAPによる次元圧縮
- 図 4.3.7 HMM による時系列解析
- 図 5.3.1 歪度と尖度
- 図 7.1.3 フーリエ変換で周波数の情報を取り出す(データが必要)
- 図 7.1.4 周波数の時間変化を見る(データが必要)
- 図 7.1.5 心電図データの分析(データが必要)
- 図 7.2.1 ボロノイ図による空間の分割
- 図 7.3.2 様々なネットワーク指標の計算例
