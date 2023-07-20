# План автоматизации

# 1. Перечень автоматизируемых сценариев.
Сценарий перехода к форме по записи на курс

| Путь до страницы курса "Тестировщик ПО" |                                                                                                       |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------|
| Название                                | Путь до формы                                                                                         |
| Хедер - каталог курсов                  | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. Кнопка "Каталог курсов";                                                                           |
|                                         | 3. Кнопка "Программирование";                                                                         |
|                                         | 4. Уровень "Новичкам";                                                                                |
|                                         | 5. Курс "Тестировщик ПО".                                                                             |
| Полный каталог - строка поиска          | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. Кнопка "Полный каталог;                                                                            |
|                                         | 3. Строка поиска: в строке поиска ввести "тестировщик";                                               |
|                                         | 4. Курс "Тестировщик ПО.                                                                              |
| Полный каталог - фильтры                | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. Кнопка "Полный каталог";                                                                           |
|                                         | 3. Фильтры: "Программирование" --> "Стоимость: платное" --> "Длительность: 6-12 мес." --> "Новичкам"; |
|                                         | 4. Курс "Тестировщик ПО.                                                                              |
| Направления обучения - строка поиска    | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. Раздел "Направления обучения";                                                                     |
|                                         | 3. Кнопка "Программирование";                                                                         |
|                                         | 4. Строка поиска: в строке поиска ввести "тестировщик";                                               |
|                                         | 5. Курс "Тестировщик ПО.                                                                              |
| Направления обучения - фильтры          | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. Раздел "Направления обучения";                                                                     |
|                                         | 3. Кнопка "Программирование";                                                                         |
|                                         | 4. Фильтры: "Стоимость: платное" --> "Длительность: 6-12 мес." --> "Новичкам";                        |
|                                         | 5. Курс "Тестировщик ПО.                                                                              |
| Футер - каталог курсов - строка поиска  | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. В конце страницы раздел "Обучение";                                                                |
|                                         | 3. Кнопка "Каталог курсов"                                                                            |
|                                         | 4. Строка поиска: в строке поиска ввести "тестировщик";                                               |
|                                         | 5. Курс "Тестировщик ПО.                                                                              |
| Футер - каталог курсов - фильтры        | 1. Главная страница сайта Нетологии https://netology.ru/;                                             |
|                                         | 2. В конце страницы раздел "Обучение";                                                                |
|                                         | 3. Кнопка "Каталог курсов"                                                                            |
|                                         | 5. Фильтры: "Программирование" --> "Стоимость: платное" --> "Длительность: 6-12 мес." --> "Новичкам"; |
|                                         | 5. Курс "Тестировщик ПО.                                                                              |

Сценарий по отправке формы для записи

| Название                                              | Путь до формы                                                                             |
|-------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Кнопка "Записаться"                                   | 1. Главная страницам программы курса "Тестировщик ПО": https://netology.ru/programs/qa#/; |
|                                                       | 2. Кнопка "Записаться";                                                                   |
|                                                       | 3. Переадресация в футер страницы "Записаться / Получить консультацию";                   |
|                                                       | 4. Ввод контактных данных;                                                                |
|                                                       | 5. Кнопка "Записаться".                                                                   |
| Кнопка "Условия акции"                                | 1. Главная страницам программы курса "Тестировщик ПО": https://netology.ru/programs/qa#/; |
|                                                       | 2. Кнопка "Условия акции";                                                                |
|                                                       | 3. Кнопка "Купить курс";                                                                  |
|                                                       | 4. Переадресация в футер страницы "Записаться / Получить консультацию";                   |
|                                                       | 5. Ввод контактных данных;                                                                |
|                                                       | 6. Кнопка "Записаться".                                                                   |
| Форма заполнения в футере                             | 1. Главная страницам программы курса "Тестировщик ПО": https://netology.ru/programs/qa#/; |
|                                                       | 2. Футер "Записаться / Получить консультацию";                                            |
|                                                       | 3. Ввод контактных данных;                                                                |
|                                                       | 4. Кнопка "Записаться".                                                                   |
| Форма заполнения для зарегистрированного пользователя | 1. Главная страницам программы курса "Тестировщик ПО": https://netology.ru/programs/qa#/; |
|                                                       | 2. При прокрутке вниз появляется кнопка записи рядом с аватаром пользователя;             |
|                                                       | 3. Кнопка "Записаться"                                                                    |
|                                                       | 4. Переадресация в футер страницы "Записаться / Получить консультацию";                   |
|                                                       | 5. Ввод контактных данных;                                                                |
|                                                       | 6. Кнопка "Записаться".                                                                   |

# Сценарий тестов по отправке формы
| Тест                                                                     | Описание шагов                                                                                             | Результат                                                                                                       |
|--------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|
| Ввод валидных данных                                                     | 1. Заполнение формы валидными данными;                                                                     | Введеные данные успешно отправлены, появляется всплывающее окно об успешном завершении записи                   |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |
| Отправка пустой формы                                                    | 1. При заполнении формы, оставить форму пустой;                                                            | Запись не завершается, под незаполненными полями появляется сообщение об ошибке: "Обязательное поле"            |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |
| Отправка формы с незаполненным полем "Имя" и заполненным полем "Телефон" | 1. Поле "Имя" остается не заполненным, в поле "Телефон" вводятся валидные данные                           | Запись не завершается, под незаполненными полями появляется сообщение об ошибке: "Обязательное поле"            |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |
| Отправка формы с заполненным полем "Имя" и незаполненным полем "Телефон" | 1. В поле "Имя" вводятся валидные данные, поле "Телефон" остается незаполненным;                           | Запись не завершается, под незаполненными полями появляется сообщение об ошибке: "Обязательное поле"            |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |
| Ввод невалидных данных в поле "Имя"                                      | 1. В поле "Имя" ввести невалидные данные (цифры, спец.символы), в поле "Телефон" вводятся валидные данные; | Запись не завершается, под полем "Имя" появляется сообщение об ошибке: "Должно состоять из букв"                |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |
| Ввод граничных значений в поле "Имя"                                     | 1. В поле "Имя" вводятся данные, содержащие 1 букву, в поле "Телефон" вводятся валидные данные;            | Запись не завершается, под полем "Имя" появляется сообщение об ошибке: "Должно быть не короче 2 символов"       |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |
| Ввод невалидных данных в поле "Телефон"                                  | 1. В поле "Имя" вводятся валидные данные, в поле "Телефон" вводятся невалидные данные;                     | Запись не завершается, под полем "Телефон" появляется сообщение об ошибке: "Номер в формате +9 (999) 999-99-99" |
|                                                                          | 2. Клик по кнопке "Записаться".                                                                            |                                                                                                                 |

# Сценарий тестирования API
| 1. Проверка статуса и совпадения валидных данных отправленных через UI форму записи на курс "Тестировщик ПО" с данными в body POST-запроса к серверу и новыми данными из базы данных. | Статус 200, данные совпадают                       |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| 2. Проверка статуса и отсутствие новых записей в базе данных при отправке пустого body в POST-запросе отправки формы записи на курс "Тестировщик ПО"                                  | Статус 500, новые записи в базе данных отсутствуют |
| 3. Проверка статуса и отсутствие новых записей в базе данных при отправке пустого значения у атрибута name в body в POST-запросе отправки формы записи на курс "Тестировщик ПО"       | Статус 500, новые записи в базе данных отсутствуют |
| 4. Проверка статуса и отсутствие новых записей в базе данных при отправке пустого значения у атрибута name в phone в POST-запросе отправки формы записи на курс "Тестировщик ПО"      | Статус 500, новые записи в базе данных отсутствуют |

# 2.Перечень используемых инструментов с обоснованием выбора.
1. Среда разработки - IntelliJ IDEA – это интегрированная среда разработки (комплекс программных средств, который используется для написания, исполнения, отладки и оптимизации кода). Отличается обширным набором инструментов для рефакторинга (перепроектирования) и оптимизации кода. 
2. Язык программирования: Java JDK 11 - имеет набор готового ПО для разработки и запуска приложений.
3. Система автоматической сборки: Gradle Преимущества:
•	Код на Gradle проще и меньше, разница заметна при реализации сборок с большим числом зависимостей.
•	Благодаря использованию общих принципов проектирования Gradle позволяет создать удобный, понятный и быстро реализуемый проект.
•	Проработанный API упрощает отслеживание и настройку конфигурации сборки, контроль ее исполнения.
•	Система совместима с задачами Ant, инфраструктурой репозитория (сетевого хранилища) Maven и lvy, где можно опубликовать и получить зависимые компоненты. Есть также конвертеры для превращения Maven pom.xml в скрипт Gradle.
•	Gradle легко приспосабливается к любой структуре, благодаря чему можно переносить с него и на него проекты, разработанные для других систем сборок.
•	открытый код. Сторонние разработчики смогли написать множество полезных плагинов, библиотек и других компонентов. Они расширяют функционал и создают полноценную Gradle-экосистему.
•	Gradle Wrapper – эта опция разрешает реализацию сборок, созданных в Gradle, на машинах, где система не установлена. Это упрощает непрерывную интеграцию серверов.
•	Гибкость языка - Groove, в отличие от жестко заданных XML-иерархий Ant и Maven, дает разработчику больше вариантов действия, позволяет оптимизировать проект.
4. Тестовая среда: TestNG - имеет богатый функционал для создания и выполнения тестовых сценариев, а также управления и отчетности о результатах тестирования. TestNG разработан для улучшения и расширения возможностей другого популярного фреймворка тестирования — JUnit, и предлагает множество дополнительных функций, таких как поддержка аннотаций, конфигураций тестов, группировка тестов, параллельное выполнение тестов, дата-провайдеры, слушатели событий и многое другое.
5. Selenide (для UI тестирования)- библиотека для написания лаконичных и стабильных UI тестов с открытым исходным кодом.
6. Rest Assured (для API тестирования) - java-библиотека для тестирования REST API, позволяет автоматизировать тестирование GET и POST запросов.
7. Lombok - плагин для минимизации строк кода за счет аннотаций позволяет оптимизировать код автотестов, добавляет в Java новые «ключевые слова» и превращает аннотации в Java-код, уменьшая усилия на разработку и обеспечивая некоторую дополнительную функциональность.
8. JavaFaker - библиотека для генерации случайных тестовых данных.
9. Docker Desktop - это платформа контейнеризации с открытым исходным кодом. для развертывания контейнера с базой данных MySQL.
10. Allure - фреймворк для создания отчетов о тестировании, для наглядного отображения прохождения тестов и ошибок (более сложные системы репортинга будут излишни).
11. Git и GitHub - для хранения кода. Git достаточно прост и удобен для управления исходным кодом, очень распространенная система контроля версий, поэтому достаточно хорошо взаимодействует с различными ОС. GitHub специализированный веб-сервис с удобным интерфейсои, интегрирован с Git.

# 3. Перечень необходимых разрешений, данных и доступов.
1.	Письменное разрешение на тестирование и автоматизацию от руководства Нетологии;
2.	Статистика, в которой отображаются основные пути пользователей (для их первоочередной проверки);
3.	Технические данные полей (для четкого понимания, что является вылидными/невалидными данными);
4.	Доступ в тестовый режим сервиса и тестовую базу данных для проверки результатов отправки валидных/невалидных тестовых данных через форму для записи;

# 4. Перечень и описание возможных рисков при автоматизации.
1.	Инструменты автоматизированного тестирования могут занять много времени и средств;
2.	При отсутствии статистики по предпочтительному пути поиска, есть риск не проверить ее в первую очередь;
3.	Тесты могут не покрывать всех возможных негативных сценариев - пользователь может повести себя так, как мы не можем предвидеть;
4.	Падение автотестов даже при незначительном изменении кода (изменения: структуры сайта, локаторов элементов сайта).

# 5. Перечень необходимых специалистов для автоматизации.
1.	QA-инженер уровня middle/senior;
2.	QA-инженер уровня junior.

# 6. Интервальная оценка с учётом рисков в часах.
На данные задачи можно выделить около 45 часов рабочего времени. Входит:
•	подготовка мануальных тестов
•	автоматизация мануальных тестов
•	настройка окружения и поведение тестирования
•	формирование отчета о тестировании






