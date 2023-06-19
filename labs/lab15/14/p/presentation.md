---
## Front matter
lang: ru-RU
title:  Именованные каналы
subtitle: Лабораторная работа №14
author:
  - Миронова М. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 13 мая 2023

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
backgroundColor: orange
---



# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="60%"}

  * Миронова Мария Вадимовна
  * студент 1 курса, группа НММбд-03-22
  * Российский университет дружбы народов

:::
::: {.column width="40%"}

![](./image/1.jpg)

:::
::::::::::::::

# Вводная часть

## Цель работы

- Приобретение практических навыков работы с именованными каналами.

## Задание
Изучить приведённые в тексте программы server.c и client.c. Взяв данные примеры
за образец, написать аналогичные программы, внеся следующие изменения:
1. Работает не 1 клиент, а несколько (например, два).
2. Клиенты передают текущее время с некоторой периодичностью (например, раз в пять
секунд). Используйте функцию sleep() для приостановки работы клиента.
3. Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). Используйте функцию clock() для определения времени работы сервера.
Что будет в случае, если сервер завершит работу, не закрыв канал?

# Выполнение лабораторной работы №14

## Внесение изменений в программы

:::::::::::::: {.columns align=center}

::: {.column width="45%"}

![](./image/1.png)

:::

::: {.column width="45%"}

![](./image/2.png)

:::


::::::::::::::

## Внесение изменений в программы

:::::::::::::: {.columns align=center}

::: {.column width="45%"}

![](./image/3.png)

:::

::: {.column width="45%"}

![](./image/4.png)

:::


::::::::::::::

## Внесение изменений в программы

:::::::::::::: {.columns align=center}

::: {.column width="45%"}

![](./image/5.png)

:::

::: {.column width="45%"}

![](./image/6.png)

:::


::::::::::::::

## Внесение изменений в программы

:::::::::::::: {.columns align=center}

::: {.column width="45%"}

![](./image/7.png)

:::

::: {.column width="45%"}

![](./image/8.png)

:::


::::::::::::::




## Ответы на контрольные вопросы

:::::::::::::: {.columns align=center}


::: {.column width="45%"}

![](./image/9.png)

:::

::: {.column width="45%"}

![](./image/10.png)

:::
::::::::::::::


# Результаты

## Выводы из лабораторной работы №14

В ходе выполнения были приобретены навыки работы с именованными каналами.



