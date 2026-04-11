---
title: Rectangle
second_title: Справочник API Aspose.Drawing для Java
description: Хранит набор из четырёх целых чисел, представляющих положение и размер прямоугольника.
type: docs
weight: 38
url: /ru/java/com.aspose.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.lang.Cloneable
```
public class Rectangle extends Struct<Rectangle> implements System.IEquatable<Rectangle>, Cloneable
```

Хранит набор из четырёх целых чисел, представляющих положение и размер прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Инициализирует новый экземпляр структуры Rectangle с указанным расположением и размером. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-) | Инициализирует новый экземпляр структуры [Rectangle](../../com.aspose.drawing/rectangle) с указанным расположением и размером. |
## Методы

| Метод | Описание |
| --- | --- |
| [fromLTRB(int left, int top, int right, int bottom)](#fromLTRB-int-int-int-int-) | Создаёт структуру [Rectangle](../../com.aspose.drawing/rectangle) с указанными позициями краёв. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Возвращает третью структуру [Rectangle](../../com.aspose.drawing/rectangle), представляющую пересечение двух других структур [Rectangle](../../com.aspose.drawing/rectangle). |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Проверяет, имеют ли две структуры [Rectangle](../../com.aspose.drawing/rectangle) одинаковое расположение и размер. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Проверяет, отличаются ли две структуры [Rectangle](../../com.aspose.drawing/rectangle) по расположению или размеру. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.drawing.RectangleF-) | Преобразует указанную структуру [RectangleF](../../com.aspose.drawing/rectanglef) в структуру [Rectangle](../../com.aspose.drawing/rectangle), округляя значения [RectangleF](../../com.aspose.drawing/rectanglef) до следующего большего целого. |
| [truncate(RectangleF value)](#truncate-com.aspose.drawing.RectangleF-) | Преобразует указанную [RectangleF](../../com.aspose.drawing/rectanglef) в [Rectangle](../../com.aspose.drawing/rectangle), отбрасывая дробную часть значений [RectangleF](../../com.aspose.drawing/rectanglef). |
| [round(RectangleF value)](#round-com.aspose.drawing.RectangleF-) | Преобразует указанную [RectangleF](../../com.aspose.drawing/rectanglef) в [Rectangle](../../com.aspose.drawing/rectangle), округляя значения [RectangleF](../../com.aspose.drawing/rectanglef) до ближайшего целого. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) | Получает структуру [Rectangle](../../com.aspose.drawing/rectangle), содержащую объединение двух структур [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.drawing.Rectangle-int-int-) |  |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-) |  |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-) | Создаёт новый прямоугольник по двум точкам. |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры `Rectangle`, у которого значения `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` и `Rectangle.Height` установлены в ноль. |
| [getX()](#getX--) | Получает координату X верхнего левого угла этой структуры Rectangle. |
| [setX(int value)](#setX-int-) | Устанавливает координату X верхнего левого угла этой структуры Rectangle. |
| [getY()](#getY--) | Получает координату Y верхнего левого угла этой структуры Rectangle. |
| [setY(int value)](#setY-int-) | Устанавливает координату Y верхнего левого угла этой структуры Rectangle. |
| [getLocation()](#getLocation--) | Получает координаты верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| [setLocation(Point value)](#setLocation-com.aspose.drawing.Point-) | Устанавливает координаты верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| [getWidth()](#getWidth--) | Получает ширину этой структуры Rectangle. |
| [setWidth(int value)](#setWidth-int-) | Устанавливает ширину этой структуры Rectangle. |
| [getHeight()](#getHeight--) | Получает высоту этой структуры Rectangle. |
| [setHeight(int value)](#setHeight-int-) | Устанавливает высоту этой структуры Rectangle. |
| [getSize()](#getSize--) | Получает размер этой [Rectangle](../../com.aspose.drawing/rectangle). |
| [setSize(Size value)](#setSize-com.aspose.drawing.Size-) | Устанавливает размер этой [Rectangle](../../com.aspose.drawing/rectangle). |
| [getLeft()](#getLeft--) | Получает координату X левой границы этой структуры Rectangle. |
| [getTop()](#getTop--) | Получает координату Y верхней границы этой структуры Rectangle. |
| [getRight()](#getRight--) | Получает координату X, которая является суммой значений свойств X и Width этой структуры Rectangle. |
| [getBottom()](#getBottom--) | Получает координату Y, которая является суммой значений свойств Y и Height этой структуры Rectangle. |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, имеют ли все числовые свойства этой [Rectangle](../../com.aspose.drawing/rectangle) значение ноль. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли obj структурой [Rectangle](../../com.aspose.drawing/rectangle) с тем же расположением и размером, что и эта структура [Rectangle](../../com.aspose.drawing/rectangle). |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| [toString()](#toString--) |  |
| [intersect(Rectangle rect)](#intersect-com.aspose.drawing.Rectangle-) | Заменяет эту [Rectangle](../../com.aspose.drawing/rectangle) пересечением её с указанной [Rectangle](../../com.aspose.drawing/rectangle). |
| [inflate(int width, int height)](#inflate-int-int-) | Увеличивает эту [Rectangle](../../com.aspose.drawing/rectangle) на указанную величину. |
| [inflate(Size size)](#inflate-com.aspose.drawing.Size-) | Увеличивает эту [Rectangle](../../com.aspose.drawing/rectangle) на указанную величину. |
| [contains(int x, int y)](#contains-int-int-) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Point pt)](#contains-com.aspose.drawing.Point-) | Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| [contains(Rectangle rect)](#contains-com.aspose.drawing.Rectangle-) |  |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.drawing.Rectangle-) | Определяет, пересекается ли этот прямоугольник с `rect`. |
| [offset(int x, int y)](#offset-int-int-) | Корректирует положение этого прямоугольника на указанную величину. |
| [offset(Point pos)](#offset-com.aspose.drawing.Point-) | Корректирует положение этого прямоугольника на указанную величину. |
| [equals(Rectangle other)](#equals-com.aspose.drawing.Rectangle-) | Проверяет, имеет ли другая структура [Rectangle](../../com.aspose.drawing/rectangle) то же расположение и размер, что и эта структура [Rectangle](../../com.aspose.drawing/rectangle). |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.drawing.Rectangle-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [normalize()](#normalize--) | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней. |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Инициализирует новый экземпляр структуры Rectangle с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x верхнего левого угла прямоугольника. |
| y | int | Y‑координата верхнего левого угла прямоугольника. |
| width | int | Ширина прямоугольника. |
| height | int | Высота прямоугольника. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.drawing.Point-com.aspose.drawing.Size-}
```
public Rectangle(Point location, Size size)
```


Инициализирует новый экземпляр структуры [Rectangle](../../com.aspose.drawing/rectangle) с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| location | [Point](../../com.aspose.drawing/point) | Точка [Point](../../com.aspose.drawing/point), представляющая верхний левый угол прямоугольной области. |
| size | [Size](../../com.aspose.drawing/size) | Объект `Size`([.getSize](../../null/\#getSize)/[.setSize(Size)](../../null/\#setSize-Size-)), представляющий ширину и высоту прямоугольной области. |

### fromLTRB(int left, int top, int right, int bottom) {#fromLTRB-int-int-int-int-}
```
public static Rectangle fromLTRB(int left, int top, int right, int bottom)
```


Создаёт структуру [Rectangle](../../com.aspose.drawing/rectangle) с указанными позициями краёв.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | int | Координата X верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| top | int | Координата Y верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| right | int | Координата X нижнего правого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |
| bottom | int | Координата Y нижнего правого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The new [Rectangle](../../com.aspose.drawing/rectangle) that this method creates.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Возвращает третью структуру [Rectangle](../../com.aspose.drawing/rectangle), представляющую пересечение двух других структур [Rectangle](../../com.aspose.drawing/rectangle). Если пересечения нет, возвращается пустая [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Первый прямоугольник для пересечения. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Второй прямоугольник для пересечения. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) that represents the intersection of `a` and `b`.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Проверяет, имеют ли две структуры [Rectangle](../../com.aspose.drawing/rectangle) одинаковое расположение и размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle), находящаяся слева от оператора равенства. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle), находящаяся справа от оператора равенства. |

**Returns:**
boolean — Этот оператор возвращает `true`, если две структуры [Rectangle](../../com.aspose.drawing/rectangle) имеют одинаковые свойства X, Y, Width и Height.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Проверяет, отличаются ли две структуры [Rectangle](../../com.aspose.drawing/rectangle) по расположению или размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle), находящаяся слева от оператора неравенства. |
| right | [Rectangle](../../com.aspose.drawing/rectangle) | Структура [Rectangle](../../com.aspose.drawing/rectangle), находящаяся справа от оператора неравенства. |

**Returns:**
boolean — Этот оператор возвращает `true`, если любое из свойств X, Y, Width или Height двух структур [Rectangle](../../com.aspose.drawing/rectangle) не равно; в противном случае `false`.
### ceiling(RectangleF value) {#ceiling-com.aspose.drawing.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Преобразует указанную структуру [RectangleF](../../com.aspose.drawing/rectanglef) в структуру [Rectangle](../../com.aspose.drawing/rectangle), округляя значения [RectangleF](../../com.aspose.drawing/rectanglef) до следующего большего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | Структура [RectangleF](../../com.aspose.drawing/rectanglef), подлежащая конвертации. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - Returns a [Rectangle](../../com.aspose.drawing/rectangle).
### truncate(RectangleF value) {#truncate-com.aspose.drawing.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Преобразует указанную [RectangleF](../../com.aspose.drawing/rectanglef) в [Rectangle](../../com.aspose.drawing/rectangle), отбрасывая дробную часть значений [RectangleF](../../com.aspose.drawing/rectanglef).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef), подлежащий конвертации. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - The truncated value of the [Rectangle](../../com.aspose.drawing/rectangle).
### round(RectangleF value) {#round-com.aspose.drawing.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Преобразует указанную [RectangleF](../../com.aspose.drawing/rectanglef) в [Rectangle](../../com.aspose.drawing/rectangle), округляя значения [RectangleF](../../com.aspose.drawing/rectanglef) до ближайшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.drawing/rectanglef) | [RectangleF](../../com.aspose.drawing/rectanglef), подлежащий конвертации. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle).
### union(Rectangle a, Rectangle b) {#union-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Получает структуру [Rectangle](../../com.aspose.drawing/rectangle), содержащую объединение двух структур [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.drawing/rectangle) | Первый прямоугольник для объединения. |
| b | [Rectangle](../../com.aspose.drawing/rectangle) | Второй прямоугольник для объединения. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A [Rectangle](../../com.aspose.drawing/rectangle) structure that bounds the union of the two [Rectangle](../../com.aspose.drawing/rectangle) structures.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.drawing.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| x | int |  |
| y | int |  |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.drawing.Rectangle-com.aspose.drawing.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.drawing/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.drawing.Point-com.aspose.drawing.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Создаёт новый прямоугольник из двух точек. Созданный прямоугольник будет нормализован так, чтобы (left,top) были меньше, чем (right,bottom).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.drawing/point) | Первая точка. |
| point2 | [Point](../../com.aspose.drawing/point) | Вторая точка. |

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle) - A newly created rectangle.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Получает новый экземпляр структуры `Rectangle`, у которого значения `Rectangle.X`, `Rectangle.Y`, `Rectangle.Width` и `Rectangle.Height` установлены в ноль.

**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### getX() {#getX--}
```
public final int getX()
```


Получает координату X верхнего левого угла этой структуры Rectangle.

**Returns:**
int — координата x верхнего левого угла этой структуры Rectangle.
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Устанавливает координату X верхнего левого угла этой структуры Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | координата x верхнего левого угла этой структуры Rectangle. |

### getY() {#getY--}
```
public final int getY()
```


Получает координату Y верхнего левого угла этой структуры Rectangle.

**Returns:**
int — координата y верхнего левого угла этой структуры Rectangle.
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Устанавливает координату Y верхнего левого угла этой структуры Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | координата y верхнего левого угла этой структуры Rectangle. |

### getLocation() {#getLocation--}
```
public final Point getLocation()
```


Получает координаты верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Point](../../com.aspose.drawing/point) - the coordinates of the upper-left corner of this [Rectangle](../../com.aspose.drawing/rectangle) structure.
### setLocation(Point value) {#setLocation-com.aspose.drawing.Point-}
```
public final void setLocation(Point value)
```


Устанавливает координаты верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.drawing/point) | координаты верхнего левого угла этой структуры [Rectangle](../../com.aspose.drawing/rectangle). |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину этой структуры Rectangle.

**Returns:**
int — ширина этой структуры Rectangle.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Устанавливает ширину этой структуры Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | ширина этой структуры Rectangle. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту этой структуры Rectangle.

**Returns:**
int — высота этой структуры Rectangle.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Устанавливает высоту этой структуры Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | высота этой структуры Rectangle. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Получает размер этой [Rectangle](../../com.aspose.drawing/rectangle).

**Returns:**
[Size](../../com.aspose.drawing/size) - the size of this [Rectangle](../../com.aspose.drawing/rectangle).
### setSize(Size value) {#setSize-com.aspose.drawing.Size-}
```
public final void setSize(Size value)
```


Устанавливает размер этой [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.drawing/size) | размер этой [Rectangle](../../com.aspose.drawing/rectangle). |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Получает координату X левой границы этой структуры Rectangle.

**Returns:**
int — координата x левой грани этой структуры Rectangle.
### getTop() {#getTop--}
```
public final int getTop()
```


Получает координату Y верхней границы этой структуры Rectangle.

**Returns:**
int — координата y верхней грани этой структуры Rectangle.
### getRight() {#getRight--}
```
public final int getRight()
```


Получает координату X, которая является суммой значений свойств X и Width этой структуры Rectangle.

**Returns:**
int — координата x, являющаяся суммой значений свойств X и Width этой структуры Rectangle.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Получает координату Y, которая является суммой значений свойств Y и Height этой структуры Rectangle.

**Returns:**
int — координата y, являющаяся суммой значений свойств Y и Height этой структуры Rectangle.
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Получает значение, указывающее, имеют ли все числовые свойства этой [Rectangle](../../com.aspose.drawing/rectangle) значение ноль.

**Returns:**
boolean - Это свойство возвращает `true`, если свойства `Rectangle.Width`, `Rectangle.Height`, `Rectangle.X` и `Rectangle.Y` данного [Rectangle](../../com.aspose.drawing/rectangle) имеют значение ноль; в противном случае `false`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли obj структурой [Rectangle](../../com.aspose.drawing/rectangle) с тем же расположением и размером, что и эта структура [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean - Этот метод возвращает `true`, если obj является структурой [Rectangle](../../com.aspose.drawing/rectangle) и её свойства X, Y, Width и Height равны соответствующим свойствам этой структуры [Rectangle](../../com.aspose.drawing/rectangle); в противном случае `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этой структуры [Rectangle](../../com.aspose.drawing/rectangle). Для получения информации об использовании хеш‑кодов см. GetHashCode.

**Returns:**
int - Целое число, представляющее хеш‑код для этого прямоугольника.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### intersect(Rectangle rect) {#intersect-com.aspose.drawing.Rectangle-}
```
public final void intersect(Rectangle rect)
```


Заменяет эту [Rectangle](../../com.aspose.drawing/rectangle) пересечением её с указанной [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Этот [Rectangle](../../com.aspose.drawing/rectangle), с которым нужно выполнить пересечение. |

### inflate(int width, int height) {#inflate-int-int-}
```
public final void inflate(int width, int height)
```


Увеличивает эту [Rectangle](../../com.aspose.drawing/rectangle) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Величина, на которую следует расширить этот [Rectangle](../../com.aspose.drawing/rectangle) по горизонтали. |
| height | int | Величина, на которую следует расширить этот [Rectangle](../../com.aspose.drawing/rectangle) по вертикали. |

### inflate(Size size) {#inflate-com.aspose.drawing.Size-}
```
public final void inflate(Size size)
```


Увеличивает эту [Rectangle](../../com.aspose.drawing/rectangle) на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.drawing/size) | Размер, на который следует расширить этот [Rectangle](../../com.aspose.drawing/rectangle). |

### contains(int x, int y) {#contains-int-int-}
```
public final boolean contains(int x, int y)
```


Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x точки, которую нужно проверить. |
| y | int | Координата Y точки для проверки. |

**Returns:**
boolean - Этот метод возвращает `true`, если точка, определённая `x` и `y`, находится внутри этой структуры [Rectangle](../../com.aspose.drawing/rectangle); в противном случае `false`.
### contains(Point pt) {#contains-com.aspose.drawing.Point-}
```
public final boolean contains(Point pt)
```


Определяет, содержится ли указанная точка внутри этой структуры [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.drawing/point) | [Point](../../com.aspose.drawing/point), который нужно проверить. |

**Returns:**
boolean - Этот метод возвращает `true`, если точка, представленная `pt`, находится внутри этой структуры [Rectangle](../../com.aspose.drawing/rectangle); в противном случае `false`.
### contains(Rectangle rect) {#contains-com.aspose.drawing.Rectangle-}
```
public final boolean contains(Rectangle rect)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) |  |

**Returns:**
boolean
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.drawing.Rectangle-}
```
public final boolean intersectsWith(Rectangle rect)
```


Определяет, пересекается ли этот прямоугольник с `rect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.drawing/rectangle) | Прямоугольник для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если есть какое‑либо пересечение, иначе false.
### offset(int x, int y) {#offset-int-int-}
```
public final void offset(int x, int y)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Горизонтальное смещение. |
| y | int | Вертикальное смещение. |

### offset(Point pos) {#offset-com.aspose.drawing.Point-}
```
public final void offset(Point pos)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pos | [Point](../../com.aspose.drawing/point) | Смещение. |

### equals(Rectangle other) {#equals-com.aspose.drawing.Rectangle-}
```
public final boolean equals(Rectangle other)
```


Проверяет, имеет ли другая структура [Rectangle](../../com.aspose.drawing/rectangle) то же расположение и размер, что и эта структура [Rectangle](../../com.aspose.drawing/rectangle).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.drawing/rectangle) | Другой прямоугольник для проверки |

**Returns:**
boolean - Этот метод возвращает `true`, если другая структура [Rectangle](../../com.aspose.drawing/rectangle) и её свойства X, Y, Width и Height равны соответствующим свойствам этой структуры [Rectangle](../../com.aspose.drawing/rectangle); в противном случае `false`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.drawing.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.drawing/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.drawing/rectangle)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### normalize() {#normalize--}
```
public void normalize()
```


Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней.

