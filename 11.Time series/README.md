## 11. Временные ряды

### Цели проекта

- Спрогнозировать количество заказов такси на следующий час.
- Построить модель для такого предсказания.
- Значение метрики RMSE на тестовой выборке должно быть не больше 48.

### Задачи проекта

- Предобработка данных
- Анализ данных. Определение тренда, сезонности, остатков
- Обучение и тестирование моделей.
- Анализ результатов предсказаний

### Итоги

- Обучены четыри модели LinearRegression, RandomForestRegressor, LGBMRegressor, CatBoostRegressor. 
- Все модели после подбора параметров показали метрику RMSE ниже порога в 48. 
- Лучшая метрика у CatBoostRegressor 41.78.
