**Задача**:

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

**Решение**:
1. Объявляем два массива: изначальный и вторый такой же длины. 
2. Пишем метод, в котором цикл соразмерный длине массива, проверяет условие ( <=3 ). Если да элемент первого массива заносится в count элемент второго массива. Переменная count нужна чтобы нужные данные переносить из первого массива во второй. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
3. Выводим данные второго массива.

Схема находится в файле 'shema control' в двух расширениях.