---
description: >-
  Добавили автоматическое отключение записи звонка для всех через 3 часа после
  ее начала
---

# Отключение записи звонка

Мы обнаружили немало многочасовых записей звонков, где сначала идет занятие, а затем несколько часов ничего не происходит, т.к. занятие фактически завершено, но кто-то остался висеть в звонке (не закрыл вкладку), а если преподаватель/администратор не завершил звонок для всех, запись продолжится.

Для оптимизации данного процесса реализовали автоматическое отключение записи звонка через 3 часа после ее начала.

При этом всем участникам звонка, которые имеют права на включение записи, за 2 минуты до истечения 3 часов отобразится модальное окно с сообщением о том, что запись будет отключена, если не будет нажата кнопка “продолжить запись”.

![](<../../.gitbook/assets/image (1) (3) (1).png>)

Если хотя бы один человек в звонке, который имеет права на включение записи, нажал кнопку “продолжить запись” за эти две минуты, то запись продолжится. По истечению трех часов такое модальное окно будет отображаться каждый следующий час, если запись еще идет.

10.02.2023
