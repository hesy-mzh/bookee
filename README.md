# 説明

GnuCash 用のデータを置いています。


# ファイルの説明

## ``nisshoboki.2019.csv``

[商工会議所簿記検定試験 商業簿記標準・許容勘定科目表 2019年改定](https://www.kentei.ne.jp/wp/wp-content/uploads/2019/02/2019_kamoku.pdf)
のA欄にある勘定科目をGnuCashのインポート用csvファイルにまとめたもの。

資産、負債、純資産、収益、費用、その他 の6つをプレースホルダーとしてある。

その他に属する勘定科目以外はタイプを設定している。
必要に応じてタイプは振り直す必要がある。

## ``nisshoboki.2019.gnucash``

``nisshoboki.2019.csv`` をインポートした後のGnuCash用XMLファイル。

