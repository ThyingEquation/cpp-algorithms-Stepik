**Решение задач, на языке C++, из двух курсов "Алгоритмы: теория и практика. Методы" и "Алгоритмы: теория и практика. Структуры данных" на образовательной платформе Stepik**
=====================

Условия задач взяты из материалов [Алгоритмы: теория и практика. Методы](https://stepik.org/course/217/info) и [Алгоритмы: теория и практика. Структуры данных](https://stepik.org/course/217/info). Данные задачи выполняюются путем консольного ввода (через cin) данных и оценкой выведенного результата через консоль (через cout). Тестовые входные данные с выходными данными, для каждой задачи, приведены в материалах курса. 

 ## :shipit: Оглавление: 
1. Алгоритмы: теория и практика. Методы :white_check_mark: (20/20)
   
:large_orange_diamond: [Небольшое число Фибоначчи](#1)

:large_orange_diamond: [Последняя цифра большого числа Фибоначчи](#2)

:large_orange_diamond: [Огромное число Фибоначчи по модулю](#3)

:large_orange_diamond: [Наибольший общий делитель](#4)

:large_orange_diamond: [Покрыть отрезки точками](#5)

:large_orange_diamond: [Непрерывный рюкзак](#6)

:large_orange_diamond: [Различные слагаемые](#7)

:large_orange_diamond: [Кодирование Хаффмана](#8)

:large_orange_diamond: [Декодирование Хаффмана](#9)

:large_orange_diamond: [Очередь с приоритетами](#10)

:large_orange_diamond: [Двоичный поиск](#11)

:large_orange_diamond: [Число инверсий](#12)

:large_orange_diamond: [Точки и отрезки](#13)

:large_orange_diamond: [Сортировка подсчётом](#14)

:large_orange_diamond: [Наибольшая последовательнократная подпоследовательность](#15)

:large_orange_diamond: [Наибольшая невозрастающая подпоследовательность](#16)

:large_orange_diamond: [Расстояние редактирования](#17)

:large_orange_diamond: [Рюкзак](#18)

:large_orange_diamond: [Лестница](#19)

:large_orange_diamond: [Калькулятор](#20)



**Алгоритмы: теория и практика. Методы**
=====================
 **Раздел 2. Введение: теория и задачи.** 
 -----------------------------------

 
 + ### ***Задача 2.1. Небольшое число Фибоначчи***  <a name="1"/>
   > ***Дано целое число 1 ≤ n ≤ 40, необходимо вычислить n число Фибоначчи.***

      Решение: [a_small_Fibonacci_number.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/Алгоритмы%20теория%20и%20практика.%20Методы/2.%20Введение.%20Теория%20и%20задачи/a_small_Fibonacci_number.cpp)

+  ### ***Задача 2.2. Последняя цифра большого числа Фибоначчи.*** <a name="2"/>
   > ***Дано число 1 ≤ n ≤ 10^7, необходимо найти последнюю цифру n-го числа Фибоначчи.***

   Решение: [the_last_digit_of_a_large_Fibonacci_number.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/2.%20Введение.%20Теория%20и%20задачи/the_last_digit_of_a_large_Fibonacci_number.cpp)

+  ### ***Задача 2.3. Огромное число Фибоначчи по модулю.*** <a name="3"/>
   > ***Даны целые числа 1 ≤ n ≤ 10^18 и 2 ≤ m ≤ 10^5, необходимо найти остаток от деления n-го числа Фибоначчи на m.***
   
    Решение: [a_huge_Fibonacci_number_modulo.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/2.%20Введение.%20Теория%20и%20задачи/a_huge_Fibonacci_number_modulo.cpp)

+ ### ***Задача 2.4. Наибольший общий делитель.*** <a name="4"/>
   > ***По данным двум числам 1 ≤ a, b ≤ 2⋅10^9, найдите их наибольший общий делитель.***
   
   Решение: [greatest_common_divisor.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/2.%20Введение.%20Теория%20и%20задачи/greatest_common_divisor.cpp)




**Раздел 4. Жадные алгоритмы: теория и задачи.** 
 -----------------------------------
 + ### ***Задача 4.1. Покрыть отрезки точками.*** <a name="5"/>
   > ***По данным n отрезкам необходимо найти множество точек минимального размера, для которого каждый из отрезков содержит хотя бы одну из точек. В первой строке дано число 1 ≤ n ≤ 100  отрезков. Каждая из последующих n строк содержит по два числа 0 ≤ l < r ≤ 10^9, задающих начало и конец отрезка. Выведите оптимальное число m точек и сами m точек. Если таких множеств точек несколько, выведите любое из них.***

   Решение: [points_on_the_segment.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/4.%20Жадные%20алгоритмы.%20теория%20и%20задачи/points_on_the_segment.cpp)

 + ### ***Задача 4.2. Непрерывный рюкзак.*** <a name="6"/>
   > ***Первая строка содержит количество предметов 1 ≤ n ≤ 10^3 и вместимость рюкзака 0 ≤ W ≤ 2⋅10^6. Каждая из следующих n строк задаёт стоимость 0 ≤ ci ≤ 2⋅10^6 и объем 0 < wi ≤ 2⋅10^6 предмета (n, W, ci, wi - целые числа). Выведите максимальную стоимость частей предметов (от каждого предмета можно отделить любую часть, стоимость и объём при этом пропорционально уменьшатся), помещающихся в данный рюкзак, с точностью не менее трёх знаков после запятой.***

   Решение: [continuous_backpack.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/4.%20Жадные%20алгоритмы.%20теория%20и%20задачи/continuous_backpack.cpp)

 + ### ***Задача 4.3. Различные слагаемые.*** <a name="7"/>
   > ***По данному числу 1 ≤ n ≤ 10^9 найдите максимальное число k, для которого n можно представить как сумму k различных натуральных слагаемых. Выведите в первой строке число k, во второй — k слагаемых.***

   Решение: [various_summand.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/4.%20Жадные%20алгоритмы.%20теория%20и%20задачи/various_summand.cpp)

 + ### ***Задача 4.4. Кодирование Хаффмана.*** <a name="8"/>
   > ***По данной непустой строке s длины не более 10^4, состоящей из строчных букв латинского алфавита, постройте оптимальный беспрефиксный код. В первой строке выведите количество различных букв k, встречающихся в строке, и размер получившейся закодированной строки. В следующих k строках запишите коды букв в формате "letter: code". В последней строке выведите закодированную строку.***

   Решение: [huffman_coding.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/4.%20Жадные%20алгоритмы.%20теория%20и%20задачи/huffman_coding.cpp)

 + ### ***Задача 4.5. Декодирование Хаффмана.*** <a name="9"/>
   > ***Восстановите строку по её коду и беспрефиксному коду символов. В первой строке входного файла заданы два целых числа k и l через пробел — количество различных букв, встречающихся в строке, и размер получившейся закодированной строки, соответственно. В следующих k строках записаны коды букв в формате "letter: code". Ни один код не является префиксом другого. Буквы могут быть перечислены в любом порядке. В качестве букв могут встречаться лишь строчные буквы латинского алфавита; каждая из этих букв встречается в строке хотя бы один раз. Наконец, в последней строке записана закодированная строка. Исходная строка и коды всех букв непусты. Заданный код таков, что закодированная строка имеет минимальный возможный размер. В первой строке выходного файла выведите строку s. Она должна состоять из строчных букв латинского алфавита. Гарантируется, что длина правильного ответа не превосходит 10^4 символов.***

   Решение: [huffman_decoding.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/4.%20Жадные%20алгоритмы.%20теория%20и%20задачи/huffman_decoding.cpp)

 + ### ***Задача 4.6. Очередь с приоритетами.*** <a name="10"/>
   > ***Первая строка входа содержит число операций 1 ≤ n ≤ 10^5. Каждая из последующих n строк задают операцию одного из следующих двух типов: Insert x, где 0 ≤ x ≤ 10^9 — целое число; ExtractMax. Первая операция добавляет число x в очередь с приоритетами, вторая — извлекает максимальное число и выводит его.***

   Решение: [priority_queue.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/4.%20Жадные%20алгоритмы.%20теория%20и%20задачи/priority_queue.cpp)




**Раздел 6. "Разделяй и властвуй": теория и задачи.** 
 -----------------------------------
 + ### ***Задача 6.1. Двоичный поиск.*** <a name="11"/>
   > ***В первой строке даны целое число 1 ≤ n ≤ 10^5 и массив A[1 … n] из n различных натуральных чисел, не превышающих 10^9, в порядке возрастания, во второй — целое число 1 ≤ k ≤ 10^5 и k натуральных чисел b1 ,…, bk, не превышающих 10^9. Для каждого i от 1 до k необходимо вывести индекс 1 ≤ j ≤ n, для которого A[j] = bi, или −1, если такого j нет.***

   Решение: [binary_search.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/6.%20Разделяй%20и%20властвуй.%20Теория%20и%20задачи/binary_search.cpp)

 + ### ***Задача 6.2. Число инверсий.*** <a name="12"/>
   > ***Первая строка содержит число 1 ≤ n ≤ 10^5, вторая — массив A[1 … n], содержащий натуральные числа, не превосходящие 10^9. Необходимо посчитать число пар индексов 1 ≤ i < j ≤ n, для которых A[i] > A[j]. (Такая пара элементов называется инверсией массива. Количество инверсий в массиве является в некотором смысле его мерой неупорядоченности: например, в упорядоченном по неубыванию массиве инверсий нет вообще, а в массиве, упорядоченном по убыванию, инверсию образуют каждые два элемента.)***

   Решение: [number_of_inversions.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/6.%20Разделяй%20и%20властвуй.%20Теория%20и%20задачи/number_of_inversions.cpp)

 + ### ***Задача 6.3. Точки и отрезки.*** <a name="13"/>
   > ***В первой строке задано два целых числа 1 ≤ n ≤ 50000 и 1 ≤ m ≤ 50000 — количество отрезков и точек на прямой, соответственно. Следующие n строк содержат по два целых числа ai и bi ai ≤ bi) — координаты концов отрезков. Последняя строка содержит m целых чисел — координаты точек. Все координаты не превышают 10^8 по модулю. Точка считается принадлежащей отрезку, если она находится внутри него или на границе. Для каждой точки в порядке появления во вводе выведите, скольким отрезкам она принадлежит.***

   Решение: [points_and_segments.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/6.%20Разделяй%20и%20властвуй.%20Теория%20и%20задачи/points_and_segments.cpp)

 + ### ***Задача 6.4. Сортировка подсчётом.*** <a name="14"/>
   > ***Первая строка содержит число 1 ≤ n ≤ 10^4, вторая — n натуральных чисел, не превышающих 10. Выведите упорядоченную по неубыванию последовательность этих чисел.***

   Решение: [sorting_by_counting.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/6.%20Разделяй%20и%20властвуй.%20Теория%20и%20задачи/sorting_by_counting.cpp)




 **Раздел 8. Динамическое программирование.** 
 -----------------------------------
 +  ### ***Задача 8.1. Наибольшая последовательнократная подпоследовательность.*** <a name="15"/>
    > ***Дано целое число Дано целое число 1 ≤ n ≤ 10^3 и массив A[1 … n] натуральных чисел, не превосходящих 2⋅10^9. Выведите максимальное 1 ≤ k ≤ n, для которого найдётся подпоследовательность 1 ≤ i1 ​< i2 ​< … < ik ​≤ n длины k, в которой каждый элемент делится на предыдущий (формально: для всех 1 ≤ j < k, A[ij] A[ij+1]).***

    Решение: [the_greatest_sequencefold_subsequence.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/8.%20Динамическое%20программирование/the_greatest_sequencefold_subsequence.cpp)

 + ### ***Задача 8.2. Наибольшая невозрастающая подпоследовательность.*** <a name="16"/>
   > ***Дано целое число 1 ≤ n ≤ 10^5 и массив A[1 … n], содержащий неотрицательные целые числа, не превосходящие 10^9. Найдите наибольшую невозрастающую подпоследовательность в A. В первой строке выведите её длину k, во второй — её индексы 1 ≤ i1 < i2 < … < ik ≤ n (таким образом, A[i1] ≥ A[i2] ≥ … ≥ A[in]).***

    Полезная [информация](https://e-maxx.ru/algo/longest_increasing_subseq_log) по задаче.
    Решение: [the_greatest_increasing_subsequence.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/8.%20Динамическое%20программирование/the_greatest_increasing_subsequence.cpp)

 +  ### ***Задача 8.3. Расстояние редактирования.*** <a name="17"/>
    > ***Вычислите расстояние редактирования двух данных непустых строк длины не более 10^2, содержащих строчные буквы латинского алфавита.***

    Решение: [editing_distance.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/8.%20Динамическое%20программирование/editing_distance.cpp)

 +  ### ***Задача 8.4. Рюкзак.*** <a name="18"/>
    > ***Первая строка входа содержит целые числа 1 ≤ W ≤ 10^4 и 1 ≤ n ≤ 300 — вместимость рюкзака и число золотых слитков. Следующая строка содержит n целых чисел 0 ≤ w1 ,…, wn ≤ 10^5, задающих веса слитков. Найдите максимальный вес золота, который можно унести в рюкзаке.***

    Решение: [backpack.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/8.%20Динамическое%20программирование/backpack.cpp)

 +  ### ***Задача 8.5. Лестница.*** <a name="19"/>
    > ***Даны число 1 ≤ n ≤ 10^2 ступенек лестницы и целые числа −10^4 ≤ a1 ,…, an ≤ 10^4, которыми помечены ступеньки. Найдите максимальную сумму, которую можно получить, идя по лестнице снизу вверх (от нулевой до n-й ступеньки), каждый раз поднимаясь на одну или две ступеньки.***

    Решение: [stairs.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/8.%20Динамическое%20программирование/stairs.cpp)

 +  ### ***Задача 8.6. Калькулятор.*** <a name="20"/>
    > ***У вас есть примитивный калькулятор, который умеет выполнять всего три операции с текущим числом x: заменить x на 2x, 3x или x + 1. По данному целому числу 1 ≤ n ≤ 10^5 определите минимальное число операций k, необходимое, чтобы получить n из 1. Выведите k и последовательность промежуточных чисел.***

    Решение: [calculator.cpp](https://github.com/ThyingEquation/cpp-algorithms-Stepik/blob/main/8.%20Динамическое%20программирование/calculator.cpp)




**Алгоритмы: теория и практика. Структуры данных.**
=====================
 **Раздел 1. Базовые структуры данных.** 
 -----------------------------------

 
 + ### ***Задача 1.1. Расстановка скобок в коде.***  <a name="21"/>
   > ***Проверить, правильно ли расставлены скобки в данном коде.***

      Решение: [placing_pare_theses_in_the_code.cpp](sssss)

 + ### ***Задача 1.2. Высота дерева.***  <a name="22"/>
   > ***Вычислить высоту данного дерева.***

      Решение: [height_of_the_tree](sssss)

 + ### ***Задача 1.3. Симуляция обработки сетевых пакетов.***  <a name="23"/>
   > ***Реализовать обработчик сетевых пакетов.***

      Решение: [simulation_of_network_packet_processing](sssss)

 + ### ***Задача 1.4. Стек с поддержкой максимума.***  <a name="24"/>
   > ***Реализовать стек с поддержкой операций push, pop и max.***

      Решение: [stack_with_maximum_support](sssss)

 + ### ***Задача 1.5. Максимум в скользящем окне.***  <a name="25"/>
   > ***Найти максимум в каждом окне размера m данного массива чисел A[1 ... n].***

      Решение: [maximum_in_the_sliding_window](sssss)

 
