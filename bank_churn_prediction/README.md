# Прогнозирование оттока клиентов банка

### Задача
С минимально допустимым значением F1 = 0,59 нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.  

### Решение
- проведена предобработка данных,
- показан дисбаланс классов,
- в 5 сценариях борьбы с дисбалансом классов протестированы RandomForestClassifier, LogisticRegression и DecisionTreeClassifier, 
- для RandomForestClassifier с подбором порога классификации достигнуто требуемое качество прогнозирования. 

### Инструменты
- pandas,
- numpy,
- sklearn,
- matplotlib,
- seaborn, 
- re
