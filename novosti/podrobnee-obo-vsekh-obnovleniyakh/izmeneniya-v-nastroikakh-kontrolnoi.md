---
title: Изменения в настройках "Контрольной"
---

Вместе с представителями ТГУ был разработан ряд требований к активности с типом "Контрольная" для программ с меткой “Нацпроект Демография ТГУ” с указанным годом 2024 и позднее. Реализовали следующие общие настройки:

Количество попыток сдачи не более 3х., то есть в поле “Количество попыток сдачи” можно ввести значение \<= 3. Если же пользователь вводит значение >3, то высвечивается ошибка:

![](<../../.gitbook/assets/image (249).png>)

Для поля “Временной лимит” поменяли подсказку на:

![](<../../.gitbook/assets/image (251).png>)

Минимальный порог баллов должен быть не менее 50%. Минимальный порог баллов рассчитывается автоматически, если в активность подгружен материал типа “Тест”:

-  Минимальный порог баллов должен рассчитываться как 50% от максимального количества баллов, который можно набрать за тест, прикрепленный к активности (округление до целого в соответствии со стандартными правилами округления).

-  Если в тесте присутствует несколько вариантов, где максимальное количество баллов разное, то для расчета минимального балла берем максимальный балл того варианта, где баллов меньше.

-  Если пользователь вводит значение \< *максимально возможного балла за тест* (округление до целого в соответствии со стандартными правилами округления), то поле подсвечивается и показывается ошибка:

![](<../../.gitbook/assets/image (252).png>)

27\.02.2024