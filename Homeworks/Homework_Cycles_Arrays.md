
Задание 1  
---  
Небоходимо создать программу, в которой будет происходить работа с матрицами.
В программе должны генерироваться две матрицы размерности 3x3, в которых каждый элемент - рандомное число в диапазоне от 0 до 10.
Далее выполняются операции, если они возможны:
1. Сложение исходных двух матриц, вывод исходных матриц и результата (normal)
2. Вычитание из первой исходной матрицы второй исходной матрицы, вывод исходных матриц и результата (normal)
3. Умножение первый матрицы на вторую, вывод исходных матриц и результата (hard)  


Советы и рекомендации к выполнению:  
* Материал о матрицах можно найти в интернете, проверять свои вычисления можно с помощью онлайн-калькулаторов  
* Для генерации рандомных чисел воспользуйтесь классом [Random](https://learn.microsoft.com/ru-ru/dotnet/api/system.random?view=netframework-4.8)  
* Для выполнения задания используйте массивы и циклы.  

Задание 2
---

Разработайте игру "угадай число" по следующему алгоритму:

1. Пользователь вводит максимальное целое число диапазона.
2. На основе диапазона целых чисел (от 0 до «введено пользователем») программа генерирует случайное целое число из диапазона. 
3. Пользователю предлагается ввести загаданное программой случайное число. Пользователь вводит свои предположения в консоли приложения. 
*  Если число меньше загаданного, программа сообщает об этом пользователю. 
*  Если больше, то тоже сообщает, что число больше загаданного.
6. Программа завершается, когда пользователь угадывает число. 
7. Если пользователь устал играть, то вместо ввода числа он вводит пустую строку и нажимает Enter.
 Тогда программа завершается, предварительно показывая, какое число было загадано.

Советы и рекомендации к выполнению:
* Чтобы организовать бесконечный ввод чисел и дать пользователю возможность вводить сколько угодно чисел, 
используйте цикл while или do while.
> Подсказка: Для выхода из цикла можно использовать оператор break, но есть и другой вариант.