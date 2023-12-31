# Обезличивание данных с помощью матричного преобразования

### Задача

Предложите метод для обезличивания персональных данных. Используя метрику R2 покажите, что качество моделей LinearRegression не отличается до и после обезличивания.

### Решение

- проведена предобработка данных,
- аналитически показано, что качество линейной регрессии не меняется при умножении признаков на обратимую матрицу,
- сформулированы зависимости параметров линейной регрессии для исходных и преобразованных данных,
- предложен алгоритм обезличивания данных путем умножения на обратимую матрицу,
- экспериментально показано, что значение R2 линейной регрессии не зависит от предложенного алгоритма

### Инструменты

- pandas,
- numpy,
- sklearn
