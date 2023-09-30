<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWo4bzN4ODlqYWZiM3lldHBnMXlzMGhzNHBic2U3d3R3d3Nob3lqaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZgTR3UQ9XAWDvqy9jv/giphy.gif" width="300" height="300"/>
</div>

# Портфолио: Инженер По Тестированию

## :man_technologist: Обо мне:
Приветствую! Меня зовут Илья, я начинающий тестировщик.
В этом репозитории вы сможете найти некоторые из моих проектов, выполненных во время обучения.
  
# :hammer_and_wrench: Навыки и технологии
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original-wordmark.svg" title="Jira" alt="Jira" width="40" height="40"/>&nbsp;
  <img src="https://asset.brandfetch.io/idy_3xttWU/idFUHFXmio.jpeg" title="QaseIO" alt="QaseIO" width="40" height="40"/>&nbsp;
  <img src="https://asset.brandfetch.io/idAnDTFapY/idG4aRyg5R.svg" title="Miro" alt="Miro" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/chrome/chrome-original.svg" title="Chrome" alt="Chrome" width="40" height="40"/>&nbsp;
  <img src="https://www.svgrepo.com/show/354202/postman-icon.svg" title="Postman" alt="Postman" width="40" height="40"/>&nbsp;
  <img src="https://seeklogo.com/images/S/swagger-logo-A49F73BAF4-seeklogo.com.png" title="Swagger" alt="Swagger " width="40" height="40"/>&nbsp;
  <img src="https://logovectorseek.com/wp-content/uploads/2020/09/soapui-supported-by-smartbear-logo-vector.png"  title="SOAP UI" alt="SOAP UI" width="80" height="40"/>&nbsp;
  <img src="https://mockoon.com/images/logo.svg" title="Mockoon" alt="Mockoon" width="80" height="40"/>&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/DBeaver_logo.svg" title="DBeaver" alt="DBeaver" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>
</div>

- Навыки: ``Функциональное тестирование``, ``Тестирование API``, ``SQL``, ``Тестирование документации``;
- Инструменты для функционального тестирования: ``Jira``, ``qase.io``, ``Sitechco``, ``Miro``, ``Chrome devtools``;
- Инструменты для тестирования API: ``Postman``, ``Swagger``, ``SoapUI``, ``Mockoon``, ``DBeaver``;
- Инструменты для тестирования SQL: ``PostgreSQL``, ``pgAdmin 4``;

# :page_facing_up: Проекты
**Проект 1**: Тестирование расписания в разделе "Личные события" в веб-приложении для учителей от Skyeng

Что нужно было сделать:
1. Подготовить тест-план
2. Подготовить тестовую документацию
3. Провести тестирование
4. Написать отчет о результатах тестирования

Как решал: 
1. Ознакомился с требованиями, настроил окружение, зашёл во все необходимые аккаунты.
2. Составил тест-план, в котором указал информацию о тестируемом продукте, основные требования, расписание тестовых работ, виды тестирования и тестовую документацию. Для составления тест-плана использовал ``Confluencе``
3. Провёл тестирование требований
4. Сделал декомпозицию тестируемого функционала в ``Miro``
5. Составил smoke-тест в ``Qase.io``
6. Составил приёмочные тест-кейсы в ``Qase.io``, основываясь на требованиях стейкхолдеров
7. Провёл тест-ран приёмочных и smoke-тестов
8. Составил чек-листы функциональных проверок в ``Sitechco``, там же составил чек-лист для регрессионного тестирования
10. В ``Jira`` завёл баг-репорты на найденные баги
11. Занёс всю тестовую документацию в тест-план
12. Написал отчет о тестировании, в который приложил тестовую документацию и данные о найденных дефектах, а так же свои рекомендации по результатам тестирования

Ссылка на проект: https://ilua-bug-report.atlassian.net/wiki/spaces/~63f8e150526117e1514d7c5a/pages/950273/1+2


Выводы(Итоги):  
В ходе тестирования были обнаружены несколько некритичных багов, критичных багов не обнаружено. Результаты тестирования показали, что продукт готов к релизу.




**Проект 2**: Тестирование API расписания в разделе "Личные события" в веб-приложении для учителей от Skyeng

Что нужно было сделать:
1. Дополнить тест-план
2. Создать коллекцию в Postman
3. Провести тест-ран
4. На основе результатов тест-рана дополнить отчет о тестировании

Как решал:
1. Изучил документацию API в ``Swagger``
2. Провёл исследовательское тестирование используя ``Chrome devtools``
3. Дополнил тест-план тестированием API
4. В qase.io создал тест-сьюты и составил API-тест-кейсы
5. Создал рабочее простраство в ``Postman``. Создал коллекцию и 4 группы для запросов, в зависимости от выполняемой ими функции - создание личного события, редактирование, отображение и удаление
6. В колекции создал запросы, соответствующие тест-кейсам в ``Qase.io``
7. Автоматизировал тест-ран в ``Postman``, используя последовательность действий (Создание -> Редактирование -> Отображение -> Удаление) и переменные. Получилось написать 2 тест-кейса, которые можно проверить через API, но невозможно проверить через интерфейс
8. В qase.io провел тест-ран на основе запущенной коллекции в Postman
9. На основе результатов тест-рана дополнил отчет о тестировании

Ссылка на проект: https://ilua-bug-report.atlassian.net/wiki/spaces/~63f8e150526117e1514d7c5a/pages/950273/1+2

Выводы(Итоги):
Тестирование API расписания в разделе "Личные события" в веб-приложении для учителей от Skyeng пройдено успешно. Была создана Postman-коллекция из 4-х групп и 15 тестов API. Запуск коллекции в ``Postman`` удачно пройден, дефектов выявлено не было. Результаты тестирования показали, что продукт готов к релизу.

# :envelope: Контактная информация:
Email: ilkuz99@mail.ru
