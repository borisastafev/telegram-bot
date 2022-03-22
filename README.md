# telegram-bot
# В данном проекте я создаю телеграм-бота, который визуализирует основные характеристики компаний, входящих в S&P 500. Предварительно я спарсил всё необходимую информацию.

# Для корректной работы нужно: 
 - загрузить всю информацию с сайта - данные по каждой компании
 - сохранить в файл finanz_data
 - сохранить в папку fig_png визуалиции всех компаний
 - запуск основной функции - get_data() у себя на пк, либо на хостинге
 
 # если на хостинге:
- загрузить на сервер следующие файлы: mydata.py, finanz_data, папку fig_png, host_auto_run.py(собственно сама функция)
- установить на самом сервере python3, библиотеку TeleBot
- установить screen для непрерывной работы на сервере и запустить файл host_auto_run.py
