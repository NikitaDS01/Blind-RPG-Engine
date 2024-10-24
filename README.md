# Blind-RPG-Engine

Blind-RPG-Engine — это игровой движок для создания RPG игр, в котором все действия выполняются с помощью API. Данный проект написан на языке C# и предназначен как для начинающих, так и опытных разработчиков.

# Содержание

1. [Описание](#описание-проекта)
   1. [Статус проекта](#статус-проекта)
   1. [Принципы](#принципы-данного-программного-обеспечения)
   1. [Цели](#цели)
   1. [Технологии](#технологии)
1. [Дорожная карта](#дорожная-карта)
1. [Установка](#установка)
1. [Пример](#примеры)
1. [Вклад](#вклад)
1. [Авторы](#авторы)
1. [Лицензия](#лицензия)

# Описание проекта

Blind-RPG-Engine - предоставляет пользователям инструменты для создания RPG игр. Его особенность считается то, что он работает только с помощью API. Он включает в себя систему управления событиями, интеграцию данных, механики боев, квестов и мн. другое. Интуитивно понятное API позволяет легко взаимодействовать с игровыми элементами. Визуальный часть создаётся на стороне пользователя данного движка. База данных создаётся на стороне пользователя.

## Статус проекта

Начальная стадия проекта. Разработка только началась

## Принципы данного программного обеспечения

- Реализовывать взаймодейстие с программой только через API

## Цели

- Создание игрового движка для создание RPG.

## Технологии

- Язык программирования: Python
- Для работы с API используется: FastAPI

# Дорожная карта

### Q4 2023

- [ ] Начальная настройка проекта и структуры папок

# Установка

Начальная стадия проекта. Пока проект установить невозможно.

# Использование

Начальная стадия проекта. Пока проект использовать невозможно.

# Примеры

Приведем несколько примеров использования API:

### Создание персонажа

```HTTP
POST /api/v1/characters
Content-Type: application/json
Body:
{
    "name": "Hero",
    "class": "Warrior",
    "level": 1
}
```

### Получение информации о персонаже

```HTTP
GET /api/v1/characters/{id}
Content-Type: application/json
Response:
{
    "name": "Hero",
    "class": "Warrior",
    "level": 1,
    "Stats": {
      "Health": {
         "Current": 100,
         "Max": 100,
         "Regeneration": 3
      }
    }
}
```

# Вклад

Если вы хотите внести свой вклад в проект, пожалуйста, следуйте этим шагам:

1. Сделайте форк репозитория.
2. Создайте свою ветку: `git checkout -b feature/ИмяВашейФичи`
3. Внесите изменения и сделайте коммит: `git commit -m 'Добавил новую фичу'`
4. Сделайте пуш в вашу ветку: `git push origin feature/ИмяВашейФичи`
5. Создайте pull request.

# Авторы

Пока что пусто :з

# Лицензия

Этот проект лицензирован под [MIT](LICENSE).
