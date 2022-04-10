# auto-shop-bot ✨ 
_Бот автопродаж в телеграме + админ панель + REST API_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


![python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![python2](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![python3](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)

![flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![nuxtjs](https://img.shields.io/badge/nuxt.js-00C58E?style=for-the-badge&logo=nuxtdotjs&logoColor=white)
![telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![vuejs](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)


## Техническое задание
> 
> Необходимо разработать телеграм бота автоматических продаж и API - далее "Система".

**Система должна состоять из следующих компонентов:**

- Python Aiogram приложение для функций бота
- MongoDB хранилище коллекций и документов (БД)
- REST API для доступа к БД, авторизации и использования в админке
- NustJS CRUD панель с авторизацей через API и возможностью
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


































