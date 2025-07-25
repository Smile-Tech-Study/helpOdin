---
description: Реализовали автоматическое сохранение “черновика” набираемого в чате сообщения
---

# Черновики сообщений в чатах

Информация будет храниться в браузере в течение 3-х дней. Сохранится не только текст сообщения, но и прикрепленные файлы (загрузка которых уже была завершена), а также информация о цитируемом сообщении (на которое пользователь отвечает), упоминания и пр., т.е. полностью всё сообщение.

![](<../../.gitbook/assets/image (4) (1) (4).png>)

Если пользователь стёр набираемое сообщение, черновик тоже опустошится (аналогично с файлами и пр.). То есть реализовано сохранение состояния ввода сообщения, чтобы информация не терялась при обновлении страницы или переходе между страницами.

Черновики будут сохраняться как в тредах, так и в обычных чатах. Черновики “переносятся” в том числе между мини-чатом и страницей “Чаты” (а также в чатах решений). На странице звонка черновики не будут сохраняться (и не должны применяться сохраненные прежде черновики), т.к. контекст общения во время звонка обычно отличается от стандартных сценариев.

09.02.2023
