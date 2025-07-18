---
description: Запретили студентам начинать звонок в дисциплинах
---

# Запрет на начало звонка студентами

Раньше мы позволяли студентам начинать звонок в чатах дисциплины самостоятельно (но не отправляли при этом уведомление участникам звонка о входящем звонка), чтобы студенты могли заранее познакомиться с функционалом звонков, подключаться к занятию пораньше, да и в целом чтобы было меньше ограничений. Однако оказалось, что практической пользы от этого особой нет. Плюс это приводит к появлению в чате дисциплины множества сообщений о “звонках”, которые длятся всего минуту-другую, и в котором участвовали 1-3 человека. Пришли к выводу, что студентам нет необходимости иметь возможность подключаться к звонку дисциплины, когда звонка еще нет.

Что было реализовано:

1. Убрали у студентов в мини-чате и на странице “Чаты” кнопку “Позвонить” в чате (и комнатах) дисциплины. Теперь эта кнопка отображается только тем, кто может редактировать дисциплину.
2. На странице активности и в календаре при просмотре детальной информации об активности, если это онлайн-активность, представляющая собой звонок в Odin, кнопка “Звонок в Odin” теперь имеет следующие состояния:

* В системе есть активный звонок, привязанный к этой активности - кнопка “Звонок в Odin” активна, никаких тултипов нет
* В системе нет активного звонка, привязанного к этой активности, дата начала активности > текущей - кнопка “Звонок в Odin” не активна, на ней тултип “Вы сможете присоединиться к звонку за 5 минут до начала активности“
* В системе нет активного звонка, привязанного к этой активности, дата начала активности < текущей - кнопка “Звонок в Odin” не активна, на ней тултип “Звонок завершен и к нему больше нельзя присоединиться“
* В системе нет активного звонка, привязанного к этой активности, дата начала активности не указана - кнопка “Звонок в Odin” не активна, на ней тултип “Вы сможете присоединиться к звонку, когда его инициирует преподаватель“

Например:

![](<../../.gitbook/assets/image (3) (5).png>)



19.04.2023
