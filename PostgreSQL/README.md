Вот README только с тем, что выполнено на вашем фото:

```markdown
# PostgreSQL в Docker

## 1. Запуск контейнера

```bash
docker run -d \
    --name my-postgres \
    -p 5432:5432 \
    -e POSTGRES_PASSWORD=mysecretpassword \
    postgres:alpine
```

![alt text](image.png)

## 2. Подключение к PostgreSQL

```bash
docker exec -it my-postgres psql -U postgres
```

![alt text](image-1.png)

## 3. Список баз данных

```sql
\l
```

![alt text](image-2.png)

## 4. Версия PostgreSQL

```sql
SELECT version();
```

![alt text](image-3.png)

## 5. Выход

```sql
exit
```


