---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: 
author: 
  - Дзаки Рафли Зайдан
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 16.03.2024

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

## Цель работы

Целью данной лабораторной работы является ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы

## Задание

1. Выполнить все примеры из лабораторной работы
2. Выполнить команды по копированию, созданию и перемещению файлов и каталогов
3. Определить опции команды chmod
4. Изменить права доступа к файлам
5. Прочитать документацию о командах mount, fsck, mkfs, kill

# Выполнение лабораторной работы

## Выполнение примеров

Создаю файл, дважды копирую его с новыми имtнами и проверяю, что все команды были выполнены корректно.

![Создание файла](image/1.png){#fig:001 width=70%}


## Выполнение примеров

Создаю директорию, копирую в нее два файла, созданных на прошлом этапе, проверяю, что все скопировалось.

![Создание директории](image/2.png){#fig:002 width=70%}


## Выполнение примеров

Копирую файл, находящийся не в текущей диреткории в файл с новым именем тоже не  текущей директории.

![Копирование файла](image/3.png){#fig:003 width=70%}


## Выполнение примеров

Создаю новую директорию. Копирую предыдущую созданную директорию вместе со всем содержимым в каталог /tmp. Затем копирую предыдущую созданную директорию в новую созданную.

![Создание директории](image/4.png){#fig:004 width=70%}


## Выполнение примеров

Переименовываю файл, затем перемещаю его в каталог.

![Переименовывание файла](image/5.png){#fig:005 width=70%}

## Выполнение примеров

Создаю новую диреткорию, переименовываю monthly.00 в monthly.01, перемещаю директорию в директорию reports, переименовываю эту директорию, убираю из названия 01.

![Создание директории](image/6.png){#fig:006 width=70%}

## Выполнение примеров

Создаю пустой файл, проверяю права доступа у него, изменяю права доступа, добавляя пользователю (создателю) возможность выполнять файл .

![Работа с правами доступа](image/7.png){#fig:007 width=70%}

## Выполнение примеров

Меняю права доступа у директории: группы и остальные пользователи не смогут ее прочесть.

![Работа с правами доступа](image/8.png){#fig:008 width=70%}

## Выполнение примеров

Изменяю права доступа у директории, запрещаю группам и остальным пользователям читать. Создаю новый пустой файл, даю ему права доступа: группы могут в этом чато писатю  содержимое.

![Работа с правами доступа](image/9.png){#fig:009 width=70%}

## Выполнение примеров

Проверяю файловую систему.

![Проверка файловой системы](image/10.png){#fig:010 width=70%}

## Прочитать документацию о командах mount, fsck, mkfs, kill

- mount — утилита командной строки в UNIX-подобных операционных системах. Применяется для монтирования файловых систем.
- fsck (проверка файловой системы) - это утилита командной строки, которая позволяет выполнять проверки согласованности и интерактивное исправление в одной или нескольких файловых системах Linux. Он использует программы, специфичные для типа файловой системы, которую он проверяет.

## Прочитать документацию о командах mount, fsck, mkfs, kill

- mkfs используется для создания файловой системы Linux на некотором устройстве, обычно в разделе жёсткого диска. В качестве аргумента filesys для файловой системы может выступать или название устройства
- Команда Kill посылает указанный сигнал указанному процессу. Если не указано ни одного сигнала, посылается сигнал SIGTERM. Сигнал SIGTERM завершает лишь те процессы, которые не обрабатывают его приход. Для других процессов может быть необходимым послать сигнал SIGKILL, поскольку этот сигнал перехватить невозможно.

## Выводы

При выполнении данной лабораторной работы я ознакомилась с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрела практические навыки по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы


# Спасибо за внимание
