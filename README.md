# hw-data-structures


## Темы на повторения 

- [Объекты](https://learn.javascript.ru/object)
- [Копирование объектов и ссылки](https://learn.javascript.ru/object-copy)
- [Map и Set](https://learn.javascript.ru/map-set)

### Задача 1

Создайте ф-цию `function findSingleNumber(nums)`. `nums` -  массив целых чисел nums, каждый элемент появляется дважды, кроме одного. Найдите этот элемент. Релиазуйте решение с линейной сложностью O(n). 
Данные для проверки. 

```
Input: nums = [2,2,1]
Output: 1

Input: nums = [4,1,2,1,2]
Output: 4

Input: nums = [1]
Output: 1
```

**Дополнительно** попробуйте написать второй вариант решение, где нужно использовать O(1) (константного) пространства. _Имеется ввиду решить задачу не создавая дополнительных структур ( таких как массив, объект и т.п. )_


### Задача 2

Создайте ф-цию `function searchInsert(nums, target)`. `nums` - отсортированный массив целых чисел, верните индекс, если цифра найдена. Если нет, верните индекс, который соответствовал бы позиции искомого числа, если бы это число было бы вставлено в массив в правильном порядке. Решите задачу со сложностью выполнения `O(log n)`.

Примеры для проверки 

```
Input: nums = [1,3,5,6], target = 5
Output: 2

Input: nums = [1,3,5,6], target = 2
Output: 1

Input: nums = [1,3,5,6], target = 7
Output: 4

Input: nums = [1,3,5,6], target = 0
Output: 0

Input: nums = [1], target = 0
Output: 0
```

**Hint** Воспользуйтесь примером, который был показан на уроке (для бинарного поиска)

### Задача 3 

Создайте ф-цию `function findMajorityElement(nums)`. `nums` - массив чисел размера n, верните элемент, который встречается более `⌊n / 2⌋` раз. 
Примеры для проверки. 

```
Input: nums = [3,2,3]
Output: 3

Input: nums = [2,2,1,1,1,2,2]
Output: 2
```
