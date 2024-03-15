---
## Front matter
title: "Отчёт по лабораторной работе №6"
author: "Гиршфельд Александр"

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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Выполнение лабораторной работы

Определил с помощью команды pwd путь до домашнего каталога.(рис. @fig:001).

![pwd](image/1.png){#fig:001 width=70%}

Перешел в католог tmp с помощью команды cd и вывел его содержиое с помощью ls.(рис. @fig:002).

![tmp](image/2.png){#fig:002 width=70%}

Посмотрел на содержимое tmp с помощью ls с другим флагом -а(рис. @fig:003).

![ls -a](image/3.png){#fig:003 width=70%}

Узнал есть ли папка(рис. @fig:004).

![ /cron](image/4.png){#fig:004 width=70%}

Вывел содержимое домашнего каталога (рис. @fig:005).

![ls -alF](image/5.png){#fig:005 width=70%}

Создал в домашнем катологе новую папку, внутри нее еще одну, проверил, что внутренняя создалась.(рис. @fig:006).

![mkdir](image/6.png){#fig:006 width=70%}

Создал несколько папок( одной командойрис. @fig:007).

![несколько папок](image/7.png){#fig:007 width=70%}

Удалил их одной командой(рис. @fig:008).

![rm -r](image/8.png){#fig:008 width=70%}

Попробовал удалить папку комнадой rm без использования флагов.(рис. @fig:009)

![rm для каталогов не работает](image/9.png){#fig:009 width=70%}

Удалил каталог вместе с его подкатлогом(рис. @fig:010).

![удаление католога](image/10.png){#fig:010 width=70%}

С помощью команды man рассмотрел флаги команды ls.
Например, для рекурсивного вывода подкаталогов можно использовать флаг 
-R(рис. @fig:011)

![описание флага -R](image/11.png){#fig:011 width=70%}

Чтобы вывести файлы в порядке их создания, можно использовать флаг -t(рис. @fig:012)

![описание флага -t](image/12.png){#fig:012 width=70%}

Флаг -Z выводит более подробную информацию об файлах(рис. @fig:013)

![описание флага -Z](image/13.png){#fig:013 width=70%}


man pwd (рис. @fig:014)

![флаги для pwd](image/14.png){#fig:014 width=70%}

man mkdir флаги(рис. @fig:015)

![флаги для mkdir](image/15.png){#fig:015 width=70%}

man rm (рис. @fig:016)

![флаги для rm](image/16.png){#fig:016 width=70%}

Ввел history(рис. @fig:017)

![history](image/17.png){#fig:017 width=70%}

# Выводы

Приобрел практические навыки взаимодействия пользователя с системой по-
средством командной строки.


