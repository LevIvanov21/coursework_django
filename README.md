Курсовая работа.
Для начала нужно установить зависимости командой "pip -r requirements.txt".
Переименовать файл ".env.example" в ".env" и внести необходимые данные.
Запустить команду "python3 manage.py csu" для создания администратора.
(администратор - admin@service.py, пароль - 1)
Запустить сервер коммандой: python manage.py runserver
(Для вызова функции непосредственной рассылки сообщений необоходимо прописать команду:
"python manage.py runapscheduler")
