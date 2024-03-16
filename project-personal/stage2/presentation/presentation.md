---
## Front matter
lang: ru-RU
title: 
subtitle: Отчет о выполнении индивидуального проекта.Этап 2.
author: 
  - Дзаки Рафли Зайдан
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 2.03.2024

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
        - spelling=modern
        - babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Дзаки Рафли Зайдан
  * студент группы  НБИбд-01-23
  * Российский университет дружбы народов

:::
::: {.column width="30%"}


:::
::::::::::::::

# Цели и задачи работы

## Цели и задачи

Разместить фотографию владельца сайта.
Разместить краткое описание владельца сайта.
Добавить информацию об интересах.
Добавить информацию об образовании.
Сделать пост по прошедшей неделе.
Добавить пост на тему: "Управление версиями.Git."

# Процесс выполнения индивидуального проекта

## Добавление фотографии на сайт

Путь к фотографии: "work", "blog", "content", "authors", "admin".

![Добавление фотографии](image/1.png){ #fig:001 width=100% }

## Добавление информации о себе

![Добавление информации о себе](image/2.png){ #fig:002 width=100% }

## Создание постов

Каталог "blog". Команда: hugo new --kind post post/(название поста).

![Создание двух постов](image/3.png){ #fig:003 width=100% }

## Проверка создания постов

![Новые подкаталоги для постов](image/4.png){ #fig:004 width=100% }

## Внесение информации для поста

![Информация для поста](image/5.png){ #fig:005 width=100% }

## Внесение информации для поста

![Информация для поста](image/6.png){ #fig:006 width=100% }

## Запуск команды hugo

![Запуск команды hugo](image/7.png){ #fig:007 width=100% }

## Выгрузка на github

![Выгрузка из подкаталога "public"](image/8.png){ #fig:008 width=100% }

## Выгрузка на github
	
![Выгрузка из каталога "blog"](image/9.png){ #fig:009 width=70% }

## Просмотр изменений на сайте

![Информация о себе на сайте](image/10.png){ #fig:010 width=100% }

## Просмотр изменений на сайте

![Новые посты на сайте](image/11.png){ #fig:011 width=100% }

# Выводы

В ходе выполнения второго этапа индивидуального проекта мы научились добавлять к сайту информацию о себе, а также создавать новые посты.
