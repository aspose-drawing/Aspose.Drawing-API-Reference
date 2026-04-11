---
title: SizeF
second_title: Справочник API Aspose.Drawing для Java
description: Сохраняет упорядоченную пару чисел с плавающей запятой, обычно представляющих ширину и высоту прямоугольника.
type: docs
weight: 43
url: /ru/java/com.aspose.drawing/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class SizeF extends Struct<SizeF> implements System.IEquatable<SizeF>, Cloneable
```

Хранит упорядоченную пару чисел с плавающей запятой, обычно ширину и высоту прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(float width, float height)](#SizeF-float-float-) | Инициализирует новый экземпляр структуры SizeF с указанными размерами. |
| [SizeF(PointF pt)](#SizeF-com.aspose.drawing.PointF-) | Инициализирует новый экземпляр структуры [SizeF](../../com.aspose.drawing/sizef). |
| [SizeF(SizeF size)](#SizeF-com.aspose.drawing.SizeF-) | Инициализирует новый экземпляр структуры [SizeF](../../com.aspose.drawing/sizef). |
## Методы

| Метод | Описание |
| --- | --- |
| [op_Equality(SizeF sz1, SizeF sz2)](#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Проверяет, равны ли две структуры [SizeF](../../com.aspose.drawing/sizef). |
| [op_Inequality(SizeF sz1, SizeF sz2)](#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Проверяет, различаются ли две структуры [SizeF](../../com.aspose.drawing/sizef). |
| [add(SizeF sz1, SizeF sz2)](#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Добавляет ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) к ширине и высоте другой структуры [SizeF](../../com.aspose.drawing/sizef). |
| [subtract(SizeF sz1, SizeF sz2)](#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Вычитает ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) из ширины и высоты другой структуры [SizeF](../../com.aspose.drawing/sizef). |
| [op_Addition(SizeF sz1, SizeF sz2)](#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Добавляет ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) к ширине и высоте другой структуры [SizeF](../../com.aspose.drawing/sizef). |
| [op_Subtraction(SizeF sz1, SizeF sz2)](#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) | Вычитает ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) из ширины и высоты другой структуры [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(float left, SizeF right)](#op-Multiply-float-com.aspose.drawing.SizeF-) | Умножает [SizeF](../../com.aspose.drawing/sizef) на `float`, получая [SizeF](../../com.aspose.drawing/sizef). |
| [op_Multiply(SizeF left, float right)](#op-Multiply-com.aspose.drawing.SizeF-float-) | Умножает [SizeF](../../com.aspose.drawing/sizef) на `float`, получая [SizeF](../../com.aspose.drawing/sizef). |
| [op_Division(SizeF left, float right)](#op-Division-com.aspose.drawing.SizeF-float-) | Делит [SizeF](../../com.aspose.drawing/sizef) на `float`, получая [SizeF](../../com.aspose.drawing/sizef). |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.drawing.SizeF-) |  |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-) |  |
| [getEmpty()](#getEmpty--) |  |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, имеет ли эта структура [SizeF](../../com.aspose.drawing/sizef) нулевую ширину и высоту. |
| [getWidth()](#getWidth--) | Возвращает горизонтальную компоненту этой структуры SizeF. |
| [setWidth(float value)](#setWidth-float-) | Устанавливает горизонтальную компоненту этой структуры SizeF. |
| [getHeight()](#getHeight--) | Возвращает вертикальную компоненту этой структуры SizeF. |
| [setHeight(float value)](#setHeight-float-) | Устанавливает вертикальную компоненту этой структуры SizeF. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой структуры [SizeF](../../com.aspose.drawing/sizef). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект структурой [SizeF](../../com.aspose.drawing/sizef) с теми же размерами, что и эта структура [SizeF](../../com.aspose.drawing/sizef). |
| [toSize()](#toSize--) | Преобразует структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size). |
| [toPointF()](#toPointF--) | Преобразует структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [PointF](../../com.aspose.drawing/pointf). |
| [equals(SizeF other)](#equals-com.aspose.drawing.SizeF-) | Проверяет, имеет ли другая структура [SizeF](../../com.aspose.drawing/sizef) тот же размер, что и эта структура [SizeF](../../com.aspose.drawing/sizef). |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.drawing.SizeF-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Инициализирует новый экземпляр структуры SizeF с указанными размерами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | float | Компонента ширины новой структуры SizeF. |
| height | float | Компонента высоты новой структуры SizeF. |

### SizeF(PointF pt) {#SizeF-com.aspose.drawing.PointF-}
```
public SizeF(PointF pt)
```


Инициализирует новый экземпляр структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.drawing/pointf) | Структура [PointF](../../com.aspose.drawing/pointf), из которой инициализируется эта структура [SizeF](../../com.aspose.drawing/sizef). |

### SizeF(SizeF size) {#SizeF-com.aspose.drawing.SizeF-}
```
public SizeF(SizeF size)
```


Инициализирует новый экземпляр структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef), из которой создаётся новая структура [SizeF](../../com.aspose.drawing/sizef). |

### op_Equality(SizeF sz1, SizeF sz2) {#op-Equality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Equality(SizeF sz1, SizeF sz2)
```


Проверяет, равны ли две структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) слева от оператора равенства. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) справа от оператора равенства. |

**Returns:**
boolean - Этот оператор возвращает true, если `sz1` и `sz2` имеют одинаковую ширину и высоту; в противном случае — false.
### op_Inequality(SizeF sz1, SizeF sz2) {#op-Inequality-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean op_Inequality(SizeF sz1, SizeF sz2)
```


Проверяет, различаются ли две структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) слева от оператора неравенства. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) справа от оператора неравенства. |

**Returns:**
boolean - Этот оператор возвращает true, если `sz1` и `sz2` различаются по ширине или высоте; false, если `sz1` и `sz2` равны.
### add(SizeF sz1, SizeF sz2) {#add-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF add(SizeF sz1, SizeF sz2)
```


Добавляет ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) к ширине и высоте другой структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Первая структура [SizeF](../../com.aspose.drawing/sizef) для добавления. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Вторая структура [SizeF](../../com.aspose.drawing/sizef) для добавления. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is the result of the addition operation.
### subtract(SizeF sz1, SizeF sz2) {#subtract-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF subtract(SizeF sz1, SizeF sz2)
```


Вычитает ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) из ширины и высоты другой структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) слева от оператора вычитания. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) находится справа от оператора вычитания. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) structure that is a result of the subtraction operation.
### op_Addition(SizeF sz1, SizeF sz2) {#op-Addition-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Addition(SizeF sz1, SizeF sz2)
```


Добавляет ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) к ширине и высоте другой структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Первая структура [SizeF](../../com.aspose.drawing/sizef) для добавления. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Вторая структура [SizeF](../../com.aspose.drawing/sizef) для добавления. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [Size](../../com.aspose.drawing/size) structure that is the result of the addition operation.
### op_Subtraction(SizeF sz1, SizeF sz2) {#op-Subtraction-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static SizeF op_Subtraction(SizeF sz1, SizeF sz2)
```


Вычитает ширину и высоту одной структуры [SizeF](../../com.aspose.drawing/sizef) из ширины и высоты другой структуры [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz1 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) слева от оператора вычитания. |
| sz2 | [SizeF](../../com.aspose.drawing/sizef) | Структура [SizeF](../../com.aspose.drawing/sizef) находится справа от оператора вычитания. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - A [SizeF](../../com.aspose.drawing/sizef) that is the result of the subtraction operation.
### op_Multiply(float left, SizeF right) {#op-Multiply-float-com.aspose.drawing.SizeF-}
```
public static SizeF op_Multiply(float left, SizeF right)
```


Умножает [SizeF](../../com.aspose.drawing/sizef) на `float`, получая [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | float | Множитель типа `float`. |
| right | [SizeF](../../com.aspose.drawing/sizef) | Множитель типа [SizeF](../../com.aspose.drawing/sizef). |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Multiply(SizeF left, float right) {#op-Multiply-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Multiply(SizeF left, float right)
```


Умножает [SizeF](../../com.aspose.drawing/sizef) на `float`, получая [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Множитель типа [SizeF](../../com.aspose.drawing/sizef). |
| right | float | Множитель типа `float`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Product of type [SizeF](../../com.aspose.drawing/sizef).
### op_Division(SizeF left, float right) {#op-Division-com.aspose.drawing.SizeF-float-}
```
public static SizeF op_Division(SizeF left, float right)
```


Делит [SizeF](../../com.aspose.drawing/sizef) на `float`, получая [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [SizeF](../../com.aspose.drawing/sizef) | Делимое типа [SizeF](../../com.aspose.drawing/sizef). |
| right | float | Делитель типа `int`. |

**Returns:**
[SizeF](../../com.aspose.drawing/sizef) - Result of type [SizeF](../../com.aspose.drawing/sizef).
### to_PointF(SizeF size) {#to-PointF-com.aspose.drawing.SizeF-}
```
public static PointF to_PointF(SizeF size)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
[PointF](../../com.aspose.drawing/pointf)
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.drawing.SizeF-com.aspose.drawing.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.drawing/sizef) |  |
| obj2 | [SizeF](../../com.aspose.drawing/sizef) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Возвращает значение, указывающее, имеет ли эта структура [SizeF](../../com.aspose.drawing/sizef) нулевую ширину и высоту.

**Returns:**
boolean — значение, указывающее, имеет ли эта структура [SizeF](../../com.aspose.drawing/sizef) нулевую ширину и высоту.
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Возвращает горизонтальную компоненту этой структуры SizeF.

**Returns:**
float — горизонтальная компонента этой структуры SizeF.
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Устанавливает горизонтальную компоненту этой структуры SizeF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | горизонтальная компонента этой структуры SizeF. |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Возвращает вертикальную компоненту этой структуры SizeF.

**Returns:**
float — вертикальная компонента этой структуры SizeF.
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Устанавливает вертикальную компоненту этой структуры SizeF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | вертикальная компонента этой структуры SizeF. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой структуры [SizeF](../../com.aspose.drawing/sizef).

**Returns:**
int — целочисленное значение, определяющее хеш‑значение для этой структуры [SizeF](../../com.aspose.drawing/sizef).
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект структурой [SizeF](../../com.aspose.drawing/sizef) с теми же размерами, что и эта структура [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean — этот метод возвращает `true`, если obj является [SizeF](../../com.aspose.drawing/sizef) и имеет ту же ширину и высоту, что и этот SizeF; в противном случае `false`.
### toSize() {#toSize--}
```
public final Size toSize()
```


Преобразует структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [Size](../../com.aspose.drawing/size).

**Returns:**
[Size](../../com.aspose.drawing/size) - Returns a [Size](../../com.aspose.drawing/size) structure.
### toPointF() {#toPointF--}
```
public final PointF toPointF()
```


Преобразует структуру [SizeF](../../com.aspose.drawing/sizef) в структуру [PointF](../../com.aspose.drawing/pointf).

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - Returns a [PointF](../../com.aspose.drawing/pointf) structure.
### equals(SizeF other) {#equals-com.aspose.drawing.SizeF-}
```
public final boolean equals(SizeF other)
```


Проверяет, имеет ли другая структура [SizeF](../../com.aspose.drawing/sizef) тот же размер, что и эта структура [SizeF](../../com.aspose.drawing/sizef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [SizeF](../../com.aspose.drawing/sizef) | Другой размер для проверки |

**Returns:**
boolean — этот метод возвращает `true`, если другая структура [SizeF](../../com.aspose.drawing/sizef) и её свойства Width и Height равны соответствующим свойствам этой структуры [SizeF](../../com.aspose.drawing/sizef); в противном случае `false`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.drawing.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.drawing/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.drawing/sizef)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
