# Анализ пользовательского поведения в мобильном приложении

## Задача

1. На основании данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж. 
2. Иследовать результаты А/А/В-тестов на основе 3х групп тестирования. Как изменение шрифтов в приложении повлияет на поведение пользователей?

## Ход работы

1. Выполнили предобработку данных.
2. Провели исследовательский анализ данных
  * Посчитали события и пользователей в логе, рассчитали среднее число событий, приходящихся на пользователя
  * Определили период, закоторый располагаем полными данными
3. Исследовали воронку событий
  * Изучили частоту событий в логах и число пользователей, которые их совершают
  * Рассмотрели последовательность воронки и где теряются пользователи
4. Проверили гипотезы:
  * о равенстве пропорций заказов в контрольных группах, применив Z-критерий.
  * о равенстве конверсий в каждое событие воронки событий в контрольных группах, применив Z-критерий.
  * о равенстве конверсий в каждое событие воронки событий в контрольных и экспериментальной группах, применив Z-критерий.
* Применили поправку Бонферонни для корректировки уровня значимости при множественном тестировании гипотез.


## Использованные библиотеки

- pandas 
- numpy
- math
- stats
- matplotlib
- mpatches
- seaborn
- plotly
- re

## Статус проекта
Завершен
