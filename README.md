# Привет, это мы 👋

Мы — разработчики Dodo Engineering. Тут мы открыто рассказываем про то, как создаём и развиваем IT в Dodo Brands (Додо Пицца, Дринкит, Донер 42). Здесь ты узнаешь про ценности, принципы, бизнес-процессы, инструменты и правила жизни нашей команды.

[![http://dodo.dev/](images/header.png)](http://dodo.dev/)

> Мы приветствуем принцип **no bullshit**, поэтому если увидишь информацию, которая покажется странной, неправильной и ты знаешь как лучше — смело присылай pull requests или пиши в личку @Schvepsss в любых соц. сетях (ну или почти любых).

# Коротко о команде Dodo Engineering

Наша команда появилась 22 апреля 2011 года в Сыктывкаре вместе с появлением первой пиццерии Додо Пиццы. Тогда она состояла из двух разработчиков, которые создали сайт для заказа пиццы и заложили основу Dodo IS, нашей самописной системы. За это время мы сильно выросли. Сейчас система объединяет в себе функционал ERP+CRM+HRM и помогает франчайзи открывать бизнес «из коробки».

В 2017 году нас было 20, сейчас больше 200. 2019 год стал переломным: команда выросла больше чем в 3 раза, процессы поплыли, структура перестала работать эффективно. Мы начали перестройку и за полгода прошли путь от хаоса и разрухи до понятной структуры на 120+ человек и 18 команд. Мы будем дальше масштабироваться и теперь понимаем, как работает команда на 300 человек и будет работать на 500. Понимаем, какие задачи будут перед нами стоять, какую роль во всём этом играет распил монолита, куда можно расти разработчикам.

В 2020 году наш бизнес вырос – помимо Додо Пиццы запустили и развиваем кофейни Дринкит и донерные Донер 42. Планируем открытие новых стран. Мы как IT-команда продолжаем расти и масштабироваться вместе с бизнесом, решая проблему с помощью написания строчки кода и раскатки решения на все точки питания.

# Коротко в цифрах

| Мы | Цифры и знаки|
|:------------- |:---------------:|
| Всего сотрудников в компании | 500+ |
|IT-команда | 200+ |
|Количество пиццерий | 770+ |
|Количество стран | 15 |
|Количество клиентов | 21 000 000+ |
|Максимальная нагрузка (заказов в минуту) | 370 |
|Стандартная нагрузка (заказов в минуту) | 250 |
|RPS | 3700 |
|Выручка в 2021 году (рублей) | 40 000 000 000 |

# Коротко о технологиях

* .NET Framework, переходим постепенно на .NET Core:
  * ASP.NET MVC в монолите – 14 сервисов;
  * ASP.NET Core в монолите – 2 сервиса;
  * ASP.NET Core вне монолита на win серверах – 4 сервиса;
  * ASP.NET Core вне монолита в k8s – 24 сервиса.
* на сайте React + TypeScript, в бекофисе мигрируем с jQuery, Angular первых версий тоже на React + TypeScript;
* 36 баз MySql на кластерах, кроме dev окружений;
* всё на Azure, с использованием RabbitMQ (местами Kafka, Azure Event Hubs), Kusto, CosmosDB, Redis и ещё много мелких радостей;
* все новые сервисы мы пишем на .Net, под Linux, запускаем в Kubernetes;
* детальный мониторинг на продакшене на базе Prometheus, сбор логов в Kusto, визуализация в Grafana, пейджер для дежурного в PagerDuty.

# 7 технологических радаров Dodo Engineering

1. [Infrastructure](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1ztSpWjMYITWqemHAWOQvKZif308NzDSKsqmdBAA8EE4%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BInfrastructure.csv).
2. [Backend](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F18Q1uHEuyqqS3tttHHnHXBX1HGoKZ2QfSirTsPyiClTM%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BBackend.csv).
3. [Frontend](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F15B0mJaxj8gdS4opGCsn42w3PeIAV0YCfVeEFzzcFe5w%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BFrontend.csv).
4. [QA](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1Us_0_jAawz2CvGw2QWSNBBdkTszFEHU3OBIaCoBakkI%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BQA.csv).
5. [Data](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1AlBKLqQbfXnw4GOdcsnfmWDt8gpGyp2VuezmvnsLMTo%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BData.csv).
6. [iOS](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1675l-O8_tuO15uGCYaevKwvuTAvLbY2GdLNwzzPSX7c%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BiOS.csv).
7. [Android](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1Gfjm3g3-u-WrZsynq7trQ3PiqQJozf7ceNy6wdUvxYk%2Fpub%3Foutput%3Dcsv%26format%3D%252FDodo%2BEngineering%2BAndroid.csv).

# Что ещё?

* Стратегия и правила жизни на корабле.
  * [Миссия, ценности, принципы](docs/our-mission.md).
  * Стратегия в IT.
* Как мы ведём разработку Dodo IS.
  * [Что такое Dodo IS](https://habr.com/ru/company/dododev/blog/506136/).
  * [Структура команды](docs/team-structure.md).
  * Инженерные практики.
  * [Развитие и возможности в IT](docs/self-development.md).
  * [Onboarding](https://habr.com/ru/company/dododev/blog/510382/).
* Как проходят собеседования и как стать частью нашей команды:
  * Как проходят собеседования.
  * [Вакансии](https://dodo.dev/manager#jobs).
* [Где нас можно найти](docs/resource-links.md).
