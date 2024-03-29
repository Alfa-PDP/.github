# __ALFA PDP__

Ваш помощник в создании и управлении индивидуальными планами развития сотрудников в Альфа-Банке*

<sup>_\* с отличным бэкендом по версии нашей команды, подтверждено [Яндексом и Альфа-Банком](https://github.com/Alfa-PDP#%D0%B4%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC%D1%8B)_</sup>

___

### MVP

[Главная страница](https://alfa-eight.vercel.app)

[Swagger документация](https://alfa-idp.ddns.net/openapi/)

___

### ВВЕДЕНИЕ

ALFA PDP - новый сервис по ведению индивидуальных планов развития, встраиваемый во внутреннюю платформу “Alfa People”.\
Сервис позволит наглядно планировать и контролировать выполнение мероприятий по развитию и профессиональному росту сотрудников компании.

___

### ЦЕЛЬ ПРОЕКТА

Создать простой сервис, который позволит унифицировать процесс ведения индивидуальных\
планов развития как со стороны руководителя, так и со стороны сотрудника.

---

### ОПИСАНИЕ

| Задачи продукта                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <p align="center"> Систематизировать создание планов развития сотрудников в соответствии <br/> с потребностями компании или отдельных проектных команд </p> |
| <p align="center"> Упростить подбор сотрудников на проекты, благодаря аккумулированию <br/> информации о профессиональных навыках сотрудников </p>          |
| <p align="center"> Сделать прозрачным и понятным процесс оценки компетенций </p>                                                                            |
| <p align="center"> Сделать прозрачным и понятным процесс карьерного роста и профессионального <br/> развития в компании </p>                                     |

| Функционал для роли "Руководитель"                                                                                                     | Функционал для роли "Сотрудник"                                                                 |
|----------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Просматривает список сотрудников своей команды с информацией <br/> о задачах ИПР и прогрессе их выполнения                             | Декларирует (определяет) для себя: Цели развития / Сильные стороны / Зоны роста                 |
| Открывает карточку сотрудника                                                                                                          | Просматривает список задач                                                                      |
| Просматривает информацию о сотруднике, диаграмму прогресса <br/> выполнения ИПР, Цели развития, Сильные стороны, Зоны роста сотрудника | Выбирает задачу, открывает (разворачивает) задачу                                               |
| Создает задачу для сотрудника в формате индивидуального плана развития                                                                 | Берет в работу (нажатием соответствующе кнопки) после чего задача приобретает статус “В работе” |
| Определяет название задачи                                                                                                             | Может написать комментарий, который увидит Руководитель                                         |
| Описывает задачу так, чтобы сотруднику было понятно, <br/> что необходимо выполнить                                                    |                                                                                                 |
| Устанавливает сроки: дату начала выполнения и дедлайн                                                                                  |                                                                                                 |
| Выбирает тип задачи: Hard skills / Soft skills / Обучение                                                                              |                                                                                                 |                                                                                                   | "Работа взята на проверку ревьюером."          || Открывает карточку сотрудника                                                                                                    | "Работа взята на проверку ревьюером."          || Открывает карточку сотрудника                                                                                                    | "Работа взята на проверку ревьюером."          |
| Определяет значимость задачи: Высокая /Средняя / Низкая                                                                                |                                                                                                 |
| Может оставить комментарий, который увидит Сотрудник                                                                                   |                                                                                                 |
| Может поменять данные о задаче (название, описание, срок, тип, значимость, статус)                                                     |                                                                                                 |
| Может отредактировать или удалить задачу                                                                                               |                                                                                                 |

#### Развитие продукта в будущем:

Представленная концепция содержит минимальный функционал продукта, который позволит пользователям получить практическое представление о продукте,
подтвердить или опровергнуть гипотезы, понять целесообразность внедрения в масштабах компании. В процессе создания настоящего продукта и изучения доступных решений открылись достаточно большие возможности для развития функционала, который может оказаться востребован и решить некоторые другие
корпоративные задачи:

⇒ Возможность создания задач самими сотрудниками;

⇒ Механизм согласования задач между сотрудником и руководителем, для обеспечения двустороннего взаимодействия при формировании планов развития;

⇒ Добавление ролей ментора, HR, куратора и др;

⇒ Шаблоны для создания задач с редактором шаблонов для создания собственных типовых перечней задач;

⇒ Системы логирования изменений;

⇒ Автосохранение версий ИПР, с возможностью бэкапа по состоянию на заданную дату;

⇒ Система уведомлений об изменениях, с возможностью подсветить измененный раздел или поле;

⇒ Встраивание механизма уведомлений в Alfa People;

⇒ Рейтинг руководителей по прогрессу сотрудников в команде руководителя с учетом количества сотрудников в команде и количества задач;

⇒ Интеграция с корпоративными сервисами такими как Альфа Академия и образовательными сервисами партнеров;

⇒ Возможность прикреплять файлы (картинки, PDF, word, excel) к задачам для подтверждения выполнения.

___

### ТЕХНОЛОГИИ

Alfa PDP разработан с использованием следующих технологий:

- [Python] (v.3.11) - целевой язык программирования backend;
- [FastAPI] (v.0.100.1) - фреймворк для создания лаконичных и быстрых HTTP API-серверов со встроенными валидацией, сериализацией и асинхронностью из коробки;
- [SQLAlchemy] (v.2.0.25) - библиотека для работы с РСУБД с применением ORM;
- [PostgreSQL] (v.13.10) - объектно-реляционная база данных;
- [Pydantic] (v.2.5.3) - Python-библиотека для выполнения валидации данных;
- [Redis] (v.4.6.0) - резидентная система управления NoSQL базами данных;
- [Alembic] (v.2.5.3) - инструмент работы с миграциями для SQLAlchemy;
- [Uvicorn] (v.0.23.1) - Python ASGI HTTP-сервер;
- [Nginx] (1.22.1) - HTTP-сервер и обратный прокси-сервер;
- [Docker] (v.24.0) - инструмент для автоматизации процессов разработки, доставки и запуска приложений в контейнерах.

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![FastAPI](https://img.shields.io/badge/fastapi-%23092E20.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-696969?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Pydantic](https://img.shields.io/badge/pydantic-FF1493?style=for-the-badge&logo=pydantic&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-778899?style=for-the-badge&logo=sqlalchemy)
![Uvicorn](https://img.shields.io/badge/uvicorn-1E90FF?style=for-the-badge&logo=gunicorn&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

- [TypeScript] (v.5.2.2) - целевой язык программирования frontend;
- [React] (v.18.2) - JavaScript-библиотека для создания пользовательских интерфейсов;
- [React Redux] (v.9.1.0) - библиотека для React, связывающая UI и Redux;
- [SCSS] (v.1.70.0) - язык предназначенный для упрощения создания CSS-кода;
- [RTK-query] (v.2.0.1) - инструмент для создания сервисов для запросов на сервер;
- [Vite] (v.5.0.8) - инструмент для быстрого старта проекта из основного шаблона для популярных фреймворков.
- [alfalab/core-components] (v.44.5.1) - библиотека React компонентов для создания веб-интерфейсов.


![TypeScript](https://img.shields.io/badge/typescript-%23323330.svg?style=for-the-badge&logo=typescript&logoColor=%23F7DF1E) 
![React](https://img.shields.io/badge/react-%23323330.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Redux](https://img.shields.io/badge/redux-%23323330.svg?style=for-the-badge&logo=redux&logoColor=white)
![SCSS](https://img.shields.io/badge/scss-%23323330.svg?style=for-the-badge&logo=sass&logoColor=white)
![RTK-query](https://img.shields.io/badge/RTK_query-%23323330.svg?style=for-the-badge&logo=react-query&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23323330.svg?style=for-the-badge&logo=vite)
![alfalab/core-components](https://img.shields.io/badge/alfalab-core_components-%23323330.svg?style=for-the-badge&logo=jetpack-compose&logoColor=white)

___

### ЛИЦЕНЗИЯ

MIT

___

### PROJECT MANAGER

🙋‍♀️ [Юлия Никифорова]

### PRODUCT MANAGER

🙋‍♂️ [Алексей Смирнов]

### BUSINESS ANALYTICS

🙆‍♀️️ [Катя Хейчеева]

💁‍♀️ [Илона Кончугова]

### SYSTEMS ANALYTICS

🙆 [Мария Дергунова]

🙋‍♀️ [Ольга Дмитриева]

### DESIGNERS

🙋‍♂️ [Алексей Селезнев]

🙋‍♀️ [Асия Ахмерова]

💁 [Маргарита Церт]

### FRONTEND

🧙🏻‍♂️ [Константин Епифанов]

🙋‍♂️️ [Андрей Родителев]

🧑 [Максим Смелый]

### BACKEND

😎 [Михаил Спиридонов]

🦸🏻‍♂️ [Максим Головин]

🙋‍♂️ [Павел Ермеев]

🤵 [Кирилл Широков]

___

### ДИПЛОМЫ

|                                                                                                                         RU                                                                                                                         |                                                                                 EN                                                                                  |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ![Михаил Спиридонов (RU)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20%D0%9C%D0%B8%D1%85%D0%B0%D0%B8%D0%BB%20%D0%A1%D0%BF%D0%B8%D1%80%D0%B8%D0%B4%D0%BE%D0%BD%D0%BE%D0%B2%20(RU).png) | ![Михаил Спиридонов (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20Mikhail%20Spiridonov%20(EN).png) |
|           ![Максим Головин (RU)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20%D0%9C%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%20%D0%93%D0%BE%D0%BB%D0%BE%D0%B2%D0%B8%D0%BD%20(RU).png)            |     ![Максим Головин (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20Maxim%20Golovin%20(EN).png)     |
|                  ![Павел Ермеев (RU)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20%D0%9F%D0%B0%D0%B2%D0%B5%D0%BB%20%D0%95%D1%80%D0%BC%D0%B5%D0%B5%D0%B2%20(RU).png)                   |      ![Павел Ермеев (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20Pavel%20Ermeev%20(EN).png)       |
|           ![Кирилл Широков (RU)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20%D0%9A%D0%B8%D1%80%D0%B8%D0%BB%D0%BB%20%D0%A8%D0%B8%D1%80%D0%BE%D0%BA%D0%BE%D0%B2%20(RU).png)            |    ![Кирилл Широков (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/1st%20Backend%20Kirill%20Shirokov%20(EN).png)    |
|                ![Юлия Никифорова (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%AE%D0%BB%D0%B8%D1%8F%20%D0%9D%D0%B8%D0%BA%D0%B8%D1%84%D0%BE%D1%80%D0%BE%D0%B2%D0%B0%20(RU).png)                |           ![Юлия Никифорова (EN)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/Yulia%20Nikiforova%20(EN).png)           |
|                ![Алексей Смирнов (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%90%D0%BB%D0%B5%D0%BA%D1%81%D0%B5%D0%B9%20%D0%A1%D0%BC%D0%B8%D1%80%D0%BD%D0%BE%D0%B2%20(RU).png)                |            ![Алексей Смирнов (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Alexey%20Smirnov%20(EN).png)            |
|                       ![Катя Хейчеева (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9A%D0%B0%D1%82%D1%8F%20%D0%A5%D0%B5%D0%B9%D1%87%D0%B5%D0%B5%D0%B2%D0%B0%20(RU).png)                       |            ![Катя Хейчеева (EN)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/Katya%20Keicheeva%20(EN).png)             |
|                ![Илона Кончугова (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%98%D0%BB%D0%BE%D0%BD%D0%B0%20%D0%9A%D0%BE%D0%BD%D1%87%D1%83%D0%B3%D0%BE%D0%B2%D0%B0%20(RU).png)                |           ![Илона Кончугова (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Ilona%20Konchugova%20(EN).png)           |
|                ![Мария Дергунова (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9C%D0%B0%D1%80%D0%B8%D1%8F%20%D0%94%D0%B5%D1%80%D0%B3%D1%83%D0%BD%D0%BE%D0%B2%D0%B0%20(RU).png)                |           ![Мария Дергунова (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Maria%20Dergunova%20(EN).png)            |
|                ![Ольга Дмитриева (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9E%D0%BB%D1%8C%D0%B3%D0%B0%20%D0%94%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B5%D0%B2%D0%B0%20(RU).png)                |            ![Ольга Дмитриева (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Olga%20Dmitrieva%20(EN).png)            |
|            ![Алексей Селезнев (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%90%D0%BB%D0%B5%D0%BA%D1%81%D0%B5%D0%B9%20%D0%A1%D0%B5%D0%BB%D0%B5%D0%B7%D0%BD%D0%B5%D0%B2%20(RU).png)             |           ![Алексей Селезнев (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Alexey%20Seleznev%20(EN).png)           |
|                       ![Асия Ахмерова (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%90%D1%81%D0%B8%D1%8F%20%D0%90%D1%85%D0%BC%D0%B5%D1%80%D0%BE%D0%B2%D0%B0%20(RU).png)                       |            ![Асия Ахмерова (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Asiia%20Akhmerova%20(EN).png)             |
|                   ![Маргарита Церт (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9C%D0%B0%D1%80%D0%B3%D0%B0%D1%80%D0%B8%D1%82%D0%B0%20%D0%A6%D0%B5%D1%80%D1%82%20(RU).png)                    |            ![Маргарита Церт (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Margarita%20Tsert%20(EN).png)            |
|  ![Константин Епифанов (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9A%D0%BE%D0%BD%D1%81%D1%82%D0%B0%D0%BD%D1%82%D0%B8%D0%BD%20%D0%95%D0%BF%D0%B8%D1%84%D0%B0%D0%BD%D0%BE%D0%B2%20(RU).png)  |       ![Константин Епифанов (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Konstantin%20Epifanov%20(EN).png)        |
|            ![Андрей Родителев (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%90%D0%BD%D0%B4%D1%80%D0%B5%D0%B9%20%D0%A0%D0%BE%D0%B4%D0%B8%D1%82%D0%B5%D0%BB%D0%B5%D0%B2%20(RU).png)             |          ![Андрей Родителев (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Andrei%20Roditelev%20(EN).png)           |
|                       ![Максим Смелый (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9C%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%20%D0%A1%D0%BC%D0%B5%D0%BB%D1%8B%D0%B9%20(RU).png)                       |              ![Максим Смелый (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Maxim%20Smely%20(EN).png)               |
|         ![Михаил Спиридонов (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9C%D0%B8%D1%85%D0%B0%D0%B8%D0%BB%20%D0%A1%D0%BF%D0%B8%D1%80%D0%B8%D0%B4%D0%BE%D0%BD%D0%BE%D0%B2%20(RU).png)         |         ![Михаил Спиридонов (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Mikhail%20Spiridonov%20(EN).png)         |
|                   ![Максим Головин (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9C%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%20%D0%93%D0%BE%D0%BB%D0%BE%D0%B2%D0%B8%D0%BD%20(RU).png)                    |             ![Максим Головин (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Maxim%20Golovin%20(EN).png)             |
|                          ![Павел Ермеев (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9F%D0%B0%D0%B2%D0%B5%D0%BB%20%D0%95%D1%80%D0%BC%D0%B5%D0%B5%D0%B2%20(RU).png)                           |              ![Павел Ермеев (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Pavel%20Ermeev%20(EN).png)               |
|                   ![Кирилл Широков (RU)](https://github.com/Alfa-PDP/.github/blob/a18dcacfeb3e2194f03a91ffb4b87d495b22ddc5/assets/%D0%9A%D0%B8%D1%80%D0%B8%D0%BB%D0%BB%20%D0%A8%D0%B8%D1%80%D0%BE%D0%BA%D0%BE%D0%B2%20(RU).png)                    |            ![Кирилл Широков (EN)](https://github.com/Alfa-PDP/.github/blob/c4f9c6837c0df874f2e3ee538ca0a0a80bb1554c/assets/Kirill%20Shirokov%20(EN).png)            |

___

[Юлия Никифорова]: <https://t.me/Niki_for_Ova/>
[Алексей Смирнов]: <https://t.me/lenreg/>
[Катя Хейчеева]: <https://t.me/kashkaldykova1/>
[Илона Кончугова]: <https://t.me/elmxln/>
[Мария Дергунова]: <https://t.me/Dergunovamv/>
[Ольга Дмитриева]: <https://t.me/olgadmitrievaSA/>
[Алексей Селезнев]: <https://t.me/xeyeyseleznev/>
[Асия Ахмерова]: <https://t.me/bibeloto/>
[Маргарита Церт]: <https://t.me/diavale/>
[Константин Епифанов]: <https://t.me/alter_const/>
[Андрей Родителев]: <https://t.me/roditelev/>
[Максим Смелый]: <https://t.me/SenpaiSun/>
[Михаил Спиридонов]: <https://t.me/MikhailSpiridonov/>
[Максим Головин]: <https://t.me/PrimeStr/>
[Павел Ермеев]: <https://t.me/byt_plokhim/>
[Кирилл Широков]: <https://t.me/Kirill_Sh_ow/>

[Python]: <https://www.python.org/>
[FastAPI]: <https://fastapi.tiangolo.com/>
[SQLAlchemy]: <https://www.sqlalchemy.org/>
[PostgreSQL]: <https://www.postgresql.org/>
[Pydantic]: <https://docs.pydantic.dev/latest/>
[Redis]: <https://redis.io/>
[Alembic]: <https://alembic.sqlalchemy.org/en/latest/>
[Uvicorn]: <https://www.uvicorn.org/>
[Nginx]: <https://nginx.org/en/>
[Docker]: <https://www.docker.com/>

[TypeScript]: <https://www.typescriptlang.org/>
[React]: <https://react.dev/>
[React Redux]: <https://react-redux.js.org/>
[SCSS]: <https://sass-scss.ru/>
[RTK-query]: <https://redux-toolkit.js.org/rtk-query/overview>
[Vite]: <https://vitejs.dev/>
[alfalab/core-components]: <https://github.com/alfa-laboratory/core-components>
