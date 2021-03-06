---
layout: post
title: "Installation on Windows"
date: 2017-10-13 23:29:00 +0900
tags: blog
comments: false
lang: ru
---
# Инструкция по установке на Windows

**Важно! Прочитайте инструкцию от начала до конца, а затем действуйте! Удачи!**

## Установка Python 3

1. Перейдите на сайт [Python](https://www.python.org/downloads/).
2. Выберите подходящую вам версию (зависит от операционной системы).
3. Скачайте.
4. Запустите установщик.
5. Следуйте инструкции, которую предлагает вам установщик. Поставьте галочку на “Add Python 3.x to Path” и нажмите на Install Now (смотрите рисунок ниже). Если вы опытный пользователей, выберите Customize installation.
![Install Python 3 and add to PATH](https://github.com/damirqa/instabot/blob/master/docs/img/install_python_on_Windows.PNG "Install Python 3 and add to PATH")

## Скачивание проекта с GitHub

Есть два варианта скачивания проекта:

a) Перейдите по ссылке https://github.com/instagrambot/instabot. Нажмите на “Clone or download”, а затем на “Download ZIP”. Распакуйте.

b) Установка клиента Git:
1. Перейдите на сайт [Git](https://git-scm.com/downloads).
2. Выберите подходящую вам версию (зависит от операционной системы).
3. Скачайте.
4. Запустите установщик.
5. Следуйте инструкции, которую предлагает вам установщик (нажимайте на Next). Можете настроить клиент самостоятельно, если вы – опытный пользователь.
6. После установки запустите командную строку.
7. В командной строке наберите .
``` python
git clone https://github.com/instagrambot/instabot
```
и нажмите на Enter.

***Поздравляю! Вы скачали проект!***

## Установка instabot в виртуальное окружение Python

В командной строке наберите.
``` python
pip install -U instabot
```
и нажмите Enter.