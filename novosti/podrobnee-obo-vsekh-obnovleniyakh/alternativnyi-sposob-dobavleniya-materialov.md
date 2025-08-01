---
description: Реализовали альтернативный способ добавления материалов в библиотеку
title: Альтернативный способ добавления материалов
---

Ранее уже реализовывали функционал копирования/перемещения материалов из одной библиотеки (каталога) в другой. Напомним, что копирование/перемещение работает следующим образом - в библиотеке, откуда требуется скопировать/перенести, выбирается файл и через контекстное меню совершается действие по копированию/перемещению в библиотеку куда следует скопировать/перенести файл.

Однако, выяснилось, что такой сценарий используют далеко не все пользователи. Чтобы не искать куда добавить и не промахнуться при выборе добавлена возможность находиться в библиотеке, куда следует скопировать/переместить этот файл, и через интерфейс этой библиотеки забирать файл из какой-то другой.

В связи с этим были произведены следующие доработки:

Добавили в “Материал” в библиотеке опцию “Из другой библиотеки”:

![](<../../.gitbook/assets/image (46) (3).png>)

По нажатию на данную опцию открывается следующее модальное окно.

![](<../../.gitbook/assets/image (42).png>)

-  Выбор материалов осуществляется через чекбоксы

-  Пользователь имеет возможность переходить в папку, чтобы выбрать требуемые материалы из нее

-  При выборе материалов из папки есть отображение количества материалов выбранных из нее

-  Внизу окна есть подсчет количества выбранных материалов.

В окне выбора материалов для добавления в текущую библиотеку изначально открывается "Моя библиотека".

Возможность скопировать через новое окно материал из одной папки библиотеки в другую папку этой же библиотеки не ограничена.

24\.05.2023