---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
subtitle: Первоначальна настройка git
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

Изучить идеологию и применение средств контроля версий.Освоить умения по работе с git.


# Процесс выполнения лабораторной работы

## Базовая настройка git:

![Базовая настройка git](image/1.png){#fig:001 width=70%}


## Создаём ключ SSH и GPG.

![Создание ключа SSH](image/2.png){ #fig:002 width=70% }
![Создание ключа GPG](image/3.png){ #fig:003 width=70% }


## Ключ нужно добавить на github. Для этого переходим на сайте в раздел “Settings” и выбираем “SSH and GPG keys”.

![Ключ SSH создан](image/4.png){ #fig:004 width=70% }
![Ключ GPG создан](image/5.png){ #fig:005 width=70% }


## Выводим список ключей и копируем отпечаток приватного ключа

![Отпечаток приватного ключа](image/6.png){ #fig:006 width=70% }


## Настройка автоматических подписей коммитов git

![Настройка подписей](image/7.png){ #fig:007 width=70% }


## Возвращаемся в наш терминал и настраиваем gh.

![Настройка gh](image/8.png){ #fig:008 width=70% }


## Создаём репозиторий курса на основе шаблона.

![Создание репозитория](image/9.png){ #fig:009 width=70% }


## Настраиваем каталог курса.

![Настраиваем каталог курса](image/10.png){ #fig:010 width=70% }


## Создаём необходимые каталоги и отправляем наши файлы на сервер	

![Отправляем наши файлы на сервер](image/11.png){ #fig:011 width=70% }


## Вывод

В ходе выполнения лабораторной работы изучили идеологию и применение средств контроля версий, а также освоили умения по работе с git.
