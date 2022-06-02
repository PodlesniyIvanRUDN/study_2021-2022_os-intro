---
## Front matter
title: "Отчёт по лабораторной работе №9"
subtitle: "НКНбд-01-21"
author: "Подлесный Иван Сергеевич"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
lofTitle: "Цель Работы"
lotTitle: "Ход Работы"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---



># ЦЕЛЬ РАБОТЫ

>**Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs**

# Ход работы

1. Открыть emacs.

![Шаг 1](1.jpg)

2. Создать файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f.

![Шаг 2](2.jpg)

3. Наберите заданный текст:

![Шаг 3-4](3-4.jpg)

4. Сохранить файл с помощью комбинации Ctrl-x Ctrl-s 
  
![Шаг 3-4](3-4.jpg)

5. Проделать с текстом стандартные процедуры редактирования, каждое действие должно осуществляться комбинацией клавиш

![Шаг 5](5.jpg)

6. Научитесь использовать команды по перемещению курсора.

![Шаг 6](6.jpg)

7. Изучите управление буферами

![Шаг 7](7.jpg)

8. Изучите управление окнами

![Шаг 8](8.jpg)

9. Изучите режим поиска

![Шаг 9](9.jpg)


# ВЫВОДЫ

>**Мы Познакомились с операционной системой Linux и Получили практические навыки работы с редактором Emacs**