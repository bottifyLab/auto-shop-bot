# auto-shop-bot ✨ 
_Бот автопродаж в телеграме + админ панель + REST API_

![python3](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![nuxtjs](https://img.shields.io/badge/nuxt.js-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white)


## Техническое задание
> 
> Необходимо разработать телеграм бота автоматических продаж и API - далее "Система".

Система должна состоять из следующих компонентов:

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="15" height="15"/> **Aiogram** приложение для функций бота

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="15" height="15"/></a> **MongoDB** хранилище коллекций и документов (БД) 

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-plain.svg" alt="nestjs" width="15" height="15"/></a> **REST API** для доступа к БД, авторизации и использования в админке 

<img src="https://www.vectorlogo.zone/logos/nuxtjs/nuxtjs-icon.svg" alt="nuxtjs" width="15" height="15"/></a> **NuxtJS** панель с авторизацей через API и возможностью добавлять/менять/удалять коллекциии и документы 


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



