# quiz-bot
## todo
1. Интерфейс для работы с данными
   1. Придумать модель храниния данных по вопросам и по пользователям
   2. Один интерфейс для работы с вопросами
      1. Загрузки вопроса
      2. Получения вопросов, с возможностью фильтрации по статусу и по пользователям
      3. Изменить статус вопроса
      4. Подписаться на изменение стутуса
2. Реализовать паттер observable, чтобы была возможность подписки на изменение вопросов
3. Реализация интерфейса на основе файлового хранилища
4. апи
   1. user front - дает возможность отправить вопрос
   2. moderator front - получает по одному вопросу по мере поступления. Имеет возможность изменять статус
   3. admin front - получает все обновления статусов.
5. Придумать механизм авторизации
6. Придумать механизм для учета rate-limit
7. Реализация интерфейса на основе файлового бд
8. Реалиховать di-контейнер, чтобы можно было подменять интерфейс работы с данными в зависимости от окружения и среды
