# Кэширование проекта
Существует возможность настроить кэширование проекта, чтобы робот мог выполнять его быстрее. Кэширование настраивает администратор в конфигурационном файле Оркестратора (WebApi). 

Для этого нужно установить для параметра **AllowCaching** значение **true**:
```json
"RpaProject": {
"RemoveOrphans": false,
"AllowCaching": true
},
```
Если кэширование отключено (значение false), то Робот каждый раз перед запуском будет скачивать процесс. Это более безопасный вариант, но занимает больше времени.
