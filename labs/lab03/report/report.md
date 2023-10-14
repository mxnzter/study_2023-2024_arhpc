---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Язык разметки"
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.


# Выполнение лабораторной работы

1. Откройте терминал

2. Перейдите в каталог курса сформированный при выполнении лабораторной работы
№2:
<p align="center">![Каталог курса](image/1.png)

Обновите локальный репозиторий, скачав изменения из удаленного репозитория с помо-
щью команды
<p align="center">![Обновление локального репозитория](image/2.png)

3. Перейдите в каталог с шаблоном отчета по лабораторной работе № 3
<p align="center">![Переход в каталог с шаблоном отчёта lab3](image/3.png)

4. Проведите компиляцию шаблона с использованием Makefile. Для этого введите ко-
манду
<p align="center">![Проведение компиляции шаблона](image/4.png)

5. Удалите полученный файлы с использованием Makefile. Для этого введите команду
<p align="center">![Удаление полученных файлов](image/5.png)

6. Откройте файл report.md c помощью любого текстового редактора, например gedit
<p align="center">![Открытие файла](image/6.png)

7. Заполните отчет и скомпилируйте отчет с использованием Makefile. Проверьте кор-
ректность полученных файлов. 
<p align="center">![Открытие файла](image/7.png)

8. Загрузите файлы на Github.
<p align="center">![Загрузка файлов](image/8.png)
# Выводы

Таким образом мы освоили процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Список литературы{.unnumbered}

