# auto-shop-bot ✨ 
_Бот автопродаж в телеграме + админ панель + REST API_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

![python3](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![python3](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![python3](https://img.shields.io/badge/Python-14354C?style=flat&logo=python&logoColor=white)
![python3](https://img.shields.io/badge/Python-14354C?style=plastic-square&logo=python&logoColor=white)

![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![nuxtjs](https://img.shields.io/badge/nuxt.js-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white)


## Техническое задание
> 
> Необходимо разработать телеграм бота автоматических продаж и API - далее "Система".

**Система должна состоять из следующих компонентов:**

#### ![python3](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) Python Aiogram приложение для функций бота
- ![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)MongoDB хранилище коллекций и документов (БД)
- ![nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)REST API для доступа к БД, авторизации и использования в админке
- ![nuxtjs](https://img.shields.io/badge/nuxt.js-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white) NustJS CRUD панель с авторизацей через API и возможностью
  добавлять/менять/удалять коллекциии и документы

---
## 1. Python бот

### 1.1 Функционал 
При нажатии команды "/start":

- Бот присылает стикер/изображение логотип магазина.
  Настраиваться админом. (1)

- Бот отправляет приветственное сообщение, текст которого можно
менять, либо отключать вовсе (2)
- Вторым сообщением приходит статистика пользователя(Баланс, количество покупок и т.д)(3)
- Появляется меню с инлайн кнопками:
  - Город
  - Кошелек
  - Настройки
  - Поддержка
При нажатии на любую из кнопок меню, сообщение (3) меняется на сообщение соответсвующее разделу.
### 1.2 Разделы


































