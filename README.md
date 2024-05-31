# Graph_tutorial
グラフニューラルネットワークに関する解説資料

奥野研究室で主催中のグラフニューラルネットワークに関する資料を公開しています。

フォルダの構成は以下になります。

``` 
.  
├── DGL_tutorial                     : DGLライブラリのチュートリアル  
|
└── README.md                        : this file  

```

## Deep Graph Library (DGL) 
こちらの資料はグラフを扱うライブラリであるDeep Graph Library の[チュートリアル](https://docs.dgl.ai/) を日本語訳し、初学者向けに加筆したものです。

ライブラリの依存関係は以下になります。
- Python=3.11.8
- Pytorch==2.1.2+cu121
- dgl==2.1.0.cu121
- dglgo==0.0.2


1. `1_introduction.ipynb`: DGLを用いたノード分類
2. `2_dglgraph.ipynb`: DGLを用いたグラフの構築
3. `3_message_passing.ipynb`: GNNモジュールの作成
4. `4_link_predict.ipynb`: GNNを用いたリンク予測
5. `5_graph_classification.ipynb`: GNNを用いたグラフ分類
6. `6_load_data.ipynb`: 自作のデータセットを作成する
7. `7_molecule_dataset.ipynb`: 分子データセット作成とGCNの学習
8. `8_graph_transformer.ipynb`: 簡単に作れる Graph Transformer 