# SYRNIKI Telegram Bot

## Работа с кодом

### Первоначальная настройка

- `python3 -m venv env` - создать виртуальное окружение
- `source ./env/bin/activate` - применить виртуальное окружение, появится префикс **(env)**
- `pip install -r requirements.txt` - установить в виртуальное окружение зависимости проекта
- Создать файл `.env` и добавить строку `TG_TOKEN='<TG_API_TOKEN>'` для целей разработки использовать разные токены
- `python bot.py` - запуск бота

### Продолжение работы с кодом

- `source ./env/bin/activate` - нужно только применить виртуальное окружение

- `python bot.py` - стартовать бота или же можно воспользоваться следующей командой (по желанию)

- `nodemon bot.py` - бот будет перезапускаться при каждом обновлении файла на диске (необходимо иметь nodejs и глобально установить nodemon - `npm install -g nodemon`)

### Добавление зависимостей

`pip freeze -l > requirements.txt` - создаст файл с зависимостями в текущей директории, дальше можно закоммитить

## Работа с Git

- Посмотреть статус - `git status`
- История коммитов - `git log`
- Добавить изменения со всех файлов проекта - `git add .`
- Создать коммит с сообщением - `git commit -m "<message>"`
- Отправить локальные коммиты на сервер - `git push`
- Отправить локальные коммиты из ветки (даже если ветки нет на сервере) - `git push origin <branch>`
- Получить и применить данные из GH - `git pull`
- Создать ветку с именем `<branch>` и переключиться на нее - `git checkout -b <branch>`
- Переключиться на ветку `<branch>` - `git checkout <branch>`
- Замержить ветку можно на сайте GH
