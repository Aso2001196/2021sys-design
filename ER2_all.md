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
