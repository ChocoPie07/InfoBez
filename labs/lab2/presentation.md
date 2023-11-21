---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Основные атрибуты
author:|
         Эттеев Сулейманр\inst{1}

institute: |
         \inst{1}Российский Университет Дружбы Народов

date: 20 ноября, 2023, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

# Цели и задачи работы

## Цель лабораторной работы

Получить практические навыки работы в консоли с атрибутами файлов, закрепить теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

# Процесс выполнения лабораторной работы

## Определяем UID и группу

![Информация о пользователе guest](images/1.png){ #fig:001 width=70% height=70% }

## Файл с данными о пользователях

![Сожержимое файла /etc/passwd](images/2.png){ #fig:002 width=70% height=70% }

## Доступ к домашним директориям

![Расширенные атрибуты](images/3.png){ #fig:003 width=70% height=70% }

## Атрибуты директории

![Снятие атрибутов с директории](images/4.png){ #fig:004 width=70% height=70% }

# Выводы по проделанной работе

## Вывод

В ходе выполнения лабораторной работы были получены навыки работы с атрибутами файлов и сведения о разграничении доступа.
