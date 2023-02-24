---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Операционные системы"
author: "Дмитрий Юрьевич Дымченко"

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
lot: true # List of tablesbre
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

Сделать отчёт по предыдущей лабораторной работе в формате Markdown.

# Выполнение лабораторной работы

Заголовки в Markdown вводятся символом "#" (рис. @fig:001).

![Оформление заголовка](image/1.png){#fig:001 width=70%}

Текст вводится под заголовком, ссылки на изображения добавляются с помощью команды, указанной на скриншоте  (рис. @fig:002).

![Текст и ссылка на изображение](image/2.png){#fig:002 width=70%}

Само изображение добавляется командой, указанной на рисунке номер 3 (рис. @fig:003).

![Добавление изображения](image/3.png){#fig:003 width=70%}

Когда оформление отчета завершено, скомпилируем его командой make, чтобы получить варианты отчетов в форматах PDF и DOCX (рис. @fig:004).

![Компиляция отчетов](image/4.png){#fig:004 width=70%}

# Выводы

В ходе выполнения данной работы я освоил процедуру оформления отчетов с помощью легковесного языка разметки Markdown.


