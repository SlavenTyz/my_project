
## Описание наиболее интересных проектов в которых применил большенство полученых знаний во время обучения 
<div class="foo">
|Название проекта|  Описание и  реализации проекта &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;           | Приобретеные навыки           |
|----------------|:-----------------------------------------------------------------------------:|-----------------------------------------------|
|<img width=50/>[Identifying_promising_games Выявление перспективных игр](https://github.com/SlavenTyz/my_project/tree/main/Identifying_promising_games)| <img width=500/>Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить параметры которые влияют на успешность продаж игр. Для начала подготовил данные на наличие пропусков или не корректных данных обработал их. Далее проверил различные зависимости, корреляции. Затем перебрал различные комбинации параметров и построил графики, что бы выделить зависимости. В заключении выдвинул и проверил различные гипотезы |изминения типов данных, работа с дубликатами,категоризация данных,склеивание таблиц, статистика, теория вероятности,формулирование и подтверждения гипотез, гистограммы (частот, плотностей), визуализация взаимосвязи данных
|[job_parser_hh Парсер вакансий с сайта HeadHunter](https://github.com/SlavenTyz/my_project/tree/main/job_parser_hh)|     Ищу вакансии где не требуется опыт или опыт от 1 года Вытаскиваю различные данные из вакансий, что бы можно  было работать с таблицей, в которой данные с группировал по компаниям, городу, зарплате, описанием и т.д На основании описания распределил вакансии по категориям. Вакансия определяется в нужную категорию на основании ключевых слов в описании (Город, возможность удаленки, направление деятельности, Зарплата). На основании этого могу выбрать интересную вакансию и загрузить ее на сайте. Так как кол-во API запросов ограничино по этому, при привышении лимита появляется ошибка            |API, JSON, ознакомился с библиотеками IPython,json,matplotlib, seaborn,requests|
|[Forecasting_outflow_client_bank Прогнозирование оттока клиентов из банка](https://github.com/SlavenTyz/my_project/tree/main/Forecasting_outflow_client_bank)|На основании исторических данных о поведении клиентов и расторжение договора с банком, прогнозировал уйдет клиент в ближайшее время или нет. Построил модели  и при помощи перебора различных параметров искал лучшие метрики. Выбрал модель с наибольшими значениями F1-меры.|Модели  Классификации (логическая регрессия, дерево решений, случайный лес) Различные метрики (F1-мера,Precision(Точность),Recall(Полнота), Матрица ошибок, Accuracy). Для улучшения метрик приминял:масштабирование, взвешивание классов, порог классификации, увеличение/уменшение выборки  
|[search_production Поиск региона для нефте добычи](https://github.com/SlavenTyz/my_project/tree/main/search_production)|На основании данных, нужно решить какой регион разрабатывать для бурения скважин, что бы минимизировать риски у получить наибольший доход. Для этого решил следующие задачи обработал исходные данные, что бы не было пропусков, или не корректных значений, заполнил их. На основании предсказанний различных моделе анализирую риски/убытки и делаю выводы о наиболее перспективных регионах для разработки нефти рождения|Модели  Регрессии (дерево решений в регресии, линейная регресия, случайный лес). Различные метрики (MSE,RMSE,r2,MAE).Для выявления лучшей модели по разному обрабатывал данные (кросс-валидация,Bootstrap). Доверительный интервал |
</div>
 
Эксперемент
| Tables                                                                                                                             | Are           | Cool  |
| ---------------------------------------------------------------------------------------------------------------------------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
