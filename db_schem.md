# データベース詳細

### d_purchase
|属性名|型|PK|NN|FK|
|-------|-------|---|---|---|
|order_id|bigint(20)|○|○||
|customer_code|varchar(50)||○||
|purchase_date|date||○||
|total_price|int(11)||○||

### d_purchase_detail
|属性名|型|PK|NN|FK|
|-------|-------|---|---|---|
|detail_id|bigint(20)|○|○||
|order_id|bigint(20)|○|○|○|
|lite_code|int(11)||○||
|price|int(11)||○||
|num|int(11)||○||
