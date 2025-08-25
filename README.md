# JSONPlaceholder Albums API

Документация API для работы с альбомами

## 📚 Swagger UI

Для просмотра интерактивной документации используйте:
https://petstore.swagger.io/?url=https://raw.githubusercontent.com/Yulia9401/albums-api/main/api.yaml

## 🚀 Быстрый старт

## 🚀 Примеры запросов (cURL)

### GET все альбомы
```bash
curl -X GET "https://jsonplaceholder.typicode.com/albums" \
-H "Content-Type: application/json"
```

### GET конкретный альбом  
```bash
curl -X GET "https://jsonplaceholder.typicode.com/albums/10" \
-H "Content-Type: application/json"
```

### POST создать альбом
```bash
curl -X POST "https://jsonplaceholder.typicode.com/albums" \
-H "Content-Type: application/json" \
-d '{
  "userId": 11,
  "title": "Гранатовый альбом"
}'
```

### PUT обновить альбом
```bash
curl -X PUT "https://jsonplaceholder.typicode.com/albums/89" \
-H "Content-Type: application/json" \
-d '{
  "userId": 9,
  "id": 89, 
  "title": "A Night at the Opera"
}'
```

### PATCH частично обновить альбом
```bash
curl -X PATCH "https://jsonplaceholder.typicode.com/albums/15" \
-H "Content-Type: application/json" \
-d '{
  "title": "Новое название"
}'
```

### DELETE удалить альбом
```bash
curl -X DELETE "https://jsonplaceholder.typicode.com/albums/91" \
-H "Content-Type: application/json"
```

# jsonplaceholder-albums-api
Тренирововчное. Работа с музыкальными альбомами без реального сервера и БД. 
