# Задача
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа (первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма).
*При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

## Описание алгоритма решения:
1. Сначало объявляется два массива: изначальный и вторый такой же длины.
2. Потом метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива. Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов.
3. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.