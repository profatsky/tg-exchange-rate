<h1>tg-exchange-rate</h1>
<hr>
<h2>Описание</h2>
<p>Телеграм бот, демонстрирующий график изменения стоимости криптовалют.</p>
Доступны 3 команды:
<ul>
    <li>/d (/day) - изменение цены за день</li>
    <li>/w (/week) - изменение цены за неделю</li>
    <li>/m (/month) - изменение цены за месяц</li>
</ul>
<img src="assets/gifs/rate.gif">

<h2>Настройка и установка</h2>

```
$ git clone https://github.com/profatsky/tg-exchange-rate.git

$ cd tg-exchange-rate

$ python3 -m pip install -r requirements.txt
```
После клонирования репозитория переименуйте файл .env.example в .env и укажите необходимые
значения: токен бота и id администратора.
