---
## Front matter
lang: ru-RU
title: Лабораторная работа № 16
subtitle: Основы администрирования операционных систем
author:
  - Иванов Сергей Владимирович, НПИбд-01-23
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 20 декабря 2024

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

Цель данной работы заключается в освоении работы с RAID-массивами при помощи утилиты mdadm.

# Выполнение работы

## Добавление дисков

![Добавление к виртуальной машине к контроллеру SATA три диска размером 512MiB](image/1.png){#fig:001 width=70%}

## Проверка создания дисков

![Получение полномочий администратора, проверка наличия созданных дисков](image/2.png){#fig:002 width=70%}

## Раздел на sde

![Создание раздела на диске sde](image/3.png){#fig:003 width=70%}

## Раздел на sdf

![Создание раздела на диске sdf](image/4.png){#fig:004 width=70%}

## Раздел на sdg

![Создание раздела на диске sdg](image/5.png){#fig:005 width=70%}

## Проверка типа

![Проверка текущего типа созданных разделов](image/6.png){#fig:006 width=70%}

## Партиции

![Просмотр типов партиций, относящиеся к RAID, которые можно задать. Установка типа разделов в Linux raid autodetect](image/7.png){#fig:007 width=70%}

## Состояние дисков 

![Просмотр состояния дисков](image/8.png){#fig:008 width=70%}

## Массив RAID 1

![Создание массива RAID 1 из двух дисков](image/9.png){#fig:009 width=70%}

## Проверка состояния массива

![Проверка состояния массива](image/10.png){#fig:010 width=70%}

## Файловая система на RAID

![Создание файловой системы на RAID](image/11.png){#fig:011 width=70%}

## Работа с RAID

![Подмонтирование RAID, открытие файла /etc/fstab в текстовом редакторе mcedit](image/12.png){#fig:012 width=70%}

## Автомонтирование

![Добавление записи для автомонтирования в файл](image/13.png){#fig:013 width=70%}

## Имитация, удаление, замена

![Имитация сбоя одного из дисков, удаление сбойного диска, замена диска в массиве](image/14.png){#fig:014 width=70%}

## Просмотр состояния массива

![Просмотр состояния массива](image/15.png){#fig:015 width=70%}

## Массив и метаданные

![Удаление массива и очистка метаданных](image/16.png){#fig:016 width=70%}

## Создание, добавление, подмонтирование

![Создание массива RAID 1 из двух дисков, добавление третьего диска, подмонтирование /dev/md0](image/17.png){#fig:017 width=70%}

## Проверка состояния массива

![Проверка состояния массива](image/18.png){#fig:018 width=70%}

## Имитация

![Имитация сбоя одного из дисков](image/19.png){#fig:019 width=70%}

## Проверка состояния массива

![Проверка состояния массива](image/20.png){#fig:020 width=70%}

## Удаление и очистка

![Удаление массива и очистка метаданных](image/21.png){#fig:021 width=70%}

## RAID 1

![Cоздание массива RAID 1 из двух дисков, добавление третьего диска, подмонтирование /dev/md0](image/22.png){#fig:022 width=70%}

## Проверка состояния массива

![Проверка состояния массива](image/23.png){#fig:023 width=70%}

## Изменение типа

![Изменение типа массива](image/24.png){#fig:024 width=70%}

## Проверка состояния массива

![Проверка состояния массива](image/25.png){#fig:025 width=70%}

## Изменение количества дисков

![Изменение количества дисков в массиве](image/26.png){#fig:026 width=70%}

## Проверка состояния массива

![Проверка состояния массива](image/27.png){#fig:027 width=70%}

## Удаление, очистка

![Удаление массива и очистка метаданных](image/28.png){#fig:028 width=70%}

## Коммент

![Коммент записи в /etc/fstab и выполнение сохранения](image/29.png){#fig:029 width=70%}

# Вывод

## Вывод 

В ходе выполнения лабораторной работы мы усвоили работу с RAID-массивами при помощи утилиты mdadm.

## Список литературы

:::{#refs}

https://esystem.rudn.ru/mod/page/view.php?id=1098933

:::









