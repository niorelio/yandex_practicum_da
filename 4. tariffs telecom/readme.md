# Определение перспективного тарифа для телеком компании

## Задача

На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа

## Ход работы

1. Предобработка данных:
- Изменили неподходящие форматы
- Нашли и удалили ошибочный столбец
- Вместо форматирования дат добавили столбец с месяцем.
2. Исследовательский анализ данных:
- Расчитали и добавили в таблицу данные для каждого пользователя по месяцам:
  - о количестве сделанных звонков и израсходованных минут,
  - о количестве отправленных сообщений,
  - об объеме израсходованного интернет-трафика,
  - помесячную выручку с каждого пользователя.
3. Проанализировали поведение пользователей на двух тарифах
4. Проверили гипотезы о различии средней выручки

## Используемые библиотеки
- pandas 
- numpy 
- matplotlib 
- datetime
- stats

## Статус проекта
Завершен

