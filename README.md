# perceptron-nand
# Перцептрон: Логическая функция NAND

Проект показывает, как однослойный перцептрон реализует функцию **NAND** (не-И).

## Что такое NAND

NAND = NOT(AND). Возвращает 1 везде, кроме [1, 1].

| Вход 1 | Вход 2 | Выход |
|--------|--------|--------|
|   0    |   0    |   1    |
|   0    |   1    |   1    |
|   1    |   0    |   1    |
|   1    |   1    |   0    |

Интересно: из NAND можно собрать любые логические функции.

## Как работает

- Классический перцептрон
- Обучается на данных для NAND
- Предсказывает результат на всех комбинациях

## Как запустить

1. Открыть `nand_perceptron.py`
2. Запустить
3. Получить результат