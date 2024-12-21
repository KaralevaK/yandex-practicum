# Маркетинг

**Описание проекта**

Интернет-магазин собирает историю покупателей, проводит рассылки предложений и планирует будущие продажи. Для оптимизации процессов надо выделить пользователей, которые готовы совершить покупку.

**Цель**

- Построить модель машинного обучения для выявления пользователей, готовых совершить покупку в интернет-магазине. Целевая метрика - ROC-AUC (значение не меньше 0.7).

**Особенности**
- Задача бинарной классификации, обучение с учителем, дисбаланс классов. 

**Рассмотренные модели**

- CatBoostClassifier
- LGBMClassifier
- KNeighborsClassifier
- LogisticRegression
- DecisionTreeClassifier
- RandomForestClassifier

**Вывод**

Построена модель для предсказания покупки, значение целевой метрики удовлетворяет требованиям.

**Инструменты**
- `Python`
- `pandas` `matplotlib` `seaborn` `scikit-learn`  

**Требования**

Перечень модулей и пакетов, необходимых для работы с проектом, находится в файле requirements.txt. 

Для установки пакетов из requirements.txt, необходимо открыть командную строку, перейти в каталог проекта и ввести следующую команду:

>pip install -r requirements.txt

Если вы хотите обновить компоненты вместо их повторной установки, используйте команду:
 >pip install -U -r requirements.txt
