---
## Front matter
title: "Отчёт по лабораторной работе №9"
subtitle: "Понятие подпрограммы. Отладчик."
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

Приобретение навыков написания программ с использованием подпрограмм. Знакомство
с методами отладки при помощи GDB и его основными возможностями.

# Выполнение лабораторной работы

1. Создайте каталог для выполнения лабораторной работы № 9, перейдите в него и создайте файл lab09-1.asm

<p align="center">![Создание файла](image/1.png)

2. В качестве примера рассмотрим программу вычисления арифметического выражения
𝑓(𝑥) = 2𝑥 + 7 с помощью подпрограммы _calcul. В данном примере 𝑥 вводится с
клавиатуры, а само выражение вычисляется в подпрограмме.

<p align="center">![Заполнение файла](image/2.png)

<p align="center">![Проверка](image/3.png)

<p align="center">![Редактирование файла](image/4.png)

<p align="center">![Проверка](image/5.png)

3. Создайте файл lab09-2.asm с текстом программы из Листинга 9.2

<p align="center">![Создание файла](image/6.png)

<p align="center">![Заполнение файла](image/7.png)

<p align="center">![Загрузка исходного файла в отладчик](image/8.png)

<p align="center">![Запуск команды](image/9.png)

<p align="center">![Запуск программы с брейкпоинтом](image/10.png)

<p align="center">![Просмотр дисассимилированного кода программы](image/11.png)

<p align="center">![Переключение на синтаксис Intel](image/12.png)

<p align="center">![Включение отображения регистров, их значений и результата программы](image/13.png)

<p align="center">![Использование команды info breakpoints](image/14.png)

<p align="center">![Создание новой точки](image/15.png)

<p align="center">![Просмотр информации](image/16.png)

<p align="center">![Отслеживание регистров](image/17.png)

<p align="center">![Просмотр значения переменной](image/18.png)

<p align="center">![Просмотр значения переменной](image/19.png)

<p align="center">![Изменение символа](image/20.png)

<p align="center">![Просмотр значения переменной](image/21.png)

<p align="center">![Просмотр значения регистра](image/22.png)

<p align="center">![Изменение регистра командой set](image/23.png)

<p align="center">![Прописывание команд c и quit](image/24.png)

<p align="center">![Копирование файла](image/25.png)

<p align="center">![Создание и запуск файл в отладчике](image/26.png)

<p align="center">![Устанавливаем точку](image/27.png)

<p align="center">![Изучение полученных данных](image/28.png)

# Задания для самостоятельной работы

1. Преобразуйте программу из лабораторной работы №8, реализовав вычисление значения функции 𝑓(𝑥) как подпрограмму
<p align="center">![Копирование и изменение файла](image/29.png)

<p align="center">![Проверка](image/30.png)

2. В листинге 9.3 приведена программа вычисления выражения (3 + 2) ∗ 4 + 5. При запуске
данная программа дает неверный результат. Проверьте это. С помощью отладчика GDB,
анализируя изменения значений регистров, определите ошибку и исправьте ее

<p align="center">![Создание файла](image/31.png)

<p align="center">![Изменение файла](image/32.png)

<p align="center">![Проверка](image/33.png)

<p align="center">![Поиск ошибки регистров в отладчике](image/34.png)

<p align="center">![Изменение файла](image/35.png)

<p align="center">![Проверка](image/36.png)

# Выводы

Я приобрёл навыки написания программ с использованием подпрограмм. Познакомился
с методами отладки при помощи GDB и его основными возможностями.

