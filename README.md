# Новое русское вино

Сайт магазина авторского вина "Новое русское вино".

## Подготовка к запуску.  

Установить библиотеки командой.  
```
pip install -r requirements.txt
```

## Запуск

- Скачайте код
- Запустите сайт командой `python3 main.py`
- Перейдите на сайт по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000).

## В файле wines.xlsx можете менять/добавлять ассортимент.  

Для того чтобы изменения вступили в силу вам нужно:
- Удалить файл index.html
- Запустите сайт командой `python3 main.py`
- Перейдите на сайт по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000).  

## Базу с напитками можно размещать в любой папке при выполнии этих действий:

- Файл должен называться строго `wines.xlsx`
- Скопируйте путь к ***папке*** где находиться файл.
- Запустите сайт командой `python3 main.py C:\Пример\herypank\`

## Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).
