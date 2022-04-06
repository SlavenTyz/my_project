
## Описание моих проектов
Выложил наиболее интересные проекты
| Название проекта      |  Навыки и инструменты                                | Задачи проекта     |
| :-------------------- | :--------------------------------------------|:----------------------------|
| job_parser_hh Парсер вакансий с сайта HeadHunter|     Ищу вакансии где не требуется опыт или опыт от 1 года Вытаскиваю различные данные из вакансий, что бы можно было работать с таблицей, в которой данные с группировал по компаниям, городу, зарплате, описанием и т.д На основании описания распределил вакансии по категориям. Вакансия определяется в нужную категорию на основании ключевых слов в описании              |*Pandas, PyMystem3, Python, лемматизация, предобработка данных*|Инвестиции






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


