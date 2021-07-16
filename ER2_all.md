```
@startuml samplediagram
title Sample ERDiagram
entity "顧客マスタ" {
    + customer_code [PK]
    ==
    pass
    name
    address
    mail
    del_flag
    reg_date
}

entity "購入テーブル" {
    + odrer_id [PK]
    ==
    customer_code [FK]
    purchase_date
    total_price
}

entity "購入詳細テーブル" {
    + odrer_id [PK]
    + detail_id [PK]
}

entity "entity4" {
}

顧客マスタ --{ entity3
顧客マスタ }--{ entity4
@enduml
```
