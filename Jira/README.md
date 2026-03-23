Вот README только с тем, что выполнено на вашем фото:

```markdown
# Jira в Docker

## 1. Запуск контейнера

```bash
docker run -d --name jira -p 2990:8080 atlassian/jira-software:latest
```

![alt text](image.png)

---

## 2. Просмотр логов

```bash
docker logs -f jira
```

![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)



---

## 3. Страница установки

Открыт браузер с формой настройки базы данных

![alt text](image-4.png)
```

