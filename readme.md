### Перед запуском

- в файл hosts добавить:
```bash
127.0.0.1 site.local
127.0.0.1 site.com
```


### Команды для запуска в режиме:

- production:

```bash
docker-compose up --build
```

- development:

```bash
docker-compose -f docker-compose.yml -f docker-compose.development.yml up --build
```

### Команда для запуска командной строки внутри контейнера:

```bash
docker exec -it name_container sh

# выход
exit
```
