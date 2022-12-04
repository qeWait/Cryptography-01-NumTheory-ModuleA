# Cryptography-01-NumTheory-ModuleA
 
Скрипт який виконує завдання: tasks.py

[x] задавати модуль m, за яким будуть вестись розрахунки
[x] розв’язувати рівняння виду  a mod m = x
[x] розв’язувати рівняння виду ab mod m = x
[x] розв’язувати рівняння виду  a*x ≡ b mod m
[x] * генерувати просте число у діапазоні від A до B.

Запускати файл з консолі, для того, щоб можна було ввести значення a, b та m

Скрипт tasks.py виконує всі завдання зазначені в документі

Для знаходження залишку за модулем використовується функція mod(). Приймає 2 аргументи. Першим аргументом приймає ціле число за яким потрібно знайти залишок від модуля, другим аргументом приймає ціле число яке є значенням модуля. Повертає залишок від ділення за модулем. Використовується в завданні 2, 3, 4

Для знаходження результату функції Ейлера, використовується функція euler(). Приймає один аргумент. Аргумент повинен бути цілим числом, який позначає останнє число діапазону для функції Ейлера. Повертає к-сть натуральних чисел в заданому діапазоні.Використовується в завданні 4

Для знаходження набору простих числе в діапазоні від а до b використовується функція prime_num(). Приймає 2 аргументи. Першим аргументом приймає ціле число, яке виступає в ролі початку діапазону. Другим аргументом приймає ціле число, яке виступає в ролі закінчення діапазону. Повертає список простих чисел. Використовується в завданні 5

Для отримання випадкового простого числа використовується функція choice() з бібліотеки random. Приймає 1 аргумент. Аргумент приймає список. Використовується в завданні 5, аргументом передається список згенерований функцією prime_num()