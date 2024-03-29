## Задание 1

Используя класс ```SpaceObject```, создайте класс ```Planet``` с аттрибутом ```Population```.
Создайте объект ```Earth``` и заселите его животными.
Для этого создайте родительский класс ```Animal```, и унаследуйте от него 3 класса разных животных. 
Каждому классу присвойте несколько атрибутов и, как минимум, один метод.
Затем создайте несколько объектов классов ваших животных и добавьте их на землю. 
Функция ```print(earth)``` должна выводить читабельное представление населения планеты

Заметки:
*  Не забывайте лучшую практику инициализации переменных с помощью оператора ```or```
*  ```__repr__()``` / ```__str__()```

## Задание 2

Напишите класс итератор ```ReverseIter```, который принимает список и итерируется по нему в обратном направлении.

```python

it = ReverseIter([10, 54, 12, 0])

next(it)
0

next(it)
12

next(it)
54

next(it)
10

next(it)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
StopIteration
```

## Задание 3

Реализуйте три генератора ```integers()```, ```squares()``` и ```take()```).
```integers()``` - бесконечный генератор чисел. ```squares()``` выводит квадраты генератора чисел ```integers()```.  Функция ```take()``` возвращает первые n значений из переданного генератора. 

```python
print(take(5, squares()))
[1, 4, 9, 16, 25]
```
