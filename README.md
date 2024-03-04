ЗАДАЧА 3 ТЕСТОВОГО КОНТЕСТА OZON TECHPOINT ЯНВАРЬ 2024

** АВТОМОБИЛЬНЫЕ НОМЕРА **

Условия задачи:
В Берляндии автомобильные номера состоят из цифр и прописных букв латинского алфавита.
Они бывают двух видов:
- либо автомобильный номер имеет вид - буква − цифра − цифра − буква − буква - (примеры корректных номеров первого вида: R48FA O00OO A99OK);
- либо автомобильный номер имеет вид - буква − цифра − буква − буква - (примеры корректных номеров второго вида: T7RR A9PQ O0OO).

Таким образом, каждый автомобильный номер является строкой либо первого, либо второго вида.

Вам задана строка из цифр и прописных букв латинского алфавита. Можно ли разделить её пробелами на последовательность корректных автомобильных номеров?
Иными словами, проверьте, что заданная строка может быть образована как последовательность корректных автомобильных номеров, которые записаны подряд без пробелов.
В случае положительного ответа выведите любое такое разбиение.


** ВЫХОДНЫЕ ДАННЫЕ **

В первой строке записано целое число t(1 <= t <= 1000) - количество наборов входных данных в тесте.

Наборы входных данных в тесте независимы. Друг на друга они никак не влияют.

Каждый набор входных данных — непустая строка s, которая состоит из цифр и прописных букв латинского алфавита. Длина строки — от 1 до 50 символов.


** ВЫХОДНЫЕ ДАННЫЕ **

Выведите n строк: очередная строка должна содержать ответ для соответствующего набора входных данных.

Если ответ отрицательный — то есть заданную строку s невозможно представить как последовательность номеров автомобилей — строка в выводе должна содержать единственный символ ''-'' (минус, ASCII-код 45).
В случае положительного ответа выведите любое разбиение заданной строки s на последовательность корректных номеров.
Каждый номер должен соответствовать одному из двух видов (см. условие). Номера разделяйте пробелами.
Вы можете выводить произвольное количество пробелов и даже лишние пробелы после последнего номера.

ПРИМЕР ТЕСТА 1:

Входные данные:
- 6
- R48FAO00OOO0OOA99OKA99OK
- R48FAO00OOO0OOA99OKA99O
- A9PQ
- A9PQA
- A99AAA99AAA99AAA99AA
- AP9QA

Выходные данные:
- R48FA O00OO O0OO A99OK A99OK
- '-'
- A9PQ
- '-'
- A99AA A99AA A99AA A99AA
- '-'
