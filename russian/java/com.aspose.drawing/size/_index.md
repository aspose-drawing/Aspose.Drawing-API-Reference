---
title: Size
second_title: Справочник API Aspose.Drawing для Java
description: Сохраняет упорядоченную пару целых чисел, обычно ширину и высоту прямоугольника.
type: docs
weight: 42
url: /ru/java/com.aspose.drawing/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Size extends Struct<Size> implements System.IEquatable<Size>, Cloneable
```

Хранит упорядоченную пару целых чисел, обычно ширину и высоту прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point pt)](#Size-com.aspose.drawing.Point-) | Создаёт новый экземпляр структуры [Size](../../com.aspose.drawing/size) из указанного [Point](../../com.aspose.drawing/point). |
| [Size(int width, int height)](#Size-int-int-) | Создаёт новый экземпляр структуры [Size](../../com.aspose.drawing/size) из указанных размеров. |
## Методы

| Метод | Описание |
| --- | --- |
| [to_SizeF(Size p)](#to-SizeF-com.aspose.drawing.Size-) | Преобразует указанный [Size](../../com.aspose.drawing/size) в [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(Size sz1, Size sz2)](#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Добавляет ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) к ширине и высоте другой структуры [Size](../../com.aspose.drawing/size). |
| [op_Subtraction(Size sz1, Size sz2)](#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Вычитает ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) из ширины и высоты другой структуры [Size](../../com.aspose.drawing/size). |
| [op_Multiply(int left, Size right)](#op-Multiply-int-com.aspose.drawing.Size-) | Умножает [Size](../../com.aspose.drawing/size) на `int`, получая [Size](../../com.aspose.drawing/size). |
| [op_Multiply(Size left, int right)](#op-Multiply-com.aspose.drawing.Size-int-) | Умножает [Size](../../com.aspose.drawing/size) на `int`, получая [Size](../../com.aspose.drawing/size). |
| [op_Division(Size left, int right)](#op-Division-com.aspose.drawing.Size-int-) | Делит [Size](../../com.aspose.drawing/size) на `int`, получая [Size](../../com.aspose.drawing/size). |
| [op_Multiply(float left, Size right)](#op-Multiply-float-com.aspose.drawing.Size-) | Умножает [Size](../../com.aspose.drawing/size) на `float`, получая [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(Size left, float right)](#op-Multiply-com.aspose.drawing.Size-float-) | Умножает [Size](../../com.aspose.drawing/size) на `float`, получая [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(Size left, float right)](#op-Division-com.aspose.drawing.Size-float-) | Делит [Size](../../com.aspose.drawing/size) на `float`, получая [SizeF](../../com.aspose.drawing/sizef). |
| [op_Equality(Size sz1, Size sz2)](#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Проверяет, равны ли две структуры [Size](../../com.aspose.drawing/size). |
| [op_Inequality(Size sz1, Size sz2)](#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Проверяет, различаются ли две структуры [Size](../../com.aspose.drawing/size). |
| [to_Point(Size size)](#to-Point-com.aspose.drawing.Size-) | Преобразует указанный [Size](../../com.aspose.drawing/size) в [Point](../../com.aspose.drawing/point). |
| [add(Size sz1, Size sz2)](#add-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Добавляет ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) к ширине и высоте другой структуры [Size](../../com.aspose.drawing/size). |
| [ceiling(SizeF value)](#ceiling-com.aspose.drawing.SizeF-) | Преобразует указанную структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size), округляя значения структуры [Size](../../com.aspose.drawing/size) до следующего большего целого. |
| [subtract(Size sz1, Size sz2)](#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-) | Вычитает ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) из ширины и высоты другой структуры [Size](../../com.aspose.drawing/size). |
| [truncate(SizeF value)](#truncate-com.aspose.drawing.SizeF-) | Преобразует указанную структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size), усеканием значений структуры [SizeF](../../com.aspose.drawing/sizef) до следующего меньшего целого. |
| [round(SizeF value)](#round-com.aspose.drawing.SizeF-) | Преобразует указанную структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size), округляя значения структуры [SizeF](../../com.aspose.drawing/sizef) до ближайшего целого. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, имеет ли этот [Size](../../com.aspose.drawing/size) ширину и высоту, равные 0. |
| [getWidth()](#getWidth--) | Возвращает горизонтальную составляющую этого [Size](../../com.aspose.drawing/size). |
| [setWidth(int value)](#setWidth-int-) | Устанавливает горизонтальную составляющую этого [Size](../../com.aspose.drawing/size). |
| [getHeight()](#getHeight--) | Возвращает вертикальную составляющую этого [Size](../../com.aspose.drawing/size). |
| [setHeight(int value)](#setHeight-int-) | Устанавливает вертикальную составляющую этого [Size](../../com.aspose.drawing/size). |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект [Size](../../com.aspose.drawing/size) с теми же размерами, что и этот [Size](../../com.aspose.drawing/size). |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой структуры [Size](../../com.aspose.drawing/size). |
| [toString()](#toString--) |  |
| [equals(Size other)](#equals-com.aspose.drawing.Size-) | Проверяет, имеет ли другая структура [Size](../../com.aspose.drawing/size) тот же размер, что и эта структура [Size](../../com.aspose.drawing/size). |
| [CloneTo(Size that)](#CloneTo-com.aspose.drawing.Size-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point pt) {#Size-com.aspose.drawing.Point-}
```
public Size(Point pt)
```


Создаёт новый экземпляр структуры [Size](../../com.aspose.drawing/size) из указанного [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Точка [Point](../../com.aspose.drawing/point), из которой инициализируется этот [Size](../../com.aspose.drawing/size). |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Создаёт новый экземпляр структуры [Size](../../com.aspose.drawing/size) из указанных размеров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина новой структуры [Size](../../com.aspose.drawing/size). |
| height | int | Высота новой структуры [Size](../../com.aspose.drawing/size). |

### to_SizeF(Size p) {#to-SizeF-com.aspose.drawing.Size-}
```
public static SizeF to_SizeF(Size p)
```


Преобразует указанный [Size](../../com.aspose.drawing/size) в [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) для преобразования. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - The [SizeF](../../com.aspose.drawing/sizef) structure to which this operator converts.
### op_Addition(Size sz1, Size sz2) {#op-Addition-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Addition(Size sz1, Size sz2)
```


Добавляет ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) к ширине и высоте другой структуры [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Первый [Size](../../com.aspose.drawing/size) для сложения. |
| sz2 | [Size](../../com.aspose.drawing/size) | Второй [Size](../../com.aspose.drawing/size) для сложения. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(Size sz1, Size sz2) {#op-Subtraction-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size op_Subtraction(Size sz1, Size sz2)
```


Вычитает ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) из ширины и высоты другой структуры [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) слева от оператора вычитания. |
| sz2 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) справа от оператора вычитания. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the subtraction operation.
### op_Multiply(int left, Size right) {#op-Multiply-int-com.aspose.drawing.Size-}
```
public static Size op_Multiply(int left, Size right)
```


Умножает [Size](../../com.aspose.drawing/size) на `int`, получая [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | int | Множитель типа `int`. |
| right | [Size](../../com.aspose.drawing/size) | Множимое типа [Size](../../com.aspose.drawing/size). |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Multiply(Size left, int right) {#op-Multiply-com.aspose.drawing.Size-int-}
```
public static Size op_Multiply(Size left, int right)
```


Умножает [Size](../../com.aspose.drawing/size) на `int`, получая [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Множимое типа [Size](../../com.aspose.drawing/size). |
| right | int | Множитель типа `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Product of type [Size](../../com.aspose.drawing/size).
### op_Division(Size left, int right) {#op-Division-com.aspose.drawing.Size-int-}
```
public static Size op_Division(Size left, int right)
```


Делит [Size](../../com.aspose.drawing/size) на `int`, получая [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Делимое типа [Size](../../com.aspose.drawing/size). |
| right | int | Делитель типа `int`. |

**Returns:**
[Size](../../com.aspose.drawing/size) - Result of type [Size](../../com.aspose.drawing/size).
### op_Multiply(float left, Size right) {#op-Multiply-float-com.aspose.drawing.Size-}
```
public static SizeF op_Multiply(float left, Size right)
```


Умножает [Size](../../com.aspose.drawing/size) на `float`, получая [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | float | Множитель типа `float`. |
| right | [Size](../../com.aspose.drawing/size) | Множимое типа [Size](../../com.aspose.drawing/size). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(Size left, float right) {#op-Multiply-com.aspose.drawing.Size-float-}
```
public static SizeF op_Multiply(Size left, float right)
```


Умножает [Size](../../com.aspose.drawing/size) на `float`, получая [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Множимое типа [Size](../../com.aspose.drawing/size). |
| right | float | Множитель типа `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(Size left, float right) {#op-Division-com.aspose.drawing.Size-float-}
```
public static SizeF op_Division(Size left, float right)
```


Делит [Size](../../com.aspose.drawing/size) на `float`, получая [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Size](../../com.aspose.drawing/size) | Делимое типа [Size](../../com.aspose.drawing/size). |
| right | float | Делитель типа `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### op_Equality(Size sz1, Size sz2) {#op-Equality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Equality(Size sz1, Size sz2)
```


Проверяет, равны ли две структуры [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) слева от оператора равенства. |
| sz2 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) справа от оператора равенства. |

**Returns:**
boolean - true, если `sz1` и `sz2` имеют одинаковую ширину и высоту; иначе false.
### op_Inequality(Size sz1, Size sz2) {#op-Inequality-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean op_Inequality(Size sz1, Size sz2)
```


Проверяет, различаются ли две структуры [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) слева от оператора неравенства. |
| sz2 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) справа от оператора неравенства. |

**Returns:**
boolean - true, если `sz1` и `sz2` различаются по ширине или высоте; false, если `sz1` и `sz2` равны.
### to_Point(Size size) {#to-Point-com.aspose.drawing.Size-}
```
public static Point to_Point(Size size)
```


Преобразует указанный [Size](../../com.aspose.drawing/size) в [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) для преобразования. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) structure to which this operator converts.
### add(Size sz1, Size sz2) {#add-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size add(Size sz1, Size sz2)
```


Добавляет ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) к ширине и высоте другой структуры [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Первый [Size](../../com.aspose.drawing/size) для сложения. |
| sz2 | [Size](../../com.aspose.drawing/size) | Второй [Size](../../com.aspose.drawing/size) для сложения. |

**Returns:**
[Size](../../com.aspose.drawing/size) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### ceiling(SizeF value) {#ceiling-com.aspose.drawing.SizeF-}
```
public static Size ceiling(SizeF value)
```


Преобразует указанную структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size), округляя значения структуры [Size](../../com.aspose.drawing/size) до следующего большего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) для преобразования. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### subtract(Size sz1, Size sz2) {#subtract-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static Size subtract(Size sz1, Size sz2)
```


Вычитает ширину и высоту одной структуры [Size](../../com.aspose.drawing/size) из ширины и высоты другой структуры [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) слева от оператора вычитания. |
| sz2 | [Size](../../com.aspose.drawing/size) | Структура [Size](../../com.aspose.drawing/size) справа от оператора вычитания. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) that is a result of the subtraction operation.
### truncate(SizeF value) {#truncate-com.aspose.drawing.SizeF-}
```
public static Size truncate(SizeF value)
```


Преобразует указанную структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size), усеканием значений структуры [SizeF](../../com.aspose.drawing/sizef) до следующего меньшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) для преобразования. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### round(SizeF value) {#round-com.aspose.drawing.SizeF-}
```
public static Size round(SizeF value)
```


Преобразует указанную структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size), округляя значения структуры [SizeF](../../com.aspose.drawing/sizef) до ближайшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) для преобразования. |

**Returns:**
[Size](../../com.aspose.drawing/size) - The [Size](../../com.aspose.drawing/size) structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.drawing.Size-com.aspose.drawing.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.drawing/size) |  |
| obj2 | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Возвращает значение, указывающее, имеет ли этот [Size](../../com.aspose.drawing/size) ширину и высоту, равные 0.

**Returns:**
boolean - значение, указывающее, имеет ли данный [Size](../../com.aspose.drawing/size) ширину и высоту, равные 0.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Возвращает горизонтальную составляющую этого [Size](../../com.aspose.drawing/size).

**Returns:**
int - горизонтальная составляющая данного [Size](../../com.aspose.drawing/size).
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает горизонтальную составляющую этого [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | горизонтальная составляющая данного [Size](../../com.aspose.drawing/size). |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Возвращает вертикальную составляющую этого [Size](../../com.aspose.drawing/size).

**Returns:**
int - вертикальная составляющая данного [Size](../../com.aspose.drawing/size).
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает вертикальную составляющую этого [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | вертикальная составляющая данного [Size](../../com.aspose.drawing/size). |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект [Size](../../com.aspose.drawing/size) с теми же размерами, что и этот [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean - true, если `obj` является [Size](../../com.aspose.drawing/size) и имеет такую же ширину и высоту, как этот [Size](../../com.aspose.drawing/size); иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой структуры [Size](../../com.aspose.drawing/size).

**Returns:**
int - целочисленное значение, определяющее хеш для этой структуры [Size](../../com.aspose.drawing/size).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Size other) {#equals-com.aspose.drawing.Size-}
```
public final boolean equals(Size other)
```


Проверяет, имеет ли другая структура [Size](../../com.aspose.drawing/size) тот же размер, что и эта структура [Size](../../com.aspose.drawing/size).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Size](../../com.aspose.drawing/size) | Другой размер для проверки |

**Returns:**
boolean - Этот метод возвращает `true`, если другая структура [Size](../../com.aspose.drawing/size) и её свойства Width и Height равны соответствующим свойствам этой структуры [Size](../../com.aspose.drawing/size); иначе `false`.
### CloneTo(Size that) {#CloneTo-com.aspose.drawing.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Size](../../com.aspose.drawing/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
### clone() {#clone--}
```
public Size clone()
```




**Returns:**
[Size](../../com.aspose.drawing/size)
