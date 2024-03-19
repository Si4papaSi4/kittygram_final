### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Si4papaSi4/kittygram_final.git
```

```
cd kittygram_final
```

Установить докер:

```
https://www.docker.com/products/docker-desktop/
```

Cоздать файл переменных окружения .env:

```
sudo tocuh .env
```


* Если у вас windows, то через встроенные интерфейсы

Заполнить файл .env:

```
POSTGRES_USER=...
POSTGRES_PASSWORD=...
POSTGRES_DB=...
DB_HOST=...
PGPORT=...
DB_ENGINE=...
SECRET_KEY=...
DEBUG=...
ALLOWED_HOSTS=...

```
Запустить проект:

```
docker build -t ContainerName .
docker run --name ContaineName_container --rm -p 8000:8000 
```

# Используемые технологии

1. **Основной фреймворк:** Django
2. **Тестирование:** Pytest
3. **CI/CD:** GitHub Actions
4. **База данных:** PostgreSQL
5. **Запуск:** Docker

# Сведения обо мне

1. **Имя:** Амир
2. **Фамилия:** Хузяхметов
3. **Опыт работы:** Менее года
4. **Образование:** Пока нету
5. **Навыки и технологии, с которыми работал:** Django, aiogram
7. **Сертификаты и курсы:** Yandex Practicum
8. **Личные интересы и хобби:** Играю на гитаре
9. **Контактная информация (по желанию):**
   - Email: amiral2612@gmail.com
   - GitHub: https://github.com/Si4papaSi4
   - Telegram: @Zachemskinyl