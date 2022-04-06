# my_project
## Описание моих проектов
=======================================
Данные проекты были выполнены мной в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных"
| Название проекта      | Сферы деятельности компаний | Направление деятельности        | Навыки и инструменты             | Задачи проекта     |
| :-------------------- | :--------------------- |:----------------------------|:----------------------------|:----------------------------|
| Исследование надёжности заёмщиков - анализ банковских данных |Банковская сфера, Кредитование|Data Analyst, Финансовый аналитик|*Pandas, PyMystem3, Python, лемматизация, предобработка данных*|На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок|
| Исследование объявлений о продаже квартир в Санкт-Петербурге - анализ рынка недвижимости |Интернет-сервисы, Площадки объявлений|Data Analyst, Fraud-аналитик, Маркетинг-аналитик|*Matplotlib, Pandas, Python, визуализация данных, исследовательский анализ данных, предобработка данных*|Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир|
| Определение перспективного тарифа для телеком-компании |Телеком|Data Analyst, Маркетинг-аналитик, Продуктовый аналитик|*Matplotlib, NumPy, Pandas, Python, SciPy, описательная статистика, проверка статистических гипотез*|На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа|
| Изучение закономерностей, определяющих успешность игр |Gamedev, Интернет-магазины|Маркетинг-аналитик, Продуктовый аналитик|*Matplotlib, NumPy, Pandas, Python, исследовательский анализ данных, описательная статистика, предобработка данных, проверка статистических гипотез*|Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры|
| Анализ бизнес-показателей продукта - интернет приложение | Стартапы, Бизнес, Интернет-сервисы |Data Analyst, Продуктовый аналитик, Маркетинг-аналитик, Аналитик (универсал)|*Matplotlib, NumPy, Pandas, Python, когортный анализ, юнит-экономика, исследовательский анализ данных, описательная статистика, предобработка данных, продуктовые метрики, визуализация данных*| Выяснение причины убыточности сервиса и формирование рекомендаций для увеличения прибыли, используя нужные бизнес-метрики. Моя задача — разобраться в причинах и помочь компании выйти в плюс| 
| Приоритизация гипотез и проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста |Интернет-магазины, Бизнес, Интернет-сервисы|Data Analyst, Продуктовый аналитик, Маркетинг-аналитик, Аналитик (универсал)|*A/B-тестирование, Matplotlib ,Pandas, Python, SciPy, проверка статистических гипотез, приоритизация гипотез*|Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами|
| Исследования рынка общепита в Москве для принятия решения об открытии нового заведения | Бизнес, Оффлайн, Стартапы|Data Analyst, Аналитик (универсал), Маркетинг-аналитик|*Pandas, Plotly, Python, Seaborn, BytesIO, Requests, визуализация данных*|Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов|
| Анализ пользовательского поведения в мобильном приложении | Бизнес Стартапы |Data Analyst, Маркетинг-аналитик, Продуктовый аналитик|*A/B-тестирование, Matplotlib, Pandas, Plotly, Python, Seaborn, визуализация данных, проверка статистических гипотез, продуктовые метрики, событийная аналитика*|На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B тестирования|

"""""""""""""""""""""""""""""""""""""""""
## job_parser_hh
Парсер вакансий с сайта HeadHunter Ищу вакансии где не требуется опыт или опыт от 1 года Вытаскиваю различные данные из вакансий, что бы можно было работать с таблицей, в которой данные с группировал по компаниям, городу, зарплате, описанием и т.д На основании описания распределил вакансии по категориям. Вакансия определяется в нужную категорию на основании ключевых слов в описании
1.	Инвестиции
2.	Обработка изображений
3.	Вакансии для сетевых магазинов
4.	Спорт
5.	Маркетинг 
	Задал критерии поиска по регионам
1	в городе Новосибирск
2	с удаленным способом работы
3	по всей России Так же строиться графики по зарплататам и кол-во вакансий для каждой категории. Для удобства ознакомления с вакансиями в конце критерия поиска(поиск в городе, вакансии с удаленькой или по всей России) имеется возможность задать категорию просмотра вакансии(маркетинг, инвестиции и т.д) через браузер т.е загружается в браузере ссылка интересной вакансии. Так как кол-во API запросов ограничено, то при превышении лимита будет появляться ошибка, в основном это происходит при поиске вакансий по всей России.
search_production
## Поиск региона для нефте добычи
На основании данных, нужно решить какой регион разрабатывать для бурения скважин, что бы минимизировать риски у получить наибольший доход. Для этого решил следующие задачи
1.	анализ данных, что бы не было пропусков иначе заполнил бы их какими ни будь значениями, проверка на корректность, анормальность и т.д
2.	Для обучения и тестирования модели разделил общею выборку на обучающею и валидную
3.	На основании предсказанных значениях линейной ригресией анализирую риски/убытки и делаю выводы о наиболее перспективных регионах для разработки нефти рождения

## Forecasting_outflow_client_bank

Прогнозирование оттока клиентов из банка
На основании исторических данных о поведении клиентов и расторжение договора с банком, прогнозировал уйдет клиент в ближайшее время или нет. Построил модели (логическая регрессия, дерево решений, случайный лес) и при помощи перебора различных параметров: масштабирование, взвешивание классов, порог классификации, увеличение выборки. Выбрал модель с наибольшими значениями F1-меры. Для этого решил следующие задачи
1.	Обработал данные, что бы не было пропусков, дубликатов, привел к нужному регистру, типу данных, проверил корреляцию в различных столбцах, оценил распределение значений функцией describe() и т.д
2.	Рассмотрел влияние признаков на уход клиентов из банка
3.	Для обучения, тестирования и проверки качества моделей разделил общею выборку на обучающею, валидную и тестовую В моделях логическая регрессия, дерево решений, случайный лес перебирал параметры: масштабирование, взвешивание классов, порог классификации, увеличение выборки. На основании F1-меры и auc_roc выбрал лучшею модель


## Identifying_promising_games

Выявление перспективных игр Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить параметры которые влияют на успешность продаж игр, решил следующие задачи
1.	Обработал данные, что бы не было пропусков, дубликатов, привел к нужному регистру, типу данных, проверил корреляцию в различных столбцах, оценил распределение значений функцией describe() и т.д
2.	Оценил
А) как со временим увеличилось кол-во новых игр
Б) время жизни платформ и кол-во продаж
           В) влияние рейтингов, отзывов критиков и пользователей на продажи
           Г) влияние жанров на продажи
           Д) Выделил ТОП 5, платформ, жанров
           Е) Составил портрет пользователей, для различных регионов какие платформы, жанры и рейтинги пользуются популярностью
3.	Проверил гипотезы
А) средние продажи платформ Xbox One и PC одинаковые
Б) средние пользовательские рейтинги жанров Action и Sports разные
На основании полученных данных сделал выводы какие параметры лучше всего влияют на продажи игр.


