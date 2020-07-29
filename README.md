# PWS-15_d7_users

## Доступен в Heroku по адресу:
https://thawing-island-83857.herokuapp.com

## Установка и запуск (все действия через коммандную строку)
  - скачать проект и перейти в директорию проекта
  ```
$ git clone https://github.com/LovingFox/PWS-15_d7_users
$ cd PWS-15_d7_users
```
  - создать виртуальное окружение
  ```
$ python -m venv env
```
  - применить виртуальное окружение
```
### Если у вас Linux:
$ source env/bin/activate
### Если у вас Windows:
$ env\Scripts\activate.bat
```
 - установить зависимости
  ```
$ pip install -r requirements.txt 
```

  - запустить сервер
  ```
$ python manage.py runserver 
```

## Использование
- открыть страницу http://127.0.0.1:8000/
- можно войти, предварительно создав пользователя или авторизоваться через GitHub

