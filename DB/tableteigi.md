# DB定義書
## ER図
[ER図はこちら](https://github.com/Aso2001226/2021sys-design/blob/main/ER_all.md "ER図はこちら")

# DBテーブルカラム詳細一覧

#　データベース詳細


### d_purchase
|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:----:|
|oder_id|order_id|bigint(20)|〇|〇||
|customer|customer_code|varchar(50)||〇||
|purchase_date|date||〇||
|total_price|int(11)||〇||

### d_purchase_detail
|属性名|||||
