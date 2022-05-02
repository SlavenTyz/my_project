## Описание наиболее интересных проектов в которых применил большенство полученых знаний во время обучения 

|Название проекта|  Описание проекта |Реализации проекта   | Приобретеные навыки           |
|:----------------|:----------------------------------------------------|:-----------------------------------------------|:---------------------------------------|
[Investigation reliability borrowers Исследование надёжности заёмщиков](https://github.com/SlavenTyz/my_project/tree/main/Investigation_reliability_borrowers)|В банке имеется база данных клиентов, на основании ее нужно выделить целевую аудиторию которая регулярно платит по кредитам|Обработал данные, Определил зависимость между наличием детей, семейным положением, уровнем дохода и целей кридита на возврат кредита|Pandas, PyMystem3, Предобработка данных, Лемматизация, Категоризация данных, Группировка данных
|[Identifying promising games Поиск перспективных игр](https://github.com/SlavenTyz/my_project/tree/main/Identifying_promising_games)| Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить параметры которые влияют на успешность продаж игр.| Для начала подготовил данные на наличие пропусков или не корректных данных обработал их. Далее проверил различные зависимости, корреляции. Затем перебрал различные комбинации параметров и построил графики, что бы выделить зависимости. В заключении выдвинул и проверил различные гипотезы |Numpy, Matplotlib,Seaborn, SciPy, изминения типов данных, работа с дубликатами, категоризация данных, склеивание таблиц, статистика, теория вероятности, формулирование и подтверждения гипотез, гистограммы (частот, плотностей), визуализация взаимосвязи данных
|[job parser hh Парсер вакансий с сайта HeadHunter](https://github.com/SlavenTyz/my_project/tree/main/job_parser_hh)|     Ищу вакансии в г Новосибирск или с возможностью удаленной работы и с минимальным опытом | Вытаскиваю различные данные из вакансий, что бы можно  было работать с таблицей, в которой данные с группировал по компаниям, городу, зарплате, описанием и т.д На основании описания распределил вакансии по категориям. Вакансия определяется в нужную категорию на основании ключевых слов в описании (Город, возможность удаленки, направление деятельности, Зарплата). На основании этого могу выбрать интересную вакансию и загрузить ее на сайте. Так как кол-во API запросов ограничино по этому, при привышении лимита появляется ошибка            |API, JSON, ознакомился с библиотеками IPython,json,matplotlib, seaborn,requests|
|[Forecasting outflow client bank Прогнозирование оттока клиентов из банка](https://github.com/SlavenTyz/my_project/tree/main/Forecasting_outflow_client_bank)|На основании исторических данных о поведении клиентов и расторжение договора с банком, прогнозировал уйдет клиент в ближайшее время или нет.| Построил модели  и при помощи перебора различных параметров искал лучшие метрики. Выбрал модель с наибольшими значениями F1-меры.|sklearn, Machine Learning, Math, несбалансированные классификации Модели  Классификации (логическая регрессия, дерево решений, случайный лес) Различные метрики (F1-мера, Precision (Точность), Recall (Полнота), Матрица ошибок, Accuracy). Для улучшения метрик приминял: масштабирование, взвешивание классов, порог классификации, увеличение/уменшение выборки  
|[search production Поиск региона для нефте добычи](https://github.com/SlavenTyz/my_project/tree/main/search_production)|На основании данных, нужно решить какой регион разрабатывать для бурения скважин, что бы минимизировать риски у получить наибольший доход.|На основании предсказанний различных моделе анализирую риски/убытки и делаю выводы о наиболее перспективных регионах для разработки нефти рождения|Bootstrap, Machine Learning, Модели  Регрессии (дерево решений в регресии, линейная регресия, случайный лес). Различные метрики (MSE, RMSE, r2, MAE).Для выявления лучшей модели по разному обрабатывал данные (кросс-валидация, Bootstrap бустинг, ансамблевые методы). Доверительный интервал |
[encryption Шифрование данных Линейная алгебра](https://github.com/SlavenTyz/my_project/tree/main/encryption)|Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось|Математически обосновал, что шифрование данных при помощи умножение признаков на обратимую матрицу, не изменит качество модели предсказания страховых выплат. Проверил качество алгоритма при помощи метрики R2 без шифрования и с шифрованием..|Научился решать матречные уровнения, работа с векторами, скалярные произвидения, работать с растояниями в многомерном пространстве (Евклидово и Манхэттенское) растояние т.е находить взаимосвязь между признаками. Создание и работа с классами
[car cost predictions Предсказания стоимости автомобиля](https://github.com/SlavenTyz/my_project/tree/main/car_cost_predictions)|На основе объявлений о продаже автомобилей написать модель которая будет предсказывать стоимость автомобилей|Обработал данные, что бы не было анимальных значений. Закодировал данные методом Ordinal Encoding и  OHE ( только для линейной регрессии), что бы типы данных object перевести в числовой формат для того что бы модели более качественно оценивали стоимость. Написал несколько моделей для выявления лучшей метрики RMSE и время обучения и предсказания|Разобрался с библиотеками lightgbm, time, catboost градиентным бустингом  LightGBM, CatBoostRegressor
