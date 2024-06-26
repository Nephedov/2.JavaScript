# «Функции»

## Решения
 * <a href="https://github.com/Nephedov/bjs-2-homeworks/blob/bjs-53/2.functions/task.js">task.js</a> - код с реализованными функциями.

<a href="https://github.com/Nephedov/bjs-2-homeworks/tree/bjs-53/2.functions">Репозиторий</a> с заданием и тестами.
Запуск через <a href="https://github.com/Nephedov/bjs-2-homeworks/blob/bjs-53/2.functions/index.html">index.html</a>.

## Что было сделано
* Реализована функция определения миннимального, максимального и среднего арифметического значения массива целочисленных элементов.
* Реализован ряд функций преобразователей данных:
  * суммирования целочисленных элементов массива;
  * вычисления разницы максимального и минимального целочисленного элемента массива;
  * вычисления разницы сумм чётных и нечётных целочисленных элементов массива;
  * вычисления среднего значения чётных целочисленных элементов массива.
* Реализована функция агрегатор - принимающая одним из аргументов функцию преобразователь данных.
* Решение задания опубликовано в GithubPages.

---
---


## Описание Задания 1
Написать функцию `getArrayParams(...arr)`, которая получает на вход числа, а возвращает минимальное, максимальное и среднее арифметическое значений массива. Используйте rest-параметр для получения произвольного количества аргументов.

## Описание Задания 2
Представьте, что у вас есть мясорубка с разными насадками. Мясорубка запускает действие, а сам процесс зависит от того, какая будет насадка. Затем мясорубка применяет насадку ко всему мясу, которое в неё поступает, и выдаёт на выход только самый лучший кусок. Используйте rest-параметр для получения произвольного количества аргументов в каждой насадке.

У мясорубки есть несколько насадок-преобразователей:

* насадка суммирования элементов;
* насадка вычисления разницы максимального и минимального элементов;
* насадка вычисления разницы сумм чётных и нечётных элементов;
* насадка вычисления среднего значения чётных элементов.

## Описание Задания 3 
В предыдущем задании вам нужно было написать насадки к мясорубке — преобразователи данных. Теперь необходимо написать саму функцию мясорубки — агрегатор преобразований.

Напишите функцию `makeWork`, которая из массива данных и насадки будет возвращать максимальный результат функции насадки.
