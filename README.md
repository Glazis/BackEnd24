# BackEnd24Ключевая информация и обоснование
Проблема, которую решает данный проект, заключается в том, что студенты сталкиваются с необходимостью эффективно управлять своими учебными заданиями, контролировать сроки сдачи, организовывать свое время. Традиционные методы управления задачами (блокноты, напоминания на телефоне) могут быть неэффективными и неудобными для студентов.

Функциональные требования:
Регистрация студентов и выдача им уникальных учетных записей.
Создание, назначение и отслеживание задач для студентов.
Возможность установки сроков выполнения задач и уведомлений о приближающихся крайних датах.
Возможность добавления приоритетов и категорий задач.
Поддержка возможности отмечать задачи как выполненные и архивировать их.
Генерация отчетов о выполненных задачах и проделанной работе.

Нефункциональные требования:
Безопасное хранение данных студентов и задач.
Интуитивный и простой пользовательский интерфейс для удобства использования.
Оперативное выдача уведомлений и обновление информации.
Высокая производительность системы даже при большом количестве пользователей и данных.
Поддержка системы на различных устройствах и браузерах.
Стек технологий для этого проекта будет зависеть от требований. Возможные технологии, которые будем использовать, включают:

Фронтенд: React.js
Бэкенд: Python, Django
База данных: PostgreSQL
Аутентификация: JWT
Коммуникация: GraphQL

Почему это нужно документировать и почему эта информация является ключевой:
 Ясное понимание проекта:
Документация позволяет всем участникам понять цели и требования проекта, обеспечивая единое видение и упрощая взаимодействие в команде.

База для будущего развития:
Документация служит основой для дальнейшего сопровождения, развития и масштабирования проекта, облегчая добавление новой функциональности и встраивание новых членов в команду.
Улучшение командной работы:
Хорошо задокументированные требования и технологический стек помогают разработчикам эффективно согласовывать усилия, уменьшая возможные конфликты и расхождения в понимании.

 Правила работы внутри репозитория
Ветвление и вливание изменений:
Основные ветки:
main: Используется для стабильной версии кода, находится в рабочем состоянии.
develop: Ветвь для разработки новых функций, объединяется с основной веткой перед релизом.
Функциональные ветки:
Новые фичи или исправления должны разрабатываться в отдельных ветках, именованных согласно задаче.
После завершения работы над задачей влить изменения обратно в develop через Pull Request.

Pull Requests и Code Review:
Создание Pull Requests:
Каждое изменение требует Pull Request.
Понятное описание изменений, связь с задачей, необходимые тесты.
Code Review:
Каждый Pull Request должен пройти через Code Review.
Конструктивная обратная связь, обсуждение проблем и улучшений.

Работа с Issues:
Создание Issues:
Проблемы, задачи и улучшения должны быть открыты через Issues.
Четкое описание задачи, при необходимости указание ответственного.
Управление задачами:
Распределение задач, комментирование, отслеживание статусов через Issues.

Коммиты и сообщения о коммитах:
Четкие коммиты:
Каждый коммит должен быть логически связан с задачей.
Описание в сообщении коммита: "Исправлена ошибка в валидации формы".

Документация и ReadMe:
Обновление документации:
Все ключевые изменения должны быть отражены в документации.
ReadMe должен содержать текущую информацию по проекту и инструкции для разработчиков.

Безопасность и конфиденциальность:
Управление доступом:
Ограничен доступ к конфиденциальным данным.
Использование ключей или токенов для безопасной аутентификации и авторизации.
