Итоговая проверочная работа Задача Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Пример: ["hello", "2","world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "long word"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []


Создали строковый массив длиной из 4 элементов. Потом метод, в котором цикл соответствующий  длине массива, внутри цикла проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива. Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.