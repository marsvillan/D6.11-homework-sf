# D6.11 Homework
## Установка и запуск (все действия через коммандную строку)
  - скачать проект и перейти в директорию проекта
  ```
$ git clone https://github.com/marsvillan/D6.11-homework-sf
$ cd D6.11-homework-sf
```
  - создать виртуальное окружение
  ```
$ python -m venv env
```
  - применить виртуальное окружение
```
### Если у вас Linux/macOS:
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
- по ссылкам на странице интуитивно можно "Добавить", "Изменить" или "Удалить" книгу
- файлы обложек можно вставлять при создании или изменении книги, они будут сохраняться в директорию media/covers/%Y/%m/%d
- статические файлы хранятся в директории p_library/static/ (например, файл bootstrap.min.css)
- админка так же доступна по адресу http://127.0.0.1:8000/admin (username: admin, password: pass)
