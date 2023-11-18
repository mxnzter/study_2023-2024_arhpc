---
## Front matter
title: "Отчёт по лабораторной работе №6"
subtitle: "Арифметические операции в NASM"
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

Освоение арифметических инструкций языка ассемблера NASM.

# Выполнение лабораторной работы

1. Создайте каталог для программам лабораторной работы № 6, перейдите в него и
создайте файл lab6-1.asm
<p align="center">![Создание файла](image/1.png)

2. Рассмотрим примеры программ вывода символьных и численных значений. Программы будут выводить значения записанные в регистр eax
<p align="center">![Заполняем программу](image/2.png)

Создайте исполняемый файл и запустите его
<p align="center">![Запуск файла](image/3.png)

3. Далее изменим текст программы и вместо символов, запишем в регистры числа. Исправьте текст программы (Листинг 6.1) следующим образом: замените строки
<p align="center">![Изменение](image/4.png)

4. Создайте файл lab6-2.asm в каталоге ~/work/arch-pc/lab06 и введите в него текст программы из листинга 6.2
<p align="center">![Создание файла](image/5.png)

Создайте исполняемый файл и запустите его
<p align="center">![Запуск файла](image/6.png)

5. Аналогично предыдущему примеру изменим символы на числа. Замените строки
<p align="center">![Замена](image/7.png)

6. Создайте файл lab6-3.asm в каталоге ~/work/arch-pc/lab06
<p align="center">![Создание файла](image/8.png)

<p align="center">![Заполнение файла](image/9.png)

<p align="center">![Проверка](image/10.png)

<p align="center">![Изменение файла](image/11.png)

<p align="center">![Проверка](image/12.png)

7. Создайте файл variant.asm в каталоге ~/work/arch-pc/lab06
<p align="center">![Создание файла](image/13.png)

<p align="center">![Заполнение файла](image/14.png)

<p align="center">![Проверка](image/15.png)

# Задания для самостоятельной работы

1. Создание файла rabota.asm в каталоге ~/work/arch-pc/lab06
<p align="center">![Создание файла](image/16.png)

2. Заполнение файла с первым значением
<p align="center">![Заполнение файла](image/17.png)

3. Проверка результата с первым значением
<p align="center">![Проверка](image/18.png)

4. Заполнение файла со вторым значением
<p align="center">![Редактирование файла](image/19.png)

5. Проверка результата со вторым значением
<p align="center">![Проверка](image/20.png)

# Выводы

Я освоил арифметические инструкции языка ассемблера NASM.

