---
## Front matter
title: "Безопасность в сети"
subtitle: "Основы информационной безопасности"
author: "Перегудов Александр Вадимович"

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

# Задание

# Теоретическое введение

# Выполнение

![](image/1.png){width=70%}

![](image/2.png){width=70%}

![](image/3.png){width=70%}

![](image/4.png){width=70%}

![](image/5.png){width=70%}

![](image/6.png){width=70%}

![](image/7.png){width=70%}

![](image/8.png){width=70%}

![](image/9.png){width=70%}

![](image/10.png){width=70%}

![](image/11.png){width=70%}

![](image/12.png){width=70%}

![](image/13.png){width=70%}

![](image/14.png){width=70%}

![](image/15.png){width=70%}

![](image/16.png){width=70%}

![](image/17.png){width=70%}

![](image/18.png){width=70%}

![](image/19.png){width=70%}

![](image/20.png){width=70%}


# Список литературы{.unnumbered}

::: {#refs}
:::
