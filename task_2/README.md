Запрос на выбор магазинов из списка партнёров

```http
GET /api/v1/partner-stores HTTP/1.1
Host: petrushka.ru
Accept: application/json
Accept-Language: ru
Authorization: Bearer <user_access_token>
```

Пример запроса на сервер: https://petrushka.ru/api/v1/partner-stores

Response body:
200 OK

Пример ответа — в файле [response_example.json](./response_example.json).

Ошибки
400 Bad Request
401 Unauthorized
403 Forbidden
500 Internal Server Error
