@startuml
entity "employee" {
    + id [PK]
    ==
    # company_id [FK(company,id)]
    * employee_code:varchar(16)
    name:varchar(128)
}
@enduml
