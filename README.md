<h1>Прогнозирование цен на дома</h1>

<h3>Цель:</h3>
Применение алгоритмов машинного обучения с целью прогнозирования цен на дома.  
<br>  
<br>
Датасет был взят с сайта Kaggle.  

<h3>Признаки</h3>

В качестве признаков выступают:
- Площадь
- Кол-во спальных комнат
- Кол-во ванных комнат
- Кол-во комнат всего
- Наличие главной дороги у дома
- Наличие гостевой комнаты
- Наличие подвала
- Наличие нагревателя воды
- Наличие системы кондиционирования
- Кол-во парковочных мест
- Наличие специальной зоны
- Статус мебели


<h3>Примененные алгоритмы</h3>  

В качестве алгоритмов машинного обучения были выбраны:
- LinearRegression
- Lasso
- RandomForestRegressor
- GradientBoostingRegressor

<h3>Результаты обучения моделей</h3>
<img width="427" alt="image" src="https://github.com/user-attachments/assets/edc5bf97-2c90-4597-a5e3-97e7c0245811" />  

Модели с алгоритмами Random Forest и Gradient Boosting показали лучшие результаты

<h3>Визуализация</h3>
<img width="515" alt="image" src="https://github.com/user-attachments/assets/97ee7ba6-40fd-4ea9-99ab-44b01b90c392" />  
<img width="512" alt="image" src="https://github.com/user-attachments/assets/5c9bf587-c6cc-4c94-bfd4-552283081a35" />

<img width="781" alt="image" src="https://github.com/user-attachments/assets/3b7b40e0-3dec-4d42-a72c-632bf35aa1df" />
<img width="666" alt="image" src="https://github.com/user-attachments/assets/8c2a28a1-82d2-4d79-867a-fb77ae2b72a0" />

<img width="614" alt="image" src="https://github.com/user-attachments/assets/1dda7005-90bb-4cd0-8249-2f252d40692f" />
<img width="514" alt="image" src="https://github.com/user-attachments/assets/51c5ec3d-67dd-4da8-a178-23a65f22b778" />




<h3>Выводы:</h3>  

- Модели с алгоритмами Gradient Boosting и Random Forest показали лучшие результаты, по сравнению с Lasso и Linear Regression
- Средняя абсолютная ошибка (MAE) у Gradient Boosting и Random Forest составляет 1,03. У Lasso и Linear Regression она значительно выше - 9,7.
- Коэффициент детерминации (R²) у всех моделей приблизительно одинаковый: 0.61 для линейных моделей и 0.65 для ансамблевых. 

