
# YAUpload

Telegram bot  который загружает фото в яндекс диск.


## Получение Яндекс Диск, Telegram bot токена.

 - [REST API Диска](https://yandex.ru/dev/disk/rest/)
 - [BotFather](https://t.me/botfather)

## Описание

У бота всего одна команда /start, после неё можно скидывать ему фотки, важно указать описание, это будет название папки куда они сохряняться, если не указать, будет создана папка "Мои Файлы".


## Функции

- Загрузка фото
- Загрузка группы фото



## Запуск

Скопировать из репозитория

```bash
  git clone https://github.com/hqwerrewq/YAUpload-tg-bot.git
```
Установить нужные библиотеки

```bash
  pip install -r requirements.txt
```

Редактировать файл .env указав ваши токены

```bash
  BOT_TOKEN='Токен бота'
  DISK_TOKE='Токен диска'
```
Запуск приложения

```bash
  python main.py
```
