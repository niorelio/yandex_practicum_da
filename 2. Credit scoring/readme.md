# Исследование надёжности заёмщиков

## Задача

На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок

## Ход работы

1. В предобработке данных:
  * отработаны пропуски в данных, заполнены медианными значениями и предположены причины их появления,
  * заменены типы данных,
  * обработаны дубликаты,
  * выделены леммы в значениях столбца и категоризированны данные.
 2. Датасет депомпозирован на 3 по категорям: целей кредита, дохода, количества детей.
 3. Изучили зависимости между количеством детей, семейным положением, уровнем дохода, целями кредита и фактом возврата кредита в срок.

## Использованные библиотеки

* Pandas, 
* PyMystem3, 
* Collections

## Статус проекта
Завершен
