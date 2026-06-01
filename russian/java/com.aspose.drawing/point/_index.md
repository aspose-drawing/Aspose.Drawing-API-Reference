---
title: Point
second_title: Справочник API Aspose.Drawing для Java
description: Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости.
type: docs
weight: 36
url: /ru/java/com.aspose.drawing/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Point extends Struct<Point> implements System.IEquatable<Point>, Cloneable
```

Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Инициализирует новый экземпляр структуры [Point](../../com.aspose.drawing/point) с указанными координатами. |
| [Point(Size sz)](#Point-com.aspose.drawing.Size-) |  |
| [Point(int dw)](#Point-int-) | Инициализирует новый экземпляр структуры [Point](../../com.aspose.drawing/point), используя координаты, указанные целочисленным значением. |
## Поля

| Поле | Описание |
| --- | --- |
| [EMPTY](#EMPTY) | Представляет [Point](../../com.aspose.drawing/point), у которого значения `Point.X` и `Point.Y` установлены в ноль. |
## Методы

| Метод | Описание |
| --- | --- |
| [to_PointF(Point p)](#to-PointF-com.aspose.drawing.Point-) | Преобразует указанную структуру [Point](../../com.aspose.drawing/point) в структуру [PointF](../../com.aspose.drawing/pointf). |
| [to_Size(Point p)](#to-Size-com.aspose.drawing.Point-) |  |
| [op_Addition(Point pt, Size sz)](#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Subtraction(Point pt, Size sz)](#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [op_Equality(Point left, Point right)](#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Сравнивает два объекта [Point](../../com.aspose.drawing/point). |
| [op_Inequality(Point left, Point right)](#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Сравнивает два объекта [Point](../../com.aspose.drawing/point). |
| [add(Point pt, Size sz)](#add-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Добавляет указанный [Size](../../com.aspose.drawing/size) к указанному [Point](../../com.aspose.drawing/point). |
| [subtract(Point pt, Size sz)](#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-) |  |
| [ceiling(PointF value)](#ceiling-com.aspose.drawing.PointF-) |  |
| [truncate(PointF value)](#truncate-com.aspose.drawing.PointF-) | Преобразует PointF в Point, выполняя усечение всех координат. |
| [round(PointF value)](#round-com.aspose.drawing.PointF-) | Преобразует указанную [PointF](../../com.aspose.drawing/pointf) в объект Point, округляя значения [Point](../../com.aspose.drawing/point) до ближайшего целого. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-) |  |
| [getEmpty()](#getEmpty--) |  |
| [getX()](#getX--) | Получает координату x этой Point. |
| [setX(int value)](#setX-int-) | Устанавливает координату x этой Point. |
| [getY()](#getY--) | Получает координату y этой Point. |
| [setY(int value)](#setY-int-) | Устанавливает координату y этой Point. |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, является ли эта [Point](../../com.aspose.drawing/point) пустой. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой [Point](../../com.aspose.drawing/point). |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, содержит ли эта [Point](../../com.aspose.drawing/point) те же координаты, что и указанный объект. |
| [offset(int dx, int dy)](#offset-int-int-) | Смещает эту [Point](../../com.aspose.drawing/point) на указанную величину. |
| [offset(Point p)](#offset-com.aspose.drawing.Point-) | Смещает эту [Point](../../com.aspose.drawing/point) на указанный [Point](../../com.aspose.drawing/point). |
| [equals(Point other)](#equals-com.aspose.drawing.Point-) | Проверяет, имеет ли другая структура [Point](../../com.aspose.drawing/point) то же расположение, что и структура этой [Point](../../com.aspose.drawing/point). |
| [CloneTo(Point that)](#CloneTo-com.aspose.drawing.Point-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Инициализирует новый экземпляр структуры [Point](../../com.aspose.drawing/point) с указанными координатами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Горизонтальное положение точки. |
| y | int | Вертикальное положение точки. |

### Point(Size sz) {#Point-com.aspose.drawing.Size-}
```
public Point(Size sz)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sz | [Size](../../com.aspose.drawing/size) |  |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Инициализирует новый экземпляр структуры [Point](../../com.aspose.drawing/point), используя координаты, указанные целочисленным значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dw | int | Целочисленное значение. |

### EMPTY {#EMPTY}
```
public static final Point EMPTY
```


Представляет [Point](../../com.aspose.drawing/point), у которого значения `Point.X` и `Point.Y` установлены в ноль.

### to_PointF(Point p) {#to-PointF-com.aspose.drawing.Point-}
```
public static PointF to_PointF(Point p)
```


Преобразует указанную структуру [Point](../../com.aspose.drawing/point) в структуру [PointF](../../com.aspose.drawing/pointf).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Точка [Point](../../com.aspose.drawing/point), которую нужно преобразовать. |

**Returns:**
[PointF](../../com.aspose.drawing/pointf) - The [PointF](../../com.aspose.drawing/pointf) that results from the conversion.
### to_Size(Point p) {#to-Size-com.aspose.drawing.Point-}
```
public static Size to_Size(Point p)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
[Size](../../com.aspose.drawing/size)
### op_Addition(Point pt, Size sz) {#op-Addition-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Addition(Point pt, Size sz)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Subtraction(Point pt, Size sz) {#op-Subtraction-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point op_Subtraction(Point pt, Size sz)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### op_Equality(Point left, Point right) {#op-Equality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Equality(Point left, Point right)
```


Сравнивает два объекта [Point](../../com.aspose.drawing/point). Результат указывает, равны ли значения свойств `Point.X` и `Point.Y` у двух объектов [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Первый [Point](../../com.aspose.drawing/point) для сравнения. |
| right | [Point](../../com.aspose.drawing/point) | Второй [Point](../../com.aspose.drawing/point) для сравнения. |

**Returns:**
boolean - true, если значения `Point.X` и `Point.Y` у `left` и `right` равны; иначе false.
### op_Inequality(Point left, Point right) {#op-Inequality-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean op_Inequality(Point left, Point right)
```


Сравнивает два объекта [Point](../../com.aspose.drawing/point). Результат указывает, не равны ли значения свойств `Point.X` или `Point.Y` у двух объектов [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Point](../../com.aspose.drawing/point) | Первый [Point](../../com.aspose.drawing/point) для сравнения. |
| right | [Point](../../com.aspose.drawing/point) | Второй [Point](../../com.aspose.drawing/point) для сравнения. |

**Returns:**
boolean - true, если значения свойства `Point.X` или свойства `Point.Y` у `left` и `right` различаются; иначе false.
### add(Point pt, Size sz) {#add-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point add(Point pt, Size sz)
```


Добавляет указанный [Size](../../com.aspose.drawing/size) к указанному [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | Объект [Point](../../com.aspose.drawing/point) для добавления. |
| sz | [Size](../../com.aspose.drawing/size) | Объект [Size](../../com.aspose.drawing/size) для добавления. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the addition operation.
### subtract(Point pt, Size sz) {#subtract-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public static Point subtract(Point pt, Size sz)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) |  |
| sz | [Size](../../com.aspose.drawing/size) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### ceiling(PointF value) {#ceiling-com.aspose.drawing.PointF-}
```
public static Point ceiling(PointF value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) |  |

**Returns:**
[Point](../../com.aspose.drawing/point)
### truncate(PointF value) {#truncate-com.aspose.drawing.PointF-}
```
public static Point truncate(PointF value)
```


Преобразует PointF в Point, выполняя усечение всех координат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Объект [PointF](../../com.aspose.drawing/pointf) для усечения. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) that is the result of the truncate operation.
### round(PointF value) {#round-com.aspose.drawing.PointF-}
```
public static Point round(PointF value)
```


Преобразует указанную [PointF](../../com.aspose.drawing/pointf) в объект Point, округляя значения [Point](../../com.aspose.drawing/point) до ближайшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.drawing/pointf) | Объект [PointF](../../com.aspose.drawing/pointf) для преобразования. |

**Returns:**
[Point](../../com.aspose.drawing/point) - The [Point](../../com.aspose.drawing/point) this method converts to.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.drawing/point) |  |
| obj2 | [Point](../../com.aspose.drawing/point) |  |

**Returns:**
boolean
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### getX() {#getX--}
```
public final int getX()
```


Получает координату x этой Point.

**Returns:**
int - координата x этой точки.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Устанавливает координату x этой Point.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | координата x этой точки. |

### getY() {#getY--}
```
public final int getY()
```


Получает координату y этой Point.

**Returns:**
int - координата y этой точки.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Устанавливает координату y этой Point.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | координата y этой точки. |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Получает значение, указывающее, является ли эта [Point](../../com.aspose.drawing/point) пустой.

Значение: `true`, если оба X и Y равны 0; иначе `false`.

**Returns:**
boolean - значение, указывающее, является ли этот [Point](../../com.aspose.drawing/point) пустым.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой [Point](../../com.aspose.drawing/point).

**Returns:**
int - целочисленное значение, определяющее хеш для этого [Point](../../com.aspose.drawing/point).
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


Указывает, содержит ли эта [Point](../../com.aspose.drawing/point) те же координаты, что и указанный объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean - `true`, если obj является объектом Point и имеет те же координаты, что и этот [Point](../../com.aspose.drawing/point).
### offset(int dx, int dy) {#offset-int-int-}
```
public final void offset(int dx, int dy)
```


Смещает эту [Point](../../com.aspose.drawing/point) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | int | Величина смещения координаты x. |
| dy | int | Величина смещения координаты y. |

### offset(Point p) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point p)
```


Смещает эту [Point](../../com.aspose.drawing/point) на указанный [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Point](../../com.aspose.drawing/point) | Объект [Point](../../com.aspose.drawing/point), используемый для смещения этого [Point](../../com.aspose.drawing/point). |

### equals(Point other) {#equals-com.aspose.drawing.Point-}
```
public final boolean equals(Point other)
```


Проверяет, имеет ли другая структура [Point](../../com.aspose.drawing/point) то же расположение, что и структура этой [Point](../../com.aspose.drawing/point).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Point](../../com.aspose.drawing/point) | Другой объект Point для тестирования |

**Returns:**
boolean - Этот метод возвращает `true`, если структура другого [Point](../../com.aspose.drawing/point) и её свойства X и Y равны соответствующим свойствам этой структуры [Point]; иначе `false`.
### CloneTo(Point that) {#CloneTo-com.aspose.drawing.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Point](../../com.aspose.drawing/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.drawing/point)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
