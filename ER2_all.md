```
@startuml samplediagram
title Sample ERDiagram
entity "顧客マスタ" {
    + customer_code [PK]
    ==
    # entity2_id [FK(entity2,id)]
    # entity4_id [FK(entity4,id)]
    * code:varchar(64)
    name:varchar(128)
}

entity "entity2" {
}

entity "entity3" {
}

entity "entity4" {
}

顧客マスタ --{ entity3
顧客マスタ }--{ entity4
@enduml
```
