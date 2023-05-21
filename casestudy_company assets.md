# Разбор кейса "Как определить активы организации в контексте ИБ"

*Перед выполнение домашнего задания по занятию [“Аудит информационной безопасности”](https://github.com/netology-code/ibb-homeworks/tree/IBB-29/03_audit_IS) рекомендуем ознакомиться с примером. В нем подробно разобрано, как определить актив компании в контексте ИБ и какие законы его регулируют.*

--- 
### Кейс “Как определить активы организации в контексте ИБ”

Специалисту по информационной безопасности требуется определить активы организации в контенте ИБ. Он обладает следующими вводными: 

- Государственная организация в рамках гособоронзаказа производит продукцию. 
- Технологический процесс разработки составляет государственную тайну. Все чертежи, проекты и описание технологического процесса по разработке, имеющие гриф секретности “Секретно”, хранятся в электронном виде в файловом хранилище. 
- Сотрудники для работы с чертежами и проектами используют автоматизированные рабочие места, которые с использованием локально-вычислительной сети соединены с файловым хранилищем. После окончания рабочего дня все носители сведений, составляющих государственную тайну, сдаются на хранение в помещение секретного делопроизводства.
- Сотрудники отдела кадров для оформления работников используют заранее заготовленные бланки, куда от руки вписывают нужную информацию. После подписания и утверждения бланки подшиваются в отдельную папку с фамилией работника и сдаются в архив.
- На автоматизированном рабочем месте главного бухгалтера установлено программное обеспечение “Система удаленного финансового документооборота”.

### Решение кейса
Итак, давайте найдет активы организации. 

- Известно, что в компании обрабатываются сведения, составляющие государственную тайну. Хранятся они в электронном виде на файловом хранилище, доступ к которому пользователи получают с использованием локально-вычислительной сети. Можно предположить, что в организации имеется объект информатизации для работы со сведениями, составляющими государственную тайну. Известно, что эти сведения имеют степень секретности “Секретно” - значит, можно предположить, что объект третьей категории. 
**Первый актив организации - объект информатизации для работы со сведениями, составляющими государственную тайну, 3 категории.** Данный актив регулируется [Законом РФ "О государственной тайне" от 21.07.1993 N 5485-1](https://www.consultant.ru/document/cons_doc_LAW_2481/)

- Есть информация, что после окончания рабочего дня все носители сведений, составляющих государственную тайну, сдаются на хранение в помещение секретного делопроизводства. Это делается не просто так - значит, нужно обеспечить их сохранность. 
**Второй актив - носители сведений, составляющих государственную тайну.** Данный актив регулируется [Законом РФ "О государственной тайне" от 21.07.1993 N 5485-1](https://www.consultant.ru/document/cons_doc_LAW_2481/)

- Сотрудники отдела кадров для оформления работников используют заранее заготовленные бланки, куда от руки вписывают нужную информацию. Можно сделать вывод, что в данных бланках содержатся персональные данные сотрудников. При этом на автоматизированных рабочих местах персональные данные не обрабатываются. После оформления бланки сдаются в архив для сохранности.
**Третий актив - носители информации (бумажные), содержащие персональные данные сотрудников.** Данный актив регулируется [Федеральным законом "О персональных данных" от 27.07.2006 N 152-ФЗ](https://www.consultant.ru/document/cons_doc_LAW_61801/)

- На автоматизированном рабочем месте главного бухгалтера установлено программное обеспечение “Система удаленного финансового документооборота”. Это программное обеспечение для работы с Казначейством России. То есть, скорее всего, относится к государственным информационным системам (ГИС).
**Четвертый актив - ГИС “Система удаленного финансового документооборота”.** Данный актив регулируется [Федеральным законом от 27.07.2006 N 149-ФЗ "Об информации, информационных технологиях и о защите информации"](https://www.consultant.ru/document/cons_doc_LAW_61798/)