# javascript_foundation

Набор домашних заданий к курсу GeekBrains "Базовый курс JavaScript"

## Урок 1. Основы языка JavaScript

1. Задать температуру в градусах по Цельсию. Вывести в alert соответствующую температуру в градусах по Фаренгейту. Подсказка: расчет идет по формуле `Tf = (9 / 5) * Tc + 32`, где `Tf` — температура по Фаренгейту, `Tc` — по Цельсию.
1. Объявить две переменные: admin и name. Записать в name строку "Василий"; Скопировать значение из name в admin. Вывести admin (должно вывестись «Василий»).
1. Чему будет равно JS-выражение 1000 + "108"?
1. Самостоятельно разобраться с атрибутами тега script (async и defer).

## Урок 2. Основные операторы JavaScript

1. Дан код:
    ```
    var a = 1, b = 1, c, d;
    c = ++a; alert(c);           // 2
    d = b++; alert(d);           // 1
    c = (2+ ++a); alert(c);      // 5
    d = (2+ b++); alert(d);      // 4
    alert(a);                    // 3
    alert(b);                    // 3
    ```
    Почему код даёт именно такие результаты?
1. Чему будет равен x в примере ниже?
    ```
    var a = 2;
    var x = 1 + (a *= 2);
    ```
1. Объявить две целочисленные переменные a и b и задать им произвольные начальные значения. Затем написать скрипт, который работает по следующему принципу:
    * если a и b положительные, вывести их разность;
    * если а и b отрицательные, вывести их произведение;
    * если а и b разных знаков, вывести их сумму; ноль можно считать положительным числом. 
1. Присвоить переменной а значение в промежутке [0..15]. С помощью оператора `switch` организовать вывод чисел от a до 15. 
1. Реализовать основные 4 арифметические операции в виде функций с двумя параметрами. Обязательно использовать оператор `return`. 
1. Реализовать функцию с тремя параметрами: `function mathOperation(arg1, arg2, operation)`, где `arg1`, `arg2` – значения аргументов, `operation` – строка с названием операции. В зависимости от переданного значения операции выполнить одну из арифметических операций (использовать функции из пункта 3) и вернуть полученное значение (использовать `switch`). 
1. \* Сравнить null и 0. Попробуйте объяснить результат. 
1. \* С помощью рекурсии организовать функцию возведения числа в степень. Формат: `function power(val, pow)`, где `val` – заданное число, `pow` – степень.

## Урок 3. Циклы, массивы, структуры данных

1. С помощью цикла while вывести все простые числа в промежутке от 0 до 100.
1. С этого урока начинаем работать с функционалом интернет-магазина. Предположим, есть сущность корзины. Нужно реализовать функционал подсчета стоимости корзины в зависимости от находящихся в ней товаров.
1. Товары в корзине хранятся в массиве. Задачи:  
a) Организовать такой массив для хранения товаров в корзине;  
b) Организовать функцию countBasketPrice, которая будет считать стоимость корзины.
1. \* Вывести с помощью цикла for числа от 0 до 9, не используя тело цикла. Выглядеть это должно так:
    ```
    for(…){// здесь пусто}
    ```
1. \* Нарисовать пирамиду с помощью console.log, как показано на рисунке, только у вашей пирамиды должно быть 20 рядов, а не 5:
    ```
    x
    xx
    xxx
    xxxx
    xxxxx
    ```
    
## Урок 4. Объекты в JavaScript

1. Написать функцию, преобразующую число в объект. Передавая на вход число от 0 до 999, надо получить на выходе объект, 
в котором в соответствующих свойствах описаны единицы, десятки и сотни. Например, для числа 245 надо получить следующий 
объект: `{‘единицы’: 5, ‘десятки’: 4, ‘сотни’: 2}`. Если число превышает 999, необходимо выдать соответствующее сообщение 
с помощью console.log и вернуть пустой объект.
1. Продолжить работу с интернет-магазином: В прошлом домашнем задании вы реализовали корзину на базе массивов. 
Какими объектами можно заменить их элементы? Реализуйте такие объекты.
1. Перенести функционал подсчета корзины на объектно-ориентированную базу.
1. \* Подумать над глобальными сущностями. К примеру, сущность «Продукт» в интернет-магазине актуальна не только для 
корзины, но и для каталога. Стремиться нужно к тому, чтобы объект «Продукт» имел единую структуру для различных модулей 
сайта, но в разных местах давал возможность вызывать разные методы.
1. Для игры, реализованной на уроке, добавить возможность вывода хода номер n (номер задается пользователем)
1. \* На базе игры, созданной на уроке, реализовать игру «Кто хочет стать миллионером?»

## Урок 5. Введение в DOM

1. Создать функцию, генерирующую шахматную доску. При этом можно использовать любые html-теги по своему желанию. 
Доска должна быть разлинована соответствующим образом, т.е. чередовать черные и белые ячейки. 
Строки должны нумероваться числами от 1 до 8, столбцы – латинскими буквами A, B, C, D, E, F, G, H.
1. Заполнить созданную таблицу буквами, отвечающими за шахматную фигуру, например К – король, Ф – ферзь и т.п., 
причем все фигуры должны стоять на своих местах и быть соответственно черными и белыми.
1. \* Заменить буквы, обозначающие фигуры, картинками.

## Урок 6. Обработка событий в JavaScript

1. Доработать функцию замены картинки в галерее таким образом, чтобы она проверяла наличие картинки по указанному в src адресу.
1. Реализовать модуль корзины. Создать блок товаров и блок корзины. У каждого товара есть кнопка «Купить», при нажатии на которую происходит добавление имени и цены товара в блок корзины. Корзина должна уметь считать общую сумму заказа.
1. \* Добавить в галерею функцию перехода к следующему изображению. По сторонам от большой картинки должны быть стрелки «вперед» и «назад», по нажатию на которые происходит замена изображения на следующее или предыдущее.
