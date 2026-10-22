# Доказательство проверки REST API MantisBT

## Результат

- Метод: `GET`.
- Endpoint: `/api/rest/issues/1`.
- HTTP-статус: `200 OK`.
- Результат: сервер вернул данные задачи № 1 проекта `KT6 Project`.
- Дополнительное подтверждение: успешный запрос со статусом 200 был зафиксирован в access log MantisBT.

## Обезличивание

В репозитории не сохранены URL хоста, API Token, пароль, cookie, session ID, заголовок `Authorization` и другие учётные данные. Файл `rest-api-response-sanitized.json` содержит только минимальную выборку полей, подтверждённых итоговым отчётом и скриншотами. Это не полный сырой ответ сервера.

## Связанные материалы

- `rest-api-response-sanitized.json` — обезличенная выборка данных ответа.
- `evidence/05-issue-1-details.png` — интерфейс MantisBT с данными задачи № 1.
- `KT6_MantisBT_Mikheev_MA.docx` и `KT6_MantisBT_Mikheev_MA.pdf` — итоговый отчёт.
