# **FinalTask**

## Задача:

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

## Описание решения:

1. Вводим массив строк
2. Объявляеь счетчики для двух массивов
3. Запускаем первый цикл, проверяющий чтобы значение счетчика изначального массива было меньше длины этого массива. 
4. Если да, то запускаем второй цикл, проверяющий условие чтобы длина строки массива с текущим значением счетчика была меньше 3.
5. Если да значение первого массива с текущим значением счетчика i записывается в элемент второго массива с текущим значением счетчика j. 
6. После присвоения увеличивается переменная j на 1.
7. Возвращаемся к первому циклу, в котором i увеличивается на 1. 
8. И так проверяется до конца, после чего выводим второй массив.

## Графическое представление 
Алгоритм решения представлен в двух файлах diagram.drawio и diagram.drawio.png.

## Реализация алгоритма
Программа на С# представлена в файле FinalTask/Program.cs