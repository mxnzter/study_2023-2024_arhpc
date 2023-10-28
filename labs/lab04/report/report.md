---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "Создание и процесс обработки программ на языке ассемблера NASM"
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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.


# Выполнение лабораторной работы

1. Создайте каталог для работы с программами на языке ассемблера NASM:
<p align="center">![Создание каталога](image/1.png)

2. Перейдите в созданный каталог
<p align="center">![Переход в каталог](image/2.png)

3. Создайте текстовый файл с именем hello.asm
<p align="center">![Создание текстового файла](image/3.png)

4. Откройте этот файл с помощью любого текстового редактора, например, gedit
<p align="center">![Открытие файла](image/4.png)

5. И введите в него следующий текст:
<p align="center">![Ввод текста](image/4(2).png)

6. NASM превращает текст программы в объектный код. Например, для компиляции приведённого выше текста программы «Hello World» необходимо написать:
<p align="center">![Компиляция](image/5.png)

7. Выполните следующую команду:
<p align="center">![Выполнение команды](image/6.png)

8. Чтобы получить исполняемую программу, объектный файл
необходимо передать на обработку компоновщику:
<p align="center">![Передача на обработку](image/7.png)

9. С помощью команды ls проверьте, что исполняемый файл hello был создан
<p align="center">![Проверка](image/8.png)

10. Выполните следующую команду:
<p align="center">![Выполнение команды](image/9.png)

11. Запустить на выполнение созданный исполняемый файл, находящийся в текущем каталоге,
можно, набрав в командной строке:
<p align="center">![Запуск файла](image/10.png)

# Задания для самостоятельной работы

1. В каталоге ~/work/arch-pc/lab04 с помощью команды cp создайте копию файла
hello.asm с именем lab4.asm
<p align="center">![Создание копии](image/11.png)

2. С помощью любого текстового редактора внесите изменения в текст программы в
файле lab4.asm так, чтобы вместо Hello world! на экран выводилась строка с вашими
фамилией и именем.
<p align="center">![Открытие файла](image/12.png)

<p align="center">![Редактирование](image/13.png)

3. Оттранслируйте полученный текст программы lab4.asm в объектный файл. Выполните
компоновку объектного файла и запустите получившийся исполняемый файл.
<p align="center">![Компиляция](image/14.png)

<p align="center">![Выполнение команды](image/15.png)

<p align="center">![Передача на обработку](image/16.png)

<p align="center">![Запуск файла](image/17.png)

# Выводы

Таким образом мы освоили процедуры компиляции и сборки программ, написанных на ассемблере NASM.

