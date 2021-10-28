# analista_harda
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных" 
##  Описание проектов
| Название проекта              | Описание           | Используемые библиотеки                    |
| :--------------------: | :---------------------: |:---------------------------:|
| Исследование надёжности заёмщиков | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку. | pandas, pymystem3|
|Исследование объявлений о продаже квартир|В распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно определить рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.|pandas, matplotlib|
|Определение перспективного тарифа для телеком-компании| Задача - сделать предварительный анализ тарифов на небольшой выборке клиентов и проанализировать поведение клиентов и сделать вывод — какой тариф лучше и приносит больше денег, чтобы скорректировать рекламный бюджет. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». В распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. |pandas, numpy, matplotlib.pyplot, seaborn, scipy stats|
|Исследование перспективных игр| Данное исследование проводится для выявления перспективных напрвылений на будущий год с целью планирования рекламного бюджета.В данном проекте доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation)з открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.|pandas,plotly.express, scipy stats, numpy|
|Аналитика в авиакомпании|Цель проекта: исследование предпочтений пользователей, покупающих билеты на те или иные направления.|pandas, plotly.expres|
|Анализ бизнес показателей|Задача - помочь маркетологам снизить расходы — отказаться от невыгодных источников трафика и перераспределить бюджет. Для этого изучали данные о том, как клиенты пользуются сервисом, когда делают первые покупки на сайте, сколько денег приносит компании каждый клиент, когда расходы на привлечение клиента окупаются. Источник данных - данные маркетингового отдела аналитики Яндекс.Афиша| pandas, plotly.express, matplotlib.pyplot, numpy, seaborn|
|Принятие решений в бизнесе на основе данных, приоритизация гипотез, анализ А/В-теста и его результатов| Задачи: 1. Проанализировать и построить график кумулятивной выручки по группам, график кумулятивного среднего чека по группам, график относительного изменения кумулятивного среднего чека группы B к группе A, график кумулятивной конверсии по группам, график относительного изменения кумулятивной конверсии группы B к группе A, точечный график количества заказов по пользователям,точечный график стоимостей заказов. 2. выбрать границу для определения аномальных пользователей. 3. Выбрать границу для определения аномальных заказов. 4. Посчитать и проанализаровать статистическую значимость различий в конверсии между группами по «сырым» данным, статистическую значимость различий в среднем чеке заказа между группами по «сырым» данным, статистическую значимость различий в конверсии между группами по «очищенным» данным, статистическую значимость различий в среднем чеке заказа между группами по «очищенным» данным. 5. Принять решение по результатам теста| pandas, scipy.stats, datetime, matplotlib, numpy|
|Рынок заведений общественного питания Москвы| Источник данных открытые данные о заведениях общественного питания в Москве. Задача - исследование рынка для подготовки предложения для инвесторов по открытию кафе, где клиентов обслуживают роботы, вместо людей. Основным направлением в исследовании является ответ на вопрос: останется ли заведение популярным и после снижения первоначального интереса| pandas, plotly.express, matplotlib.pyplot, numpy, seaborn, plotly graph_objects, re, BytesIO, requests|
| Исследование поведения пользователей стартапа продуктов питания| Данный проек - стартап, в котором продают продукты питания. В приложении дизайнеры решили поменять шрифты и для этого проводится А/А/В-тест с двумя контрольными группами А.  Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. В полученных данных содержатся действия пользователя или события(название события, уникальный номер пользователя, дата и время совершения действия и номер контрольной группы эксперимента). Нужно изучить воронку событий и результаты разделения пользователей на группы| pandas ,plotly.express, matplotlib.pyplot, numpy, seaborn as sns, graph_objects, requests, statistics, scipy stats, scipy.stats(norm), math|
| Дашборд яндекс дзен| Задача: ответить на вопросы менеджеров: Cколько взаимодействий пользователей с карточками происходит в системе с разбивкой по темам карточек?Как много карточек генерируют источники с разными темами? Как соотносятся темы карточек и темы источников?| Tableau|
|Разработка стратегии взаимодействия с клиентами| Целями проекта являются: 1) прогнозирование вероятности оттока (на уровне следующего месяца) для каждого клиента; 2) формирование типичных портретов клиентов: выделение нескольких наиболее ярких групп; 3) анализ основных признаков, наиболее сильно влияющих на отток; 4) формулирование основных выводов и разработка рекомендаций по повышению качества работы с клиентами: 1) выделение целевых групп клиентов; 2) предложение мер по снижению оттока; 3) определение других особенностей взаимодействия с клиентами.| import pandas, plotly.express, matplotlib.pyplot, numpy, seaborn, statistics, scipy, math, sklearn.tree, sklearn.preprocessing, sklearn.model_selection, sklearn.linear_model, sklearn.ensemble, sklearn.metrics, sklearn.ensemble, sklearn.cluster, scipy.cluster.hierarchy|
|Анализ товарного ассортимента магазина || pandas, plotly.express, matplotlib.pyplot, seaborn, plotly,scipy,scipy.stats,math,datetime, Mystem,scipy,numpy|
