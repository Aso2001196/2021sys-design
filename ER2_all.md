```
@startuml samplediagram
title Sample ERDiagram
entity "顧客マスタ" {
    + customer_code [PK]
    ==

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
