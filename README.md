![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

## Traditional clustering vs Autoencoder Clustering

Используемый [датасет](https://storage.yandexcloud.net/academy.ai/Mall_Customers.csv). Датасет загружен, проведено его исследование, удалены дубликаты, выполнено кодирование категориального признака, а также реализована предобработка данных.

В **традиционном методе** кластеризации реализованы 3 метода для определения количества кластеров, а именно: **Метод Локтя**, **Silhouette Score** и **Gap Statistic**. В финальной части для визуализации используем `PCA`, он превращает сложные многомерные данные в простую двумерную картинку, сохраняя максимально возможную информацию о структуре данных.

В **кластеризации с автокодировщиком** реализовано обучение модели, в основе которого лежат полносвязные слои (`Dense`). В финальной части визуализируем результаты кластеризации, в основе которых лежат скрытые представления.

Далее представлен вывод и сравнительный анализ двух методов, в результате которого победил метод кластеризации с автокодировщиком. 
