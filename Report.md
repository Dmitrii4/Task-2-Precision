# Отчёт о тестировании кода "Bonus"

## Краткое описание 
При функциональном тестировании кода добавляющем дополнительные бонусы клиентам обнаружена неточность в сложении типов данных double.
Итоговая сумма вычислений имеет погрешность ниже ожидаемого значения.

## Описание тестов
Производилось функциональное тестирование.

## Дефекты
[Неточность в вычислениях сложения типа данных double](https://github.com/Dmitrii4/Task-2-Precision/issues/1)

## Общие рекомендации
Возможно выбран неподходящий тип данных, скорее всего более правилен тип данных Float. (Но тип данных float тоже имеет погрешность - 0.90000004)