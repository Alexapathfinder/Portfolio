### Цель проекта:

Изучить базу данных, извлечь данные при помощи инструментов SQL и сделать анализ спроса авиапассажиров на вылеты в города, где  проводятся известные культурные фестивали.
Главная задача: подтвердить или опровергнуть гипотезу о том, что в среднем спрос на авиабилеты в то время, когда проводятся фестивали, схож со средним спросом на авиабилеты в остальное время»


### Шаги выполнения проекта:

1. Подготовка данных.
2. Анализ.
3. Работа с гипотезой.

### Установка:

Для выполнения проекта необходимо установить:

pip install pandas
pip install seaborn
pip install matplotlib

### В проекте использовались:

- sql
- matplotlib
- seaborn
- qq-plot
- тест Манна-Уитни


### Краткое описание проекта:

Проект состоял из трех частей: подготовки, анализа данных и проверки гипотезы. 

На подготовительном этапе проведена работа с базой данных. 

На этапе анализа данных были исследованы данные (в т.ч. на корректность), построены гистограммы и на основе полученной информации сделаны выводы. 

На третьем шаге осуществлялась проверка гипотезы, звучащая, как: "в среднем спрос на авиабилеты в то время, когда проводятся фестивали, схож со средним спросом на авиабилеты в остальное время".  


### Вывод по работе:

Данная работа состояла из трех частей: подготовке данных, аналитической части и проверки гипотезы. 

На этапе ***подготовки данных*** были использованы инструменты SQL, чтобы вытащить из базы данных и сформировать три таблицы: "Количество рейсов каждой модели самолётов за сентябрь 2018 г.", "Среднее число прилетающих рейсов за день для каждого города в августе 2018 г." и "Количество купленных билетов в Москву на каждой из недель за период с 23 июля по 30 сентября 2018 г.".

В ***аналитической*** части были исследованы данные, построены гистограммы. По окончании данного этапа можно сделать вывод, что данные обеих таблиц несколько сомнительны, требуется переуточнение информации.

На третьем шаге осуществлялась ***проверка гипотезы***, звучащая, как: "средний спрос на билеты во время фестивалей не отличается от среднего спроса на билеты в обычное время".  
По проведении статистического анализа можно сказать, что некоторые отличия в спросе действительно присутствуют. Тем не менее, стоит отметить, что данных было недостаточно: для опровержения/подтверждения гипотезы нам были предоставлены всего 10 недель, на трёх из которых были проведены фестивали. Таким образом, можно сказать, что хоть нулевая гипотеза и была отвергнута, при большем наборе данных результат мог быть другим.
Проект завершен.