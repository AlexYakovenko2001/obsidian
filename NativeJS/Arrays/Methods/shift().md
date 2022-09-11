[[NativeJS/Arrays/Methods/Methods]]
## Shift()
Метод **shift()**  удаляет **первый** элемент из массива и возвращает его значение. Этот метод изменяет длину массива.

#### Cинтаксис:
```
arr.shift()
```

#### Возвращаемое значение:
Нулевой элемент массива или [`undefined`](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/undefined), если массив пуст.

#### Описание
Метод `shift` удаляет элемент по нулевому индексу, сдвигает значения по последовательным индексам вниз, а затем возвращает удалённое значение. Если свойство [`length`](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array/length) массива равно 0, вернётся значение [`undefined`](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/undefined).