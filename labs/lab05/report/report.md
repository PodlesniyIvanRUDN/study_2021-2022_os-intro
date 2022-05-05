---
## Front matter
title: "Отчёт по лабораторной работе №5"
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

>** Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.**

# Ход работы

 1. Выполните все примеры, приведённые в первой части описания лабораторной работы

 ![Шаг 1](ex1.jpg)

 ![Шаг 2](ex2.jpg)

 ![Шаг 3](ex3.jpg)

 ![Шаг 4](ex4.jpg)

2. Выполните следующие действия

 2.1 . Скопируйте файл /usr/include/sys/io.h в домашний каталог и назовите его
equipment. Если файла io.h нет, то используйте любой другой файл в каталоге
/usr/include/sys/ вместо него.
   
![Шаг 2.1](2.1.jpg)

 2.2-2.3.В домашнем каталоге создайте директорию -/ski.plases и переместите equipment в -/ski.plases

![Шаг 2.2-2.3](2.2-2.3.jpg)


 2.4. 4. Переименуйте файл -/ski.plases/equipment в -/ski.plases/equiplist.
  
![Шаг 2.4](2.4.jpg)


 2.5  Создайте в домашнем каталоге файл abc1 и скопируйте его в каталог
~/ski.plases, назовите его equiplist2.
  
![Шаг 2.5](2.5.jpg)


 2.6 - 2.7. Создайте каталог equipment в каталоге -/ski.plases и Переместите файлы ~/ski.plases/equiplist и equiplist2 в 

~/ski.plases/equipmen
  
![Шаг 2.6-2.7](2.6-2.7.jpg)


 2.8 . Создайте и переместите каталог -/newdir в каталог ~/ski.plases и назовите
его plans
  
![Шаг 2.8](2.8.jpg)

3. Определите опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет:
   
 3.1
   
![Шаг 3.1](3.1.jpg)

 3.2
  
![Шаг 3.2](3.2.jpg)

 3.3 

![Шаг 3.3](3.3.jpg)

 3.4
      
![Шаг 3.4](3.4.jpg)



4. Проделайте приведённые ниже упражнения, записывая в отчёт по лабораторной
работе используемые при этом команды:

 4.1 . Просмотрите содержимое файла /etc/password.

 ![Шаг 4](4.1.jpg)

 4.2-4.3 Скопируйте файл -/feathers в файл ~/file.old и Переместите файл -/file.old в каталог -/play.

 ![Шаг 4](4.2-4.3.jpg)

 4.4 Скопируйте каталог -/play в каталог ~/fun.

 ![Шаг 4](4.4.jpg)

4.5 Переместите каталог -/fun в каталог ~/play и назовите его games.

 ![Шаг 4](4.5.jpg)

 4.6-4.7 Лишите владельца файла ~/feathers права на чтение и проверьте, что произойдеет при попытке прочтения файла командой cat

 ![Шаг 4](4.6-4.7.jpg)

4.8  Что произойдёт, если вы попытаетесь скопировать файл ~/feathers

 ![Шаг 4](4.8.jpg)

 4.9 Дайте владельцу файла ~/feathers право на чтение

 ![Шаг 4](4.9.jpg)

4.10-4.12 Лишите владельца каталога ~/play права на выполнение

Перейдите в каталог -/play. Что произошло? 

Дайте владельцу каталога ~/play право на выполнение

 ![Шаг 4](4.10-4.12.jpg)

 5. Прочитайте man по командам mount, fsck, mkfs, kill и кратко их охарактеризуйте,
приведя примеры

![Шаг 5](5.1.jpg)

![Шаг 5](5.2.jpg)

![Шаг 5](5.3.jpg)

![Шаг 5](5.4.jpg)

# ВЫВОДЫ

>**Мы ознакомились с файловой системой Linux, её структурой, именами и содержанием
каталогов и приобрели практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.**
