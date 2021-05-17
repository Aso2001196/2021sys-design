```uml
@startuml
ユーザー -> Webシステム :会員登録
Webシステム -> DBシステム :会員登録
DBシステム -> DBシステム :登録処理
Webシステム <- DBシステム :登録結果
ユーザー <- Webシステム :ログイン結果
@enduml
```
