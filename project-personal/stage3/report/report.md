---
## Front matter
title: "Отчет индивидуальный проект"
subtitle: "этап 3"
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

Добавить сайту достижения



# Выполнение лабораторной работы

Добавил свои навыки (рис. [-@fig:001]).

![Добавление навыков](image/1.png){#fig:001 width=70%}

Добавил свой опыт (рис. [-@fig:002]).  

![Добавление опыта](image/2.png){#fig:002 width=70%}


Добавил достижения (рис. [-@fig:003]).

![Добавление достижений](image/3.png){#fig:003 width=70%}

Добавил пост про легковесные языки (рис. [-@fig:004]).

![пост](image/4.png){#fig:004 width=70%}

Добавил пост про прошедшую неделю (рис. [-@fig:005]).

![пост](image/5.png){#fig:005 width=70%}

Проверил результат (рис. [-@fig:006]).

![результат](image/6.png){#fig:006 width=70%}


# Выводы

Добавил достижения

