

# Crm System with Authorization

## Описание
Этот проект - обычная срм система, сделанная под магазин. В проекте есть все что нужно для интернет магазина в наши дни:
- Дашборд
- Аналитика по выполненным/невыполненным задачам
- Заметки
- Удобный интерфейс

## Структура проекта
```
/app  - главная папка проекта 
    /forms      - папки для форм (авторизация, клиенты, задачи)
    /routes     - логика по авторизации, соеденения клиента с магазином, выполнение задач.
    /static     - css и js файлы 
    /templates  - фронтенд
app.py - файл, запускающий приложение 
requirements.txt - зависимости
```


## Как запустить проект

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/ErbolTakhirov/CRM
   ```

2. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```
3. Запустите приложение:
   ```
   python app.py
   ```
   
4. Регистрация:
   ```
   Зайдите на http://localhost:5000 в любой браузере и зарегистрируйтесь
   ```

## Используемые технологии

- Flask
- Flask-SQLAlchemy
- Flask-Login
- Flask-WTF
- email-validator
- Werkzeug

## Контакты

Автор: Erbol Takhirov  
GitHub: [https://github.com/ErbolTakhirov](https://github.com/ErbolTakhirov)  
