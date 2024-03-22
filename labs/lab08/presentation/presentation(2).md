---
## Front matter
lang: ru-RU
title: Презентация лабораторной номер 6
author:
  - Гиршфельд А. Е.
institute:
  - Российский университет дружбы народов, Москва, Россия


## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

## Цель работы

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем

# Результаты

## Запишем в file.txt названия файлов из /etc затем из ~ 

![запись в file.txt](image/1.png)

## Выведем все файлы с расширением .conf

![.conf](image/2.png)


## запуск в фоновом режиме записи в файл  ./logfile

![запуск в фоновом режиме](image/5.png)

## узнаем номер процесса gedit двумя способами, через ps и ps | grep

![ps и ps | grep](image/8.png)
## завершим процесс командой kill и проверим результат через ps

![kill](image/10.png)

##  Выводы

Ознакомился с инструментами поиска файлов и фильтрации текстовых данных.
Приобрел практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем


