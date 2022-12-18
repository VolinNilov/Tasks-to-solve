# Tasks-to-solve
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**Первое занятие**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

Не решаем
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
## #1
Дан текст, состоящий из слов, знаков препинания и других символов. Словом  в тексте считается последовательность символов из прописных и строчных букв латинского алфавита. Требуется перевернуть (записать в обратном порядке) все слова текста, оставив знаки препинания и другие символы, включая буквы русского алфавита, без изменений. В строке не более 255 символов, строк в файле не более 1000.

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|This   is an example. Prim333primяяrt | sihT   si na elpmaxe. mirP333mirpяяtr|

Не решаем
-----------------------------------------------------------------------------------------------------------------------------------------------------------------


## #2 "Карты"

Евгений продолжает набирать опыт в разработке и теперь пишет компьютерную игру в жанре «Квест», однако не все идет гладко. Основную часть игры составляет участие персонажа в различных диалогах, но для того, чтобы диалоги выглядели красиво, нужно правильно подбирать окончания у существительных. Например: 
1 карта, 2 карты, 5 карт и т. д. Помогите Евгению решить данную проблему.

**Входные данные**

В единственной строке задается одно целое число n (1 ≤ n ≤ 100).

**Выходные данные**

Выведите число n и правильно подобранное слово (латиницей), в зависимости от n. Разделите число и слово пробелом.

**Примеры**

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|           1            |        1 karta         |
|           2            |        2 karty         |
|           5            |        5 kart          |



## #3 "Работа"

Набравшись опыта, Евгений решил найти себе хорошую работу в игровой индустрии. На данный момент есть три вакансии, каждая из которых характеризуется длительностью рабочего дня Ti часов и размером зарплаты Si. Для Евгения оптимальные условия работы — длительность рабочего дня не более 8 часов или зарплата не менее 5000*Ti.
Определите, какие вакансии подойдут Евгению.

**Входные данные**

Ввод состоит из трех строк — описание вакансий. Каждая из трех строк содержит два целых числа Ti и Si * ( 0 ≤ Ti ≤ 24, 0 ≤ Si ≤ 10^6).

**Выходные данные**

Выведите целое число x — количество подходящих вакансий. Затем выведите x чисел — номера подходящих вакансий. Вы можете выводить номера вакансий в любом порядке. Вы можете разделять числа пробелами или переводами строк.

**Примеры**

|   Входные данные       |     Выходные данные    |
|:----------------------:|:----------------------:|
|    3 500               |         3              |
|    7 3000              |         1 2 3          |
|    9 50000             |                        |

|   Входные данные       |     Выходные данные    |
|:----------------------:|:----------------------:|
|    1 5000             |         2               |
|    17 8000            |         1 3             |
|    19 340000          |                         |

|   Входные данные       |     Выходные данные    |
|:-----------------------:|:---------------------:|
|     12 100             |         0              |
|     13 200             |                        |
|     14 300             |                        |


## #4 "Нечетная прогрессия"

Было записано n подряд идущих нечетных чисел. Сумма всех выписанных чисел равнялась s. По заданным значениям n и s определите выписанные числа.

**Входные данные**

В единственной строке задаются два целых числа n и s (1 ≤ n, s ≤ 2000). Гарантируется, что для заданных n и s ответ существует.

**Выходные данные**

Выведите n исходных чисел в порядке возрастания. Вы можете разделять числа пробелами или переводами строк.

**Примеры:**

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|         5 35           |       3 5 7 9 11       |

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|        1 49            |           49           |



## #5 "Количество четных элементов последовательности"

Робот «Jarvise» принимает на вход целые числа и записывает их в последовательность. «Jarvise» заканчивает работу когда получает на вход число 0 (0 — признак окончания ввода, не входит в последовательность). Определите количество четных положительных чисел после завершения работы «Jarvise».

**Входные данные**

Очередное число a для робота задается в отдельной строке (−10^9 ≤ a ≤ 10^9). Гарантируется, что 0 встречается как минимум один раз. Гарантируется, что длина полученной последовательности не превосходит 10^5.

**Выходные данные**

Выведите одно целое число n — количество четных положительных чисел в последовательности.

**Примеры**

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|           1            |            1           |
|           2            |                        |
|           -4           |                        |
|           0            |                        |
|           5            |                        |

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|           0            |            0           |
|           2            |                        |
|           4            |                        |


## #6 "Необычные часы"

Инна любит необычные вещи. Недавно она увидела в магазине часы, на которых вместо циферблата была изображена координатная плоскость с отмеченными на ней точками. Чтобы определить время, нужно посчитать количество точек в каждой из четвертей. Предположим, что получились следующие результаты:

2  точки в I (правой верхней) четверти,
0  точек во II (левой верхней) четверти,
3  точки в III (левой нижней) четверти,
4  точки в IV (правой нижней) четверти.

Это значит, что часы показывают 
02 часа 34 минуты. Помогите Инне определить текущее время по заданным координатам точек или сообщите о том, что часы неисправны. Часы неисправны только в том случае, если показываемое ими время не входит в промежуток от 00 часов 00 минут до 23 часов 59 минут.

**Входные данные**

В первой строке задается одно целое число n (0 ≤ n ≤ 50) — количество точек. Далее следует n строк. Каждая строка содержит два целых числа Xi, Yi (−100 ≤ Xi, Yi ≤ 100) — координаты очередной точки. Гарантируется, что точки не лежат на координатных осях. Гарантируется, что координаты всех точек различны.

**Выходные данные**

Если часы неисправны, выведите Broken. Иначе выведите два целых числа: количество часов и количество минут. Выводите часы и минуты в формате ЧЧ ММ. Всегда выводите по две цифры, даже если старшая из них равна 0.

**Примеры**

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|           9            |         02:34          |
|           1 1          |                        |
|           2 2          |                        |
|           -3 -1        |                        |
|           -2 -2        |                        |
|           -1 -3        |                        |
|           1 -1         |                        |
|           1 -2         |                        |
|           2 -1         |                        |
|           2 -2         |                        |

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|           6            |        21:21           |
|           -1 1         |                        |
|           -1 2         |                        |
|           -1 -3        |                        |
|           1 1          |                        |
|           -1 -1        |                        |
|           1 -1         |                        |

**Примечание**
Первый пример представлен на картинке. 2 точки в I четверти изображены фиолетовым цветом, 3 точки в III четверти — зеленым, 4 точки в IV четверти — красным.

Картинка: https://statement.bacs.cs.istu.ru/statement/get/CjZiYWNzL3Byb2JsZW0vc2Nob29sXzdfNl81X2JjL3N0YXRlbWVudC92ZXJzaW9ucy9DL2h0bWwSBgoEOhAA_w/bacs/joNyJkpzGs15Djfsqo0zg7S1k_T3JZ_okcBDmKO3JM_LOoV9M753s0InveCQVhqm8fvC3603R9duT_4Reg48eMYTvKqRHcCiQKQYuRetaPSYdcsvhtpJArZJqZS2zx7ngwhsrWAgrhi2wPK3ChqaALjDhXw92SfYCJW7-pPrAwKVj1PfDnHwcYQ48vyhctHgr6CtEkqNwN01EK7gGHJ1xkSEuI6zu5ksT229H1VUSpKBJWGDTojMchbXfuFxL-3r_C3LdD-PeuN2onk8S5R0cxy-ELiDoR1WqU7tdl3PuGokDjtrv9b8ZxWt2ZcQG024naLEZpExPDmc-o4GwMC7kg/clockexample.png




-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**Второе занятие**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

## #1 "Калькулятор"

Давайте поупражняемся в математике и напишем простой калькулятор, который выполняет несколько базовых математических функций: 
1. Сложение: +
2. Вычитание: -
3. Умножение: *
4. Деление: /
5. Взятие остатка от деления: %
6. Возведение в степень: ^


Для Вашего удобства ниже приведены примеры операций и если а = 7, и b = 3, то:
1. a + b = какое-то число; 
   7 + 3 = 10
2. a - b = какое-то число; 
   7 - 3 = 4
3. a * b = какое-то число;
   7 * 3 = 21
4. a / b = какое-то число;
   7 / 3 = 2.333
5. a % b = какое-то число
   7 % 3 = 1
6. a ^ b = какое-то число
   7 ^ 3 = 7 * 7 * 7 = 343

**Примечание**

Для реализации возведения числа в степень, необходимо подключить библиотеку `#include <cmath>` и использовать функцию `pow(a, b)`.

   
## #2 "Циферблат" 

На циферблате записана последовательность чисел в двоичной системе счисления. Линии разбиения могут проходить как между числами, так и между цифрами одного числа, разбивая его на два или больше чисел. Для каждого сектора можно посчитать сумму чисел, которые в нем расположены.

https://statement.bacs.cs.istu.ru/statement/text_get/cGFja2FnZTogJ2JhY3MvcHJvYmxlbS8xMDE3L3N0YXRlbWVudC92ZXJzaW9ucy9DL2h0bWwnIHJldmlzaW9uOiB7IHZhbHVlOiAiXFxcMjYzXDMzNXQiIH0/bacs.legacy/63rEJJsLrtXp89-Oq5vcPpbUp2DZUMlw7hE3CytPRzviBd9eYg5chW66Jx-LFVDDd3ycmE229ZG1GhPbkz-_pfFKRA-KQw6rNohErUHM9Tb-sGXITvmnezB7sQPiYJy7IvfbuLLcikNrM5twADGultoPDvhlWOjJEkQewzD5a8N2_l7Gh5Qf3c0M_Hs4q3oEusSx_VDXsD0QMRB5MZnKjpbqpYTIenOoPqDHAomw5_xNRj8t4CKK0rQX_LyBa1p43Q_evG5qBHYY83W7FYhq3JuEK0LlvQkWLiT7kTWii7-D2krGrsbadRvOnSX8WXmy6uHuDxIzN-lVJAQi4O4b0w/task1400.gif

Каждое число в последовательности не равно 0, и его запись начинается с единицы. Количество цифр в двоичной записи числа не превышает 25. Общее количество цифр на циферблате не больше чем 100.

Циферблат может быть разбит на сектора. На рисунке изображен привычный нам циферблат с числами от 1 до 12 (в немного непривычном виде). Он разбит на 4 сектора. Суммы в секторах будут 1, 15, 18 и 36.

**Задача**
   
Напишите программу, которая по заданной последовательности определяет количество разных разбиений циферблата на сектора, таких что сумма чисел во всех секторах одинакова.

**Входные данные**
   
В единственной строке входного файла DIAL.DAT задана последовательность чисел. Числа последовательности разделены пробелом.

**Пример входных данных**
   
101 1 1101

**Выходные данные**
   
В единственной строке выходного файла DIAL.SOL должно находиться натуральное число — количество искомых разбиений циферблата на сектора.

**Пример выходных данных**
   
9


## #3 "Протокол печати"

В Московском Институте Оптимизаций (МИО) был разработан новый протокол, который используется для передачи данных на принтер. Согласно этому протоколу в режиме печати текстовых файлов принтер «понимает» три команды:
  1. Letter(‘<символ>’) – печатает символ, указанный в скобках.
  2. Repeat(<число>) – повторяет печать последних N символов, где N – число, указанное в скобках.
  3. End – завершает печать файла.
Ваша задача заключается в том, чтобы написать программу, которая получая на входе строку символов оптимальным образом составляет программу для печати этой строки (оптимальным образом – значит программа должна содержать минимально возможное количество команд).

**Формат входных данных**
   
В первой строке входного файла содержится строка, которую нужно напечатать. Эта строка может содержать любые символы, ASCII коды которых не меньше 32. Длина строки не превосходит 5000 символов.

**Формат выходных данных**
   
В первой строке выходного файла должно содержаться единственное число – общее количество команд в получившейся программе. Далее должны идти сами команды – по одной команде в каждой строчке. В конце каждой команды кроме последней должен содержаться символ «;» (точка с запятой), а после последней команды должен идти символ «.» (точка).

**Пример**
   
|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|      BABBAABBAB        |     8                  |
|                        |     Letter('B');       | 
|                        |     Letter('A');       |
|                        |     Letter('B');       |
|                        |     Letter('B');       |
|                        |     Letter('A');       |
|                        |     Repeat(4);         |
|                        |     Letter('B');       |
|                        |     End.               |

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|          word          |     5                  |
|                        |     Letter('w');       | 
|                        |     Letter('o');       |
|                        |     Letter('r');       |
|                        |     Letter('d');       |
|                        |     End.               |


## #4 "Дроби"

В одной удаленной галактике давным давно люди еще не умели использовать позиционные системы счисления и натуральные дроби. Для представления чисел в диапазоне от 0 до 1 они использовали его разложение в сумму обратных натуральным числам. Дробь p/q представлялась в виде суммы 1/q1+…+1/qn, причем знаменатели дробей были попарно различны: qi <> qj, если i<>j. Для данной натуральной дроби найдите ее разложение согласно системе жителей удаленной галактики.

**Входные данные**

На входе задается два целых числа p и q такие, что 0 < p < q < 100. Каждое число задается в отдельной строке без пробелов в начале и конце строки.

**Выходные данные**

Напечатайте последовательность искомых натуральных чисел q1, …, qn в порядке возрастания. Каждое число размещается на отдельной строке без пробелов в начале и конце строки.

**Примеры**
                                                                   
|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|          2 3           |          2 6           | 

|    Входные данные      |     Выходные данные    |
|:----------------------:|:----------------------:|
|          1 7           |           7            | 


## #5 "Бета-тестирование"

Девятиклассник Вася Пупкин, несмотря на свою молодость, получил широкую известность как классный бета-тестер, и поэтому он завален предложениями от различных программистских команд. К сожалению, его молодость мешает ему правильно распределить свои силы и отказаться от некоторых предложений, какими бы заманчивыми они не казались: Ваша задача - помочь Васе определиться с выбором. Итак, Васе предложено для тестирования N программ (1 <= N <= 1000). Он знает, что для тестирования i-й программы (i=1, 2, ... , N) ему потребуется ti дней. Кроме того, он не может работать над несколькими проектами одновременно, и, закончив тестирование одной программы, приступает к работе над другой не раньше следующего дня. Сегодня Вася отдыхает, ожидая Вашего решения: С другой стороны, авторы программ ставят жесткие условия - работа над i-й программой должна быть завершена через Di дней, начиная с сегодняшнего. Например, если тестирование надо завершить послезавтра, то Di = 2. Вы должны отвергнуть минимальное число предложений, чтобы не затянуть сроки сдачи остальных проектов, а также составить для Васи одну из возможных последовательностей выполнения оставшихся заказов. Входные данные находятся в текстовом файле TESTER.IN и состоят из нескольких строк. Первая строка содержит десятичную запись числа N. Каждая из последующих N строк содержит значения ti и Di (1 <= ti <= Di <= 1000), разделенные пробелами. Выходные данные помещаются в текстовый файл TESTER.OUT. Первая строка этого файла содержит число отвергнутых предложений. Последующие строки содержат номера проектов (по одному в строке), которые Вася будет выполнять, а порядок следования этих номеров соответствует порядку выполнения заказов.

**Пример входных данных**
   
4   
2 4   
5 15   
20 30   
5 10
   

**Пример выходных данных**
   
1   
1   
4   
2


## #6 "Кубики"

Трехмерная фигура состоит из единичных кубиков. По фигуре можно построить ее фронтальную и правую проекции. Очевидно, что по этим двум проекциям не всегда можно восстановить фигуру.

https://statement.bacs.cs.istu.ru/statement/text_get/cGFja2FnZTogJ2JhY3MvcHJvYmxlbS8xMDE4L3N0YXRlbWVudC92ZXJzaW9ucy9ydS9odG1sJyByZXZpc2lvbjogeyB2YWx1ZTogInNcMjI1XDMzN1wyMTQiIH0/bacs.legacy/DQ9nZMIGcuPwpFgGVSqy5vwuxOAM7nxcF5KwfjHazKQRoA9NcB5FWBzPzpiVmNg8PojQ3Pc3sRlKyePd_R8rWfDgfdkBd12pGl3njzFqOQElcYLDgF1aGHjiCQzbIk2WW1XDYkWHC5Bf_WL8mcAClFVQFhvKunY608fAS8d6Rby0vPJQdJvonbKqvsjv_xncro29nPzn5JHHD0sDSH4MAqbQH2FlhTRESvYjpm5htOtmFZybcl8Oqi_BnXZFbzXPUeATSs_C9H00LN0cyKqXbazbS9DmmgoPfWNfAgOxchDoBmDphthQytx4geVKm9q2UG3NTWWz52gz9b9a9Z7Thg/task2100.gif

**Задача**
   
Напишите программу CUBES, которая получает на вход фронтальную и правую проекции фигуры и определяет минимальное и максимальное количество кубиков, которое можно было бы использовать для построения фигуры с заданными проекциями.

**Входные данные**
   
В первой строке входного файла CUBES.DAT находятся три числа N, M и К, которые задают размеры проекций (1£N, M, K£100). Дальше задаются две проекции: сначала фронтальная, а затем правая. Проекция задается N строками, каждая из которых состоит из чисел 0 и 1, разделенных пробелами. Для фронтальной проекции таких чисел будет M, а для правой —K. 0 означает свободную клетку проекции, 1 — заполненную.

**Пример входных данных**
   
2 2 3  
1 0  
1 1  
0 0 1 
1 1 1
   

**Выходные данные**
   
В единственной строке выходного файла CUBES.SOL должно находиться два числа: минимальное и максимальное число кубиков, которые можно было бы использовать для построения фигуры с заданными проекциями.

**Пример выходных данных**
   
4 7
   
   
   
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**Третье занятие**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
## #1 "Файл записанный дважды"

Текстовый файл "task_1.txt" (скачать можно выше) содержит произвольные слова на английском языке, по 1 слову в строке, не более 40 слов в файле, длина слова ограничена 80 символами.

**Задача**
Переписать все данные из одного файла в другой, а затем пропустив 2 строчки, продублировать эти же данныее.


## #2 "Исчезающая строка"

Задана строка s произвольного размера. Реализовать подпрограмму удаления символов из строки, начиная с символа номер n (n ≥ 0) до символа номер k включительно (k ≥ n).

**Входные данные**
В первой строке вводятся 2 числа: n - начиная с какого символа строки необходимо удалять символы, m - до какого символа строки необходимо удалять символы. В следующей сроке дана строка произвольного размера, которую необходимо отсортировать. В третьей строке идут символы, которые необходимо идалить (длина строки символов, которые необходимо удалить не превышает размера основной строки).

**Выходные данные**
Необходимо вывести на экран "отредактированную строку" в промежутке [n, m], удалив необходимые нам символы.

**Simple Input**
3 35
helloworld!!!mynameisearth!andilikeyou
!lrmi

**Simple Output**
helowordynaeseathandkeyou


**Simple Input**
0 43
i'dreallyliketoseeyouhereandicocongratulationstoyou
lar'es


## #3 "Цифры в файле"

Необходимо ввести цифры через командную строку и записать их в файл "numbers.txt", каждое число с новой строки, далее необходимо вывести из этого файла данные на экран. 

Повышаем градус:
Необходимо сделать всё тоже самое, но числа по-мимо того, что необходимо вывести, необходимо сложить между собой и также вывести на экран, пропустив одну строку (поставить строку-пробел между данными).


## #4 "Самый частый символ"

Определить, какой символ чаще других встречается в данном файле. Данные вводим самостоятельно и записываем в файл.


## #5 "Фибоначи в файле"

В файле записана непустая последовательность целых чисел, являющихся числами Фибоначчи. Приписать еще n чисел Фибоначчи. Число n спросить у пользователя (предварительно сообщив, сколько чисел уже имеется в файле).
