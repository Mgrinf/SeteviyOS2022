В данной программе демонстрируется динамическое выделение памяти для массива.

Алгоритм:
1. Пользователь вводит запрашиваемую длину массива.
2. Если введеное число больше нуля, то происходит выделение памяти с помощью функции *malloc*. При выделении памяти возвращается указатель, который будет равен NULL, если память не выделилась.
3. Eсли массив был инициализирован, то освобождаем выделенную память.

Запуск №1

`Enter length of array: 5 `

`Allocated 20 bytes `

Запуск №2

`Enter length of array: -10  `

`Error: can't allocate memory: Not enough space  `