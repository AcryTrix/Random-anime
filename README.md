
---

# 🎬 Anime Info Scraper

![Python](https://img.shields.io/badge/Python-3.8%2B-green)

Скрипт парсит случайное аниме с [animego.org](https://animego.org/anime/random): название, количество серий и жанры. Работает с ошибками, делает повторные попытки и красиво всё выводит в консоль.

---

## ⚙️ Возможности

* Получает данные об аниме с animego.org
* Парсит название, серии и жанры
* Обрабатывает ошибки и логирует проблемы
* Повторяет запросы при фейле

---

## 🚀 Пример использования

```bash
python main.py
```

---

## 💡 Зачем это нужно

Проект создан как демонстрация:

* как делать HTTP-запросы (`requests`)
* как парсить HTML (`BeautifulSoup`)
* как структурировать простой парсер
* как логировать и обрабатывать исключения

---

## 📦 Зависимости

* Python >= 3.8
* `requests == 2.32.3`
* `beautifulsoup4 == 4.12.3`

---

## 🔧 Установка

```bash
pip install requests beautifulsoup4
```

---

## 📁 Структура

```text
.
├── main.py             # Главная логика
├── http_client.py      # HTTP-запросы с повтором
├── parsers.py          # Парсеры для имени, жанров, эпизодов
├── errors.py           # Кастомные ошибки
├── config.py           # Константы и селекторы
├── LICENSE             # MIT лицензия
└── README.md           # Документация
```

---

## 📚 Полезные ссылки

* [Python Docs](https://docs.python.org/3/)
* [Requests](https://requests.readthedocs.io/en/latest/)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

---

## 📝 Лицензия

Проект распространяется по лицензии [MIT](./LICENSE).

---
