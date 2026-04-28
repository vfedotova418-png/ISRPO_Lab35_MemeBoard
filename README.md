# Лабораторная работа №35. Подключаем фронтенд к API: доска мемов

ФИО: Федотова В.С.

Группа: ИСП-232

Дата: 28.04.26

---

## Как запустить

Frontend:

1. Клонировать репозиторий [Github](https://github.com/vfedotova418-png/ISRPO_Lab35_MemeBoard.git)
2. Найти файл `index.html`
3. Запустить через расширение `Live Server`

Backend:

4. В терминале выполнить:

```bash
cd MemesApi/
dotnet run
```

## Что изучили

| Концепция                                 | Где используется                          |
| ----------------------------------------- | ----------------------------------------- |
| **fetch(url)**                            | GET-запрос к API                          |
| **fetch(url, { method, headers, body })** | POST и DELETE запросы                     |
| **response.ok**                           | Проверка успешности ответа                |
| **response.json()**                       | Чтение JSON из ответа                     |
| **JSON.stringify(...)**                   | Объект JS → JSON-строка для отправки      |
| **async / await**                         | Ожидание ответа от сервера                |
| **try / catch / finally**                 | Обработка ошибок при fetch                |
| **CORS**                                  | Разрешение запросов между разными портами |
| **AddCors + UseCors**                     | Включение CORS в ASP.NET Core — два шага  |
