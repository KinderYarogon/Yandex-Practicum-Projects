# Исследование рынка заведений общественного питания Москвы

## Описание проекта

Исследование рынка заведений общественного питания Москвы с целью выявления основных особенностей рынка и определения перспективных направлений для открытия нового заведения.

В ходе работы проведён анализ категорий заведений, их территориального распределения, сетевого формата, рейтингов, ценового сегмента и других характеристик.

## Данные

В исследовании использованы два датасета:

- `rest_info.csv` — информация о заведениях общественного питания.
- `rest_price.csv` — информация о ценах, среднем чеке и стоимости чашки капучино.

## Инструменты и библиотеки

- Python
- Pandas
- Matplotlib
- Seaborn
- Phik
- Jupyter Notebook

## Ход исследования

1. **Загрузка и изучение данных**
   - Загрузка датасетов.
   - Первичный анализ структуры и содержимого таблиц.

2. **Предобработка данных**
   - Проверка типов данных и пропусков.
   - Проверка явных и неявных дубликатов.
   - Очистка и нормализация текстовых данных.
   - Удаление четырёх неявных дубликатов: после обработки из 8 406 исходных записей осталось 8 402.

3. **Исследовательский анализ данных**
   - Анализ категорий заведений.
   - Изучение территориального распределения по административным округам.
   - Анализ сетевых и несетевых заведений.
   - Исследование рейтингов и вместимости.
   - Анализ популярных сетей и ценовых характеристик.
   - Изучение взаимосвязей между рейтингом и характеристиками заведений.

4. **Выводы и рекомендации**
   - Обобщение результатов исследования.
   - Формирование рекомендаций для выбора формата и места открытия нового заведения.

## Основные результаты

- Наиболее распространённые категории заведений — кафе (2 376), рестораны (2 041) и кофейни (1 413).
- Больше всего заведений расположено в Центральном административном округе — 2 242. Медианный средний чек в ЦАО составляет 1 000 рублей, в остальных округах — 600 рублей.
- Несетевых заведений больше, чем сетевых: 5 199 против 3 203.
- Средние рейтинги заведений по категориям находятся в диапазоне от 4,05 до 4,39. Самый высокий показатель у баров и пабов, самый низкий — у заведений быстрого питания.
- Наиболее выраженная связь с рейтингом обнаружена у ценовой категории (Phi-K = 0,28). Это указывает на взаимосвязь признаков, но не доказывает причинно-следственную зависимость.
- Среди 15 наиболее популярных сетей преобладают кофейни: на них приходится 330 заведений (40,44%). Средние рейтинги рассмотренных сетей находятся в диапазоне от 3,87 до 4,40.
- Медианная вместимость заведений составляет 75 посадочных мест. При этом встречаются отдельные заведения с очень большой вместимостью — до 1 288 мест.
- Медианный средний чек ресторанов в разных округах находится в диапазоне от 837,5 до 1 300 рублей. При интерпретации ценовых показателей важно учитывать, что данные о среднем чеке заполнены только у 27,17–47,28% заведений в зависимости от округа.

## Рекомендации

- При выборе формата стоит рассмотреть кафе и кофейни, учитывая высокую конкуренцию в этих категориях.
- Не стоит ограничиваться Центральным административным округом: несмотря на высокий средний чек, в других округах также могут быть перспективные локации.
- Ценовой сегмент следует выбирать с учётом целевой аудитории и формата заведения.
- При планировании вместимости полезно учитывать медианные показатели по категориям: 60 мест для кафе, 80 для кофеен и 86 для ресторанов.
- Перед открытием заведения необходимо дополнительно изучить конкурентов, цены и рейтинги в конкретном районе.

Результаты исследования помогают оценить особенности рынка, однако сами по себе не позволяют полностью определить спрос и финансовую эффективность будущего заведения.

## Автор

**Ярослав Никитин**

---

# Analysis of the Moscow Food Service Market

## Project Description

This project explores the food service market in Moscow to identify its key characteristics and potential opportunities for opening a new establishment.

The analysis covers establishment categories, geographical distribution, chain status, ratings, price segments, and other characteristics.

## Data

The analysis uses two datasets:

- `rest_info.csv` — information about food service establishments.
- `rest_price.csv` — information about price categories, average bills, and cappuccino prices.

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Phik
- Jupyter Notebook

## Project Workflow

1. **Data Loading and Exploration**
   - Loading the datasets.
   - Examining their structure and contents.

2. **Data Preprocessing**
   - Checking data types and missing values.
   - Checking for explicit and implicit duplicates.
   - Cleaning and normalizing text data.
   - Removing four implicit duplicates: the original dataset contained 8,406 records, leaving 8,402 records for further analysis.

3. **Exploratory Data Analysis**
   - Analyzing establishment categories.
   - Examining geographical distribution across administrative districts.
   - Comparing chain and independent establishments.
   - Analyzing ratings and seating capacity.
   - Exploring popular chains and pricing characteristics.
   - Examining relationships between ratings and establishment characteristics.

4. **Conclusions and Recommendations**
   - Summarizing the findings.
   - Developing recommendations for choosing an establishment format and location.

## Key Findings

- The most common categories are cafes (2,376), restaurants (2,041), and coffee shops (1,413).
- The Central Administrative District has the largest number of establishments (2,242). Its median average bill is RUB 1,000, compared with RUB 600 in other districts.
- Independent establishments outnumber chain establishments: 5,199 versus 3,203.
- Average ratings across categories range from 4.05 to 4.39. Bars and pubs have the highest average rating, while fast-food establishments have the lowest.
- The strongest association with ratings is observed for price category (Phi-K = 0.28). This indicates an association, not a causal relationship.
- Coffee shops predominate among the 15 most popular chains, accounting for 330 outlets (40.44%). The average ratings of the analyzed chains range from 3.87 to 4.40.
- The median seating capacity is 75 seats. Some establishments have considerably larger capacities, reaching 1,288 seats.
- The median average bill for restaurants across districts ranges from RUB 837.5 to RUB 1,300. Average bill data is available for only 27.17–47.28% of establishments, depending on the district, so these figures should be interpreted with caution.

## Recommendations

- Cafes and coffee shops are worth considering, although competition in these categories is high.
- The Central Administrative District should not be the only area considered: other districts may offer promising locations despite lower average bills.
- The price segment should be selected according to the target audience and establishment format.
- Median seating capacity can serve as a reference when planning: 60 seats for cafes, 80 for coffee shops, and 86 for restaurants.
- Before opening, it is important to study competitors, prices, and ratings in the specific area.

The findings provide an overview of the market but are not sufficient on their own to determine demand or the financial viability of a future establishment.

## Author

**Iaroslav Nikitin**
