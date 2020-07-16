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

## В excel файле можете менять/добавлять ассортимент.  

***Пример заполнения таблицы***

| Категория  | Название  | Сорт |Цена |Картинка |Акция |
|:------------- |:---------------:|:---------------:|:---------------:|:---------------:| -------------:|
| Белые вина     | Белая леди |     Дамский пальчик | 399 |belaya_ledi.png | Выгодное предложение |  
  
 Для того чтобы изменения вступили в силу вам нужно:
- Перезапусти сайт если он уже запущен или  командой `python3 main.py`
- Перейдите на сайт по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000).  
- Картинку нужно класть в папку images и указывать название строго с расширением файла.
## Базу с напитками можно размещать в любой папке при выполнии этих действий:

- Скопируйте путь к ***файлу*** где находиться файл.
- Запустите сайт командой `python3 main.py C:\Пример\herypank\file.xlsx`   
 ***Обязательно указать расширение файла***

## Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).
