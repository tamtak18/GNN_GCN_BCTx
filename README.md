# GNN_AIST_GCN_BCTx  
## Blockchain取引履歴をGCNに学習させNode classification実施：
1. GCNのライブラリにロードするための前処理
2. 乱数を用いてnodeの特徴量を付与（０～1の実数値）
3. 2の値に応じてnodeにclassのlabel付与（0 or 1）
4. GCNで二値分類のGNNモデル構築
5. モデルの評価
