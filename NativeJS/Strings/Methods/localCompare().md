[[NativeJS/Strings/Methods/Methods]]
## LocalCompare()
Метод **localeCompare()** возвращает число, указывающее, идет ли ссылочная строка до или после или совпадает с заданной строкой в порядке сортировки.

#### Синтаксис:
```
referenceStr.localeCompare(compareString)
```

#### Параметры:
`compareString` - строка, с которой `referenceStr` сравнивается.

Также есть ещё несколько параметров, которые позволяют настраивать сравнение этих двух строк.

#### Возвращаемое значение:
Отрицательное число, если оно **встречается** `referenceStr` до `compareString`; **положительный** , если `referenceStr` происходит после `compareString`; `0` если они эквивалентны.

#### Описание
Возвращает целое число, указывающее, `referenceStr` идет ли .до, после или эквивалентно `compareString`.

-   Отрицательный, когда `referenceStr` происходит до `compareString`
-   Положительный, когда `referenceStr` происходит после `compareString`
-   Возвращает `0`, если они эквивалентны