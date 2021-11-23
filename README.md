# test-project-frontend

Привет!

Суть технического задания: посмотреть, как ты справишься с реализацией небольшой части реального проекта. При выполнении задания желательно применять архитектурные решения как если бы это был полноценный объемный коммерческий проект.

Главное нужно - разработать web приложение, которое по функциональности повторяет первый шаг создания обращения в сервисе ZEN.CAR. В котором пользователь с помощью пошагового выбора услуг/симптомов получает конечный список работ и услуг. Дальнейшие шаги создания обращения реализовывать не нужно. Подробно познакомиться с данным функционалом можно по ссылке https://zen.car/repair-wizard.

Дизайн, стили и общую механику нужно взять со страницы. Если найдете баги, напишите в тех. поддержку) 

Пример запроса 







DOD задачи:
Есть список анкет
Заведены 2 анкеты, которые нельзя редактировать и удалять
Остальные анкеты можно редактировать, удалять
На основе одной анкеты можно создать другую
В анкете можно CRUD разделы
В разделах можно CRUD поля
Поля характеризуются: названием, описанием, кодом, обязательностью, типом: текст/файл
Поля можно drag&drop в рамках анкеты
Данные сохраняются в firebase firestore
Авторизация должна быть реализована через firebase authentication (достаточно использовать только email/password provider)
Разграничение доступа к данным необходимо реализовать средствами firestore rules


Дополнительная информация
API, необходимое для тестового задания реализовано на graphql.
https://zencar-backend-dev.dev.zen.car/graphql - эндпоинт и документация данного API.
Для выполнения задания понадобится использовать
Query.wizardWorks() 
Query.wizardSymptoms()

Стэк технологий:
Желательно React
графика, при ее наличии, только в SVG формате

Что мы ожидаем получить на выходе:
приложение в git репозитории и инструкцией как его запустить;





