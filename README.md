# Обработка признаков для прогнозирования цен на отели

Этот ноутбук содержит анализ и преобразование признаков из датасета [hotels.csv](/kaggle/input/sf-booking/hotels_train.csv), загруженного с Kaggle.  
**Цель**: Оптимизация признаков для минимизации метрики MAPE (Mean Absolute Percentage Error).

## 📊 Результаты
- **Исходные данные**: Корреляционная матрица до преобразований  
  [До обработки](https://github.com/UlyanaGru/EDA_project/blob/master/correlation_matrix.html)  
  *MAPE = 0.14135128786808074*

- **После feature engineering**: Корреляционная матрица  
  [После обработки](https://github.com/UlyanaGru/EDA_project/blob/master/correlation_matrix_clear.html)  
  *MAPE = 0.13178386822890106*

  Матрицы можно скачать и открыть в браузере. Так нагляжнее и можно покликать

## 🔍 Методы
- Нормализация/стандартизация данных
- Генерация новых признаков (например, "сезонность", "бренд", "класс", "тип")
- Отбор признаков на основе корреляции и feature importance

## 🛠 Технологии
- Python (Pandas, NumPy, Scikit-learn)
- Визуализация (Matplotlib/Seaborn)

Предложения по улучшению или вопросы welcome!  