Запускаем mongodb и приложение

```shell
docker compose up -d
```

Настраиваем mongodb и заполняем данными
```shell
./scripts/mongo-init.sh
```

Завершаем работу
```
docker compose down --volumes
```
