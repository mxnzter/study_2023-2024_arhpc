---
## Front matter
title: "Отчёт по лабораторной работе №8"
subtitle: "Программирование цикла. Обработка аргументов командной строки.Файл"
author: "Исупов Олег Денисович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
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
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение навыков написания программ с использованием циклов и обработкой
аргументов командной строки.


# Выполнение лабораторной работы

1. Создайте каталог для программам лабораторной работы № 8, перейдите в него и создайте
файл lab8-1.asm
<p align="center">![Создание файла](image/1.png)

<p align="center">![Заполнение файла](image/2.png)

<p align="center">![Проверка](image/3.png)

<p align="center">![Изменение](image/4.png)

<p align="center">![Проверка](image/5.png)

<p align="center">![Изменение и проверка](image/6.png)

2. Создайте файл lab8-2.asm в каталоге ~/work/arch-pc/lab08 и введите в него текст программы из листинга 8.2
<p align="center">![Создание файла](image/7.png)

<p align="center">![Заполнение файла](image/8.png)

<p align="center">![Проверка](image/9.png)

3. Создайте файл lab8-3.asm в каталоге ~/work/archpc/lab08 и введите в него текст программы из листинга 8.3
<p align="center">![Создание и заполнение файла](image/10.png)

<p align="center">![Проверка](image/11.png)

<p align="center">![Проверка с другими значениями](image/12.png)

# Задания для самостоятельной работы

1. Создайте файл lab8-4.asm в каталоге ~/work/arch-pc/lab08
<p align="center">![Создание файла](image/13.png)

<p align="center">![Заполнение файла](image/14.png)

<p align="center">![Проверка](image/15.png)

<p align="center">![Проверка с другими значениями](image/16.png)

# Выводы

Я приобрёл навыки написания программ с использованием циклов и обработкой аргументов командной строки.

