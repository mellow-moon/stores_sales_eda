# Разведочный анализ данных с продажами в магазинах Эквадора

### Данные

В исследовании используются данные с продажами различных продуктов в магазинах Эквадора. Данные включают в себя информацию о магазине, продукте, о том, рекламировался ли товар, а также объем продаж.

Данные можно найти по ссылке: https://www.kaggle.com/competitions/store-sales-time-series-forecasting.

### Используемые файлы
```
- train_df.csv - объем продаж
- stores.csv - информация о магазинах
- oil.csv - ежедневные показатели цен на нефть
- holiday_events.csv - праздники и прочие события
```

### Описание данных

### train_df.csv
```
- ID - an Id that represents a (Shop, Item) tuple within the test set
- shop_id - unique identifier of a shop
```

### stores.csv
```
- ID - an Id that represents a (Shop, Item) tuple within the test set
- shop_id - unique identifier of a shop
```

### oil.csv
```
- ID - an Id that represents a (Shop, Item) tuple within the test set
- shop_id - unique identifier of a shop
```

### holiday_events.csv
```
- ID - an Id that represents a (Shop, Item) tuple within the test set
- shop_id - unique identifier of a shop
```

### Исследуемые вопросы

1. Какая доля продаж приходится на каждый тип продукта? У каких продуктов продажи больше и у каких меньше?

2. Какая доля продаж приходится на каждый магазин? В каких магазинах наибольший объем продаж? Что это за магазины?

3. Влияет ли тип магазина на объем продаж?

4. Какая доля продаж приходится на каждый штат?

5. Оказывают ли цены на нефть влияние на объем продаж?

6. В каком городе наибольшее количество клиентов?

7. В каком штате наибольшее количество клиентов?

8. В каких месяцах продажи были наибольшими и наименьшими?

### Используемые библиотеки

![Ipynb](https://img.shields.io/badge/Python-pandas-blue.svg?style=flat&logo=python&logoColor=white)
![Ipynb](https://img.shields.io/badge/Python-numpy-blue.svg?style=flat&logo=python&logoColor=white)
![Ipynb](https://img.shields.io/badge/Python-plotly-blue.svg?style=flat&logo=python&logoColor=white)
![Ipynb](https://img.shields.io/badge/Python-scipy-blue.svg?style=flat&logo=python&logoColor=white)
