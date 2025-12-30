---
## Front matter
lang: ru-RU
title: Лабораторная работа № 11
subtitle: Основы администрирования операционных систем
author:
  - Иванов Сергей Владимирович, НПИбд-01-23
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 15 ноября 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'

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

Получить навыки работы с загрузчиком системы GRUB2.

## Задание

1. Продемонстрировать навыки по изменению параметров GRUB и записи изменений
в файл конфигурации 
2. Продемонстрировать навыки устранения неполадок при работе с GRUB 
3. Продемонстрировать навыки работы с GRUB без использования root 

# Выполнение работы

## Получение прав администратора, установка параметра

![Получение прав администратора, установка параметра отображения меню загрузки](image/1.png){#fig:001 width=70%}

## Запись изменений в GRUB2

![Запись изменений в GRUB2](image/2.png){#fig:002 width=70%}

## Перезагрузка и просмотр загрузочных сообщений

![Перезагрузка и просмотр загрузочных сообщений](image/3.png){#fig:003 width=70%}

## Редактирование в меню GRUB

![Редактирование параметров загрузки в меню GRUB](image/4.png){#fig:004 width=70%}

## Просмотр списка всех файлов модулей

![Просмотр списка всех файлов модулей, которые загружены в настоящее время](image/5.png){#fig:005 width=70%}

## Задействованные переменные среды оболочки

![Просмотр задействованных переменные среды оболочки](image/6.png){#fig:006 width=70%}

## Редактирование в меню GRUB

![Редактирование параметров загрузки в меню GRUB](image/7.png){#fig:007 width=70%}

## Просмотр списка всех загруженных файлов модулей 

![Просмотр списка всех загруженных файлов модулей](image/8.png){#fig:008 width=70%}

## Редактирование в меню GRUB

![Редактирование параметров загрузки в меню GRUB](image/9.png){#fig:009 width=70%}

## Получение доступа к системному образу

![Получение доступа к системному образу и новый корневой каталог](image/10.png){#fig:010 width=70%}

## Установка нового пароля

![Установка нового пароля](image/11.png){#fig:011 width=70%}

## Загрузка политики SELinux

![Загрузка политики SELinux](image/12.png){#fig:012 width=70%}

## Установка типа контекста и перезагрузка

![Установка типа контекста и перезагрузка](image/13.png){#fig:013 width=70%}

# Вывод

## Вывод 

В ходе выполнения лабораторной работы были получены навыки работы с загрузчиком системы GRUB2.

## Список литературы

:::{#refs}

https://esystem.rudn.ru/mod/page/view.php?id=1098933

:::









