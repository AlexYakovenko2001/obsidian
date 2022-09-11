[[NativeJS/Arrays/Methods/Methods]]
## Includes()
Метод **includes()** определяет, содержит ли массив определённый элемент, возвращая в зависимости от этого `true` или `false`.

#### Синтаксис:
> arr.includes(searchElement[, fromIndex = 0])

#### Параметры:
`searchElement` - искомый элемент.

`fromIndex` (необязательный) - позиция в массиве, с которой начинать поиск элемента `searchElement`. При отрицательных значениях поиск производится начиная с индекса `array.length + fromIndex` по возрастанию. Значение по умолчанию равно 0.

#### Возвращаемое значение:
true or false