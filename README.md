# fastapi_messenger
Attempt to create backend for messenger app with reduced functionality Like described under:


  Стек, который Вам необходимо использовать: FastAPI, PostgeSQL, Socketio, OAuth2


2. Задача
Разработать backend для чата с пользователями.

Вначале пользователь должен пройти авторизацию или зарегистрироваться по номеру телефона с помощью OAuth2.
При входе, у пользователя должен быть следующий функционал:


-- Реализовать простое редактирование профиля с изменением информации о нём и аватарки. Аватарку принимать в base64, сохранять её в 3-ёх размерах: 50х50, 100х100, 400х400, и оригинал.
Реализовать функционал чатов с использованием Socketio. Можно посмотреть список чатов для текущего пользователя, завести новый чат или создать группу с несколькими другими пользователями. Также реализовать общение в чате.
Дополнительно должны быть реализованы закреплённые чаты, типы сообщений и лайки для каждого из сообщений.
Сущности необходимо придумать и реализовать самим, на основе текущего задания. Для примера можете ориентироваться на популярные мессенджеры.
Также необходимо реализовать:
- организовать тестирование написанного кода;
- обеспечить автоматическую сборку/тестирование с помощью GitHub CI;
- подготовить docker-compose для запуска всех сервисов проекта одной командой;
- написать конфигурационные файлы (deployment, ingress, …) для запуска проекта в kubernetes и описать как их применить к работающему кластеру;
- сделать так, чтобы по адресу /docs/ открывалась страница со Swagger UI и в нём отображалось описание разработанного API. Пример: https://petstore.swagger.io
;
- обеспечить подробное логирование на всех этапах обработки запросов, чтобы при эксплуатации была возможность найти в логах всю информацию.
- 
