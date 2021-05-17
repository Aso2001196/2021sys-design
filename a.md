```uml
@startuml
ユーザー -> Webシステム :会員登録
Webシステム -> DBシステム :会員登録
DBシステム -> DBシステム :登録処理
Webシステム <- DBシステム :登録結果

alt 登録成功
 Webシステム -> ユーザー : 登録メッセージを表示
else 登録失敗
 Webシステム -> ユーザー : エラーを表示
 end
 
@enduml
```
