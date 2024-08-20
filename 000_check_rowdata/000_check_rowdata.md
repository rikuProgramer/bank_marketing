# SCOPE
生データを確認します。欠損値や異常値の確認をします。
もし欠損値・異常値が確認できた場合は適切な処理の方法や、除去するかどうかを検討します。

# PROBLEM STATEMENT
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).
今回は目的変数のyを予測するモデルを作成します。

# PROPOSAL
欠損値・異常値を確認します。

欠損値の影響が少ない場合は除去をします。もし除去した影響が大きいようであれば適切な補完方法を検討します。