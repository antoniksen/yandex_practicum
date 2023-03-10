# Рекомендация тарифов
Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
# Цель исследования:
Построить модель с максимально большим значением accuracy. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте accuracy на тестовой выборке самостоятельно.
# Итог исследования:
По результатам проведённых тестов на трёх нижеследующих моделях:

- Дерево решений
- Случайный лес
- Логистическая регрессия

Были проведены исследования точности (accuracy) различных моделей с изменяемыми параметрами на валидационых выборках изначального датасета. В результате исследования, была выявлена самая точная модель  случайный лес с параметрами 
- Количество деревьев (est): 100
- Глубина дерева (depth): 4 

Отобранная модель показана на тестовой выборке результат (accuracy) 0.7838 что является хорошоим показателем и гораздо выше случайной вероятности абонента быть пользователем пакета услуг is_ultra (0.3065). Этот показатель свидетельствут об адекватности нашей модели тк её эффективность намного выше случайности.

`Резюме:` проедставленная модель предсказывает переход клиента на новый тариф is_ultra с вероятнотью 0.7838.
# Стек технологий
`pandas`, `numpy`, `sklearn`, `seaborn`, `matplotlib`
# Статус проекта:
завершён
