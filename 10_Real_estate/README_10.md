Предсказание стоимости жилья
В проекте вам нужно обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных нужно предсказать медианную стоимость дома в жилом массиве. Обучите модель и сделайте предсказания на тестовой выборке. Для оценки качества модели используйте метрики RMSE, MAE и R2.

Описание проекта:
Цель данного проекта обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году.

Для оценки качества модли будут использоваться следущие метрики качества: RMSE, MAE и R2

Выводы:
Линейная регрессия без категориальных значений показала в среднем лучшие метрики чем с категориальными значениями:

С категориальными значениями:
Root Mean Squared Error (RMSE) = 68408.293044
Mean Absolute Error (MAE) = 49963.174372
R2 Score = 0.648230


Без категориальных значений:
Root Mean Squared Error (RMSE) = 69222.260031
Mean Absolute Error (MAE) = 50933.703413
R2 Score = 0.639809

Мы видим, что RMSE и MAE выше в модели где кат. значения были убраны и не принимали участиче в обучении модели.
